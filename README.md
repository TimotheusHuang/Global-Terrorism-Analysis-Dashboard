# Global Terrorism Analysis & Dashboard

This project was developed for course CS526: Data Interaction and Visual Analytics (DIVA)

Team Member: Keya Desai, Prakruti Joshi, Shang-Hao Huang

In this project, we have designed and developed an interactive dashboard to explore [Global Terrorism Database (GTD)](https://start.umd.edu/gtd/), which recorded ~180K terrorist events across the world from 1970 to 2017. The dashboard is divided into three main views.

## Trends
This page enables exploration of the time component of the dataset. The user can observe the trends in terrorism over time across the world, region-wise and country-wise. Furthermore, the user can view the terrorist events that occurred in a particular year as well as the detailed information on an interactive global world map. Involved interactivity includes zooming, hover, and panning. Last, a bar race chart and dynamic pie-chart of the most affected count (causualties) every year are also presented.

## Country Statistics
On this page, terrorism statistics of all the countries can be explored. Upon selecting a country, this view shows the state-wise distribution of terrorism (choropleth map), distribution of attack, target and weapon type (donut-chart), top 5 most affected cities in a country (bar chart), and the major terrorist groups responsible for the attacks (bubble plot).

## Analysis
The aggregate analysis of the entire dataset is presented here. In this view, the user can observe the number casualties incurred major terrorist groups through te years (line plot) and a timeline of deadliest events (fishbone chart). In addition, countries most affected by terrorism (bar chart), distribution of attack, target, weapon type (pie- & donut-chart), and a motive word cloud can be explored here.

**Visual representations:** Map, Line plot, pie-chart, donut-chart, bar chart (race), Fishbone chart, bubble plot, word cloud, and radar timeline.  
**Interactivity:** Zooming, Panning, Hover, Click, Drop down, Sliders, and Linking of views

The visualisations have been rendered using the JavaScript visualization libraries of D3.js and amCharts. The web application is hosted using backend framework Flask in Python. The level of interactivity is ~1s per action. All the plots can be downloded in the form of image or data. The report details the findings from the visualisation and interaction. 

The following link is video demoonstration of the project:

[![](https://img.youtube.com/vi/uTu3GNRqMJE/maxresdefault.jpg)](https://youtu.be/uTu3GNRqMJE)
