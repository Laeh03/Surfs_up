# Surfs_up

## Background 
W. Avy wants more information about temperature trends before opening the surf shop. Specifically, he wants temperature data for the months of June and December in Oahu, in order to determine if the surf and ice cream shop business is sustainable year-round, Use Python, Pandas functions, and SQLAlchemy. You’ll filter the date column of the Measurements table in the `hawaii.sqlite` database to retrieve all the temperatures for the month of June. You’ll then convert those temperatures to a list, create a DataFrame from the list, and generate the summary statistics.

## Resources
* Data Source: SurfsUp_Challenge.ipynb
* Data File: `hawaii.sqlite`
* Software: Matplotli 3.2.2, Python 3.9, Visual Studio Code 1.50.0, Anaconda 4.8.5, Jupyter Notebook 6.1.4, Pandas, Numpy, Sqlalchemy.

## Results 
![Screenshot (103)](https://user-images.githubusercontent.com/64225504/132154260-6d08eb58-67e3-425c-bab6-f85f9bf25424.png)
![Screenshot (104)](https://user-images.githubusercontent.com/64225504/132154267-5cd35d97-2756-4d04-a5a4-587d9c17a829.png)


1)	Temperatures in June and in December were stable. 
    - The mean temperature for June was 74.94℉ with a standard deviation of 3.26.
    - The mean temperature for December was 71.04℉ with a standard deviation of 3.75.
    
2)	Based on the minimum temperatures for June and December, it can be concluded that December is generally somewhat cooler than in June, and this may result in a reduced           number of customers in December.
    - The minimum temperature for December was 56℉, compared with 64℉ in June. 
    
3)	The data count was higher for June because there were data gathered for June 2017 but not for December 2017. This means that the weather stations gathered an extra set of       data that was not retrievable for December. Since the standard deviation was pretty close for both months, it’s unlikely the extra dataset for June has much of an impact on       the comparison for the two months.

## Summary:
Using the summary statistics for June and December weather data, it appears that the surf-and-ice-cream shop can remain open year-round. The temperatures are warm enough for surfing and for customers buying ice cream, so the business should be reliable and profitable. 
Furthermore, the following two queries could be run to provide even more accurate analysis of weather trends for June and December in Oahu for the business:

1)	Query for Precipitation trends in June and December. 
    - It’s reasonable to assume that people are less likely to go surf or for ice cream in the rain. We can run summary statistics for precipitation data in June and December         to see if there are reliable trends with regards to precipitation.
    
2)	Query temperature and precipitation results filtered by month and year, to determine if there are any years that are outliers.
