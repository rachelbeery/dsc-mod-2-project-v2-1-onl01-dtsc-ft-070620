
# Module 2 Final Project

**Objective:** In this project we will be finding the best model for interpretability so that our non-technical audience can understand the findings of our modeling. 

**Approach:** The OSEUMiN data science workflow is utilized to effectively create a model to find what factors can result in the most profitable house.

![](https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/king-county-housing-auuthority-logo.png)

**Data:** The data used for this project was records of houses sold in King County Washington. The columns of data provided include:

* **id** - unique identifier for a house
* **dateDate** - house was sold
* **pricePrice** -  is prediction target
* **bedroomsNumber** -  of Bedrooms/House
* **bathroomsNumber** -  of bathrooms/bedrooms
* **sqft_livingsquare** -  footage of the home
* **sqft_lotsquare** -  footage of the lot
* **floorsTotal** -  floors (levels) in house
* **waterfront** - House which has a view to a waterfront
* **view** - Has been viewed
* **condition** - How good the condition is ( Overall )
* **grade** - overall grade given to the housing unit, based on King County grading system
* **sqft_above** - square footage of house apart from basement
* **sqft_basement** - square footage of the basement
* **yr_built** - Built Year
* **yr_renovated** - Year when house was renovated
* **zip code** - zip
* **lat** - Latitude coordinate
* **long** - Longitude coordinate
* **sqft_living15** - The square footage of interior housing living space for the nearest 15 neighbors
* **sqft_lot15** - The square footage of the land lots of the nearest 15 neighbors

**Audience:** Non-technical audience of homeowners within King County, Washington who are interested to know what they can do to improve their home to maximize the selling price of their homes.

Questions we will be answering in this notebook:

* What features of a house yield make the house sell at a higher price?

* What effect does outliers have on our outcomes and overall data?

* How will multicollinearity affect what feature yields the highest selling price?

* What outlier removal method is the most effective?  Non-technical audience of homeowners within King County, Washington who are interested to know what they can do to improve their home to maximize the selling price of their homes.

Questions we will be answering in this notebook:

* What features of a house yield make the house sell at a higher price?

* What effect does outliers have on our outcomes and overall data?

* How will multicollinearity affect what feature yields the highest selling price?

* What outlier removal method is the most effective? 

**Recommendations:** 

**By increasing the “Grade” of the home the home’s value steadily increases.**

![](https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/Grade_home.png)

**Homes with more bedrooms  have a shown higher home value when selling on the market.**

![]https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/bedroom_home.png

**Houses with more bathrooms have higher value on the housing market.**

![](https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/bathrooms_home.png)

**By adding more square footage to a home the value of the house has shown to increase the value of the home.**

![](https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/sqftliving.png)

**The condition of the home increases the sale price of the home. Homes with condition score of 3 to 5 are the most profitable.**

![](https://github.com/rachelbeery/dsc-mod-2-project-v2-1-onl01-dtsc-ft-070620/blob/master/condiiton.png)
