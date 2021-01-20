# Google Play Store Apps
## by Abdelrhman Khairy Werby


## Dataset
>   Google PlayStore App analytics. (1.1 Million + App Data) Source: https://www.kaggle.com/gauthamp10/google-playstore-apps.  
    The data collected with the help of Python and Scrapy running on a google cloud vm instance, The data was collected on December 2020.
    Users download apps for various usage purposes. Given that paid service is usually better at offering a pleasant experience and that free apps are more accessible to everyone, what the dataset will tell us about that and on another questions? 

## Data wrangling process:
>   1- Drop nan value.  
    2- Drop duplicates rows.  
    3- Remove space in columns name.  
    4- Convert the string data types to float in [Size, Installs]  

## Summary of Findings

###  Which Apps Category mostly common on Google play store?  
The Top 5 most common Category in Google play:  
>   1- Education  
    2- Music & Audio  
    3- Entertainment  
    4- Books & Reference  
    5- Tools  

###  Free or paid mostly common on Google play store?  
Free apps is of course the most commmon in google play store.  

### What is the shape of the ratings distrubtion?  
60% of the apps in Google play store have rating between 4 and 4.5  

### Which apps Category has the highest rating? (with rating count > 5000)  
The bar plot shows the relationship between app category and the rating.  
NOTE: the plot may not be very accurate because the rating count varies from app to app (here I choose to plot only the apps with ratings above 5000 counts). 

The top 5 apps category in number of installs:  
>   1- Books & Reference.  
    2- Parenting.  
    3- Health & Fitness.  
    4- Word.  
    5- Casino.  

###  Which apps Category has the most number of installs?  
The bar plot shows the relationship between app category and the number of installs of the app.  
The top 5 apps category in number of installs: 
>   1- Racing.  
    2- Action.  
    3- Strategy.  
    4- Arcade.  
    5- Video Players & Editors.  

### Which app Category has the largest size?  
The bar plot shows the relationship between the app category and the size of the app.   
The top 5 apps category in size: 
>   1- Role Playing.  
    2- Strategy.  
    3- Simulation.  
    4- Action.  
    5- Racing.  

### Free or paid apps have a higher rating?  
The paid apps tend to have higher rating than free apps, the paid apps mostly well designed apps so tend to have high rating.  

### Other findings:    
>    a. Small negative relation between app price and apps with ads supported, explain: most paid apps remove ads to have a better experience. 
    b. Small negative relation between free apps and (rating, editors choice), explain: most free apps isn't very good in UI and UX so tend to have lower rating and not included in editors choice.  
    c. Small positive relation between free apps and ads supported apps, explain: most free apps make money from the ads included in the app. 
    d. large positive relation between rating counts and the number of installs, explain: cause these apps have a higher number of users so it also has higher rate count.   
    e. small positive relation between editors choice and the number of installs, explain: most people trust the editors choice apps because it has better quality.   


## Key Insights for Presentation
The presentation will show and answer those questions: 
>    1- Free or paid apps have a higher rating?  
    2- Which Apps Category mostly common on Google play store?  
    3- Which apps Category has the highest rating? (with rating count > 5000)  
    4- Which apps Category has the most number of installs?  
    5- Which app Category has the largest size?  