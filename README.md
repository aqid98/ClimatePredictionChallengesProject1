# 2022Spring-Project-STAT
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

# Climate Prediction Challenges

<span style="color:red">Gabriel Weinstein, Mohammed Aqid Khatkhatay, Simran Padam, Bowen Han, Ruoming Han
    
    
## **Effects of El Niño Events on Hurricane Formation and Landfalls in the US**
     
The goal of this project is to explore association between climate changes and Hurricanes based on El Niño events. The analysis goes deep into studying the association between likelihood of landfall, temperature, time and the origin location for El Niño and La Niña events. Machine learning methods such as K-means and logistic regression are applied to perform clustering on the Hurricane characterstics and to generate insights on El Niño events.

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
    
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/

# Models Drive Link

https://drive.google.com/file/d/1n8RlbHh1abPmFBUd2IhhZgG5EcmeQ5Ui/view?usp=sharing

# Paper Link
https://drive.google.com/file/d/13Zi08oF2SK7KGa-21_S9ejlzhZjkgXoe/view?usp=sharing
    
    
    
    
**Contribution statement:**(default) All team members contributed equally in all stages of this project. All team members approve our work presented in this GitHub repository including this contributions statement.    
