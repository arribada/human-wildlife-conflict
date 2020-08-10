## human-wildlife-conflict
# Datasets &amp; technology development of human wildlife conflict solutions.

The Arribada Initiative is actively working to develop in-field early warning systems utilising thermal technologies. This repository hosts the data, software and hardware designs for both our field research and prototype solutions.

We are currently focused on two species;

* Early warning / detection of **elephants** using microbolometer sensors & edge machine learning
* Early warning / detection of **polar bears** using microbolometer sensors & edge machine learning

# Hackster.io / SmartParks ElephantEdge Competition

Arribada's thermal elephant dataset collected at ZSL Whipsnade Zoo is open source (GPLv3) and available for use by anyone wishing to train their own models thermal / optical models for the **ElephantEdge** competition, hosted by Hackster.io and SmartParks. Arribada is also a partner of the [OpenCollar](https://opencollar.io) initiative and is delighted to support the development opportunity to incorporate an open camera system with inference on the edge.

## Overview of datasets available

As part of the WWF Human Wildlife Tech Challenge, Arribada was tasked with developing an early warning system capable of detecting Asian elephants and carnivores, specifically tigers & polar bears. We focused on elephants and polar bears first, partnering with ZSL Whipsnade Zoo to capture thermal photographs of the Asian elephant herd using FLIR Lepton 2.5 and 3.5 microbolometer sensors (80x60 and 160x120 respectively). You can read more about our [data collection methodology](https://blog.arribada.org/2020/02/17/progress-report-feburart-2020-thermal-imaging-for-human-wildlife-conflict/) or the [original WWF competition here.](https://www.wwf.org.uk/updates/human-wildlife-conflict-tech-challenge-winners-announced).

# Elephant dataset

Files are named by date, time, camera number and sensor used. E.g. *20190901_1000_1030_CAMA1_3.5b*

These are organised into the meta-folder ‘Original Folders’. Photos from DIY cameras which needed converting from BMP into PNG are maintained in original format and have been converted into PNG’s in separate folders titled “Converted to PNG” or similar.

Adobe bridge has been used to organise data into collections based on various variables:

*	Sensor used (3.5 or 2.5)
*	What labelling project they were used in (algorithm test 1, 2, sensor test 2.5 or 3.5)
*	The distance the elephant or human is from the camera (in 5 metre increments)
*	The object (human, single elephant, multiple separate elephants, multiple obstructing elephants, goats)
*	The angle of the elephant (head, side, rear) 

If there was more than one elephant in the image and they were at different distances/angles, the image was sorted into all applicable categories. E.g. one elephant 0-5m from camera at a side angle, and another 10-15m and head on to the camera would be sorted into: 0-5m, 10-15m, head & side collections. 

You can download and access the 
 


