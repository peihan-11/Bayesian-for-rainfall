## Bayesian for rainfall

## About the Data

Model rainfall data per calendar month for the city of Nashville, Tennessee. It is a classic problem in Bayesian estimation. Here is the steps:

1. Import dataset
2. Clean dataset
3. Define the function of model
4. Find parameter for each month and store it in a dictionary
5. Plot histogram and gamma distribution
6. Simulate all the months

The dataset called nashville_precip contains NOAA precipitation data for Nashville measured since 1871. I built a model to precept rainfall with the gamma distribution, which is for the sum of multiple independent and identically distributed exponentially distributed variables. Therefore. I believe the dataset using the distribution is extremely classic. 
In the Jupyter file, I clean the dataset in the beginning because there might have losing data. Then, using those data to build a histogram to show the frequency of numerical data using rectangles.
