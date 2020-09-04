# LandSuitabilityAnalysisToolForManureUtilization
This repository contains ArcGIS-based Land Suitability Analysis tools developed for Sustainable Manure Utilization

*This README.md file was generated on 20200904 by GOURAB K SAHA*


General Information
---

### Title: LAND SUITABILITY ANALYSIS TOOLS FOR SUSTAINABLE MANURE UTILIZATION

*Data and Code for "Against Lorem Ipsum: A History of Filler Text"*

### Author Information:

- Principal Investigator:
		Name: Dr. Cibin Raj
		Institution: Pennsylvania State University
		Address: 247 Agricultural Engineering Building
		Email: czr58@psu.edu

- Associate or Co-investigator:
		Name: Dr. Herschel Elliott, PE
		Institution: Pennsylvania State University
		Address: 253 Agricultural Engineering Building
		Email: hae1@psu.edu

		Name: Dr. Heather Preisendanz
		Institution: Pennsylvania State University
		Address: 252 Agricultural Engineering Building
		Email: heg12@psu.edu

- Alternate Contact(s):
		Name: Gourab Kumer Saha
		Institution: Pennsylvania State University
		Address: 208 Agricultural Engineering Building
		Email: gks13@psu.edu

### Date of data collection/creation: 20160101 to 20191231 (used readily avialable data collected by different federal and state agencies). 

### Geographic location of data collection: Armstrong County, Indiana County, Westmoreland County, Pennsylvania, United States of America

### Funders and sponsors of data collection: Pennsylvania Department of Agriculture, USDA National Institute of Food and Agriculture Federal Appropriations 
											under Project PEN04574 and Accession number 1004448, and USDA-NIFA Federal Appropriations under Project PEN04629 
											and Accession number 1014132.

Sharing/Access Information
---

### License & restrictions on data reuse: No restriction for share and adapt. Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)

### Recommended citation for the data: Saha, G., Cibin, R., Elliott, H., & Preisendanz, H. (2020). Land Suitability Analysis Tools
									   for Sustainable Manure Utilization. https://doi.org/10.26207/99tk-sn24.

### Related publications: Saha, G., Cibin, R., Elliott, H., & Preisendanz, H. (2020). Development of A Land Suitability Framework 
						  for Sustainable Manure Utilization. Transactions of the ASABE (In press).


### Links to other publicly accessible locations of the data: Github repository (CompEcohydrology-psu/LandSuitabilityAnalysisToolForManureUtilization).
															Available at https://github.com/CompEcohydrology-psu/LandSuitabilityAnalysisToolForManureUtilization

