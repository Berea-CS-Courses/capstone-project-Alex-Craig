**Overview:**

So the project that I have settled on completing is my Food Randomizer App that will try and randomize a food location based off the information given (covered in Concepts). With this app I hope to help friend groups eliminate the time it takes to choose somewhere to go and allows for more time spent hanging out rather than just searching. If enough time is available I also hope to add activities such as movies, mini golf, aracades, bowling, etc. to create an Activity Randomizer.

**Concepts:**

The main concept is to build more onto a basic wheel app that allows you to input the things you want to do inside and instead allows the app to do it for you, and gives you the information of the restaurant included. I hope to use the Google Places API and web scraping to create a website and/or app. My project will take in information such as the urgency/waiting time, how much you are willing to spend, measurements (km/mi), distance, displays the ratings and hours of the restaurant, and a possible option for a reroll as its major features. I also plan to add a search option that allows you to search based off of type of food to accomodate for allergies and dietary restrictions, but most restaurants already have alternative options so this might be dropped.

**Requirements:**

- Software must be able to scrape information from the web using Google Maps/Places API
- Software must be able to randomly generate a restaurant based off information given
- Software must be able to use user's location, map data, or search by zip
- Software must be able to have an open restaurants only mode
- Software must be able to separate restaurants based off waiting times, prices, and distance
- Software must be able to run on an app and/or web browser
- Software must be able to implement a reroll function.
- Software might be able to separate restaurants based off type of food.
- Software must be able to display directions to the chosen restaurant.
- Software must be able to sort restaurants based off of food types (Asian, Mexican, Italian, etc.)

**Updates**
- I want my app to be useable on IOS and Android devices and I have changed how the app will work. The app will now take in the user's location by asking them to type it in and will have the auto fill option to make it easier. Then the app will ask the user how many people are in the car (1-4) to divide the number of choices they get evenly (12 choices divided by number of people). Using the address given and an API (Google Places, Yelp or Zomato) will display a list of restaurants for the users to add to the roulette wheel based on the number of choices they have (choices can overlap). Once all 12 choices are added the app will ask the user to spin the wheel. After that it will display the winner's name, location, directions, website, and a roll again feature. I have dropped the urgency, costs, ratings/hours, and search option of a previous idea as the restaurants website should have most of this information and that will be implemented instead.
