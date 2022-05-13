
# Android Playstore Market Analysis
 This is a complete Exploratory Data Analysis(EDA) project which is comparing over ten thousand apps in Google Play across different categories. 
 

![Logo](https://1000logos.net/wp-content/uploads/2021/06/Google-Play-logo-768x432.png)


## Goal

Get insights from the data to devise strategies to drive growth and retention. The [data](https://www.kaggle.com/lava18/google-play-store-apps) for this project was scraped from the [Google Play](https://play.google.com/store/apps?hl=en) website. 

Which category has the highest share of (active) apps in the market?
Is any specific category dominating the market?
Which categories have the fewest number of apps?
## I answered questions like :

 - Which category has the highest share of (active) apps in the market? <p>
   <p>Family , Games and Productivity tools are the most active apps.
 - Which categories have the fewest number of apps?<p>
   <p>Entertainment , beauty, comics are happen to have not as many apps I would've expected it to.

![newplot](https://user-images.githubusercontent.com/68342710/168185464-729b2040-6898-45f5-89dd-b7cef31c517a.png)

## Distribution of app ratings 

The average volume of ratings across all app categories is 4.17. The histogram plot is skewed to the left indicating that the majority of the apps are highly rated with only a few exceptions in the low-rated apps.
    
     '''avg_app_rating = apps['Rating'].mean()
         print('Average app rating = ', avg_app_rating)'''

![newplot (1)](https://user-images.githubusercontent.com/68342710/168185421-30dfa7de-f612-4d5e-b3ee-d4d6fe63dd93.png)
    

'''
data = [go.Histogram(
        x = apps['Rating']
)]








