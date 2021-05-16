# intro_python_spatial_analytics
In this session we will learn how to use python with arcgis library (arcgis and arcpy) to do spatial data analytics for Riskesdas (Riset Kesehatan Dasar) data. To start the session, follow these steps:
1. Read "Python for Spatial Analytics.pdf"

In this part you will get the big idea of this session and learn how to setup a python environment either in your local computer or in the cloud using Google Colab. Whether you choose to use local or cloud, you can choose the next two steps: "reading and cleansing table data from pdf using Tabula in Python library" or "reading and cleansing data from pdf using Tabula Software" 

**Tabula Software**

2. Read "Tabula Installation Procedure.pdf"
3. Next, you will learn how to install Tabula as tools to extract table from pdf file. Download the data here: http://dinkes.babelprov.go.id/sites/default/files/dokumen/bank_data/20181228%20-%20Laporan%20Riskesdas%202018%20Nasional-1.pdf (The pdf file has been downloaded for you. Open 'Laporan_Nasional_RKD2018_FINAL.pdf')
4. Extract the data on page 21 (Tabel 3.1.1 Proporsi Pengetahuan Rumah Tangga terhadap Kemudahan Akses ke Rumah Sakit menurut Provinsi, Riskesdas 2018) through Tabula and process the data manually on Excel. 
5. Save the result to 'Tabula_Riskesdas_Python.csv' (The file inside this repository is the result, if you don't want to do the manual data preprocessing just skip step 3)
6. Open "Tabula_Python_for_Spatial_Analytics.ipynb" and follow the steps by running all the cells

**Tabula in Python Library**

2. Open "Python_for_Spatial_Analytics.ipynb" and follow the steps by running all the cells

At the end of this part you have joined the data from pdf file with the spatial data in shapefile (.shp) format. Congratulation!

