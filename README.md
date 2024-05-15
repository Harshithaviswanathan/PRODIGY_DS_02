Task 02:
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

Data Cleaning and Preparation:

Cabin Column: Dropped due to a high number of missing values (687).
Age: 177 missing values were noted, these entries were retained for specific analyses that did not require the age variable.
Embarked: Only 2 missing values, rows with these missing values were dropped.

Exploratory Data Analysis (EDA):

Passenger Class Distribution: Most passengers were in the Passenger class 3, which had the highest number of passengers.

Survival Analysis:
A significant survival rate discrepancy was observed across classes; Passenger class 1 had a better survival rate.
Younger passengers tended to have a higher survival rate, evident from the kernel density estimation in the age histograms.

Fare Distribution:
Fares varied significantly with passenger class; Pclass 1 generally paid more.
The boxplot highlighted the fare disparities among classes and pointed out several outliers in fare prices.

Gender Distribution:
There were notably more males than females on board.

Correlation Analysis:
Numeric data correlation highlighted some expected relationships, such as between and fare and survival.

Siblings and Spouses (SibSp):
Passengers with one or two siblings and spouse  had a higher survival rate than those with none or more than two.

Visualizations:
A series of plots were generated to visually support the analytical insights, including count plots, histograms, boxplots, and heatmaps.
Key visualizations include the survival rates by passenger class, fare distributions,  age distributions for survived and non-survived passengers ,and passenger class distribution for survived and non-survived passengers.

Conclusions:
The analysis provided valuable insights into the factors that might have influenced the survival chances of the Titanic passengers. Socio-economic status (passenger class), age, and fare appear to have been significant factors.
