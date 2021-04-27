# Global Terrorism Analysis & Dashboard

This project was developed for course CS526: Data Interaction and Visual Analytics (DIVA)

Team Member: Keya Desai, Prakruti Joshi, Shang-Hao Huang

In this project, we have designed and developed an interactive dashboard to explore [Global Terrorism Database (GTD)](https://start.umd.edu/gtd/), which recorded ~180K terrorist events across the world from 1970 to 2017. The dashboard is divided into three main views.

## Trends
This page enables exploration of the time component of the dataset. The user can observe the trends in terrorism over time across the world, region-wise and country-wise. Furthermore, the user can view the terrorist events that occurred in that particular year on an interactive world map, along with the details of the events. The most affected country or region in each year and the corresponding information on events is combined in this view.

## Country Statistics
On this page, terrorism statistics of all the countries can be explored. On selecting a country, this page describes the state-wise distribution of terrorism, distribution of attack, target and weapon type, top cities in a country affected by terrorism, and the terrorist organisations responsible for the attacks.

## Analysis
This page provides the aggregate analysis of the entire dataset. Information of activities of top terrorist groups, top deadliest events, attack, target, weapon type distribution, countries most affected by terrorism and motive can be explored here.

**Visual representations:** Map, Line plot, pie plot, bar chart, Fishbone chart, bubble plot, word cloud, and radar timeline.  
**Interactivity:** Zooming, Panning, Hover, Click, Drop down, Sliders, and Linking of views

The visualisations have been rendered using the JavaScript visualization libraries of D3.js and amCharts. The web application is hosted using backend framework Flask in Python. The level of interactivity is ~1s per action. All the plots can be downloded in the form of image or data. The report details the findings from the visualisation and interaction. 

The video of the website can be found here:

[![](https://img.youtube.com/vi/uTu3GNRqMJE/maxresdefault.jpg)](https://youtu.be/uTu3GNRqMJE)
