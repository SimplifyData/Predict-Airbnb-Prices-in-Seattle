# Predict Airbnb Prices in Seattle

Predict Airbnb Prices in Seattle using open data from Airbnb, Uber Movement, Yelp, & City of Seattle

This data science analysis will take into consideration the available data from Airbnb to analyze prices in difference areas in Seattle.
I am incorporating Uber Movement - Seattle ride data to analyze the traffic and public flow in the areas to predict popularity of the areas. 

The traffic density will be incorporated and tested against Yelp and Ticket Master open data to observe how busy and eventful these areas are. As a result, I want to find out how these factors are affecting the desirability of the Airbnb places impacting the prices.

If the Uber traffic is high, there are busy restaurants, popular restaurants and places, concerts and events in the area for the year 2017. Then what were the Airbnb prices and number of listings in those areas against the places that were in less busy areas.

I may use clustering here, density maps, do some research to analyze which supervised machine learning algorithm will be used when I combine all the features from different data sources.

Perhaps I may perform some sentiment analysis on the restaurant reviews to analyze the type of crowd in the area and find a correlation to the Airbnb prices nearby?

### Data Analysis Process: CRISP-DM
**Cross Industry Standard Process for Data Mining**
1) Business Understanding : Predict Seattle Airbnb prices.
2) Data Understanding
3) Data Preparation
4) Modeling
5) Evaluation

### Python Libraries used for the Project
1) Numpy
2) Pandas
3) Matplotlib
4) Numba

### Business Questions:
1) How does number of reviews drive the Airbnb Prices in Seattle.
2) How competent and stable are the Airbnb prices dependent on popularity of a place?
3) How does Uber traffic in an area drive the prices and number of reviews of Airbnb places?
4) How does popularity and quality of restaurants (Yelp) reflects on the Airbnb prices in the area?
5) Does proximity to places and events drives reviews and prices of Airbnb places? 

### Citations

The data sets can be obtained from the open data links from:
1) “Data retrieved from Uber Movement, (c) 2019 Uber Technologies, Inc., https://movement.uber.com”

2) Data.seattle.gov. (2019). Seattle Cultural Space Inventory Map. [online] Available at: https://data.seattle.gov/Community/Seattle-Cultural-Space-Inventory-Map/pknd-dutm [Accessed 6 Jan. 2019].

3) Inside Airbnb. (2019). Inside Airbnb. Adding data to the debate.. [online] Available at: http://insideairbnb.com/get-the-data.html [Accessed 6 Jan. 2019].

4) Yelp.com. (2019). Yelp Dataset. [online] Available at: https://www.yelp.com/dataset [Accessed 6 Jan. 2019].

5) The Ticketmaster Developer Portal. (2019). Getting Started. [online] Available at: https://developer.ticketmaster.com/products-and-docs/apis/getting-started/ [Accessed 6 Jan. 2019].

6) Devlin, J. (2018, February 06). Machine Learning Fundamentals: Predicting Airbnb Prices. Retrieved from https://www.dataquest.io/blog/machine-learning-tutorial/

7) A Quick Introduction to K-Nearest Neighbors Algorithm. Retrieved from
https://medium.com/@adi.bronshtein/a-quick-introduction-to-k-nearest-neighbors-algorithm-62214cea29c7

8) A Complete Guide to K-Nearest-Neighbors with Applications in Python and R. (n.d.). Retrieved from https://kevinzakka.github.io/2016/07/13/k-nearest-neighbor/

9) Avila, J., & Hauck, T. (2017, November). Scikit-learn Cookbook - Second Edition -Tuning an AdaBoost regressor. Retrieved January 22, 2019, from https://subscription.packtpub.com/book/big_data_and_business_intelligence/9781787286382/9/ch09lvl1sec95/tuning-an-adaboost-regressor

10) Srivastava, T. (2018, April 26). Tuning Random Forest model | Machine Learning | Predictive modeling. Retrieved from https://www.analyticsvidhya.com/blog/2015/06/tuning-random-forest-model/

11) Singh, A. (2018, September 04). A Practical Introduction to K-Nearest Neighbor for Regression. Retrieved from https://www.analyticsvidhya.com/blog/2018/08/k-nearest-neighbor-introduction-regression-python/
