---
layout: post
title: El Paso Alcohol Sales with Chart.js
---

I've been wanting to use the [Texas alcohol sales tax data](http://www.texastransparency.org/Data_Center/Search_Datasets.php) in a project for a while now. You might have seen my other post using D3.js for data visualizations, and I thought I was going to use D3 for this project too.

I then found [Chart.js](http://www.chartjs.org/); this library is little and powerful and it's fun to use.

It was very easy to get started. I got the data, and then started adapting it to work with Chart.js in my single-page application.

You can view the project [here](http://www.txalcsales.martinezgabriel.com/) and start querying which bars/restaurants are doing the best in El Paso. I might add more options later, but for now you can view data based on zip code, sales greater than amount, and search the last seven months of data that the Texas Comptroller has made available.

Some of the options that I might add in are search by bar name, by entertainment district, and some other things that I have written down. The app looks best on a desktop and larger sized model iPads, and later I could make it easier to use on an iPhone/smaller width mobile device.

* [El Paso County Mixed Beverage Tax Receipts](http://www.txalcsales.martinezgabriel.com/)
* [GitHub Project Repo](https://github.com/gabemartinez/txalcsales-chartjs)

![El Paso Alcohol Sales App Screenshot](../img/txalcsales-screenshot.png)