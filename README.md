# Comparative Study of Sentiment Expressed at Tourist Spots in Dubai and Pune

This repository contains the report for the final course project of Applied Data Science (Fall 2021) at NYU CUSP.

Tourism is one of the most important sources of economic activities in cities and a significant driver of the economy for many. While it contributes to 20% of the GDP for the small emirate of Dubai in the UAE, it contributes a minor fraction of 6.7% to the Indian GDP. It is crucial for governments to assess the impact of tourism-investment in these locations have on people around them - both tourists and residents. This raises the need to monitor the sentiment of visitors and residents both at tourist spots for developed and developing tourism locations using social media data. The explosion of available social media data allows for a more time-sensitive and geographically specific sentiment analysis than ever before. In this project, we perform a spatio-temporal sentiment analysis of data from the micro-blogging website Twitter to assess the general sentiment of both residents and visitors around these tourist destinations for the developed and developing (in the context of tourism) cities of Dubai and Pune respectively. This comparative study intends to identify differences in the patterns of sentiment distribution for both Dubai and Pune while also exploring any possible relationship between weather and these patterns.

The tourist destinations selected for Dubai are Burj Khalifa (25.1972° N, 55.2744°E), Burj Al Arab (25.1412° N, 55.1852° E), Dubai Marina (25.0805° N, 55.1403° E), Palm Jumeirah (25.1124° N, 55.1390° E), Dubai Museum (25.2635° N, 55.2972° E), and Dubai World Trade Center (25.2233° N, 55.2869° E). Selected hotspots for Pune are Dagdusheth Ganpati Temple (18.5164°N, 73.8561°E), Sinhagad Fort (18.3663°N, 73.7559°E), Shaniwar Wada Fort (18.5195°N, 73.8553°E), Aga Khan Palace (18.5525°N, 73.9015°E), and Khadakwasla Dam (18.4423°N, 73.7671°E)

# Observations
---
The average sentiment expressed at a tourism destination is indicated by the size of the circle at the spot. Larger the circle, more positive is the sentiment expressed.

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/Dubai_Tourist.jpeg" width=400>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/Pune_Tourist.jpeg" width=400>

We observe a common pattern in the trends of tweeting frequency in both cities.

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/dubai_hourly_frequency.jpg" width=600>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/pune_hourly_frequency.jpg" width=600>

We also observe unique trends in the average sentiment of expression in both cities. Tweets at night express more positive sentiment than throughout the rest of the day in both cities. These results are in agreement with previous results.

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/dubai_hourly_polarity.jpg" width=600>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/pune_hourly_polarity.jpg" width=600>

We also perform a correlation analysis between the features for tourist locations and both the cities separately to benchmark our conclusions mentioned in the report.

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/pune_tourist_weather_corr.jpg" width=400>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/dubai_tourist_weather_corr.jpg" width=400>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/pune_corr.jpg" width=400>

<img src="https://github.com/anerip98/comparative-study-of-sentiment-expressed-at-tourist-spots-in-dubai-and-pune/blob/main/images/dubai_corr.jpg" width=400>

