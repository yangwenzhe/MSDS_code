# MSDS
Introduction
-------------
This repo holds the source code and scripts for reproducing the key experiments of 'Efficient Spatial Dataset Search over Multiple Data Sources'.

Requirements
============
* JDK == 1.8
* At least two devices


Usage
============
Dependency
-----------
*Please download the 'Quadtree' folder from the above './mvn_denpendency/Quadtree/' directory and put it in your own maven repository
*this 'Quadtree' dependency provide the implementation of comparison index "quadtree".


Parameter setting
-----------
* clientSize: set the number of data sources in MSDS-InteractionCenter/src/main/interactionCenter.java
* IPaddress: set the IP address of the interaction center device in MSDS-dataSource/src/main/dataSource.java

Run experiment
----------
* Run the MSDS-InteractionCenter on one device first
* After run MSDS-InteractionCenter, run the MSDS-dataSource on the other device