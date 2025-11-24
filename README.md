# Top-Japanese-Restaurants-Tabelog

One of the things that we're the most excited about is all of the great food places in Japan. We're certain that we'll be able to find good food almost anywhere but the sheer number of excellent restaurants in Japan is mindboggling. The most popular Japanese Restaurant rating site is Tabelog which is similar to Yelp. Unfortunately, their English version of the website does not allow you to search for the restaurants by name and you can only use filters to find a place. In order to make things easier to view, I thought it would be good to scrape the areas I was interested in for different uses. 

To help us orient ourselves, I wanted to have a map showing the top rated spots in the cities so we could keep an eye out while we wander. The goal of this is to put everything onto one spreadsheet and Google Maps so that I can have the flexibility of finding spots on the go or to filter out what I want to eat from the top rated restaurants. The current workflow is scraping tabelog.com for the ranking data $\rightarrow$ outputtings a .csv file $\rightarrow$ importing to Google Sheets $\rightarrow$ export the addresses to Google MyMaps. This will import everything onto a layer that can be viewed when using Google Maps and give us the ability to do some filtering and searching in Google Sheets while on the go.

Spreadsheets that contain the organized restaurant information will have the name, address, rating, reviews, lunch/dinner pricing, address, and a link to the Google Maps page for the restaurant.
![Final Spreadsheet](https://github.com/cwfling/Top-Japanese-Restaurants-Tabelog/blob/main/Tabelog%20Scraper/img/final.png "Final Spreadsheet") 

The pins showing restaurants can be toggled on or off on Google maps to help with seeing what is currently close to you. Each pin will contain information like name, address, pricing, reviews, and cuisine type to inform the users.
<img src="https://i.imgur.com/ROQ0MJy.jpeg" width="512"/>
