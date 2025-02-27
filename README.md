# Unpacking the Perceived Cycling Safety of Road Environment Using Street View Imagery and Cycle Accident Data




The code and data for the project are divided into three parts. The first part involves data cleaning and the computation of PCA. The second part is the downloading of Google Street View images of accident sites. Google Street View images are not shared due to copyright issues. The third part involves machine learning and SHAP analysis. The transition from the second to the third part skips the semantic segmentation of the street view images, which uses the HRNet's Cityscapes dataset for analysis.


Each part can be run separately after entering its folder. Due to the large size of the data, the first part data should be downloaded from Google Drive and placed in the specified folder to run. The second and third parts include complete data and can be run directly.



The summary list of all data source employed in this research:

1. Road Safety Data

https://www.data.gov.uk/dataset/cb7ae6f0-4be6-4935-9277-47e5ce24a11f/road-safety-data

2. OS Open Roads

https://osdatahub.os.uk/downloads/open/OpenRoads

3. Google Street Images


The summary list of all methods employed in this research:

1. Cityscapes Dataset

https://www.cityscapes-dataset.com

2. HRNet-Semantic-Segmentation

https://github.com/HRNet/HRNet-Semantic-Segmentation/tree/HRNet-OCR
