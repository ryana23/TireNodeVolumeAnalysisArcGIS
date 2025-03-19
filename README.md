# TireNodeVolumeAnalysisArcGIS
Python export from the ArcPro toolbox created by WA DNR's GIS unit and Nearshore Science group.

Artificial Tire Reef Survey Project:
ArcGIS Volume Analysis Tool Use Guide
Tyler Cowdrey
Aquatic Assessment and Monitoring Team
Washington Dept. of Natural Resources


This brief README describes how to use the “Tire Node Volume Analysis” tool in ArcGIS Pro to generate analysis layers and an estimated volume output for artificial tire reef sites surveyed by DNR's Aquatic Assessment and Monitoring Group. The tool was created using the Python scripting language in the program PyCharm for use in ESRI’s ArcGIS Pro software. It requires that collected multi-beam echosounder (MBES) bathymetric data be cleaned in Qimera (or comparable software) and manually processed for tire “nodes” (described in a seperate "Analysis Protocol" document) prior to running, but is otherwise designed to complete the analysis autonomously.

The purpose for developing this tool was to: a) reduce the amount of work required by AAMT staff to manually process each tire reef site, thus improving the project’s efficiency, and b) to create a processing workflow that minimized the potential for human error to the greatest extent possible. In pursuit of these goals, many iterations were created and tested against one another for accuracy and reliability in consideration of the diverse sites tire reefs are being surveyed at.
