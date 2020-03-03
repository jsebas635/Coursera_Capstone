# Capstone project: Invest in Bogotá

## Place: Corferias, Bogotá, Colombia.

## Problem question: 

What could be the best bussines idea you can setup near to Corferias and which place would it be? 

## Description:

Bogotá is the capital and largest city of Colombia, as well as the capital of the department of Cundinamarca.Bogotá had 7,412,566 
inhabitants within the city's limits (2018 census) with a population density of approximately 4,310 inhabitants per square kilometer. 
Only 25,166 people are located in rural areas of Capital District. 
Corferias, located in the heart of Bogotá, is known due to is the most important event center in Colombia so, you can find out near 
to this a large number of hotels and commerce. If somebody is interested in invest in this place, it would be a very good idea if we 
can advice which would be the better way to put his money: A restaurant, a car parking or a bar and so on. The code would advice also 
which adress would be better taking into account commerce density. 

# Data

An open-source known as API, which is publicly available in GitHub, is used to retrieve longitude and latitude coordinates of the 
center of boroughs. The API includes coordinates of all places and boroughs in Bogotá. The information of Corferias is parsed through URL query.

To solve this problem I will use information given by Foursquare relating with restaurants, car parking and bars. In each case I want
to use K-means to deal with density problems and to provide stakeholder the best region he can invest his money. For example
If you run an initial code of restaurants near to Corferias, you will see that most of this type of commerce is located at western
of the event center, so that I forecast that it would be better to setup a restaurant in other location. I will do that with three 
distinct types of commerce and will compare between these. 
