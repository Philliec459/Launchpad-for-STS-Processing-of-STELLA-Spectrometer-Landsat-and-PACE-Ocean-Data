![Image](sts_nasa.png)

## **STELLA Videos:**

**NASA STELLA VIDEO ON THEIR STELLA SPECTROMETERS:**

[Video](https://youtu.be/QSF4F-YlcH4?si=3oZV0hKy_0xDA0NJ)

**NASA STELLA APPLICATIONS VIDEO:**

[Video](https://youtu.be/LcWqBePYx40?si=j_ZxgUGYjMyRDMdf)

## **STELLA, Landsat and PACE Ocean Data Jupyter Notebooks:**
We have 4 CoLab-ready Jupyter Notebooks in GitHub to process NASA STELLA, Landsat and PACE Ocean data. Just click on the hyperlinks below for each notebook example. 

Our **first two examples below** only require the raw STELLA data file called data.csv. Your white card readings should be the fist readings in this file. You should also add one more column to this file called **Test**. In the **Test** column, you should label each reading that was made, where all readings from the same test subject should have identical names. Please see example below:

*data.csv*
![image](data.csv.png)

**STS EXAMPLE 1:** READ IN ANY STELLA data.csv FILE:

- If you do not have a data.csv file, an example data.csv file will be uploaded to Google CoLab so that you will have a data file to run. 
- If you have another data.csv file, then just drag and drop that file onto CoLab, and it can run in **STS Example 1** Jupyter Notebooks.

[Read in any STELLA data.csv file with Test Column added](https://github.com/Philliec459/Science-and-Technology-Society-Use-of-NASA-STELLA-Q2-Spectrometer-for-Eric/blob/main/CoLab_STELLA_raw_data_input.ipynb)

**STS EXAMPLE 2:** READ IN RAW STELLA DATA AND MAKE WHITE-CARD CORRECTIONS TO THAT DATA:

- If you do not have a data.csv file, an example data.csv file will be uploaded to Google CoLab so that you will have a data file to run. 
- If you have another data.csv file, then just drag and drop that file onto CoLab, and it can run in **STS Example 2** Jupyter Notebooks.

[Read in any STELLA data.csv file with Test Column added. White card reading should be in first row](https://github.com/Philliec459/Science-and-Technology-Society-Use-of-NASA-STELLA-Q2-Spectrometer-for-Eric/blob/main/CoLab_STELLA_raw_data_input_white_card_correct.ipynb)

**STS EXAMPLE 3:** STELLA DATA SIMPLE APPLICATION:

[CoLab_STELLA_brief_ver2_backyard_grass_shoreline_condensed.ipynb](https://github.com/Philliec459/Science-and-Technology-Society-Use-of-NASA-STELLA-Q2-Spectrometer-for-Eric/blob/main/CoLab_STELLA_brief_ver2_backyard_grass_shoreline_condensed.ipynb)

**STS EXAMPLE 4:** PROCESS NASA LANDSAT DATA:

[CoLab_VegIndex4_training_RobinsonPreserve_simple_Level2.ipynb](https://github.com/Philliec459/Science-and-Technology-Society-Use-of-NASA-Landsat-Data-to-Calculate-NDVI-and-PNDVI/blob/main/CoLab_VegIndex4_training_RobinsonPreserve_simple_Level2.ipynb)

**STS EXAMPLE 5:** PROCESS NASA PACE HYPERSPECTRAL OCEAN DATA:
This takes a while to load all HyperCoast[extra] python libraries and PACE dataset.  It takes ~5 minutes to run entire project to our ÔbreakÕ point that stops the code. Beyond the break point are experimental Red Tide (Karenia brevis) indicators that have not been tested. 

[CoLab_ netCDF4_PACE.ipynb](https://github.com/Philliec459/STS-Software-to-Download-and-Process-NASA-PACE-Ocean-Ecosystem-hyperspectral-data/blob/main/CoLab_%20netCDF4_PACE.ipynb)

**STS COMPREHENSIVE STELLA EXAMPLE 6:**  PROCESS AND PREDICT VEGETATIVE SPECIES FROM HOME DEPOT STELLA DATA:
This too takes a while to load python libraries and data. It takes ~2 minutes to run. Check out the interactive Altair displays at the end where you can select samples from the plot to view the plant species photos for each reading. 

[CoLab_STELLA_brief_ver2_brief_to_Ed_Chiles_ver2.ipynb](https://github.com/Philliec459/STS-STELLA-Spectrometer-Readings-on-Various-Plant-Species-with-NDVI/blob/main/CoLab_STELLA_brief_ver2_brief_to_Ed_Chiles_ver2.ipynb)


## **ADDITIONAL RESOURCES:**
**Understanding and Accessing Landsat Data:** Great video for an introduction to Landsat data.

[Landsat Video](https://youtu.be/cRTPA1ART7g?si=3M-wvq0oyQTf1E8a)

**EARTH EXPLORER:** If you need to setup an Earth Explorer account to download PACE or Landsat data, then please click on the following link:

[Earth Explorer login](https://ers.cr.usgs.gov/login?RET_ADDR=https%3A%2F%2Fearthexplorer.usgs.gov%2F)

**GOOGLE ACCOUNT:** You will need to log into your Google Account to login. If you do not have one, then go to this link below: 

[Google Account](https://support.google.com/accounts/answer/27441?hl=en)

We have not tested this link and are not aware of any costs for the basic account.

## **WorldView for Land and Ocean Data:**

[WorldView for Land](https://worldview.earthdata.nasa.gov/?v=-84.27057327855906,26.66060096879559,-81.4117370877425,28.264287743469897&l=Reference_Labels_15m(hidden),Reference_Features_15m(hidden),Coastlines_15m,MODIS_Aqua_L3_NDVI_Monthly,VIIRS_NOAA21_CorrectedReflectance_TrueColor(hidden),VIIRS_NOAA20_CorrectedReflectance_TrueColor(hidden),VIIRS_SNPP_CorrectedReflectance_TrueColor(hidden),MODIS_Aqua_CorrectedReflectance_TrueColor(hidden),MODIS_Terra_CorrectedReflectance_TrueColor&lg=true&t=2024-06-22-T19%3A09%3A42Z)

[WorldView for Ocean data using new PACE Satellite data](https://worldview.earthdata.nasa.gov/?v=-100.02484118515916,18.222836043347293,-72.71325685606926,33.5434853077787&l=Reference_Labels_15m(hidden),Reference_Features_15m(hidden),Coastlines_15m,OCI_PACE_Chlorophyll_a,VIIRS_NOAA20_CorrectedReflectance_TrueColor(hidden),VIIRS_SNPP_CorrectedReflectance_TrueColor(hidden),MODIS_Aqua_CorrectedReflectance_TrueColor(hidden),MODIS_Terra_CorrectedReflectance_TrueColor&lg=true&t=2024-06-14-T14%3A54%3A38Z)

## **Hyperspectral Plant Data:** 
Each pixel of the plant image has a continuous range of spectral data. This is called Hyperspectral data.

[Hyperspectral Plant Data](https://github.com/Philliec459/Science-and-Technology-Society-Use-of-NASA-STELLA-Q2-Spectrometer/blob/main/HyperSpectral_NIReos.gif)

## **HOW TO RUN STS JUPYTER NOTEBOOKS IN COLAB:**
1) If you click on the Jupyter Notebook links that we have provided, you will see the following type of image while you are still in GitHub. Click on the banner **"Open in CoLab"** at the top, and this will open this notebook in Google CoLab. Look to the far upper right corner of the web page to make sure that you are logged into your google account. If not, then login before trying to run CoLab. 

![Image](GitHub_link.png)

2) On the top title bar of CoLab there is a label called **"Runtime"**(second image below). Click on this and then click on **"Run all"**. That is it. The notebook will get all of the data files and run python. It could take a few minutes, but I have tested this in my environment, and it works fine.

![Image](CoLab_link.png)

3) When finished, then I would suggest in the **"Runtime"** column, click on **"Disconnect and delete runtime"** to end your CoLab session. 






