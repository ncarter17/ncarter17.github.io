# GEO 560: GIScience I: Introduction to Geographic Information Science
## Nathaniel Carter 

# GIS Application in Mining & Geology 

Welcome to a website that is dedicated to articles that focus on GIS in Mining and Geology. I hope these references help with the applciation of different geologic, geophysical, or other methods to GIS.


# GIS in Geology

###### Geologic Modeling Software: 

Miladinović, Milena, et al. “No 19 (2011).” Http://Ume.rgf.bg.ac.rs/, http://ume.rgf.bg.ac.rs/index.php/ume/issue/view/11. 

As computer technology has improved, so has available software. In the mining industry there are many different software applications for mining designs Rockware, Rockworks, LogPlot, ERSI, Maptek, and many more applications. The best option for methods for each company can be different. Focusing on ERSI, the ArcReader function can be used to look at maps. The ArcCatalog function allows for the use of management of geographic data and spatially analyze the data. The ERSI suite allows for the analysis of different data types spatially. 

This is helpful for me as it allows me to see the other applications that can be used for geologic modeling. This would be helpful to reference for mining and geologic software’s when considering which software to invest in.

###### 3D Modeling 

Ford, Alistair. “The Visualisation of Integrated 3D Petroleum Datasets in Arcgis.” Reseachgate.net, https://www.researchgate.net/profile/Alistair-Ford-2/publication/228976050_The_visualisation_of_integrated_3D_petroleum_datasets_in_ArcGIS/links/552544830cf2561f2ac219cf/The-visualisation-of-integrated-3D-petroleum-datasets-in-ArcGIS.pdf.


The publication investigates 2D and  3D mapping tools within ArcGIS. The paper focuses specifically on petroleum reserved mapping. The writer focuses on explaining the uses of 3D modeling in mining applications. These uses include mine planning, engineering, and health and safety to name a few. The ArcGIS functions focus on the use of point, line, and polygon features for 2D mapping and solid features to accomplish 3D mapping.  The point features can be used to help define boundaries in a 2D range. The line features are a collection of points that can be pieced together. The polygon feature allows for lines to be connected to form two-dimensional shapes to define regions, boundaries, and other interactions. The solid feature allows for a 3rd dimension to be added, but with great complication. ArcGIS has a multipatch feature that simplifies the process allowing for the easy creation of 3D shapes. 

In my application, ArcGIS is useful for creating maps of planned drill holes. This can be through 2D hole collars. It is also useful to create lines that represent the depths of the drill holes. In a 3D shape looking at a certain type of rock thickness to get to the desired rock type can be useful. 


###### Geologic Mapping

Lawal, M. A., et al. “A Simplified GIS and Google-Earth-Based Approach for Lineaments and Terrain Attributes Mapping in a Basement Complex Terrain.” Nature News, Nature Publishing Group, 22 Sept. 2022, https://www.nature.com/articles/s41598-022-20057-2. 

Geologic mapping has long been used to show rock types, faults, and other stratigraphic features in an area. The use of google earth combine with GIS allow for mapping large areas in shorter amount of time and some more accuracy. The study focused on the Idanre Hills in southwestern Nigeria. The study starts off looking at images that you can see geologic changes in the ground. It moves from that to Lineament density mapping, the application of mapping things such as elevation. The elevation can be pulled and used in raster data or other forms of maps in ArcGIS. The author goes into great detail about the limitations and benefits of this type of mapping. 

In my personal use this could be helpful if a rock unit that we are mining outcrops at surface. This technique would allow for preliminary screening of potential land acquisitions. Mapping elevation and surface outcrops could help with the economics and planning of the mine. 

###### Core Application

Holmes, Elliott M., et al. “Geospatial Management and Analysis of Microstructural Data from San Andreas Fault Observatory at Depth (SAFOD) Core Samples.” MDPI, Multidisciplinary Digital Publishing Institute, 14 May 2021, https://www.mdpi.com/2220-9964/10/5/332. 
https://www.mdpi.com/2220-9964/10/5/332

