# How can we best leverage AirBnB reviews while making bookings?
[Click here to read the blog post](https://kelvinchanwh.com/projects/airbnb-analysis)

## Background

### Motivation
AirBnB is a popular platform that connects travelers with hosts who offer various types of accommodation, from private rooms to entire homes. With millions of listings worldwide, finding the right place to stay can be overwhelming and time-consuming. How can customers make sure that they are getting the best value for your money and that their expectations are met?

One way to do that is to leverage the reviews that previous guests have left for the listings. Reviews are a rich source of information that can reveal a lot about each accommodation. However, reading through hundreds or thousands of reviews can also be tedious and impractical. This project aims to combat that use natural language processing (NLP) techniques to analyse and summarize AirBnB reviews, and to determine if the ratings correlate to the sentiment of the reviews.

### Overview
In this project, I used a dataset of AirBnB listings and reviews from London, UK obtained from [Inside AirBnB](http://insideairbnb.com/get-the-data.html). The first section includes an exploratory data analysis to find some trends and patterns in the listings, such as the distribution of prices, ratings, and locations. 

The second part uses sentence embeddings to determine the correlation between the ratings of the listings and their reviews.

The main part of the project was to use a Large Language Model (LLM) to summarize all the reviews for each listing into bullet points. In this project, a LLM was used to extract the most relevant and important information from the reviews, such as the cleanliness, comfort, location, amenities, and host communication of each listing. This summary allows customers to gauge the suitability of the property at a glance.

### Business Questions
 - What are the main factors that infuence the monthly revenue of AirBnB hosts?
 - Do the review scores for each listing reflect the reviews provided by customers?
 - Can we reduce the time customers spend on reading reviews through summarization?

### Findings
To learn more about the findings, [click here to read the blog post](https://kelvinchanwh.com/projects/airbnb-analysis)

### Limitations
 - The analysis done here assumes that the data is taken at a given time and does not take into account seasonality and other factors that may affect the price. Thus, the values are only accurate at time of analysis. It is **NOT ADVISED** to use the prices found as a benchmark for your upcoming trip. 

