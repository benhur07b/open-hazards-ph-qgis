# Open Hazards PH
**Open Hazards PH** is a QGIS plugin that lets you load geospatial hazard data created by various agencies in the Philippines. It uses data stored in [https://github.com/maning/open-hazards-ph](https://github.com/maning/open-hazards-ph).

## HOW-TO
### Install the plugin
The plugin is found in the QGIS Python Plugins Repository. The plugin can be downloaded [there](https://plugins.qgis.org/plugins/open_hazards_ph/) or within QGIS via the QGIS Plugin Manager. The plugin is tagged as experimental so make sure that you check the **Show experimental plugins** checkbox in the Settings tab of the Manage and Install Plugins window.

![Install Open Hazards PH in QGIS](https://raw.githubusercontent.com/benhur07b/open-hazards-ph-qgis/gh-pages/static/images/ohph_install.png)

### Run the plugin
![Run Open Hazards PH](https://raw.githubusercontent.com/benhur07b/open-hazards-ph-qgis/gh-pages/static/images/ohph_panel.png)

#### Select Data Source
Select from 'lipad' (LiDAR Portal for Archiving and Distribution) or 'noah' (Nationwide Operational Assessment of Hazards).

#### Select Data
Select the data you want to get/load.

#### Load Vector
Use this if the data to be loaded is a vector (check the name of the file to determine whether it's a vector or raster).

#### Load Raster
Use this if the data to be loaded is a raster(check the name of the file to determine whether it's a vector or raster).

#### Save Layer
When loaded, the layers are stored in memory. If you want to save a copy (file), you can **Right click on the layer -> Export -> Save as**.
![Open Hazards PH]('https://raw.githubusercontent.com/benhur07b/open-hazards-ph-qgis/gh-pages/static/images/ohph.gif')

----
### What is the license of the data?
We respect the license of the original source, each data source and data files have a corresponding license file. License varies from different agencies, in most cases government data are public domain.

### Most data archived here are available in other government websites, why do this?
Philippine government data policy changes from the tenure of an administration to another, we want to ensure
that what was public will remain public even if projects ran out of funds or there is a change in access policy.

### I found some cool hazards data, will you host it?
Yes! Please open a ticket on the [open-hazards-ph repo](https://github.com/maning/open-hazards-ph) and let's discuss.

### The open-hazards-ph repo is maintained by:
* Maning Sambale [[@maning](https://github.com/maning)]
* RK Aranas [[@rukku](https://github.com/rukku)]

### The Open Hazards PH QGIS plugin is maintained by:
* Ben Hur Pintor [[@benhur07b](https://github.com/benhur07b)]

### TO-DO/WISH LIST
* Add default symbology when loading layers
* Add ability to search/filter data
    * by name
    * by extent/area
* Add notification when plugin is running/done

### Pull Requests and Patches are most welcome!
