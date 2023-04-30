# Capstone-Project-3-Classification
Mobile-Price-Range-Prediction. :-
Built a Multi-Class classification model to find the relation between features of a mobile phone(RAM, Internal Memory etc) and its selling price. Model will predict the price range indicating how high the price is.

 # Description.:-
lmaBetter Supervised Machine Learning Project Mobile Prize Range Prediction: ABSTRACT During the purchase of mobile phones, various features like memory, display, battery, camera, etc., are considered. People fail to make correct decisions, due to the non-availability of necessary resources to cross-validate the price. To address this issue, a machine learning model is developed using the data related to the key features of the mobile phone. The developed model is then used to predict the price range of the new mobile phone. Three machine learning algorithms namely Support Vector Machine (SVM), Random Forest Classifier (RFC), Logistic Regression are used to train the model and predict the output as low, medium, high, or very high. The dataset used in this study is taken from Kaggle platform. In order to improve the classification accuracy, Chi-Squared based feature selection method is used. Among 21 features available in the dataset, only top 10 features namely RAM, pixel height, battery power, pixel width, mobile weight, internal memory, screen width, talk time, front camera and screen height are selected and used to train the model. Before applying feature selection, the accuracy obtained using SVM, RFC and Logistic Regression is 95%, 83% and 76% respectively. After feature selection, the accuracy of SVM, RFC and Logistic Regression improved to 97%, 87% and 81% respectively. From the experiments conducted, it is found that SVM gave superior performance when compared to other two classifiers.

Mobile phones come in all sorts of prices, features, specifications, and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product.

The Problem The data contains information regarding mobile phone features, specifications etc and their price range. The various features and information can be used to predict the price range of a mobile phone.

The data features are as follows :-

1.Battery Power in MAH

2.Has Bluetooth or not

3.Microprocessor clock speed

4.The phone has dual sim support or not

5.Front Camera Megapixels

6.Has 4G support or not

7.Internal Memory in Gigabytes

8.Mobile Depth in Cm

9.Weight of Mobile Phone

10.Number of processor

11.Primary Camera Megapixels

12.Pixel Resolution height

13.Pixel resolution width

14.RAM in MB

15.Mobile screen height in cm

16.Mobile screen width in cm

17.Longest time after a single charge

18.3g or not

19.Has touch screen or not

20.Has WIFI or not Methodology We will proceed with reading the data, and then perform data analysis. The practice of examining data using analytical or statistical methods in order to identify meaningful information is known as data analysis. After data analysis, we will find out the data distribution and data types. We will train 4 classification algorithms to predict the output. We will also compare the outputs. Let us get started with the project implementation.

# Problem statement :-
In the competitive mobile phone market companies want to understand sales data of mobile phones and factors which drive the prices. The objective is to find out some relation between features of a mobile phoneleg - RAM Internal Memory, etc) and its selling price in this problem, we do not have to predict the actual price but a price range indicating how high the price is ?

# AIM :-
In this Project,On the basis of the mobile Specification like Battery power, 3G enabled , wifi ,Bluetooth, Ram etc we are predicting Price range of the mobile

# Dataset description :-

1.The given dataset from competitive mobile market companies, and we do not have to predict the actual price but a price range indicating how high the price is.

2.Mobile phones come in all sorts of prices, features, specifications and all. Price estimation and prediction is an important part of consumer strategy. Deciding on the correct price of a product is very important for the market success of a product. A new product that has to be launched, must have the correct price so that consumers find it appropriate to buy the product.

3.The above dataset has 2000 rows and 21 columns. There are no mising values and duplicate values in the dataset.

# Variables Description :-
1.Battery_power : Total energy a battery can store in one time measured in mAh

2.Blue : Has bluetooth or not

3.Clock_speed : speed at which microprocessor executes instructions

4.Dual_sim : Has dual sim support or not

5.Fc : Front Camera mega pixels

6.Four_g : Has 4G or not

7.Int_memory : Internal Memory in Gigabytes

8.M_dep : Mobile Depth in cm

9.Mobile_wt : Weight of mobile phone

10.N_cores : Number of cores of processor

11.Pc : Primary Camera mega pixels

12.Px_height : Pixel Resolution Height

13.Px_width : Pixel Resolution Width

14.Ram : Random Access Memory in Mega

15.Touch_screen : Has touch screen or not

16.Wifi : Has wifi or not

17.Sc_h : Screen Height of mobile in cm

18.Sc_w : Screen Width of mobile in cm

19.Talk_time : longest time that a single battery charge will last when you are

20.Three_g : Has 3G or not

21.Wifi : Has wifi or not

22.Price_range : This is the target variable with value of 0(low cost), (medium cost),2(high cost) and 3(very high cost).

# Conclusion :-
In this article, we looked at classification. Classifiers represent the intersection of advanced machine theory and practical application. These algorithms are more than just a sorting mechanism for organising unlabeled data instances into distinct groupings. Classifiers include a unique set of dynamic rules that include an interpretation mechanism for dealing with ambiguous or unknown values, all of which are suited to the kind of inputs being analysed. Most classifiers also utilise probability estimates, which enable end-users to adjust data categorization using utility functions.

1.From EDA we can see that here are mobile phones in 4 price ranges. The number of elements is almost similar.

2.half the devices have Bluetooth, and half don’t

3.there is a gradual increase in battery as the price range increases

4.RAM has continuous increase with price range while moving from Low cost to Very high cost.

5.costly phones are lighter.

6.RAM, battery power, pixels played more significant role in deciding the price range of mobile phone.

7.form all the above experiments we can conclude that XGboosting and linear regression with using hyperparameters we got the best results.

Built a Multi-Class classification model to find the relation between features of a mobile phone(RAM, Internal Memory etc) and its selling price. Model will predict the price range indicating how high the price is.


