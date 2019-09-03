# Predictive Maintenance using Machine Learning
## Overview
This project is done as a Capstone Project required for Udacity's Machine Learning Nanodegree program. 

In this capstone project we have explored how to effectively undertake the journey from the paradigm of Preventive Maintenance (scheduled, time-based maintenance) to the paradigm of Predictive Maintenance, where we are able to predict when a failure may occur based on the telemetry data coming from variety of the sensors on the equipment and machinery.

## Project Introduction
It is assumed that the sensor and telemetry data from the air-turbine have hidden patterns related to engine’s health and condition, and thus can be used the predict the TTF (time-to-failure) or RUL (remaining-useful-life) for an engine. 

This way the maintenance activities can be planned based on the TTF predictions complementing the time-based maintenance activities (and eventually replacing this approach for full-fledged predictive maintenance)

In this project we have peformed following predictions at a high level
•	Use of regression algorithms to predict TTF (time-to-failure)
•	Use of binary classification algorithms to predict if engine will fail in the current period
•	Use of multi class classification algorithms to predict in which period an engine will fail.

## Project Data
The sensor telemetry data from the equipment and production assets is sensitive and is not freely available.

For this reason in this project we have used Turbofan Engine Degradation Simulation dataset provided by the NASA’s prognostic centre. The dataset and the details of the simulation setup can be accessed from the following link:

http://ti.arc.nasa.gov/project/prognostic-data-repository 

## Project Files
[1. Data Processing] (https://github.com/sanjaysoni2k1/Predictive-Maintenance/blob/master/1.%20PredMaint-DataProcessing.ipynb)
