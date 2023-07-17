# CARLA Dataset Generation Module

Code coming soon

## Table of Contents
1. [Introduction](#intro)
2. [Requirements and Installation](#installation)

## Introduction  <a name="intro"></a>
This repository contains a script and config file to generates a dataset of ground vehicle and drone sensor outputs. Sensor types are configurable from a `.yaml` file and allow the user to specify any of the available sensors in Carla (RGB, semantic segmentation, instance segmentation, depth, LIDAR, and [more](https://carla.readthedocs.io/en/latest/core_sensors/#types-of-sensors)) .

The script supports generating data across different maps and weather conditions. By default, all of the weather conditions will be cycled through to render images.

IMPORTANT: To generate data using this script, the Carla environment must already be running. In a separate terminal, simply execute the run_carla.sh shell script. It will start Carla in no-rendering mode, which creates and executes the simulation environment but does not display it. This can be changed in the shell script.

## Requirements and Installation <a name="installation"></a>
Clone the repository into your working directory and install the dependencies

## Coming soon
- [ ] Log the loss functions during validation
- [ ] Compute and log average and mean average precision during training and validation.
- [ ] Make map, weather, number of images to generate, and output directory as fields in the `.yaml` file
