*DISCLAIMER
    -This project is a sole Intellectual property of mine i.e. GANDHARV GUPTA .Kindly acknowledge before copy or use of this project. The dataset is    open and is a property of Kaggle which holds all proprietary rights over it

Data Analysis and Machine Learning-Regression 
for
Price Determination

DATASET-Car prices data set

INDEPENDENT VARIABLES:

•	-Brand: Specifies the brand of car
•	-Model: The specific car model of a brand
•	-Year: Year of manufacturing(The older the cheaper)
•	-Engine size :Capacity of engine(high capacity implies costlier car)
•	-Fuel type: Petrol, Diesel ,Electric, Hybrid
•	-Transmission: Manual, Automatic, Semi-Automatic
•	-Mileage: Total distance travelled by car till date(higher mileage implies cheaper price)
•	-Doors: No of doors(2,3,4)
•	-Owner count: Number of Pre-owners of car(higher count implies cheaper car)

DEPENDENT VARIABLE/TARGET VARIABLE:
•	-PRICE

Problem Statement:
•	-Predicting price of a car based on a model trained over LABELLED data

Model Selection:
•	-The problem already has labelled data and requires prediction of a CONTINOUS NUMERICAL Variable,Hence,We will make a SUPERVISED LEARNING based REGRESSION MODEL
Data Source:
•	-A Kaggle based UNCLEEANED Car-Price dataset is pre-loaded in MYSQL database
•	-File Type: A FLAT FILE(.CSV) 

Libraries :
•	Pandas
•	Numpy
•	Mysql.connector
•	Matplotlib
•	Seaborn
•	Scipy.stats
•	Sklearn.preprocessing.StandardScaler
•	Sklearn.linear_model.LinearRegression
•	Sklearn.metrics.mean_squared_error,r2_score
•	Sklearn.model_selection.train_test_split
•	Sklearn.model_selection.cross_val_score,cross,val,predict
•	Sklearn.linear_model.Ridge
•	Warnings

Procedure:
•	Data Collection
o	Connecting to MYSQL data base with mysql.connector
o	Running queries to fetch requisite data
o	Convert the fetched data into pandas.Dataframe

•	Data Wrangling, Data cleaning, Data Preprocessing, Data Transformation:

o	Handling Missing Values
o	Handling Duplicate and Outlying Values
o	Data Standardization
o	Data normalization and scaling using z-score
o	Data Binning 
o	One-Hot-Encoding: Converting categorical to numerical variable







•	Exploratory Data Analysis(EDA):
o	Continuous numerical variables:
	Finding correlation coefficients
	Finding p-values
	Creating correlation matrix
	Plotting Heatmap of correlation
	Plotting Regplot
o	Categorical variables:
	Plotting Box plots
	Plotting Bar plots

•	Model Building and Predicting:
o	SLR(Simple Linear Regression)
o	MLR(Multiple Linear Regression)
o	Polynomial Regression

•	In-Sample Evaluation:
o	MSE(Mean squared error)
o	R2(R-squared)
o	Regression plot for SLR
o	Residual Plot
o	Distribution plot for MLR

•	Model Testing(using test-data)
o	Train_test_split

•	Out-Sample Evaluation(Using test-data)
o	MSE
o	R2
o	Regression plot
o	Residual Plot
o	Distribution plots

•	Model Refinement:
o	Ridge regression
o	Hyper-Parameter Tuning(Alpha)
o	Cross validation with
	Cross_val_score
	Cross_val_predict

•	Making Final Predictions by taking input from User and translating results

Final Remarks and Conclusions:
o	-Given the data source, Supervised Learning with Regression was adopted to predict a Continuous Numerical Value.
o	-Among the 3 Models built(SLR MLR and Polynomial),SLR performed best in Evaluation Metrics Like MSE and R2.
o	-The Regression plots and Residual Plots of SLR show a STRONG POSITIVE LINEAR RELATIONSHIP among Year and Price.
o	-The Final Predictions also testify the same trend.
o	-The newer the car, the costlier it gets.
o	-The model estimates not only the relationship among Year and Price, but also the STRENGTH of such a relationship that exists.




*DISCLAIMER
    -This project is a sole Intellectual property of mine i.e. GANDHARV GUPTA .Kindly acknowledge before copy or use of this project. The dataset is    open and is a property of Kaggle which holds all proprietary rights over it

END.

