### Related data sets: 
					1. Land-use/land cover data (USDA-NASS; https://nassgeodata.gmu.edu/CropScape/)
					2. Floodplains data (National Flood Hazard Layer (NFHL), collected by FEMA; https://msc.fema.gov/portal/advanceSearch)
					3. Streams data (National Hydrography Dataset (NHD), collected by USGS; https://viewer.nationalmap.gov/basic/)
					4. Elevation data (Digital Elevation Model (DEM), collected by USGS; https://viewer.nationalmap.gov/basic/)
					5. Soil data (USDA-NRCS; https://websoilsurvey.sc.egov.usda.gov/App/WebSoilSurvey.aspx)
					6. Precipitation data (Monthly Climate Normals (1981-2010, collected by NOAA-NCDC; https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND)
					7. Soil erodibility factor (K factor) data (from Soil Data Viewer 6.1; collected by USDA-NRCS; https://www.nrcs.usda.gov/wps/portal/nrcs/detail/soils/survey/geo/?cid=nrcs142p2_053619)


Data & File Overview
---

### File list:

•	This repository has three folders. Those folders area Toolboxes, Documents, and Sample_Data. 


•	'Toolboxes' folder includes two sub-folders: 1) ArcGIS_Toolboxes_for_Land_Suitability_Analysis, and 2) Model_Builder_based_Land_Suitability_Analysis_Tool. 

	•	1) ArcGIS_Toolboxes_for_Land_Suitability_Analysis folder contains two sub-folders: a) ArcGIS_Toolboxes and b) Final_Code_Scripts_for_ArcGIS_Toolboxes.
		 
		•	a) 'ArcGIS_Toolboxes' folder contains 9 ArcGIS toolboxes (ArcMap version 10.7 which is compatible with). 

				(i) Final_Land_Suitability_Analysis_Toolbox.tbx
				(ii) Floodplains_Identification_Toolbox.tbx
				(iii) Karst_Area_Identification_Toolbox.tbx
				(iv) Leaching_Index_based_Area_Classification_Toolbox.tbx
				(v) Pennsylvania_P_Index_based_Area_Classification_Toolbox.tbx
				(vi) Potential_Area_Identification_Toolbox.tbx
				(vii) Proximity_to_Streams_Identification_Toolbox.tbx
				(viii) Shallow_Soil_Identification_Toolbox.tbx
				(ix) Slope_based_Area_Classification_Toolbox.tbx

		•	b) 'Final_Code_Scripts_for_ArcGIS_Toolboxes' folder include the Python scripts (Python version 2.7.16):

				(i) flood raster2.py (associated with Floodplains_Identification_Toolbox.tbx); date of creation: 2019-12-10. 
				(ii) karst buffer5.py (associated with Karst_Area_Identification_Toolbox.tbx); date of creation: 2019-12-10.
				(iii) landSuitabilityTool2.py (associated with Final_Land_Suitability_Analysis_Toolbox.tbx); date of creation: 2019-12-10.
				(iv) Leaching Index Raster3.py (associated with Leaching_Index_based_Area_Classification_Toolbox.tbx); date of creation: 2019-12-10.
				(v) P index raster2.py (associated with Pennsylvania_P_Index_based_Area_Classification_Toolbox.tbx); date of creation: 2019-12-10.
				(vi) potential area raster3.py (associated with Potential_Area_Identification_Toolbox.tbx); date of creation: 2019-12-10.
				(vii) sensitive stream2.py (associated with Proximity_to_Streams_Identification_Toolbox.tbx); date of creation: 2019-12-10.
				(viii) shallow soil raster2.py (associated with Shallow_Soil_Identification_Toolbox.tbx); date of creation: 2019-12-10.
				(ix) slope raster2.py (associated with Slope_based_Area_Classification_Toolbox.tbx); date of creation: 2019-12-10.

	•	2) 'Model_Builder_based_Land_Suitability_Analysis_Tool' folder has a model builder-based toolbox named 'Model_Builder_based_Land_Suitability_Analysis_Toolbox.tbx'.


•	'Documents' folder comprises three folders and a document file. Three folders are 
										1) Instruction_for_Model_Builder_based_Toolbox, 
										2) Instructions_for_ArcGIS_based_Toolboxes, and 
										3) Instructions_for_Data_Preparation. 

	•	1) 'Instruction_for_Model_Builder_based_Toolbox' folder has a document named 'Tool_Operation_Instructions_for_Model_Buider_based_Land_Suitability_Analysis_Tool.docx.' 
		   This document describes the model-builder tool operation steps and final outputs.

	•	2) 'Instructions_for_ArcGIS_based_Toolboxes' folder comprises a document that help users to execute the tools. The document's name is 
		    'Instruction_Document_for_Land_Suitability_Analysis.docx.'

	•	3) 'Instructions_for_Data_Preparation' folder contains a document file. The file name is 'Detail_Instructions_for_Data_Preparation.docx.'	
		    User can get detail information on data preparation from these document files.
	   
 	•	4) 'Documents' folder has a document file called 'Details_of_Additional_Method_Data_Preparation_and_Tool_Operation.docx.' This file provides user an overview of the
		    data prepartion and tool operation. The document also expalins the theoretical background that were used to develop tools and assumptions made for the case study.

•	'Sample_Data' folder contains 10 individual folders that has all the example input data required to conduct land suitability analysis. Folders are

 				(1) ASCIIorText (contains two files: 
								a) Landuse_reclassification_table.txt
								b) Soil_Test_P_values_based_on_General_Land_uses.txt)

				(2) dem (contains a raster file: 
								a) dem)

				(3) floodplains (contains a shapefile: 
								a) floodplains.shp)

				(4) karst_and_sinkholes (contains two shapefiles: 
								a) karsts.shp
								b) sinkholes.shp)

				(5) landuse (contains a raster file: 
								a) landuse)

				(6) precipitation (contains a shapefile: 
								a) precipitation.shp)

				(7) proximityToStreams (contains a shapefile: 
								a) NHD_Streams.shp)

				(8) soil (contains a shapefile: 
								a) soil.shp)

				(9) soilErodibilityFactor (contains a shapefile: 
								a) soilErodibilityFactor.shp)

				(10) studyArea (contains a shapefile: 
								a) StudyArea.shp)

### Additional notes: ArcGIS toolboxes and their corresponding Python scripts are available in 'ArcGIS_Toolboxes' and 'Final_Code_Scripts_for_ArcGIS_Toolboxes' folders.
					The procedure to connect scripts with their respective toolboxes were illustrated in 'Procedure_of_Adding_Python_Scripts_to_Their_Respective_ArcGIS_Toolboxes.docx',
					which is in 'Instructions_for_ArcGIS_based_Toolboxes' folder.

  
