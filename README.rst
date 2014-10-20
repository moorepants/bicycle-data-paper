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
  - Matlab software

- Time sync

Experiments
-----------

- Manuever descriptions
- Rider descriptions
- Environments: treadmill, gym
- Description of data collection days

Data description
================

Meta Data
---------

Explain the run table meta data columns.

Raw Data
--------

Explain the raw measurements that came out of the onboard software. Make a
table.

Processed Data
--------------

- Explain all the processed values.
- How to compute all the interesting variables
- Software description

Data Availability
=================

- Raw mat files (runs and calibrations)
- HDF5 file with raw and some processed data
- A csv file with meta data in it?
