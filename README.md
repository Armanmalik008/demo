# Zomato Restaurant Data Analysis and Recommendation System 🔥

<p align="center">

  [![forthebadge made-with-python](http://ForTheBadge.com/images/badges/made-with-python.svg)](https://www.python.org/)
  
  ![GitHub stars](https://img.shields.io/github/stars/chiragsamal/Zomato)
  ![GitHub forks](https://img.shields.io/github/forks/chiragsamal/Zomato)
  [![GitHub contributors](https://img.shields.io/github/contributors/chiragsamal/Zomato.svg)](https://GitHub.com/chiragsamal/Zomato/graphs/contributors/)
  [![GitHub license](https://img.shields.io/github/license/chiragsamal/Zomato.svg)](https://github.com/chiragsamal/Zomato/blob/master/LICENSE)
  [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
  [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity)
</p>  

![Zomato](https://github.com/chiragsamal/Zomato/blob/master/Images/zomato.jpg)

##  Overview
This project involves analyzing data from Zomato to derive insights into restaurant trends, customer preferences, and other key metrics. The goal is to uncover patterns and provide actionable insights to improve decision-making for stakeholders in the food and beverage industry.

##  Features
Data Cleaning: Handling missing values, duplicates, and data inconsistencies.
Exploratory Data Analysis (EDA): Identifying trends in ratings, pricing, locations, and cuisines.
Visualizations: Creating plots and charts to showcase findings.
Insights & Recommendations: Offering actionable recommendations based on analysis.

## Methodology 🛠️
### Phase I,

In Phase I of extraction only the URL, name and address of the restaurant were extracted which were visible on the front page. The URl's for each of the restaurants on the zomato were recorded in the csv file so that later the data can be extracted individually for each restaurant. This made the extraction process easier and reduced the extra load on my machine. The data for each neighborhood and each category can be found here

### Phase II,

In Phase II the recorded data for each restaurant and each category was read and data for each restaurant was scraped individually. 15 variables were scraped in this phase. For each of the neighborhood and for each category their online_order, book_table, rate, votes, phone, location, rest_type, dish_liked, cuisines, approx_cost(for two people), reviews_list, menu_item was extracted. See section 5 for more details about the variables.

### Phase III,
In Phase III, Sentiment Analysis of Reviews of the dataset to identify the feelings of the users towards Restaurants. Sentiment analysis is the computational task of automatically determining what feelings a writer is expressing in text. Sentiment is often framed as a binary distinction (positive vs. negative), but it can also be a more fine-grained, like identifying the specific emotion an author is expressing (like fear, joy or anger).

### Phase IV,
The rapid growth of data collection has led to a new era of information. Data is being used to create more efficient systems and this is where Recommendation Systems come into play. Recommendation Systems are a type of information filtering systems as they improve the quality of search results and provides items that are more relevant to the search item or are realted to the search history of the user. They are active information filtering systems which personalize the information coming to a user based on his interests, relevance of the information etc. Recommender systems are used widely for recommending movies, articles, restaurants, places to visit, items to buy etc. Here I will be using Content Based Filtering
Content-Based Filtering: This method uses only information about the description and attributes of the items users has previously consumed to model user's preferences. In other words, these algorithms try to recommend items that are similar to those that a user liked in the past (or is examining in the present). In particular, various candidate items are compared with items previously rated by the user and the best-matching items are recommended.

## Inspiration
I was always astonished by how each of the restaurants are able to keep up the pace inspite of that cutting edge competition. And what factors should be kept in mind if someone wants to open new restaurant. Does the demography of an area matters? Does location of a particular type of restaurant also depends on the people living in that area? Does the theme of the restaurant matters? Is a food chain category restaurant likely to have more customers than its counter part? Are any neighborhood similar ? If two neighborhood are similar does that mean these are related or particular group of people live in the neighborhood or these are the places to it? What kind of a food is more popular in a locality. Do the entire locality loves vegetarian food. If yes then is that locality populated by a particular sect of people for eg. Jain, Marwaris, Gujaratis who are mostly vegetarian. There are infacts dozens of question in my mind. lets try to find out the answer with this dataset.

You can download the dataset here: [Zomato Bangalore Restaurants](https://www.kaggle.com/himanshupoddar/zomato-bangalore-restaurants/download)

## Sections 📚
✔️ Exploratory Data Analysis\
✔️ Visualization \
✔️ Rate Prediction\
✔️ Sentiment Analysis of Reviews\
✔️ Recommendation System\

## License 📄
This project is licensed under the MIT License - see the [LICENSE.md](./LICENSE) file for details.

## Contributing 💡
If you can help us with these. Please don't hesitate to open an [pull request](https://github.com/chiragsamal/Zomato/pulls) or [issue](https://github.com/chiragsamal/issue/issues).

### Refrences 👏
 - [Finding the best restaurants in Bangalore](https://www.kaggle.com/parthsharma5795/finding-the-best-restaurants-in-bangalore)
 - [Zomato Bangalore Restaurant Rating Prediction](https://www.kaggle.com/bablukd/zomato-bangalore-restaurant-rating-prediction)

