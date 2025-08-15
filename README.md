# Weather Data Cleaning and Analysis
Overview

This project involves cleaning and analyzing a weather dataset to extract meaningful patterns and insights. The analysis covers various weather conditions, wind speeds, visibility, and humidity patterns.

##  Data Cleaning Steps

- Converted the Date/Time column to proper datetime format.

- Renamed columns for better readability:

Press_kPa → Pressure_kPa

Temp_C → Temprature_C

Rel Hum_% → Humidity_%

Weather → Weather Condition

- Checked for and summarized null values.

- Verified data types and structure.

##  Analysis Performed

- Instances when weather is clear – Filtered all records where the weather condition is exactly "Clear".

- Wind speed exactly 4 km/h – Extracted records with Wind Speed_km/h equal to 4.

- Null value check – Verified the dataset for missing values in each column.

- Renamed columns – Applied meaningful column names for clarity.

- All instances of Snow – Retrieved all records where Weather Condition contains "Snow".

- High wind and low visibility – Found instances where wind speed > 24 km/h and visibility = 25 km.

- Mean statistics by weather – Calculated the mean value of each numeric column for every unique Weather Condition.

- Clear weather with high visibility – Selected records where weather is "Clear" and visibility > 40 km.

- Clear weather with high humidity and visibility – Filtered records where weather is "Clear", humidity > 50%, and visibility > 40 km.

##  Technologies Used

- Python – Core programming language.

- Pandas – For data cleaning and analysis.

- NumPy – For numerical computations.

##  Results

This analysis provides insights into patterns of clear and snowy weather, relationships between wind speed and visibility, and statistical summaries by weather condition.
