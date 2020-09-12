---
title: "predicting house prices"
subtitle: 'uc berkeley | machine learning'
date: 2020-03-16 00:00:00
featured_image: '/images/ML_cover.png'
---

<!-- ![](/images/impact_chart.png) -->

<!-- ## About the Project -->
<br> Contributors: Allison Godfrey, Ian Anderson, Jacky Ma, and Surya Gutta

#### Project Description

The <a href="https://github.com/allison-godfrey/w207-final-group-project/blob/master/W207_Predict_Property_Sale_Price.ipynb">House Price Prediction</a> Kaggle competition is based on the <a href="http://jse.amstat.org/v19n3/decock.pdf">Ames Housing Dataset</a>. The goal of this project is to predict sale price of homes on the given training and test data sets containing 90 features of each home. 
In this <a href="https://github.com/allison-godfrey/w207-final-group-project/blob/master/W207_Predict_Property_Sale_Price.ipynb">Final Notebook</a>, my team and I used machine learning approaches to try to most accurately predict home price based on relevant features. 

The main components of the notebook are:

* EDA and data cleansing
	* Outlier analysis
	* Replace missing values
	* Exclude columns over 10% missing values
* Feature Engineering
	* Univariate and Bivariate analysis of explanatory features
	* Encode categorical and ordinal features
	* Transform skewed variables (features and outcome variable)
* Data split - 
	* 80% train, 20% dev 
	* 5-fold Cross Validation
* Model Building
	* Bayesian Ridge Regression
	* Lasso Model
	* Bayesian ARD Regression
	* Elastic Net Regressor
	* Theil-Sen Estimator
	* Ordinary Least Squares Linear Regression
	* Random Forest Regressor
	* XGB Regressor
	* Ada Boost Regressor
	* Blended Model
* Assessment of individual and blended models
	* Adjust model weights 
	* Overfitting versus generalization analysis
<br>

#### Skills

Machine Learning, Data Cleansing, Correlation Analysis, Feature Engineering

#### Tools

Python, SciKit Learn, Jupyter Notebooks, Matplotlib

<!-- The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| Duet Jekyll Theme    | Jekyll Themes | Yes              | $49   |
| Index Jekyll Theme   | Jekyll Themes | Yes              | $49   |
| Journal Jekyll Theme | Jekyll Themes | Yes              | $49   |

And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too:
 -->
---

<!-- ### Image galleries

Here's a really neat custom feature we added – galleries:

<div class="gallery" data-columns="3">
	<img src="/images/demo/demo-portrait.jpg">
	<img src="/images/demo/demo-landscape.jpg">
	<img src="/images/demo/demo-square.jpg">
	<img src="/images/demo/demo-landscape-2.jpg">
</div>

Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a bit of simple HTML in your post to create a masonry grid image layout:

```html
<div class="gallery" data-columns="3">
    <img src="/images/demo/demo-portrait.jpg">
    <img src="/images/demo/demo-landscape.jpg">
    <img src="/images/demo/demo-square.jpg">
    <img src="/images/demo/demo-landscape-2.jpg">
</div>
```

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page. -->

---

### Results

We measured each model's accuracy by its Root Mean Squared Log Error (RMSLE). Looking at the following chart, the RMSLE was lowest in our Blended Model with a distinct set of model weights. This RMSLE (0.09252) achieved our best competition score, but was not our lowest RMSLE within our notebook, illustrating that our models were prone to overfitting. The RMSLE of 0.09252 represents our best balance between overfitting and generalizability. 

<img src="/images/RMSE_analysis.png">


### Summary

From the beginning, our focus was more on *know your data*. Therefore, we were very intentional about how we encoded each categorical and ordinal feature, how we assigned missing values, how we aggregated some features to avoid multicolinearity, and how we iteratively performed our feature selection process. See the following <a href="https://allison-godfrey.github.io/assets/final_project.pdf">Slide Deck</a> to discover more about our iterative process and some further extensions of the model. 

We started at a Kaggle placement of 3500 and have worked our way up to a placement of 525 **(top 12% of submissions).** 



---


