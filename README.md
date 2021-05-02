# Remote-Sensing

Temporal changes in major water Bodies in Ranchi City Area using LISS_III satellite data on QGIS software.

Group ID : mapathon3153
Team name : SXCR mappers
Members : The group consist of 4 members
	NAME	CONTACT NO	E- MAIL	INSTITUTION
1.	Anurag Ajit Topno (leader)	+918757195091	1002anurag@gmail.com	ST. Xaviers College Ranchi
2.	Devraj Singh	+916299304650	sdevraj30@gmail.com	ST Xaviers College Ranchi
3.	Mehrun Nisha	+916205583349	nisha.nasim005@gmail.com	ST Xaviers College Ranchi
4.	Riya Shankar	+916205088989	riyashankar123@gmail.com	ST Xaviers College Ranchi

METHODOLOGY
DATA SETS :   The data sets for the above mentioned project were downloaded from BHUVAN website. The data sets were sourced from Resourcesat-1/Resourcesat-2: LISS-III Sensor satellite . The satellite has 4 bands- Green, Red, NIR ,SWIR . All four Bands  Data set of the topographic tiles number F45B03, F45B07,F45B11 were downloaded of the time 20th Oct., 2008 , 26th Nov., 2017.
Steps in QGIS:
       
1.First all four bands data of band data were added as a rastor layer in canvas section of both Oct. 2008 and Nov. 2017.
2.Then using the Raster Calculator  in Raster heading we calculate MNDWI( modified normalized difference Water index) using the equation {( Green band – SWIR)/(Green band +SWIR)}. The output is an MNDWI raster layer of both Oct. 2008 and Nov. 2017.

3.MAP_1
 It depicts an MNDWI image of the 2008 map. We perform some colour correction using  select multiple band option having values - Red (min 1 & max 0), Green (min 1 &  max 0), Blue (min 2 & max 0). 

4.MAP_2
In MNDWI 2017 map we select the layer styling  option where we select the multible band option. Red (min 0.1& max 0), Green (min 0,2 & max 0), Blue( min 3 & max 0) were adjusted.

5.Contrast enhancement were set to  stretch to minMax and rendering of contrast was done to 100% and hence A map of surface water bodies were obtained of both MNDWI.
6.Both the maps were added in one print composure where the differences in maps were marked ( ponds disappeared , or new water bodies that were formed ).
7.For the analysis of the stream and wetland we take 2008 MNDWI raster layer under the layer styling we select single pseudoband colour . Then in continous colour rendering where different values were represented by different colours the spectral values other than water were dimmed thus obtaining a raster layer with sign of water spectral index representing streams and wetland. Similar process were done for the 2017 MNDWI map and another raster layer was obtained.
8.Pseudocolour raster layers were overlapped to distinguish the area of the streams and wetlands between 2018 and 2008. The resulting raster layer shows the difference of stream and wetland . the resulting map is send to print composure  where the north arrow , grid, legends and scale of the map is added to make the map.
9.In the maps denoting streams the spectral signatures of road networks and built-ups are similar to the streams hence areas where these both occur in proximity, there exists a chance of error.


APPLICATION OF THE MAP

The following maps can be used for various  purposes:-
1.Through the maps we get information on various ponds that have disappeared in Ranchi as well as formation of the new surface water bodies in ranchi such as construction of new surface water bodies.
2.Dams are the main source water in Ranchi City and monitoring of Dams of past ten years can be inferred . The Dams show little change over the course of time meaning the inflow of water from upper catchment areas are good resulting to adequate supply of water for different purposes.
3.Deficiency of water in Dams may directly signal to water crisis in the city.
4.The surface area of water bodies can be calculated for use in LULC  data.
5.The stream and wetland Map shows the dissapperance of streams in an around Ranchi which shows the effect of urbanization , deforestation and other detrimental human activities in the areas around Ranchi . The disappearance of the streams have led to the disappearance of catchment areas . 

