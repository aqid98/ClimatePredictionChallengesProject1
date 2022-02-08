# 2022Spring-Project1-STAT5242
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1vfp3VXw4_rtEkLs-aq_l-UcZq-daOR-K?usp=sharing)

# Climate Prediction Challenges
        
## **Effects of El Niño Events on Hurricane Formation and Landfalls in the US**

<span style="color:red">Gabriel Weinstein, Mohammed Aqid Khatkhatay, Simran Padam, Bowen Han, Ruoming Han (Group 6)
     
The goal of this project is to explore association between climate changes and Hurricanes based on El Niño events. The analysis explores Hurricane characteristics such as likelihood of landfall, sea surface temperature, time and the origin location of El Niño and La Niña events. K-means algorithm is applied on the moments of Hurricane tracks and prediction of landfall is analysed on clusters and sea surface temperature.
     
    
![Alt text](https://raw.githubusercontent.com/aqid98/ClimatePredictionChallenges/main/Images/el-nino.jpeg)

Source: https://www.nationalgeographic.org/encyclopedia/el-nino/
## Code Run Instructions
Install the necessary requirements by running the following command.

~~~python
!pip install matplotlib 
# These uninstallation must be done to ensure that no version conflicts would happen.
!pip uninstall --yes cartopy 
!pip uninstall --yes shapely
# Shapely and cartopy are used for graphing maps and tracks.
!pip install shapely cartopy --no-binary shapely --no-binary cartopy
    
~~~

next run the code to upload the dataset.  
~~~python
%%capture
!wget https://www.ncei.noaa.gov/data/international-best-track-archive-for-climate-stewardship-ibtracs/v04r00/access/csv/ibtracs.NA.list.v04r00.csv
!wget https://raw.githubusercontent.com/aqid98/ClimatePredictionChallenges/main/Data/Monthly%20Oceanic%20Nino%20Index%20\(ONI\)%20-%20Wide.csv
~~~

    
## Organisation of this directory 

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
├── images/        
└── output/
        
```
    
## Data Description
        
+ International Best Track Archive for Climate Stewardship [(IBTrACS)](https://www.ncdc.noaa.gov/ibtracs/) from NOAA National Centers for Environmental Information.
+ Oceanic Niño Index [(El Niño-Southern Oscillation Index)](https://origin.cpc.ncep.noaa.gov/products/analysis_monitoring/ensostuff/ONI_v5.php)
        
## Collab Link


    
    
    
    
**Contribution statement:** All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement.    
