<div id="top"></div>

<!-- PROJECT LOGO -->
<br />
<div align="center">


  <h3 align="center">Data-Driven Fault Detection in Autonomous Drone</h3>

  <p align="center">
    Designing and Implementing a Fault detector and a Sliding Window 
    <br />
    <b> Training and Testing on AirLab Failure and Anomaly(ALFA) Dataset </b>
    <br />
    <b> An Electrical Engineering final B.Sc. Project </b>
    <br />
    <a href="https://github.com/HabibNaeimi/Data-Driven-Fault-Detection"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/HabibNaeimi/Data-Driven-Fault-Detection//issues">Report Bug & Request Feature</a>
  </p>
</div>





## About The Project
This repository contains the Python implementation of "Data-Driven Fault Detection in Autonomous Drones," an Electrical Engineering final B.Sc. project by *Habibollah Naeimi* at the Petroleum University of Technology.


This project has developed a fault detector based on the Support Vector Machine (SVM) classification method. The data are from the [ALFA dataset](https://theairlab.org/alfa-dataset/) by AirLab Failure and Anomaly at Carnegie Mellon University in Pittsburgh, Pennsylvania, USA. Three Fault detectors have been developed during this project for three datasets of engine faults, including GPS, Compass, and Global Location data. 

Also, a sliding Window is developed for each detector in order to make the detector's output smoother and raise its stability.

Implementation of these classifiers is in Python programming language by using scikit-learn library. The sliding windows are also implemented in Python.
