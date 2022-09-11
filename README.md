
<h1 align="center"> Mobile Price Range Prediction
 </h1>

<h3 align="center"> AlmaBetter Verified Project - <a href="https://www.almabetter.com/"> AlmaBetter School </a> </h5>

<p align="center"> 
<img src="https://miro.medium.com/max/687/1*HOeXnYBa03ZIiPFeJUHY1g.png" height="400px">
</p>


<p> </p>

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> :floppy_disk: Table of Content</h2>

 
  * [Introduction](#Introduction)
  * [Problem Statement](#Problem-Statement)
  * [Dataset Information](#dataset-information)
  * [Steps involved](#Steps-involved)
  * [Models used](#Models-used)
  * [Conclusion](#Conclusion)


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> 📄 Introduction</h2>

Mobile phones are one of the most common and most in demand electronic devices in today’s times.Theis device has revolutionized our society and simplified our lives in many ways. Mobile phones have enabled us to easily communicate with people all over the globe regardless of where we are, stay informed with the help of the internet, play music ,videos and games, take photos and videos,store and share considerable amounts of data,conduct monetary transactions and much more.

The demand for mobile phones grows in tandem with technological advancements,every year. Needless to say, there are a large number of companies competing in this market right now. Therefore,companies want to understand sales data of mobile phones and factors which drive the prices.
🎯The goals of this project are:
* To find the relation between the features (RAM, phone dimensions,camera quality,etc.) of the phone and the selling price.
* To identify the Classification  model which accurately predict the price range of the phones based on features.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> ❓ Problem Statement</h2>

The rising demand for mobile phones has led to fierce competition in the market.Pricing is an important factor that determines the product's success on the market. Therefore,it is important for companies to identify the important features which influence the price of the phone  .This will help them to decide the appropriate price for their product.



![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2> :book: Dataset information </h2>

* **battery_power** - Total energy a battery can store in one time measured in mAh
* **blue** - Has bluetooth or not
* **clock_speed** - speed at which microprocessor executes instructions
* **dual_sim** - Has dual sim support or not
* **fc** - Front Camera mega pixels
* **four_g** - Has 4G or not
* **int_memory** - Internal Memory in Gigabytes
* **m_dep** - Mobile Depth in cm
* **mobile_wt** - Weight of mobile phone
* **n_cores** - Number of cores of the  processor
* **pc** - Primary Camera megapixels
* **px_height** - Pixel Resolution Height
* **px_width** - Pixel Resolution Width
* **ram** - Random Access Memory in MegaBytes
* **sc_h** - Screen Height of mobile in cm
* **sc_w** - Screen Width of mobile in cm
* **talk_time** - longest time that a single battery charge will last when you are
* **three_g** - Has 3G or not.
* **touch_screen** - Has touch screen or not
* **wifi** - Has wifi or not
* **price_range** - This is the target variable with value of 0(low cost), 1(medium cost), 2(high cost) and 3(very high cost).


![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2>🛠️ Tools and Technologies Used </h2>


The programming language used in this project is Python . The following libraries were used for data analysis and data visualization and to build a classifier to predict the price range of mobile phones.

* **Pandas** :  For loading the dataset and performing data wrangling
* **Matplotlib**: For  data visualization.
* **Seaborn**: For data visualization.
* **WarningsWarnings**: For filtering and ignoring the warnings.
* **NumPy**: For some math operations in predictions.
* **Statsmodels**: For statistical computations
* **Sklearn**:  For the purpose of analysis,prediction and evaluation.

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

<h2> 📑 Steps involved </h2>

* **Data Preprocessing** :  Dealt with outliers, incorrect values, missing values (if any), duplicates (if any), and data type corrections. 
* **Exploratory Data Analysis** : Performed Univariate, Bivariate, and Multivariate analysis with various graphs and plots to better understand the distribution of features and their relationships.
* **Feature Selection** :  Selected important features while discarding those that were irrelevant to our purpose,using SelectKBest  method .
* **Feature Scaling** : Brought  features to a similar range using MinMaxScaler.
* **Implementation of Classification models** 
* **Hyperparameter tuning** 
* **Comparison of models**

![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)


<h2>💻 Algorithms used</h2>

* Logistic regression
* K-Nearest Neighbors
* Support Vector Machines
* Naive Bayes
* Random Forest Classifier
* XGBoost

<h2> :bulb: Conclusion</h2>

*  SVM and Logistic regression models  give the most accurate prediction  and hence these models are best fit in this scenario.
*  Feature selection based on ‘Chi2’ and Feature importance graphs plotted from the models suggest that RAM, pixel resolution (pixel width and pixel height) and battery power are the most important factors that influence the pricing of the mobile phones.






![-----------------------------------------------------](https://raw.githubusercontent.com/andreasbm/readme/master/assets/lines/rainbow.png)

Footer
© 2022 GitHub, Inc.
Footer navigation
Terms
Privacy
Security
Status
Docs
Contact GitHub
Pricing
API
Training
Blog
About
