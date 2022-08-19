# Visualizing-Craigslist-Vehicles-in-the-US
Car purchase on Craigslist could result in significant savings on a pricey investment. On Craigslist, several vehicles are for sale. People can narrow down their search results to make it easier to identify the type of automobile they desire and the price range they can afford. They can look at the pictures if a car listing gets their attention. The listing includes information on the vehicles’ year, make, model, and trim.In this report I’m going to visualize these listings based on the above mentioned parameters. This data set can be used by people around the US to study and predict future car sales. It explains the actual price, how to choose an automobile, and how to assess the car’s condition. It even displays the most typical automobile model per state. The common characteristics and status of autos can be discovered by
researchers.

# Data Set
[Vehicle DataSet](https://drive.google.com/file/d/1qJCY3ys8Md_7NmYfaT61DRpP3utl8gi5/view?usp=sharing)

The vehicle data set has 26 columns and 426880 rows. Each row represents an entry for a used car.The Data Set also has many missing values in each row.

# Tidying the Data Set
Since Craigslist ads allow for a lot of flexibility, several fields—including those for the condition, odometer, size, paint color, and cylinders—have blank values. When we look more closely, we see that most of the columns have multiple null entries. Either we can proceed by learning how to estimate these numbers, or we may do away with
the rows altogether. There are missing values for several factors, including condition, odometer, size, paint color, and cylinders. Since none of the columns have any values and there are zero rows as a result, we are unable to use omit.na(). I’ve taken out any missing rows from the particular visualization to avoid this.

# Aim
1. Which car(manufacturer) has the highest number of listing on Craigslist?

2. What is the highest listing of different cars based on state?

3. Exploring top 5 States Manufacturer wise.

4. Figuring the kind of car somebody needs.

5. What is the price for different brand cars?

# Types of graphs Visualized
1. Bar Plot

2. Scatter Plot

3. Box Plot

4. Line Graph

5. Heatmaps

6. cloud Image

7. Statistic Plot

# Run
1. Download the data set and rmd file and paste it in the same folder.
2. Set working directory.
3. Run each chunks.
