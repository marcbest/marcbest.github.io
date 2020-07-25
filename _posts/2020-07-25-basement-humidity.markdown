---
title: "🌡️ Using a Raspberry pi to monitor temperature and humidity"
layout: post
date: 2019-11-25 08:00
tag: [python, influxdb, raspberrypi, bme280, grafana]
image: https://koppl.in/indigo/assets/images/jekyll-logo-light-solid.png
headerImage: false
projects: true
hidden: true # don't count this post in blog pagination
description: "Monnitoring basement temperature and humidity with a Raspberry pi"
category: project
author: Marc Best
externalLink: false
---

Using a Raspberry Pi & [OpenWeatherMap](https://openweathermap.org/) to measure basement and outside temperature and humidity.

Also uses Influxdb and Grafana to store and view data

![Alt text](../assets/images/posts/pi-grafana.png?raw=true "Grana Dashboard")

### Pi script
Set the following [code](https://github.com/marcbest/home_automation_scripts/blob/master/pi_to_influx.py) to run via a cron job on the Pi

Followed this [tutorial](https://medium.com/initial-state/how-to-build-a-crawl-space-humidity-monitor-with-a-raspberry-pi-669f2a632cf4) for Pi sensor setup 

### OpenWeatherMap
Set the following [script](https://github.com/marcbest/home_automation_scripts/blob/master/outside_temp_to_influx.py) to run via a cron job somewhere to pull data from the OpenWeatherMap and insert it into Influxdb

---

[find the code on Github here](https://github.com/marcbest/home_automation_scripts).

---



