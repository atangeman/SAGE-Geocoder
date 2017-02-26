## Super-Accurate Geocoding Engine (SAGE)
is a Multi-Stage batch geocoder encorporating 
Google, Yahoo, and ArcGIS. 

Written in Python, the script was adapted to fit the ESRI ArcGIS 10.x ToolBox environment. By simply entering into ArcGIS, right clicking "ArcToolbox" and selecting "Add Custom Toolbox," a user can geocode using a variety of web geocoding API's with this custom module on the fly. 

## Purpose

Geocoding is one of the most important tools for a GIS Analyst, and also one of the most challenging to obtain. Specifically, choosing the correct geocoder can be cumbersome, especially if field values are incomplete or include special characters. ArcGIS offers a wide variety of ways to create geocoding tools out of street files, but what if the street layer you are using is out of date or invalid? 

GeoPy is an open-source library for Python that allows for records to be sent to one or more online geocoding engines for fast and efficient geocoding. Coupled with ArcGIS' capability for custom Python scripting, this module allows for custom-made geocoders to incorporate pre-filters not available through contemporary means. Specifically, by utilizing Python's text parsing capabilities, it is possible to recognize and filter records prior to processing.

## Instructions

Step 1: Add Custom Toolbox (If necessary) 

![Add Custom Toolbox](/ScreenCaptures/Step1.png)

Step 2. Open Script, Provide Inputs

![Open Script, Provide Inputs](/ScreenCaptures/Step2.png)

Step 3. Run Script and View Returns!

![ Run Script and View Returns](/ScreenCaptures/Step3.png)


Source code, toolbox, and Mxd document created by:

Andrew G. Tangeman (2014)
Department of Geography
San Diego State University

For questions or comments, please contact
the author above. For non-commercial use only.
 