The author focuses on the analysis of core samples to apply data to GIS. The author was interested in applying spatial visualizations and storing the data in GIS. The data was capture using a camera and other lab-based methods. To store the data HTML is used to store the lab data, while the photographs of are stored in polygon features. The y-data is used to represent depth, while x-axis in this case, was chosen to be the core size. The depths allow for lines and modeling to be created. The author also applied CL image analysis to help classify the rock material. This was done though creating vector points from the images to create sample groups. Then an unsupervised classification method is applied to determine different vein types. Then the analysis is applied to GIS to provide a view of the classification methods. 

This would be helpful for core drilling campaigns. Logging core and then modeling it takes time. This application could help if photographs can be taken and then logged using image classification methodology. It also would be very helpful to have a central place where the core logging, photos, and analysis can be stored for access. This is done mainly in excel files, but other software exists, but they can be expensive. Since GIS is widely used, this could provide an easy way to fix the storage issue. 


###### GIS and Remote Sensing

Ezabti, Abubaker, and Verka Jovanović. “GIS and Remote Sensing Application in Geological Mapping and 3D Terrain ...” Researchgate.net, https://www.researchgate.net/profile/Verka-Jovanovic-2/publication/300485817_GIS_and_Remote_Sensing_Application_in_geological_mapping_and_3D_terrain_modeling_a_case_study_in_Eghei_Uplift_Libya/links/58a19a0345851598bab976b2/GIS-and-Remote-Sensing-Application-in-geological-mapping-and-3D-terrain-modeling-a-case-study-in-Eghei-Uplift-Libya.pdf?origin=publication_detail. 

The author is presents how GIS can be used to take geo-data to create geologic maps and 3D models. The author focuses on the use or remoting sensing data with geo data with interpretation in GIS. The study focuses on an area in Libya. The use of satellite images is explained with pre-processing steps listed. The Geologic mapping was done in the field before being digitized for interpretation. The models were then combined to provide both a topographic, geologic, and structural interpretation. 

Geologic mapping is useful for mapping rock units. This allows for interpretation of geologic structural happenings. The ability to apply surface elevation would allow for better modeling for rock unit interpretation. This would allow for a better geologic model and economic interpretation for mining. 

###### 3D virtual simulation of geology based

   Liang, Zhijian, et al. “Research on 3D Virtual Simulation of Geology Based on GIS - Arabian Journal of Geosciences.” SpringerLink, Springer International Publishing, 1 Mar. 2021, https://link.springer.com/article/10.1007/s12517-021-06615-4. 
   
   The author focuses on making 3D models in an accurate and time friendly manner. The author uses virtual reality modeling language applied to GIS to complete this. The virtual reality modeling language was specifically designed for 3D modeling. To create a model, borehole data, topography, and other mapping is required to be stored in a database on GIS. In GIS, a selection on a map is chosen using a rectangle or other selection shape. Then using coordinates from the drill holes can be used to provide only the drillholes in that area. These drillholes are used to create the model. The virtual reality modeling language is then applied and creates the 3D model without implementation of a human. The method can provide fast results with cost savings. The limitations on the 3D modeling relies on a relatively simple geologic interpretation.

   3D modeling is important for calculating reserves, mine planning and development, and for providing information for future land acquisitions. In application this might not be the most in-depth model. In my position, while running a drilling campaign being able to create a rough model from the information, we are getting in real time would help with decision making on which boreholes to drill when budgets are tight.

















# GIS in Mining


