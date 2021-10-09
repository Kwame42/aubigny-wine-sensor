# Aubigny Wine Sensor
## Introduction to Aubigny

Aubigny is an outstanding estate located in Burgundy (France) producing wine (Bourgogne White and red, white Rully Village and red Mercurey 1er Cru). I am lucky enough to animate the estate, and my background in software ... pushed me to create a set of tools to manage the estate!

## Sensor project
The idea is to collect as much data as possible to run the domain, and create tools to help for decision.

## information

Here you can only find a poor warpscript. I promised I will do an effort and write a full documentation for any farmer to be able to create it's own set of data. Anyway, everuything  I will do, I will published it, and create a "as a service version" (maybe with some maintenance fees, like 1$/months...) for any of my colleague farmer in the world...

## Technical info
- aubigny.mc2: warscript to collect the data from the sensor in the warp10. It connect in MQTT to TT_network and store each data of the sensor.
- sensor: warscipt to read data from sensor inside the grafana warp10 module

