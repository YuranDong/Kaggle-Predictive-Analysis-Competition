# Kaggle-Predictive-Analysis-Competition
■ Description
Predict the price of a used car. You are given a dataset on 40,000 used cars. The data describes each car based on its features and its condition.
■ Goal
Construct a model to predict sale price of a used car based on its features and condition and use it to generate predictions for a set of unlabeled data.
■ Metric
Submissions will be evaluated based on RMSE (root mean squared error) (Wikipedia). Lower the RMSE, better the model.
■ About Data
Here is a description of variables included in the dataset. Your goal is to predict the last variable, price.

id: Unique identifier
make_name: Make of car
model_name: Model of car
trim_name: Trim
body_type: Body Type (e.g., sedan, convertible)
fuel_tank_volume_gallons: Fuel tank capacity in gallons
fuel_type: Fuel type (e.g., gasoline, diesel)
highway_fuel_economy: Miles per gallon on highway
city_fuel_economy: Miles per gallon in city
power: horsepower at a certain RPM
torque: Torque in lb-ft at a certain RPM
transmission: car transmission (e.g., M, A)
transmission_display: transmission display (e.g., Manual, Automatic, 6-Speed Automatic)
wheel_system: wheel system (e.g., FWD, RWD)
wheel_system_display: wheel system display (e.g., Front-Wheel Drive, Rear-Wheel Drive)
wheelbase_inches: Wheel base size in inches
back_legroom_inches: Back legroom in inches
front_legroom_inches: Fron legroom in inches
length_inches: Length of car in inches
width_inches: Width of car in inches
height_inches: Height of car in inches
engine_type: Number of cylinders and cylinder configuration (e.g., V8, I4)
engine_displacement: Engine displacement in cubic centimeters
horsepower: horsepower of car
daysonmarket: days the car has been on the market
description: description of car by seller
exterior_color: exterior color
interior_color: interior color
major_options: major options in car
maximum_seating: maximum seating
year: Year of car. Note: It is common for car manufacturers to launch a 2024 car in 2023.
fleet: Whether this car was part of a fleet. True if it was, False if it was not. Blank indicates the seller did not share this information.
frame_damaged: Whether the frame has been damaged. True if it is damaged, False if it is not. Blank indicates the seller did not share this information.
franchise_dealer: Sold by a franchise dealer (True) or not (False)
franchise_make: If sold by a franchise dealer, the maker of cars sold by the franchise
has_accidents: Whether the car has been in an accident (True) or not (False). Blank indicates the seller did not share this information.
isCab: Whether the car has been used as a cab (True) or not (False). Blank indicates the seller did not share this information.
is_cpo: Whether the car is certified pre-owned (True). Blank indicates it is not certified.
is_new: Whether the car is new (True) or not (False)
listed_date: date car was listed for sale
listing_color: color in the listing
mileage: odometer mileage
owner_count: number of previous owners
salvage: whether the car has been salvaged (True) or not (False). Blank indicates the seller did not share this information.
seller_rating: Average rating of seller on a 1-5 scale where is 5 is excellent
price: List price of car

Citation
Name #1, Vishal. (2023). How much is your car worth?. Kaggle. https://kaggle.com/competitions/usedcars2023
