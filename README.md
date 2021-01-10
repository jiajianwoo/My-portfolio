# Portfolio

## [Analysing and Predicting Customer Churn in Telcom](https://github.com/jiajianwoo/telco_churn/blob/main/telco%20churn.ipynb)
* Dataset from Kaggle: https://www.kaggle.com/blastchar/telco-customer-churn

All analysis was based only on this dataset. It seems that churn rate was lower among customers who subscribed for extra services like streaming TV, streaming movies, online backup, online security, tech support etc. Higher churn rate was also observed for newer customers, customers who paid monthly (instead of paying annually), senior citizens and customers with no partners/dependents.

* **Churn rate is the highest among new customers (<3 months).**
<img src="image/Screenshot%202021-01-10%20at%2017.15.19.png" alt="drawing" width="500" />

* **ROC curve of the logistic regression model built**
<img src="image/Screenshot%202021-01-10%20at%2017.14.45.png" alt="drawing" width="500" />



## [Analysing Tripadvisor Reviews (Python)](https://github.com/jiajianwoo/Analysing-museum-reviews-on-Tripadvisor/blob/main/BM%20reviews.ipynb)
* Web scraped British Museum reviews from Tripadvisor
* Performed sentiment analysis
* Performed topic modelling to gain insights on visitor reviews

* **Distribution of positive and negative reviews:**

<img src="image/Screenshot%202020-12-22%20at%2012.12.27.png" alt="drawing" width="500" />

* **Word cloud representing the words used in positive reviews left by visitors:**

<img src="image/Screenshot%202020-12-21%20at%2015.46.37.png" alt="drawing" width="600" />

* **Word cloud representing the words used in negative reviews left by visitors:**

<img src="image/Screenshot%202020-12-21%20at%2015.46.46.png" alt="drawing" width="600" />

* **Upon topic modelling on positive reviews, the following are the words used in each of two topics:**

<img src="image/Screenshot%202020-12-21%20at%2015.47.00.png" alt="drawing" width="450" />

Positive reviews of the museum were mainly about 2 topics: its temporary exhibitions (one of which is the Troy exhibition) and its permanent exhibitions.

The collections displayed in the permanent collection, e.g. items in the Egyptian gallery and the Rosetta Stone were mentioned frequently in the positive reviews, as well as the fact that its entrance is free of charge.


* **Words used in negative reviews:**

<img src="image/Screenshot%202020-12-21%20at%2015.46.18.png" alt="drawing" width="250" />

Looking at the topic modelling results, it seems like the negative reviews revolved around only one topic. The negative reviews were mostly about the exhibitions and the crowds. The imperialist controversies around British Museum, primarily its acquisition of items of like the Elgin Marbles and the Rosetta Stone were not mentioned as frequently in the reviews.

To improve visitor experience, the museum can work on improving how the exhibitions are organised and crowd management.



## [Analysing Booking.com Reviews (Python)](https://github.com/jiajianwoo/text-mining-hotel/blob/main/Booking%20text%20mining-2.ipynb)
* Web scraped reviews of a hotel in Kuala Lumpur from Booking.com
* Performed sentiment analysis
* Performed topic modelling to gain insights on guest reviews to explore issues that can be addressed to improve guest satisfaction

* **Distribution of positive and negative reviews:**

<img src="image/Screenshot%202020-12-22%20at%2012.12.40.png" alt="drawing" width="500" />

* **Word cloud representing the words used in positive reviews left by guests:**

<img src="image/Screenshot%202020-12-21%20at%2022.41.16.png" alt="drawing" width="600" />

* **Word cloud representing the words used in negative reviews left by guests:**

<img src="image/Screenshot%202020-12-21%20at%2022.41.33.png" alt="drawing" width="600" />

* **Words used in negative reviews:**

<img src="image/Screenshot%202020-12-21%20at%2022.42.13.png" alt="drawing" width="600" />

This should give the hotel's management some insights on what their guests were mostly unsatisfied about: parking, staff, breakfast and room condition/cleanliness. The management should still look at the detail reviews to see exactly what improvements are needed.




## [Predicting Cancellation of Hotel Reservations (R)](https://rpubs.com/jiajianwoo95/706496)
* Analysed guest visits at a city hotel and a resort
* Analysed reservation cancellation behaviour
* Built a model to predict whether guests would cancel their reservations


<img src="image/Screenshot%202020-12-21%20at%2016.39.36.png" alt="drawing" width="600" />

Significant proportion of guests cancelled their hotel reservations.

<img src="image/Screenshot%202020-12-21%20at%2016.56.20.png" alt="drawing" width="600" />

People from some countries are more likely to cancel their reservations compared to other countries.

<img src="image/Screenshot%202020-12-21%20at%2016.56.30.png" alt="drawing" width="600" />

The above graph compares the predictions made by the model on the number of cancellations every day with the actual number.


