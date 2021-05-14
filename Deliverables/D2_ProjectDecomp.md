# Deliverable 2 - Project Decomposition

**Name: Alex Craig**  

**Components**
- Take in the users location
- Use Google Places API to display restaurants based on the location of the users input.
- Filter the restaurants by availability, distance, price range, and food type (possibly web scraping).
- Display the list of restaurants to allow the user to select certain restaurants.
- Spin the wheel and choose a random restaurant.
- Allow the user to spin again if needed.
- Get directions for chosen restaurant.

**Understanding the components**
- By writing out my components in a list in order based on what I want the app to do seems a lot easier than I first assumed and was worried about. When I see this list I realize that the previous step is required for the next step. Now I have a timeline and backbone of what I need to get done I think I will be able to implement these features easier.

**Breaking up components**
- My components are pretty much broken up into the bits and pieces that I need to work on. However I could break up the filtering process into different steps but I think the Google Places API will already display the distance, price range, etc.

**Prioritize**
- Think of app names (Restaurant Roulette - Ezra S.)
- Learn Google Places API (https://www.youtube.com/watch?v=5oG2Q2GMOBE&ab_channel=GoogleDevelopers)
- Design a logo (Needed for Google Places)
- Everything else is in the order needed from the components
- Putting everything together into an app and/or website.
- https://ibb.co/C2sQDRh (Paper Drawing)
- https://ibb.co/f96ZfVV (logo)

**Notes**
- I actually figured out how to create this app with coding from Apple's IOS Shortcuts. The only problem with this is that if I do this my app will be limited to IOS devices only.
- Also as of Thursday (3/4/21) I was able to learn enough html code to create a map that displays a given location (from the code) and marks restaurants in a 5 mi radius (set in code). When the marker is left clicked it displays the restaurant name, if a new location on the map is right clicked it clears the previous markers and displays the new markers.
- However for the time being there is a small problem with the filter as Google separates fast food from non fast food resaurants and won't display everything.

**Updates**
- Now that I have changed what I want my app to do I can go more in depth on what I want to accomplish.
- ~~To begin I need to create an editable text box that allows the user to type in their location~~.
- My application will be able to automatically take in the user's location.
- ~~Then I have a line of text asking how many people are in the car and a 4 cicle choice option.~~
- ~~After that I have an adjustable text option that let's the user know how many options each person gets. (12 choices/people).~~
- The app is more focused for one person, but if it is a group of friends it'll basically have one person controlling it.
- ~~Then using Google, Yelp, or Zomato APIs, I can display the restaurants around. (They all do the same thing but I havent done enough research to see what might be easier to implement)~~
- The Yelp API was used along with a QR Code API.
- After that I need to create a ~~12~~ 8 color wheel that spins using HTML, CSS/Javascript. (https://www.youtube.com/watch?v=Gcz5RM-imJ8&ab_channel=LearnDesign)
- Then using the previous API I will display the winner of the color wheel with a picture of the restaurant, a text box with the restaurants name and address.
- I will also have ~~3~~ buttons; "Get directions" to open the user's phone map, "visit website" to open the user's browser, and "Spin Again" to spin the wheel again.
- Understanding these new components I will need to learn more HTML, and Javascript as I don't have much knowledge in these (I have a bunch of youtube videos and websites bookmarked for this). I need to research more into the APIs of Google, Yelp and Zomato to make my decision. ~~I also have touched basis on App Inventor to see if I can create the app there. Mario and I have discussed this and we think it might be possible.~~
- Added a QR Code Scanner for the online menus from restaurants during the COVID times.
- Used Thunkable for app creation 
