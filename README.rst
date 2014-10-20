Build Instructions
==================

Make sure you have a LaTeX suite installed and simply type ``make`` at the
command line or checkout the ShareLaTeX CI build.

.. image:: https://www.sharelatex.com/github/repos/moorepants/bicycle-data-paper/builds/latest/badge.svg
   :target: https://www.sharelatex.com/github/repos/moorepants/bicycle-data-paper/builds/latest/output.pdf

Journal
=======

I'm planning to submit this as a "Data Note" to F1000Research.

Authors
=======

- Jason K. Moore
- Mont Hubbard

Introduction
============

- Reason for collecting data: identify human control
- Possible uses for the data.

Methods
=======

Equipment: Instrumented Bicycle
-------------------------------

- Bicycle
- Rigidifying the rider
- Kinematic measurements

   - Rear frame rates and accels
   - Roll angle and steer angle
   - Rear wheel rate

- Kinetic measurements

  - Steer torque: cite other paper
  - Lateral force

- Calibration procedures
- Data acquisition

  - NI box
  - Laptop
  - Strain gauge amp
  - Matlab software, BicycleDAQ

- Time sync

Experiments
-----------

- Manuever descriptions
- Rider descriptions
- Environments: treadmill, gym
- Description of data collection days

Data description
================

Report some stats about the data, i.e. how many runs, how many of each type,
how many valid (not corrupt), etc.

Meta Data
---------

Explain the run table meta data columns.

Raw Data
--------

Explain the raw measurements that came out of the onboard software. Make a
table.

Make a plot of the raw data. Maybe for one treadmill and one pavillion trial
group like measurements into subplots.

Processed Data
--------------

- Explain all the processed values.
- How to compute all the interesting variables
- Software description, BicycleDataProcessor

Make a plot of the processed data. Maybe for one treadmill and one pavillion
trial group like measurements into subplots. Similar to:

http://moorepants.github.io/dissertation/_images/time-history-treadmill.png

Data Availability
=================

- Raw mat files (runs and calibrations)
- HDF5 file with raw and some processed data
- A csv file with meta data in it?
