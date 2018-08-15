---
title: "Turplan (Hike Planner)"
permalink: /showcases/turplan/
excerpt: "Turplan"
last_modified_at: 2018-08-15T12:00:00 +01:00
redirect_from:
  - /turplan/
toc: true
gallery:
  - url: /assets/images/turplan-screen2.png
    image_path: /assets/images/turplan-screen2.png
    alt: "Map with parking lots"
    title: "Map with parking lots"
  - url: /assets/images/turplan-screen3.png
    image_path: /assets/images/turplan-screen3.png
    alt: "Map with charging stations for electric cars"
    title: "Map with charging stations"
  - url: /assets/images/turplan-screen4.png
    image_path: /assets/images/turplan-screen4.png
    alt: "Map with hikes"
    title: "Map with hikes"
---
## About the case

Turplan is a web-based application for hike planning with parking information. It has been implemented by a group of students from NTNU supervised by SINTEF during the course "TDT4290 Customer-driven projects" in the autumn of 2017. The purpose of the project was to build an innovative application using available open transport data and evaluate how open data can contribute to innovations from the experience of this process.

{% include gallery %}

The motivation for the application is that Norwegians are very fond of nature and love hiking. There have been separate applications that provide relevant information for hike planning, e.g., hiking tracks (trails) and parking information, but such information has not been integrated in one single easy-to-use application. The application concept is also very expandable and new functionalities can be added, e.g., various transport modes can be integrated, like bus, boat, plane, to plan a route from the selected starting point to the desired destination (the start point for a hike trip).

## Functionality

Turplan allows the user to find a hike in Norway and get to the starting point or closest parking lot. A main view showas a map of the area with different features for the user, including:
- showing hiking trips in the area
- showing parking lots in the selected area
- showing charging stations for electic cars
- showing navigation between a selected starting point and destination

The screenshot shows the hike planner with a view of parking lots in the area, and a path with directions from a selected starting point to a destination.  

![Turplan screenshot](/assets/images/turplan-screen1.png)

## Open data source used

From the multiple data sources that was evaluated during the implementation process, the following data sources (datasets and their providers) have been used in the prototype:  
### Maps
* [Official hiking map of Norway from Statens Kartverk](https://www.kartverket.no/kart/)

### Parking lots  
* [Parkeringsregisteret from Statens Vegvesen (SVV)](https://www.vegvesen.no/trafikkinformasjon/Reiseinformasjon/parkeringsregisteret#/kart/63.990556,12.307778,3?_k=zhjveb).
* [Parking information from OpenStreetMap](https://www.openstreetmap.org/)

### Charging stations  
* [Nobil-ladestasjoner-elbiler dataset from Nobil Transnova](https://data.norge.no/data/enova-sf/nobil-ladestasjoner-elbiler)
* [Charging station information from OpenStreetMap](https://www.openstreetmap.org/)

### Trips  
* [Open data about trips from Nasjonal Turbase](http://www.nasjonalturbase.no/)

## Source code
The source code of the showcase is available at GitHub:
- <https://github.com/OpenTransportDataProject/turplan>


## Demonstration
- Try [Turplan](http://showcase.opendatalab.no)
