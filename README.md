# Vegetation-indices-calculator
if you need the minimum, mean, and maximum values of spectral bands and vegetation indices in your study area or plots,
Project Title


[Calculate some important statistical metrics of narrow spectral bands and vegetation indices based on red, green, blue, red edge, and Nir bands ]


Description


[if you need the minimum, mean, and maximum values of spectral bands and vegetation indices in your study area or plots, this tool would be helpful. You need a feature layer of your case study or plot boundary. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image or tiff format of your separate bands (Red, Green, Blue, Rededge, and Nir)  as input]

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/aecdab3f-bcfe-4115-a465-9584bec46447)


 
Table of Contents

•	Installation
•	Usage
•	Contributing
•	License

Installation

ARCGIS PRO

[Download the tool and csv folder, put csv folder in your C drive.]

[Go to the insert tab of your ArcGIS PRO project]
![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/ca0d3a49-32a6-4bfb-af8a-6d3efa9253d2)


 
[Select add folder and browse to the folder that you have saved your script and add that folder]

[Go to the Catalog and find your folder in the Folders section and then find the tool with the name of CropHeightMetrics.atbx, then open it to find the script]
  
 ![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/baa860be-121a-4b94-9dac-6aaf25d1791e)

 ![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/957f2e3e-39bb-47b7-a861-7675d97f0ea1)
 



[Double click and open the script]

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/13ebaac7-567e-444f-890e-ea572de5a1e5)


 
[Call the input feature layer (your plot boundaries). Note: You should have a feature layer not shape file. Your feature layer should be a polygon.


![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/83575dde-6013-4cdf-addf-675ce12f8813)



 
Before running the tool you should paste csv folder in your C drive directory to save the results on there. 

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/01764840-b3e5-42fd-b5f3-0849261feac7)


 
Usage

if you need the minimum, mean, and maximum values of spectral bands and vegetation indices in your study area or plots, this tool would be helpful. You need a feature layer of your case study or plot boundary. This layer should have a field with the name of New_ID that shows the unique ID for your plots (plot number). In addition, you need to have an image or tiff format of your separate bands (Red, Green, Blue, Rededge, and Nir) as input

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/5d54d07f-a52f-48b2-b3a2-a51442da96d9)


 
After running the tool four excel file will be created in your csv folder at your C drive. In addition, if you open 6.gdb at your ARCMAP you can see the resulted raster and feature layers.

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/7a0c86d5-c076-4511-afbe-e39f604f6e9b)

 
The tool calculates some important statistical metrics including: minimum, mean, maximum of narrow spectral bands, RGB based vegetation indices, Red edge based vegetation indices and NIR based vegetation indices in each plot.

Narrow spectral bands

 ![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/32b8c02c-c290-44d4-b195-8b38b9f9346e)


NIR based vegetation indices
 
![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/478fa07c-c301-48d9-9b2a-960cae77f50d)


Red edge-based vegetation indices
 
![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/20ead770-906f-40af-9153-1d8845b4d474)


RGB-based vegetation indices

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/54d29198-b274-44cd-8847-7d77f16e2d5b)

 
The tool also creates some raster format for vegetation indices.

![image](https://github.com/AliBgisrs/Vegetation-indices-calculator/assets/109620013/89dc784e-888e-4cd1-aedd-b95e6b025fff)

 
Contributing

[Please run the script, use it and help me to improve the performance of that script using your valuable suggestions.]
License

About the Author

[Developed by Aliasghar Bazrafkan.]
Acknowledgments

[I would like to express my sincere appreciation to my supervisor, Dr. Paulo Flores, from North Dakota State University (NDSU), for providing invaluable support and guidance throughout the development of this script. His expertise and encouragement have been instrumental in making this project possible].
Contact

[Aliasghar.bazrafkan@ndus.edu]
Additional Notes

[https://sites.google.com/ndsu.edu/floreslab/home?authuser=0]