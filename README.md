# 🏡 Statistical-Analysis-of-Real-Estate-Prices-in-Australia
This project performs statistical analysis and hypothesis testing on real estate prices using a housing dataset from Australia. The objective is to apply statistical methods to investigate pricing trends, feature impacts, and market insights using Python.

The analysis focuses on decision-making using statistical tests, including hypothesis testing, probability analysis, and ANOVA.

# 📊 Project Objectives
The project investigates several key questions about the housing market:
* Test assumptions about average property prices in specific suburbs
*  Analyze seasonal price differences
*  Estimate probabilities related to property features
*  Determine whether property characteristics influence prices
*  Evaluate policy-related claims using statistical hypothesis testing

# 📂 Dataset

The dataset contains property sales information including:
| Feature      | Description                            |
| ------------ | -------------------------------------- |
| Suburb       | Location of property                   |
| Price        | Sale price                             |
| Rooms        | Number of rooms                        |
| Bathroom     | Number of bathrooms                    |
| Car          | Number of parking spaces               |
| Type         | Property type (House, Unit, Townhouse) |
| Date         | Sale date                              |
| Distance     | Distance from city center              |
| Landsize     | Land area                              |
| BuildingArea | Building area                          |
| Regionname   | Geographic region                      |

The dataset contains 13,000+ property sales records.

# 🧹 Data Preprocessing
The following steps were performed before statistical analysis:
* Handling missing values
* Removing duplicates
* Distribution analysis of numerical variables
* Creating new features such as:
  * Seasonal classification (Summer vs Winter)
  * Parking availability indicator
* Preparing subsets for specific suburb analysis

# 📈 Statistical Methods Used
The project applies several statistical techniques:









# 🔬 Key Analyses Performed
  1️⃣ Price Assumption Testing

  Tested whether the average property price in Altona equals $800,000.

2️⃣ Seasonal Price Analysis

Compared property prices in winter vs summer (2016).

3️⃣ Feature Probability Analysis

Estimated probability of features such as:
  * Properties without parking
  * Properties with specific room counts
  * Properties with certain bathroom counts

4️⃣ Industry Claim Testing

Validated whether average property price in Richmond is $1,000,000.

5️⃣ Feature Impact Analysis

Analyzed whether car parking affects property prices.

6️⃣ Two-Way ANOVA

Investigated whether property prices are influenced by:
  * Suburb
  * Property Type
  * Interaction between suburb and property type

7️⃣ Policy Decision Analysis

Tested whether properties with more than two bathrooms command a price premium.

# 📊 Key Insights

* Property prices vary significantly by suburb.
* Property type has a strong influence on price.
* Seasonal differences exist in property sales prices.
* Additional bathrooms significantly increase property value.
* Some features such as car parking may not significantly affect prices across the dataset.

# 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* SciPy
* Statsmodels
* Matplotlib
* Seaborn














