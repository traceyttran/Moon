---
layout: post
title: "Covid Tracker App: Chart.js bug"
date: 2020-12-28
excerpt: "I've decided to create my very own Covid Tracker App. Seeing the gravity of our global situation today, I wanted to create something 
that would be relevant, interesting and educative to those who are ill informed about just how severe and widespread Coronavirus really is..."
tag: react
comments: false
---

I've decided to create my very own Covid Tracker App. Seeing the gravity of our global situation today, I wanted to create something 
that would be relevant, interesting and educative to those who are ill informed about just how severe and widespread Coronavirus really is. With that being said,
I will be developing the app in the next few days, while also noting things I've learned and tools I've acquired.

I have already found an API for the app found here_ that gives me a total count of coronavirus cases gloablly as well as the count for each country. I will
be including other information like the daily amount of cases, the amount of recovered cases and number of deaths. 

Today, I encountered this bug while trying to create a Chart for my site: 

>**`Failed to compile ../node_modules/react-chartjs-2/es/index.js Module not found: Can't resolve 'chart.js'`**

I have found that with 


> **`npm i chart.js`** 

everything worked smoothly thereafter. It seems that while I am referring to it in the package.json, I still have to download it
individually. 