###### Groundwater Movement 

   Prasad, R. K., et al. “Deciphering Potential Groundwater Zone in Hard Rock through the Application of GIS - Environmental Geology.” SpringerLink, Springer-Verlag, 25 Aug. 2007, https://link.springer.com/article/10.1007/s00254-007-0992-3. 

   The author focuses on the application of remoting sensing with the application of GIS to help with mapping underground water ways. The factors that influence groundwater movement is geology, lineaments, drainage, slope, and  geomorphology. The rock types deposited can influence structures such as weathering, jointing, fractures, or even faults. The lineaments are found using remote sensing analysis. The focus is to determine linear features. The drainage is focused on the runoff density in the area. The slope angle can affect the rate that the water is able to percolate into the ground. The Geomorphology focuses on the features of the area and elevation profile of the area. The Geomorphology is found using remote sensing data. All the data gathered from the factors are inputted into a spatial database. This can be done through scanning, topography building, assigning attributes, and buffering to build a map. Each factor map can all affect the path of groundwater. GIS can use the raster calculation function to be applied to each factor to provide a weights to the information. The results can then be combined to create one map with all features. 

   Groundwater movement is a large concern in the mining industry. Mining pits must be dewatered. This can be done in a variety of ways, using pumps, redirecting streams, redirecting groundwater. In the location that I currently work the use of traditional methods have yielded no results. Being able to apply remote sensing data in GIS could help the mining team find the larger underground waterways to allow for better water diversion. 
   
 
 ###### Remediation and Biodiversity
 
   Antwi, Effah Kwabena, et al. “Detecting the Effect of Disturbance on Habitat Diversity and Land Cover Change in a Post-Mining Area Using GIS.” Landscape and Urban Planning, vol. 87, no. 1, 2008, pp. 22–32., https://doi.org/10.1016/j.landurbplan.2008.03.009. 

   Mining can influence the habitat of not only the land being mined, but neighboring properties. The mining industry has placed an increased priority for remediation and diversity. The focus is post-mining areas. The study used satellite images from two different years, 1995 and 2000, to be able to classify regions based on dominant fauna. From these classifications statistical methods were applied to calculate area, size, shape, and other metrics. GIS is used to apply the patch analyst to create a map using spatial statistical methods. These new spatial maps were then analyzed using a change in detection extension in GIS. The areas were classified as negative change, no change , positive change to represent a reduction, no change, or increase in land coverage area, respectively. The application of GIS, satellite images, and remote sensing data can help track and analyze habitat diversity for better remediation results.

   Remediation has always been important in mining. In the more recent times, biodiversity has become a very important factor. This has application to not only post mining activities, but a similar study could be done in actively mined areas to ensure that the natural fauna is able to survive and that the animals in the surrounding areas are not disturbed.

###### Slope Stability

Chen, Wei, et al. “Prioritization of Landslide Conditioning Factors and Its Spatial Modeling in Shangnan County, China Using GIS-Based Data Mining Algorithms - Bulletin of Engineering Geology and the Environment.” SpringerLink, Springer Berlin Heidelberg, 17 Jan. 2017, https://link.springer.com/article/10.1007/s10064-017-1004-9. 

   The paper focuses on the application of statistical models to provide information on factors that heavily influence the results. The area in question was previously mapped, arial photographs, and landslides were mapped in GIS. The factors the study focused on was slope, aspect, altitude, distance to faults, lithology, normalized difference vegetation index, plan curvature, profile curvature, distance to rivers, distance to roads, slope angle, stream power index, and topographic wetness index. The statistical models used were frequency ratio (FR), multivariate adaptive regression splines (MARS), and random forest (RF). The frequency ratio is a calculation that comparing the landslide occurrence ratio by the are ratio. A large ratio is comparable with a higher probability of landslide occurrence.  The MARS method aims to draw a relationship  between the variables and the landslide condition. The random forest is applied to predict responses based on decisions on predictors. The MARS model was observed to provide a slightly better output than the RF model. 
   
   In mining safety is very important in all aspects of the process. Being able to design pits that are safe is the number one priority. Being able to predict landslides or slope fails would help with keeping ground conditions safe. Being able to determine the major factors in the area would help with design and prevention methods being applied. 


