# Theory

Planning



* [Rebreather Rule of Thirds](http://www.cavedivers.com.au/rebreather-gas-management-vs-the-rule-of-thirds) (JDZ)
* [Cave DPV Planning](http://www.divegainesville.org/cave-dpv-dive-planning/)
* [Bailout Planning](https://www.tdisdi.com/tdi-diver-news/an-updated-approach-to-bailout-planning/)
* [GUE Standard Gases](https://www.baue.org/procedures/standardmixes.php)

Psychology



* [“Slow Down Young Fella”](https://www.tdisdi.com/tdi-diver-news/slow-down-young-fella-attitudes-in-technical-diving/) Tech Attitudes
* [Lessons From Overhead](https://dtmag.com/thelibrary/cave-diving-overhead-environment/)
* [Cave Stress Control](https://www.protecblog.com/641/psychological-adjustment-and-stress-control/)

Decompression



* [Dive Rite - Gradient Factors Explainer](https://www.diverite.com/articles/gradient-factors/)
* [Eliminating the Helium Penalty](https://www.shearwater.com/monthly-blog-posts/eliminating-helium-penalty/) & Heliox vs Trimix - Mitchell 
    * Same deco time, but more in shallows
* [Avoiding Deep Stops](https://gue.com/blog/gradient-factors-in-a-post-deep-stops-world/) - Doolette (GFLow = 83% of GFHigh) [eg. 60/85 or 50/70]
* [Metabolism-Based Bubble Model](https://alertdiver.eu/en_US/articles/it-s-the-metabolism-stupid-a-new-model-for-bubble-formation?fbclid=IwAR3fzHqnAMG0Gxa0u3hd-K7puzcPoLO-SoRMZKPlqR-I8g4VjiSAGnxvjAE)

Super Deep



* [Raising The Dead (Outside)](https://www.outsideonline.com/1922711/raising-dead)
* [Will Goodman 300m Dive Diary](https://blackwatertek.com/divers-diary/)
* [Jim Bowden - Zacaton](https://www.tdisdi.com/aquacorps/jim-bowden/)

# Ideas & Tech 

## Radiolocators & GPR
* Pingers ([CDAA Page](http://www.cavedivers.com.au/simple-underwater-radiolocation-system))
* [DIY Radiolocator Kits](https://radiolocation.weebly.com/basic-1--basic2-radios.html)
* Thumpers (JDZ)
* Cocklebiddy Cache (Contains ground-wave SMS device?)
* GPR Unit

## Satellite Imagery & GIS

* **[QGIS](https://qgis.org/en/site/)**
    * [GPSBabel to Convert Coordinates](https://www.gpsbabel.org/)
    * Use QGIS to analyse [NovaSAR data](https://data.novasar.csiro.au/#/home)
    * **Hyperspectral remote sensing **[to find wombat warrens](https://www.abc.net.au/news/2020-05-18/hairy-nosed-wombat-survey-satellite-imagery-sa-murray-mallee/12258398)
    * **Lidar** - Forestry Survey data?
    * Use remote sensing for groundwater detection
    * Drone survey - Integrate with QGIS to record survey zones
* Geodata Sets
    * **[Open Data Cube](https://www.opendatacube.org/)** [IMPORTANT] 
        * [CSIRO EASI](https://research.csiro.au/cceo/underpinning-technologies/earth-analytics/) platform
    * [AWS Open Data Registry](https://registry.opendata.aws/) 
        * Collect Cave data and add to this?
    * [AuScope](http://avre.auscope.org/store) (Wide range of tools available)
    * [Geoscience Aus - Surface Topo](http://maps.ga.gov.au/interactive-maps/#/theme/minerals/map/geology), [Full Topo Map Index](https://geoscience-au.maps.arcgis.com/apps/opsdashboard/index.html#/5908193d3a834e35bb8fbff0e252c08b)
    * [Geophysical Archive Data Delivery System](https://portal.ga.gov.au/persona/gadds)
    * [ArcGIS Hub](https://hub.arcgis.com/search?categories=environment)
    * [Sentinel Earth Observation Browser](https://apps.sentinel-hub.com/eo-browser/)
    * [BOM - Groundwater Explorer](http://www.bom.gov.au/water/groundwater/explorer/map.shtml)
    * [TanDEM-X SAR Dataset](https://data.europa.eu/data/datasets/5eecdf4c-de57-4624-99e9-60086b032aea?locale=en)
    * [Nine Free Satellite Data Sources](https://skywatch.com/free-sources-of-satellite-data/)
    * [SARIG](https://map.sarig.sa.gov.au/) (SA Gov)
        * Look at conductance & electromagnetic?
        * Use “Shallow Groundwater Yield” layer 
        * Use Gravity UC1000 Residual
        * Use Total Magnetic Intensity VRTP 1st vert derivative** [VERY INTERESTING]**
        * Use Radiometrics 
            * DOSE
            * Potassium - Interesting results, different to topo
            * Ternary - Very interesting results, wildly different to topo
            * Uranium - low Res but interesting results different to topo
            * Thorium - Limited use, mostly matches irrigated areas
        * Remote Sensing - Use False-Colour Composite & Ferric Oxide Composition
    * [Virtual Geophysics Lab](https://vgl.auscope.org/) - Auscope
        * Use “Total Magnetic Intensity (TMI) Colour Composite Image of Australia with Variable Reduction to Pole (VRTP) 2015”
        * Use “Gravity Anomaly Greyscale Image of the Australian Region - 2010”
* Machine Learning to ID sites
    * [Leak detection using sat images & machine learning](https://threespringstechnology.com/projects/leak-detection/)
    * [Yolo3 object detection How-To](https://machinelearningmastery.com/how-to-perform-object-detection-with-yolov3-in-keras/)
    * Use AWS for IDing caves on Nullabor/Cape Range (ASF/WASG database?) 
