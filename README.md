# British Airways Data Science Simulation on Forage

* Completed a simulation focussing on how data science is a critical component of British Airways success
* Scraped and analysed customer review data to uncover findings 
* Built a predictive model to understand factors that influence buying behaviour using Machine Learning
* Tools: Python & PowerPoint

# Sentiment Analysis

* Positive trend
* Reviews larger than 0 show greater customer satisfaction
* More than 50% of the reviews are positive

<img width="490" alt="image" src="https://github.com/eparaschou/BritishAirwaysAnalysis/assets/148002149/8c64980b-d6d7-45bb-86fc-3839254099b8">

# Word Cloud Analysis

<img width="796" alt="Screenshot 2023-11-17 at 7 23 36 PM" src="https://github.com/eparaschou/BritishAirwaysAnalysis/assets/148002149/7ac50ecd-738d-42d4-9686-3bc8f1874f01">

<img width="853" alt="Screenshot 2023-11-17 at 7 46 25 PM" src="https://github.com/eparaschou/BritishAirwaysAnalysis/assets/148002149/c3c1d724-c6e2-4fff-bc3a-cac7bc450e39">

The most common words extracted from the customers’ reviews are:
  * ‘Trip’
  * ‘Verified’
  * ‘BA’
  * ‘flight’
  * ‘time’
  * ‘seat’
  * ‘check’
  * ‘service’

Based on the results, passengers care most about the quality of the trip, flight delays, and comfort.

# Topic Modeling - LDA 

<img width="1182" alt="Screenshot 2023-11-17 at 7 00 22 PM" src="https://github.com/eparaschou/BritishAirwaysAnalysis/assets/148002149/8866be78-4d50-4453-9856-7248a570cd26">

# Classification Report
 
<img width="448" alt="image" src="https://github.com/eparaschou/BritishAirwaysAnalysis/assets/148002149/384fb908-4951-403e-9d5d-ecc583383dd3">

* The model accurately predicts 85% of instances
* When the model predicts a booking (class 1), it is less certain and has a higher chance of false positives
* The model is better at capturing instances where there is no booking (class 0) than instances where there is a booking (class 1)
* F1 score = 92% indicates good performance
* The model relies heavily on features like purchase_lead and length_of_stay to make predictions

# Cross-Validation

* Cross-validated Accuracy on Sample: 0.85 (+/- 0.01) 
* Cross-validated Accuracy on Full Dataset: 0.73 (+/- 0.20)
* The sample indicates a higher cross-validated accuracy compared to the full dataset
* There is more variability in the full dataset