###### Environmental Impacts

   Liao, Xueqin, et al. “Application of GIS Based Ecological Vulnerability Evaluation in Environmental Impact Assessment of Master Plan of Coal Mining Area.” Procedia Environmental Sciences, Elsevier, 6 June 2013, https://www.sciencedirect.com/science/article/pii/S1878029613001679. 
   
   The author is studying the ecological vulnerability of coal mining specifically. The area of focus was the Fuxin mining area in Liaoning province in  China. The area of study contains 8 active coal mines and two proposed mines. An ecological vulnerability index  (EVI) was created to create a weight to different layers. These factors included an ecological index (EI), Eological sensitivity index (ESI), and landscape structure composite index (LSCI). Each of these factors were modeled in GIS using spatial analysis functions. These layers were then analyzed using a multiple factor weighted summation model. This model was analyzed using an overlay analysis function in GIS. This analysis created 5 zones appropriate exploitation zone, optimized exploitation zone, moderate exploitation zone, restrictive exploitation zone, and forbidden exploitation zone.  This methodology allows for improvement to land remediation, improvement suggestions for current mining, and defining areas that should be left unmined. 
   
   For me I think this is applicable to my current operation. While coal mining is different the ecological impact of mining can be tracked anywhere. Being able to apply the methodology used improvements to current environmental situations, future development, and remediation could be improved. 
   
###### Ground Condition Evaluation

   Nandia, A., and A. Shakoor. “A GIS-Based Landslide Susceptibility Evaluation Using Bivariate and Multivariate Statistical Analyses.” Engineering Geology, Elsevier, 25 Oct. 2009, https://www.sciencedirect.com/science/article/pii/S0013795209002646. 
   
   The author is focusing on the analysis of landslide using statistical analysis methods. The study region is the Cuyahoga River watershed in Ohio. The first step is to gather background on the area. This is done through the field survey, photography interpretations, and historical landslide information. The goal of the background information is to identify past areas of landslides for analysis. A landslide susceptibility map focus on previous landslides, slope, soil type, rock types, structure, hydrology, and other potential factors. Two statistical methods, bivariate and multivariate statistics were applied. The bivariate analysis looks at the factors and applies a value from 0 to 1 based on intensity. Categorical variables are divided to a set number of classes with weight values applied. The data above is inputted in GIS to build new maps. A equation for landslide susceptibility was created to be one over the number of factors multiplied by the sum of individual geospatial factors rank over the maximum rank for that factor. This analysis can then be applied to the entire area.  The multivariate statistical analysis used logistic analysis. The variables included were slope angle, soil liquidity index, soil erodibility, proximity to streams, precipitation data, landcover, soil type, and presence of landslide or absence of landslide. A forward stepwise regression was applied to the logistic regression. The results were inputted into GIS using a raster calculation. The results were a probability landslide susceptibility map. The results of the study methods showed that the multivariate statistical analysis provide better results than the bivariate analysis.
   
   The predictive model could help provide information on areas of mine designs that could have large probabilities of having landslides. This analysis could help redesign pits to limit the probability of landslides. This would be helpful from a safety, economic, and time concern. 

###### Surface Water Quality

   Tiwari, Ashwani Kumar, et al. “Evaluation of Surface Water Quality by Using GIS and a Heavy Metal Pollution Index (HPI) Model in a Coal Mining Area, India - Bulletin of Environmental Contamination and Toxicology.” SpringerLink, Springer US, 12 May 2015, https://link.springer.com/article/10.1007/s00128-015-1558-9. 
   
   The author focuses on the concentration of heavy metals in surface water surrounding coal mining areas in India. The area is known for monsoons during 4 months of the year. The authors sampled 14 sites before monsoon season and 14 after monsoon season. Lab work and proper chain of custody was complete. The data was then inputted into GIS and mapped using a spatial distribution function to create a map.  Statistical analysis was applied using a paired t-test. The results showed a statistically significant concentration of metals pre-monsoon. The average heavy metal pollution index was calculated using the mean concentration values. All the analysis could be plotted using ArcGIS.
   
   Water pollution is regulated heavily from the EPA. Mining activities discharge water in production and excavation of the materials. Water sampling is an important part of ensuring natural and acceptable contamination levels. Creating maps allows for easy viewing and tracking of the sampling results. GIS also allows for the storage of the information easily. The use of both visual representations and statistical analysis allow the companies to ensure communities are unaffected by the companies methods. 




 
 
# Please send any Comments/Questions to: 

### cartnath@oregonstate.edu 

   
   
	
