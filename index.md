# Welcome!
## Contents
* [About Me](#about-me)
* [Projects](#projects)
    * [What Else Did The Chase Stadium Bring to SF?](#what-else-did-the-chase-stadium-bring-to-sf)
    * [How Are Airbnb Listing Prices Determined?](#how-are-airbnb-listing-prices-determined)
    * [Your Anime Match Maker: An Anime Recommender System](#your-anime-match-maker-an-anime-recommender-system)
* [Case Studies](#case-studies)
    * [Classifying Fraud](#classifying-fraud)
    * [Sentiment Classification](#sentiment-classification)
    * [Preventing Churn](#preventing-churn)

---

## About Me

<b>I'm Sherry. I am a Data Scientist with a background in business operations in the consumer goods industry.</b>
<br>I have an insatiable sense of curiosity and I use Data Science to answer my many questions: Did the opening of the Chase Stadium bring more crime and mayhem to my beloved Dogpatch neighborhood in San Francisco? Let's find out with some hypothesis testing!
<br>I’ve always enjoyed streamlining processes, and have experimented with machine learning to do so: I created an Anime Recommender System to make finding my next anime faster. The application had over 4500 impressions within one week of posting on LinkedIn. Check out the WebApp to find your next anime!

---

## Projects

### [What Else Did The Chase Stadium Bring to SF?](/chase_center_impact)
<img src="https://camo.githubusercontent.com/4285e057a79646b9639752fe67a8f8e4d3549285/68747470733a2f2f692e696e73696465722e636f6d2f3563396366386366656535326566336265333739313330333f77696474683d3131303026666f726d61743d6a706567"/>
An exploratory data analysis comparing crime incidents and fire department service call volume in the Dogpatch and Mission Bay neighborhoods in San Francisco. Used Welch's T-Test and Mann Whitney U Test to confirm statistical significance between crime/fire during dates with events at the Chase Center versus not. <br>
<b>Technologies Used: Numpy, Pandas, Scipy, Matplotlib</b>

[Github Repo](https://github.com/sherryduong93/chasestadiumimpact)
<br>[PPT](/pdf/Chase_Center_Presentation.pdf)

---
### [How Are Airbnb Listing Prices Determined?](/predict_airbnb)
<img src="https://camo.githubusercontent.com/44e3714a5a3f647026db8008a65ca962d94ee1e1/68747470733a2f2f6d656469612e7465676e612d6d656469612e636f6d2f6173736574732f574e45502f696d616765732f38373364336266372d636137372d346437342d383234362d3133343830353762663563392f38373364336266372d636137372d346437342d383234362d3133343830353762663563395f3139323078313038302e6a7067"/>
Analyzed current Airbnb daily listing prices in San Francisco to predict prices of future listings using Linear Regression, Random Forest, and Gradient Boosting. Performed feature engineering and hyper-parameter tuning, eventually achieving a 75% improvement on baseline RMSE of $207, for a final RMSE of $54 on the cross-validated model with Random Forest.
<br><b>Technologies Used: Numpy, Pandas, Matplotlib, Seaborn, Sklearn, NLTK</b>

[Github Repo](https://github.com/sherryduong93/Predict_AirBnB_Listings)
<br>[PPT](/pdf/Airbnb_PPT.pdf)
<br>[Video Presentation](https://www.youtube.com/watch?v=ne7t15Zso4Y&t=2s)

---
### [Your Anime Match Maker: An Anime Recommender System](/animematchmaker)
<img src="https://github.com/sherryduong93/Anime_Recommender/raw/master/images/flask_welcome.png"/>
Created an Anime Recommender system using MyAnimeList's dataset of animes released prior to 2018. Recommender utilizes popularity-based, content-based similarity between anime (calculated with cosine similarity), and matrix factorization collaborative filtering techniques with Spark's ALS model.
<br><b>Technologies Used:  Numpy, Pandas, Matplotlib, Sklearn, Spark ML, AWS Sagemaker</b>

[Check out the Web App!](https://animerecz.herokuapp.com/) (It takes a second to load)

[Github Repo](https://github.com/sherryduong93/Anime_Recommender)
<br>[PPT](/pdf/Anime_PPT.pdf)
<br>[Video Presentation](https://www.youtube.com/watch?v=XqmXutqqiNI&feature=youtu.be)     

---
## Case Studies
### [Classifying Fraud](/pdf/Fraud_Classification.pdf)
Maximized profit for a ticket sales and distribution company by identifying fraudulent users and posts using Logistic Regression, Random Forest, Gradient Boosting, MLP Classifier, and XGBoost. Eventually achieving an AUC of 99.4%.
<br><b>Technologies Used:  Numpy, Pandas, Matplotlib, Seaborn, Sklearn, Github</b>

### [Sentiment Classification](/pdf/Sentiment_Classification.pdf)
Classified Sentiments of movie reviews using Text Classification techniques: Stopword removal, Stemming, Clustering, Topic Modeling, and Machine Learning Models: Naive Bayes, Logistic Regression, Random Forest, and Gradient Boosting. Eventually achieving an accuracy of 88%.
<br><b>Technologies Used:  Numpy, Pandas, Matplotlib, Seaborn, Sklearn, NLTK, Github</b>

### [Preventing Churn](/pdf/Preventing_Churn_Case_Study.pdf)
Using classification to identify potential customers with potential to churn. Utilized Logistic Regresssion, Random Forest, and Gradient Boosting, eventually achieving an accuracy of 78%.
<br><b>Technologies Used:  Numpy, Pandas, Matplotlib, Sklearn, Github</b>


