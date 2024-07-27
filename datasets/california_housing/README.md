# California House Prices
### Median house prices for California districts derived from the 1990 census.
#### Source
This dataset was downloaded from the [Kaggle](https://www.kaggle.com/datasets/camnugent/california-housing-prices?resource=download). The dataset was originally featured in the paper: _Pace, R. Kelley, and Ronald Barry. "Sparse spatial autoregressions." Statistics & Probability Letters 33.3 (1997): 291-297._

#### About Dataset

##### Context
This dataset is used in the second chapter of Aurélien Géron's book 'Hands-On Machine learning with Scikit-Learn and TensorFlow', and serves as an excellent introduction to implement machine learning algorithms because it requires rudimentary data cleaning, has an easily understandable list of variables and has an optimal size.

The data contains information from the 1990 California census. So although it may not help you with predicting current housing prices like the Zillow Zestimate dataset, it does provide an accessible introductory dataset for teaching people about the basics of machine learning.

##### Content
The data pertains to the houses found in a given California district and some summary stats about them based on the 1990 census data. Be warned the data aren't cleaned so there are some preprocessing steps required! The columns are as follows, their names are pretty self explanitory:

1. `longitude`: A measure of how far west a house is; a higher value is farther west
2. `latitude`: A measure of how far north a house is; a higher value is farther north
3. `housing_median_age`: Median age of a house within a block; a lower number is a newer building
4. `total_rooms`: Total number of rooms within a block
5. `total_bedrooms`: Total number of bedrooms within a block
6. `population`: Total number of people residing within a block
7. `households`: Total number of households, a group of people residing within a home unit, for a block
8. `median_income`: Median income for households within a block of houses (measured in tens of thousands of US Dollars)
9. `median_house_value`: Median house value for households within a block (measured in US Dollars)
10. `ocean_proximity`: Location of the house w.r.t ocean/sea

Here, the dependent variable is `median_house_value`. The dataset contains 20640 data about housing in California from 1990 database.

### Example usage using python Pandas

    >>> cal_housing = pd.read_csv(datapath + "housing.csv")
    ...


