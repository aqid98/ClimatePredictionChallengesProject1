# 2022Spring-Project-STAT
[![GitHub license](https://img.shields.io/github/license/Naereen/StrapDown.js.svg)](https://github.com/Naereen/StrapDown.js/blob/master/LICENSE)

# Climate Prediction Challenges

<span style="color:red">Gabriel Weinstein, Mohammed Aqid Khatkhatay, Simran Padam, Bowen Han, Ruoming Han

This project aims to predict the climate changes based on finding the changes between the Ei Nino events and the US landfalls of the hurricanes. Besides, we plan to explore other elements that may affect the probability of landfall such as the temperature, time and the origin location of the hurricane using the machine learning method like K-means and logistic regression.   

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


# Organization of this directory
The project directory is organised as follows
```



```

# Code Content

>dataset_loader
~~~python
Loads the MNIST Dataset
~~~

>CustomActivations
~~~python
Contain activation functions implemented
~~~

>CustomCallbacks
~~~python
Contain callback functions implemented
~~~

>CustomLayers
~~~python
Contain binary and ternary layers implemented
~~~

>CustomOperations
~~~python
Contain binary and ternary operations implemented
~~~


# Models Drive Link

https://drive.google.com/file/d/1n8RlbHh1abPmFBUd2IhhZgG5EcmeQ5Ui/view?usp=sharing

# Paper Link
https://drive.google.com/file/d/13Zi08oF2SK7KGa-21_S9ejlzhZjkgXoe/view?usp=sharing
