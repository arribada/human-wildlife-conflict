## human-wildlife-conflict
# Datasets &amp; technology development of Arribada's human wildlife conflict solutions.

The Arribada Initiative is actively working to develop in-field early warning systems utilising thermal technologies. This repository hosts the data, software and hardware designs for both our field research and prototype solutions.

We are currently focused on two species;

* Early warning / detection of **elephants** using microbolometer sensors & edge machine learning
* Early warning / detection of **polar bears** using microbolometer sensors & edge machine learning

# Hackster.io / SmartParks ElephantEdge Competition

Arribada's thermal elephant dataset collected at ZSL Whipsnade Zoo is open source (GPLv3) and available for use by anyone wishing to train their own models thermal / optical models for the **ElephantEdge** competition, hosted by Hackster.io and SmartParks. Arribada is also a partner of the [OpenCollar](https://opencollar.io) initiative and is delighted to support the development opportunity to incorporate an open camera system with inference on the edge.

## Overview of datasets available

As part of the WWF Human Wildlife Tech Challenge, Arribada was tasked with developing an early warning system capable of detecting Asian elephants and carnivores, specifically tigers & polar bears. We focused on elephants and polar bears first, partnering with ZSL Whipsnade Zoo to capture thermal photographs of the Asian elephant herd using FLIR Lepton 2.5 and 3.5 microbolometer sensors (80x60 and 160x120 respectively). You can read more about our [data collection methodology](https://blog.arribada.org/2020/02/17/progress-report-feburart-2020-thermal-imaging-for-human-wildlife-conflict/) or the [original WWF competition here.](https://www.wwf.org.uk/updates/human-wildlife-conflict-tech-challenge-winners-announced).

# Elephant dataset

Total number of photographs: **75,830**
Total size: **550MB**

Adobe bridge has been used to organise data into collections based on various variables:

**Angle**
* -- Front
* -- Rear
* -- Side

**Distance**
* -- 0-5m
* -- 5-10m
* -- 10-15m
* -- 15-20m
* -- 20-25m
* -- 25m+

**Object**
* -- Goat
* -- Human
* -- Human & Elephant
* -- Multiple obstructing elephants
* -- Multiple separate elephants
* -- Single elephant

**Sensor**
* -- Lepton 2.5
* -- Lepton 3.5

If there was more than one elephant in the image and they were at different distances/angles, the image was sorted into all applicable categories. E.g. one elephant 0-5m from camera at a side angle, and another 10-15m and head on to the camera would be sorted into: 0-5m, 10-15m, head & side collections. 
 


