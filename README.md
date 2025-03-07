# Digital Nomads in Europe

This project is a comprehensive analysis of the cost of living in different cities across Europe. The analysis is performed using Python, Jupyter Notebook and VS Code.

## Project Overview
In an ever-growing digital world with less and less traditional office restrictions and requirements, we sought out to find conditions that would reflect an ideal setting for digital nomads in 2025.

The goal of project is to analyze the cost of living data in the top 10 most populous cities in Europe and provide insights for Digital Nomads based on the most impactful factors. 

The analysis includes data cleaning, visualization, filtering and statistical analysis.

## Requirements

- Python 3.x
- Jupyter Notebook
- Pandas
- NumPy
- Requests

## Usage

1. Clone the repository
2. Install the required libraries
3. Open the Jupyter Notebook
4. Run the cells to perform the analysis

## Description

This project is an analysis on the most impactful criteria for attracting Digital Nomads for top 10 most populous cities in Europe. The outcome is a list of cost of living in these cities based on specific criteria detailed in the following lines.
Below is described the methods used and the reasoning for the decisions made.

Digital Nomads look for good infrastructure, affordable cost of living and enjoyable weather conditions. These were the data we looked for when defining the main attraction criteria for this kind of people. 

We started by defining the sample of cities to analyze. The top 10 most populous cities in Europe were considered. Our analysis, was restricted to European countries and these are the places people can enjoy more activities and, usually, better infrastructure.

### Sample of Cities

The final list of the cities we analyzed data for are the following:
* Berlin, Hamburg and Munich in Germany
* Madrid and Barcelona in Spain
* Rome, Milan and Naples in Italy
* Paris in France
* Vienna in Austria

### Criteria
In each of the cities in the previous list, different sets of data were used to evaluate the most important aspects of living for digital nomads: affordability and weather conditions.

We picked values that are the most impactful regarding affordability. 

#### Rent
At the top of the list is rent. We considered values for 1 and 3 bedroom apartments both in city centers and outside of city centers. The different values would be useful for later analysis and to create optionality for a user to choose the amount of space and main area he/she would prefer to be located at.

#### Cost of Public Transport 
Digital Nomads travel light and by public means. Usually, don't possess a private car and, as such, an affordable network of public transportation is a high-valued criteria. We selected the price of the a single short-term trip and a monthly pass, to allow the user to tailor the results to its needs.

#### Food and Dining
Eating out can amount to considerable sums. We gathered and analyzed data on 2 options of costs: a single meal at an inexpensive restaurant and a meal for 2 people at a mid-range restaurant.

#### Gym Subscription Cost
The public of Digital Nomads are usually young active people and fitness is part of their lifestyle. We considered data for gym subscriptions in the selected cities as a measure of the typical cost for physical activities for these people.

#### Internet Connection
Digital Nomads are called digital for a reason. A stable and fast Internet connection is a pivot point when selecting a city.

### Data Sources

  
##### Kaggle dataset for global cost of living
https://www.kaggle.com/datasets/mvieira101/global-cost-of-living

##### Kaggle dataset for best cities for a workation
https://www.kaggle.com/datasets/prasertk/the-best-cities-for-a-workation

##### Weatherbit API for weather data
http://api.weatherbit.io/v2.0/current

## Contributing

Pull requests are welcome. Feel free to fork the file and develop further.

## License

This project is licensed under the MIT License.

## Authors 
Project made with love by Team RAMB:
* Rafal Kolakowski
* André Barros
* Manoela Calabresi
* Ben Thomas
