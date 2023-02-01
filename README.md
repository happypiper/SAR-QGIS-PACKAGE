# DESCRIPTION

This repository stores the python package created to assist Midland County Search and Rescue members in operating the QGIS software package to create maps. The initial phase of the project/package will be to deliver initial search maps and include the creation of Koester objects, Koester rings by POA, and include TOPOs, Sat maps, and street maps in pdf form for printout. The maps will be delivered to a standardized current search directory, mimicing existing processes. The package design intention is to create objects that can be loaded, edited, and managed by gui within QGIS, but which will be operated by more highly trained users doing package maintenance. The package itself needs to have a simple enough interface that the initial search maps can be generated by someone with less than 30 mminutes training. The normal operation of the package will initially involve a short script driven interaction with the user to develop the inital search areas. 

# Licensing

The licensing will be the standard licensing called out by the QGIS and QT software aps.Neither of these will be revised in any way, but will be used to create the package.

# Plan

-   Contact the QGIS developers chat / support rooms and seek advice on what to copy / how best to proceed.

-   Ruthlessly copy an existing package that delivers 80% of the GUI and minimizes our work

-   Identify where to source the OSM database for the lower penn of MI

-   Disucss sourcing the topos from the USGS with USGS experts. Their web sites seem to understand the need/direction.

-   Bone up on Git use and leverage the tools on the Github web where possible.
