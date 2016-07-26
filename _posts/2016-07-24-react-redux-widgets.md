---
layout: post
title: Developing Widgets with React and Redux
---

Recently we were tasked with developing widgets that could be embedded into an [ASU Now](https://asunow.asu.edu/) news story to promote additional reader engagement.

A widget can be anything from a chart that changes based on input, a quiz, or anything that can be created based on the news story.

After our team of developers finished an initial brainstorming session, one of the things that stood out was that we wanted to use [React](https://facebook.github.io/react/) for these widgets. React is a JavaScipt library that Facebook developed for creating user interfaces. It is currently at peak popularity level among web and software nerds that are learning to use it. React is the V in the model–view–controller (MVC) software architectural pattern. If Facebook uses is, it must be awesome, right?

It took me about two weeks of using the React library and watching and reading many tutorials to grasp the fundamentals behind it.

Here's how I explain it in simple terms: React allows you to break your UI/DOM elements into components that can be reused. These components come together like [Voltron](https://en.wikipedia.org/wiki/Voltron) to form what can be a large app of moving parts with independent states and data behind them.

When React is used with [Redux](https://github.com/reactjs/redux), things are broken down even further with component states into a single store that you don't have to worry about, you just have to utilize it.

Shoutout to Stephen Grider for creating this nice [React/Redux boilerplate](https://github.com/StephenGrider/ReduxSimpleStarter).

After you get your feet wet with React components via the [Facebook documentation](https://facebook.github.io/react/), check out Dan Abramov's (author of Redux) [Getting Started with Redux video series](https://egghead.io/courses/getting-started-with-redux).

Back to our widgets. You can preview the trivia widget that I built [here on CodePen](http://s.codepen.io/gabemartinez/debug/YWLPQv).

The widget consists of different components, both dumb and smart components, that work with each other to modify the app's immutable state while users interact with and dispatch actions to in order to see changes.

As you might have noticed, this trivia widget has to do with [ASU golf](http://asukarsten.com/).

![Trivia Screenshot](http://i.imgur.com/4fv16kT.png)

Other than using React and Redux, I also utilized [Bootstrap](http://getbootstrap.com/) to make sure that this widget would adapt well on mobile devices, which made life easier. I also used the [Animate.css](https://daneden.github.io/animate.css/) css library for UX purposes as widgets re-render based on state change.

We will be reusing these widgets for other stories, in this trivia example we might just add extra functionality and change the questions object data being used by the app.

A widget that is already live is the chart widget, which you can see in [this news story](https://asunow.asu.edu/20160720-exemplifying-entrepreneurial-spirit-sun-devil-owned-businesses). The chart widget displays industries that ASU communication majors go into after graduation. My colleague Sebastian Nievas developed that bad boy. And the original content is also from our office.

If you're interested in contributing or using this project, check it out on [Github here](https://github.com/gabemartinez/trivia).
