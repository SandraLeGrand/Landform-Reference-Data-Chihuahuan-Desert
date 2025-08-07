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

## Data Source References
* Cook, S. N., Bigl, M. F., LeGrand, S. L., Webb, N., Tyree, G., & Treminio, R. (2022). Landform Identification in the Chihuahuan Desert for Dust Source Characterization Applications.
* Hawley, J.W., McCraw, D.J., Love, D.W., and Connell, S.D., Map of Surficial Geologic Materials of New Mexico, The New Mexico Bureau of Geology and Mineral Resources and The New Mexico Institute of Mining and Technology, Open-File Geologic Map 295, https://doi.org/10.58799/OF-GM-295, Cartography by: Miller, P.L., Dunn, A.L., Knight, A.D., and Nicolette, J.L., Digital Database, Scale:  1:500,000
* Stoeser, D.B., Green, G.N., Morath, L.C., Heran, W.D., Wilson, A.B., Moore, D.W., and Van Gosen, B.S., Preliminary Integrated Geologic Map Databases for the United  States Central States: Montana, Wyoming, Colorado, New  Mexico, Kansas, Oklahoma, Texas, Missouri, Arkansas, and Louisiana, - The State of Texas, U.S. Geological Survey, Open-File Report 2005-1351, http://pubs.usgs.gov/of/2005/1351/, Digital Data, Scale: 1:500,000
* Bullard, J. E., Harrison, S. P., Baddock, M. C., Drake, N., Gill, T. E., McTainsh, G., and Sun, Y.: Preferential dust sources: A geomorphological classification designed for use in global dust-cycle models, J. Geophys. Res., 116, F04034, https://doi.org/10.1029/2011JF002061, 2011. (Open access journal article)
* Baddock, M. C., Gill, T. E., Bullard, J. E., Acosta, M. D., and Rivera Rivera, N. I.: Geomorphology of the Chihuahuan Desert based on potential dust emissions, J. Maps, 7, 249–259, https://doi.org/10.4113/jom.2011.1178, 2011.
* Lee, J. A., Baddock, M. C., Mbuh, M. J., and Gill, T. E.: Geomorphic and land cover characteristics of aeolian dust sources in West Texas and eastern New Mexico, USA, Aeolian Res., 3, 459–466, https://doi.org/10.1016/j.aeolia.2011.08.001, 2012.
* Lee, J. A., Gill, T. E., Mulligan, K. R., Dominguez Acosta, M., and Perez, A. E.: Land use/land cover and point sources of the 15 December 2003 dust storm in southwestern North America, Geomorphology, 105, 18–27, https://doi.org/10.1016/j.geomorph.2007.12.016, 2009.
* Monger, H. C., Mack, G. H., Nolen, B. A., and Gile, L. H.: Regional setting of the Jornada Basin, in: Structure and Function of a Chihuahuan Desert Ecosystem: The Jornada Basin Long-Term Ecological Research Site, edited by: Havstad, K. M., Huenneke, L. F., and Schlesinger, W. H., Oxford University Press, 15–43, 2006.
* KellerLynn, K. 2012. White Sands National Monument: geologic resources inventory report. Natural Resource Report NPS/NRSS/GRD/NRR—2012/585. National Park Service, Fort Collins, Colorado, USA. {available at https://irma.nps.gov/DataStore/DownloadFile/456858; last access: 26 October 2023}
