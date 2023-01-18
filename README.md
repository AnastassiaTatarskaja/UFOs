# Filter UFO sightings on multiple criteria

## Overview of the analysis:

The webpage and dynamic table are designed to provide an in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, user will be able to filter by city, state, country, and shape.

## Results:

Let’s take a look at our webpage and learn how functional search fields are. Below is what the page looks like while it is in the default stage.

![image](https://user-images.githubusercontent.com/107759305/213323148-3159b3ee-ad27-43db-9cff-8260a3247dbe.png)

From there, if we would like to filter the results by date, we will simply enter the date in the “Enter a Date” field, and receive a result below. Let’s enter 1/3/2010. As you can see from the table below, there is only one data entry for that date. 

![image](https://user-images.githubusercontent.com/107759305/213323215-ecfd1ef8-ffa7-4edf-acb0-fbc89db8c34a.png)

Let’s say you would like to filter by shape, specifically “circle”. Once you enter the word “circle” in the “Enter a Shape” field, the following result will be displayed. 

![image](https://user-images.githubusercontent.com/107759305/213323366-7689112e-b0ca-4c3e-beaf-b2d28736f7d0.png)

Additionally, you can perform a search on multiple search criteria. For example, if you would like to search by date (1/2/2010) and state(fl), the following result would be displayed in the table. 

![image](https://user-images.githubusercontent.com/107759305/213323508-7b67d179-663f-4172-9ebf-6a91a3155aba.png)

## Summary:

One drawback of this particular webpage design is that there is no way for the user to know the timeframe that Dana was logging her data for. It makes it difficult to perform a search, unless the user has access to the original data set, (data.js).

Recommendations that will help improve the user experience:

1. Identify a timeframe, such as 1/1/2010 - 1/13/2010, so that the user will only enter dates within that timeframe.

2. Add an analysis box that will identify for example, the number of states, and/or total number of minutes, almost like an analytical summary or a total for each column. It could say something like: “According to the search criteria, there was a total of 50 minutes spent on observation during this period of time”.
