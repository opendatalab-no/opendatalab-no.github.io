---
title: "FiskInfo (Fish Info)"
permalink: /showcases/fiskinfo/
excerpt: "Fiskinfo"
last_modified_at: 2018-08-15T12:00:00 +01:00
redirect_from:
  - /fiskinfo/
toc: true
gallery:
  - url: /assets/images/fiskinfo-screen3.jpg
    image_path: /assets/images/fiskinfo-screen3.jpg
    alt: "Overview"
    title: "Overview"
  - url: /assets/images/fiskinfo-screen2.jpg
    image_path: /assets/images/fiskinfo-screen2.jpg
    alt: "Reporting of fishing equipment"
    title: "Reporting of fishing equipment"
  - url: /assets/images/fiskinfo-screen1.jpg
    image_path: /assets/images/fiskinfo-screen1.jpg
    alt: "Map showing current locations of fishing equipment in use"
    title: "Map showing current locations of fishing equipment in use"
---

## About the case

The goal of FiskInfo is to be a one-stop-shop for digital distribution of important information for the fishing fleet. 

FiskInfo is developed by [SINTEF](https://www.sintef.no) in collaboration with [Fiskeri- og havbruksnæringens Forskningsfond (FHF)](http://www.fhf.no/) and [Barentswatch](https://www.barentswatch.no/). 

FiskInfo is available as a [web site from Barentswatch](https://www.barentswatch.no/en/fishinfo/) and as a mobile app for [Android](https://play.google.com/store/apps/details?id=fiskinfoo.no.sintef.fiskinfoo&hl=no) and [iOS](https://itunes.apple.com/no/app/fiskinfo/id1081341585?mt=8). This showcase description covers only the mobile app developed by SINTEF, with some reference to resources from Barentswatch.

{% include gallery %}

## Functionality

The FishInfo app offers a map with multiple layers that enable fishermen to have an update view of the seas in which they operate. Layers available include:
- Vessel postitions (AIS)
- Active fishing facilities (e.g. nets, lines, crab pots)
- Subsea facilities
- Restriction zones, e.g coral reefs
- Planned and ongoing seismic activity
- Ice concentration and ice edge

A popular feature of the app is reporting of deployment and retieval of fishing equipment, where the current GPS position can be used to speed up the process. Reports are sent to the Coast Guard (Kystvaktsentralen).

Map layers can also be downloaded for use with map plotters and other equipment.

Some of the map layers and functionality of the app is only available for users with registered fishing vessels.

The FiskInfo app is under ongoing further development, and among the plans is new functionality that provides decision support for chosing the best time and location for getting the right catch.

## Open data sources used

The app uses open data from multiple sources: 
Maps and map layers:
* [Official maps and layers from Statens Kartverk](https://www.kartverket.no/kart/)
Via Barentswatch APIs:
* Ice concentration and ice edge (met.no)
* Fishery regulations (fiskeridirektoratet)
* Seismic surveys and subsea facilities (Oljedirektoratet)
* Bottom types (NGU)

## Other data sources used
- Position of active fishing factilities (Coast Guard)
- AIS (The Norwegian Coastal Administration)

## Source code
The source code of the Android version of FiskInfo is available at GitHub:
- <https://github.com/PeterHaro/Fiskinfoo>

## App download
- Try [FiskInfo for Android](https://play.google.com/store/apps/details?id=fiskinfoo.no.sintef.fiskinfoo&hl=no)
- Try [FiskInfo for iOS](https://itunes.apple.com/no/app/fiskinfo/id1081341585?mt=8)
