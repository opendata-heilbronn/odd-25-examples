# Example Projects for Open Data Day 25

This repository contains example projects for Open Data Day 25. This year, we are focusing on a city wide crowd density monitoring system. The goal is to create a system that can monitor crowd density in real-time and provide insights to the city officials to manage crowd density in the city.

## Project Ideas

## Sensors

Sensors will be build using ESP32 LORA boards. These sensors will be placed at different locations in the city to monitor crowd density. The sensors will be battery powered and will send data to a central server using LORA. The crowd size will be estimated using bluetooth signals from mobile phones.

## Working with the data

Since the system is not ready yet, we provided some examples of how the data might look like. We also provided a sample implementation of how the data can be visualized using leaflet in the sample-pax directory. Feel free to use this as a starting point for your project.

## Possible Projects

1. Trash collection optimization - Use crowd density data to optimize trash collection routes.
1. Revenue for local stores - Use crowd density data to estimate revenue for local stores.
1. Opening hours for local stores - Use crowd density data to estimate opening hours for local stores.

For a more realistiv approach with existing data, you can also have a look at the parkhausdaten -> https://ckan.cfhn.it/dataset/parkhaus-belegungsdaten or the more up to date version https://grafana.cfhn.it/d/opuCJ4vik/parkhausdaten-hn?orgId=1