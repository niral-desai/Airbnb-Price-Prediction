# Airbnb-Price-Prediction


## Background

AirBnb is a San Francisco based company that offers an online marketplace for booking short-term lodging and experiences. It acts a middleman and takes a cut of each transaction. The company was created back in 2008 by Brian Chesky, Nathan Blecharczyk, and Joe Gebbia.

AirBnb is a platform that connects local homeowners with travelers looking for unique and affordable accommodations options. Hosts can earn extra income by renting out their homes or rooms and have access to millions of potential guests worldwide. The platform offers a secure and streamlined booking process and support for both hosts and guests. For travelers, host offers a wide range of accommodations, from cozy cottages to luxurious penthouses, for any type of trip, whether it be for work, a weekend getaway, a family vacations, or an extended stay. With millions of options to choose from, there is a perfect place for every traveler.


## Problem

As there is no simple way to obtain the information, figuring out the ideal rental pricing for and AirBnb listing can be difficult for hosts. Although it is offered through various third-party software, but it can be very pricey. Finding comparable listings in the neighborhood and averaging their prices is a common strategy, but it is not always reliable and necessitates frequent updating.



## Solution

To estimate rental prices, our aim is to offer a data driven approach. The suggested model will incorporate a new predictor based on the property’s proximity to certain locations and enabling the model to consider the value of being situated close to facilities like train station or supermarkets or tourist spots and modify its predictions accordingly.


## Data Description 

We were searching for a specific type of dataset for our project, which included all the listings of currently available places on a AirBnb marketplace. However, the website we were interested in, AirBnb, does not publicly release this type of data. Therefore, we had to turn to third-party websites such as Inside AirBnb to obtain information. These sites offer real-time data, but obtaining it was time-consuming process and came at a cost. As a result, we had to settle for a free dataset from Kaggle, which was the New York City AirBnb listings dataset.
![image](https://github.com/niral-desai/Airbnb-Price-Prediction/assets/46837140/6b535999-5db7-46ec-beac-4ba158815fd5)

Some of the important aspects of the dataset we will be looking forward to work with are:
Last_scraped: Date on which the place is last rented out on.
Accomodates: How many people does it accommodates.
Beds/Bath: Number of beds and baths the place has.
Price: Price for the rented place.
Max_Nights: Maximum number of nights it can be rented out.
Min_Nights: Minimum number of nights it can be rented out.
Review_Score_Accuracy: Accurate review score.
Property Type: The Type of rented place is.
![image](https://github.com/niral-desai/Airbnb-Price-Prediction/assets/46837140/78a23e32-1003-44fe-b3c0-7ef5a1fd441e)

