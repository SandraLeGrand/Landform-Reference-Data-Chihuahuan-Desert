# Landform Reference Dataset: Chihuahuan Desert Region

## Created 
Winter 2025

## Purpose
This repository contains a landform reference dataset for the Chihuahuan Desert region compiled by researchers from the U.S. Army Engineer Research and Development Center (ERDC).

## Dataset Authors
* Taylor S. Hodgdon (ERDC)
* Matthew F. Bigl (ERDC)
* Sandra L. LeGrand (ERDC)
* Brendan A. West (ERDC)
* Chelsea L. Dandridge (ERDC)

## Background
This dataset was compiled by combining published sources and geospatial analyst identification. Landform labels represent the dominant landform type within a 500m resolution grid cell.

## Field Descriptions
**Point_ID**: A unique identification string associated with the point record.

**Latitude_Published**: Latitude associated with the point record from the original source (decimal degrees). 

**Longitude_Published**: Longitude associated with the point record from the original source (decimal degrees). 

**Centroid_ID**: A unique identification string associated with the 500m grid cell centroid.

**Latitude_Centroid**: Latitude of the 500m grid box centroid associated with the point record (decimal degrees). 

**Longitude_Centroid**: Longitude of the 500m grid box centroid associated with the point record (decimal degrees). 

**Landform_Type**: Official landform classification determined by the analyst, that corresponds to a predefined mapping schema. 

**Landform_Type_Published**: Landform classification from original source.

**Confidence_Level**: A subjective, qualitative score reflecting the analyst’s self-assessed confidence in their chosen landform designation. Ranges in integer values from 0 to 3. 

**Comments**: Any relevant notes associated with the point record, including analyst commentary and information derived from published sources. 

**Reference**: Reference information associated with the point record. (Full list of references can be found below)

**Cook_Point**: Indicates the total number of landform reference examples in the grid cell that originated from the Cook et al. 2022 ERDC report.

**BLM_Point**: Indicates the total number of landform reference examples in the grid cell that originated from the BLM Assessment, Inventory, and Monitoring (AIM) dataset.

**NRCS_Point**: Indicates the total number of landform reference examples in the grid cell that originated from the USDA NRCS pedon dataset.

**Derivation**: Letter (A, B, or C) to indicate if the landform designation was derived from published data. 

* A = Landform type and location were derived from a published source. 

* B = Landform designation was subjectively determined by an analyst to be a continuation of a neighboring landform point identified in a published source. 

* C = Landform designation was subjectively determined by an analyst.

## Contents of Zip File

* Landform_Reference_Data-Chihuahuan_Desert.cpg
* Landform_Reference_Data-Chihuahuan_Desert.dbf
* Landform_Reference_Data-Chihuahuan_Desert.prj
* Landform_Reference_Data-Chihuahuan_Desert.sbn
* Landform_Reference_Data-Chihuahuan_Desert.sbx
* Landform_Reference_Data-Chihuahuan_Desert.shp
* Landform_Reference_Data-Chihuahuan_Desert.shp.xml
* Landform_Reference_Data-Chihuahuan_Desert.shx 

## Data Source References
* Börker, J., J. Hartmann, T. Amann, and G. Romero-Mujalli. 2018. "Terrestrial Sediments of the Earth: Development of a Global Unconsolidated Sediments Map Database (GUM)." Geochemistry, Geophysics, Geosystems 19, 997–1024. https://doi.org/10.1002/2017GC007273.
* Bullard, J. E., S. P. Harrison, M. C. Baddock, et al. 2011. “Preferential Dust Sources: A Geomorphological Classification Designed for Use in Global Dust-Cycle Models.” Journal of Geophysical Research 116(F4): F04034. https://doi.org/10.1029/2011JF002061.
* Cook, S. N., M. F. Bigl, S. L. LeGrand, N. Webb, G. Tyree, and R. Treminio. 2022. Landform Identification in the Chihuahuan Desert for Dust Source Characterization Applications: Developing a Landform Reference Data Set. ERDC TR-22-20. US Army Engineer Research and Development Center. http://dx.doi.org/10.21079/11681/45644.
* Hall, S. A., M. R. Miller, and R. J. Goble. 2010. “Geochronology of the Bolson Sand Sheet, New Mexico and Texas, and Its Archaeological Significance.” Geological Society of America Bulletin 122 (11–12): 1950–1967. https://doi.org/10.1130/B30173.1. 
* Hawley, J. W., D. J. McCraw, D. W. Love, and S. D. Connell. 2021. “Map of Surficial Geologic Materials of New Mexico.” New Mexico Bureau of Geology and Mineral Resources. https://doi.org/10.58799/OF-GM-295.
* KellerLynn, K. 2012. White Sands National Monument: Geologic Resources Inventory Report. Natural Resource Report NPS/NRSS/GRD/NRR—2012/585. National Park Service. https://irma.nps.gov/DataStore/DownloadFile/456858.
* Lee, J. A., M. C. Baddock, M. J. Mbuh, and T. E. Gill. 2012. “Geomorphic and Land Cover Characteristics of Aeolian Dust Sources in West Texas and Eastern New Mexico, USA.” Aeolian Research 3(4): 459–466. https://doi.org/10.1016/j.aeolia.2011.08.001.
* Monger, H. C., G. H. Mack, B. A. Nolen, and L. H. Gile. 2006. “Regional Setting of the Jornada Basin.” In Structure and Function of a Chihuahuan Desert Ecosystem: The Jornada Basin Long-Term Ecological Research Site, edited by Kris M. Havstad, Laura F. Huenneke, and William H. Schlesinger. Oxford University Press.
* NCSS (National Cooperative Soil Survey). 2020. National Cooperative Soil Survey Characterization Database. Accessed 1 July 2021. http://ncsslabdatamart.sc.egov.usda.gov. 
* Stoeser, D. B., G. N. Green, L. C. Morath, et al. 2005. Preliminary Integrated Geologic Map Databases for the United States: Central States: Montana, Wyoming, Colorado, New Mexico, North Dakota, South Dakota, Nebraska, Kansas, Oklahoma, Texas, Iowa, Missouri, Arkansas, and Louisiana. Report 2005–1351. Version 1.2, December 2007. Open-File Report. USGS Publications Warehouse. https://doi.org/10.3133/ofr20051351.
* Taylor, J., E. Kachergis, G. R. Toevs, et al. 2014. AIM-Monitoring: A component of the BLM Assessment, Inventory, and Monitoring Strategy. Technical Note 445. US Department of the Interior, Bureau of Land Management, National Operations Center. Accessed 16 April 2025. https://www.blm.gov/sites/default/files/documents/files/Library_BLMTechnicalNote445.pdf.
* USDA (US Department of Agriculture). n.d. National Soil Information System (NASIS). Accessed 1 July 2021. https://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/tools/?cid=nrcs142p2_053552.
