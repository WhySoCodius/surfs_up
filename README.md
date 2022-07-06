# Trends in Temperature for the Proposed Oahu Surf Shop
Statistical analytics using SQLite, SQLAlchemy, and Flask on the Oahu island weather dataset.


## Overview of the analysis

W. Avy is interested in the Hawaii weather analysis, and he wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round.

## Resources 
### Data Sources: 
[Oahu_Weather_details sqlite](/hawaii.sqlite)
 

### Software:

![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)

![Visual Studio Code](https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white)

![SQLite](https://img.shields.io/badge/sqlite-%2307405e.svg?style=for-the-badge&logo=sqlite&logoColor=white)

![Jupyter Notebook](https://img.shields.io/badge/jupyter-%23FA0F00.svg?style=for-the-badge&logo=jupyter&logoColor=white)

![Anaconda](https://img.shields.io/badge/Anaconda-%2344A833.svg?style=for-the-badge&logo=anaconda&logoColor=white)


## Results


![June_Temps](/Resources/June_Temps.png)  ![December_Temps](/Resources/December_Temps.png)

- June has 1700 Station counts and December has 1517 Station Counts, which is 10% less than in June.
- June is comparatively hotter than December, Mean for June is 74.94˚F & Mean for Decemeber is 17.04˚F
- Minimum Temprature is June is 64˚F whereas for December is 56˚F.
- There is not much difference in maximum temprature between June with 85˚F whereas for December is 83˚F.

## Summary

![June_Precipitation](/Resources/June_Precipitation.png)  ![Dec_Precipitation](/Resources/Dec_Precipitation.png)

The investor's greatest concern was that it rained too much. The temperatures and precipitation means between the weather patterns in June and December are fairly similar. For either month, the temperature data is not significantly distorted. With only a few outliers above 3 inches of precipitation, the temperature-to-precipitation ratio for the two months is likewise quite consistent. The evidence is in favour of creating a year-round surf and ice cream shop.