File/Format-Specific Information
---

### `Model_Builder_based_Land_Suitability_Analysis_Toolbox/*.tbx`
- Number of variables: 8
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Projected Landuse Raster, (ii) Reclassification Table, (iii) Projected Study Area Shapefile, (iv) Projected Flood Layer Shapefile,
			  																		  (v) Projected Soil Shapefile, (vi) Station with Annual and Seasonal Precipitation, (vii) Projected DEM, and (viii) Soil Shapefile with K Factor.
- Missing data codes: N/A
- Specialized formats or other abbreviations used: N/A

### `Potential_Area_Identification_Toolbox/*.tbx`
- Number of variables: 3
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Land Use / Land Cover Raster, (ii) Input Reclassification ASCII Text File, and (iii) Input Study Area Shapefile
- Specialized formats or other abbreviations used: N/A

### `Floodplains_Identification_Toolbox/*.tbx`
- Number of variables: 2
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Floodplains Shapefile and (ii) Study Area Shapefile
- Specialized formats or other abbreviations used: N/A

### `Proximity_to_Streams_Identification_Toolbox/*.tbx`
- Number of variables: 3
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Stream Shapefile, (ii) Input Buffer Distance, and (iii) Input Study Area
- Specialized formats or other abbreviations used: N/A

### `Shallow_Soil_Identification_Toolbox/*.tbx`
- Number of variables: 2
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Soil Shapefile and (ii) Input Study Area
- Specialized formats or other abbreviations used: N/A

### `Karst_Area_Identification_Toolbox/*.tbx`
- Number of variables: 4
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Sinkhole Shapefile (Optional), (ii) Input Sinkhole Buffer Distance, (iii) Input Karst Area Shapefile (Optional), and (iv) Study Area Shapefile
- Specialized formats or other abbreviations used: N/A

### `Slope_based_Area_Classification_Toolbox/*.tbx`
- Number of variables: 2
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input DEM Raster and (ii) Input Study Area
- Specialized formats or other abbreviations used: N/A

### `Leaching_Index_based_Area_Classification_Toolbox/*.tbx`
- Number of variables: 3
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Soil Shapefile, (ii) Input Precipitation Shapefile, and (iii) Input Study Area Shapefile
- Specialized formats or other abbreviations used: N/A

### `Pennsylvania_P_Index_based_Area_Classification_Toolbox/*.tbx`
- Number of variables: 16
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Land Use / Land_Cover_Raster, (ii) Input Reclassification ASCII Text File, (iii) Input Study Area, (iv) Input Soil Test P Text File, (v) Input Fertilizer P Rate,
																					  (vi) Input Fertilizer Application Method, (vii) Input Manure P Rate, (viii) Input Manure Application Method, (ix) Input P Source Coefficient, (x) Input Precipitation Shapefile,
																					  (xi) Input Soil Erosivity Factor (K factor) Shapefile, (xii) Input DEM Raster, (xiii) Input Soil Shapefile, (xiv) Input Subsurface Drainage, (xv) Input Streams Shapefile, and
																					  (xvi) Input Modified Connectivity Factor.
- Specialized formats or other abbreviations used: N/A

### `Final_Land_Suitability_Analysis_Toolbox/*.tbx`
- Number of variables: 9
- Number of cases/rows: N/A
- Variable list, defining any abbreviations, units of measure, codes or symbols used: (i) Input Potential Raster, (ii) Input Floodplain Raster, (iii) Input Proximity to Stream Raster, (iv) Input Shallow Soils Raster, (v) Input Karst Raster (optional),
			  																		  (vi) Input Slope Raster, (vii) Input Leaching Index Raster, and (viii) Input Phosphorus Index Raster, and (ix) Input Study Area.
- Specialized formats or other abbreviations used: N/A

Methodological Information
---

Description of methods used for collection/generation of data: The study used readily avaiable data collected by different federal and state agencies of the United States. Links have been provided in the 'SHARING/ACCESS INFORMATION' section.
Methods for processing the data: Detail data processing instructions have been described in the 'Detail_Instructions_for_Data_Preparation.docx' in 'Instructions_for_Data_Preparation' folder.
Standards and calibration information, if appropriate: N/A
Environmental/experimental conditions: N/A
Describe any quality-assurance procedures performed on the data: N/A
People involved with sample collection, processing, analysis and/or submission: N/A
