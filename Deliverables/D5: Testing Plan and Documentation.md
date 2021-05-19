1. Creating a test plan.
- I plan to do the cognitive walkthrough and the end-to-end testing portions.
- I think the coginitive walkthough will help because it will be an outside perspective looking at my project to see how it works without me telling them what to do so they will be able to provide the most use in finding out any bugs that I might have in my app. I also believe that end-to-end testing will be great for my app because it'll allow me to see any of my own personal bugs that I know shouldn't be there and I can try to fix them as soon as possible.

2. Define Testing objectives
- By using a cognitive walkthrough, a usability test, I am able to test out how easy different people can get a random restaurant from start to finish. I also wasnt to measure the different likes and dislikes that my app has so far, especially with the UI Design.
- By doing end-to-end testing, a implementation test, I am able to test the functionality of my app's interface and behind the scenes in the code. I want to make sure that my app will be fully functional and ready for launch soon.

3. a) Cognitive Walkthroughs
- For my goal I want the user to be able to find a random restaurant based off the user's location, price range, and any search filters that they want to add. To do this I made the buttons very simple to understand with enough text on them to let them know what each button will do and the screen it will lead to.
- The easiest path to get from start to finish is to leave the color sliders alone, click on "pick a restaurant", Set your distance, set your price range, click "find a restaurant", click "spin", click "next", and then you have your restaurant. Other features include, visiting the website, rerolling, getting directions, and scanning the qr code (for menus).
- Some defining characteristics include: 16+ (depending on the legal driving age), occupation could be any, hobbies would include eating out as this app my not be suited for those who do their own cooking, but can be for the people the occasionally go out or the ones that go out alot, since I built that app in english its preferably for english speakers. But to sum it all up this app can be for anyone of any age who loves to go out to eat but is indecisive about where they want to go.
- [Karmadri - Cognitive Walkthrough Worksheet.docx](https://github.com/Berea-CS-Courses/capstone-project-Alex-Craig/files/6481229/Karmadri.-.Cognitive.Walkthrough.Worksheet.docx)
- [Alexander - Cognitive Walkthrough Worksheet.docx](https://github.com/Berea-CS-Courses/capstone-project-Alex-Craig/files/6481230/Alexander.-.Cognitive.Walkthrough.Worksheet.docx)
- [Elizabeth - Cognitive Walkthrough Worksheet.docx](https://github.com/Berea-CS-Courses/capstone-project-Alex-Craig/files/6481231/Elizabeth.-.Cognitive.Walkthrough.Worksheet.docx)
- To reflect on what I learned. I figured out that most people were able to get the random restaurant from start to finish pretty easily. The main problem lied within the design of the app as the color changes where not important and could throw people off. I actually deicded to remove that feature and settled for a nice rainbow background. Another problem that I had with my first test is that there was no home button for each screen so the user would have to basically start all the way over if they messed up. So I added a home button before my second test. I also added a QR Code Scanner button to the home screen to allow the user to jump straight to the scanner if they already got a restaurant and closed out of the app to prevent them from having to start everything over. At this time I haven't been able to get the food types function to work but I feel as if I am getting closer because I can get it to output the food type but for some reason I cannot get it to take in. I thought it worked because my last test typed in chinese and got the output of a chinese restaurant however it was purely luck that it happened.

3. b) End-to-End Testing
- Horizontal Test Steps:
- Navigate to the filters screen
 
i. The app uses the button press to change to the filters screen
- Navigate to the QR Code Screen
 
i. The app uses the button press to skip the restaurant selection and go to the QR Screen

- Navigate to Home
 
i. The code takes us back to the home screen from the filters
- Only show restaurants open now
 
i. The Yelp API takes in the value of open or closed
- Set a distance range
 
i. The Yelp API takes in the distance (m) and the code converts it to miles.
- Set a price range
 
i. The Yelp API takes in the price selection and filters restaurants only of the price
- Take in food types
 
i. The Yelp API uses the alias and categories to filter out restaurants that don’t fit.
- Navigate to Wheel screen
 
i. The code moves on to the color wheel.
- Navigate to Home 
 
i. The code moves back home from the wheel screen.
- Spin the wheel
 
i. The code sets the image to a random degree then spins for 4.5 seconds and plays a sound.
- Output the Result

i. The code gathers Yelp API info and displays it in the right color of the wheel.
- Swap Buttons
 
i. The code swaps the spin button for the next button
- Navigate to Results Screen
 
i. The code moves to the results screen with the next button press
- Navigate to Home
 
i. The code moves back home with a button press from the results screen
- Display Restaurant Information
 
i. The code takes information from the yelp API and displays it.
- Open Yelp Website
 
i. The code uses the yelp API for a URL for the restaurant
- Navigate to Wheel screen (Reroll)
 
i. The code moves back to the wheel screen
- Open Google Maps with directions
 
i. The code takes in the user's location and the restaurant's location from the yelp API and gives directions.
- Navigate to QR Code Screen
 
i. The code moves the app on to the qr code screen with the button press.
- Navigate to Home
 
i. The code goes back home from the qr code screen
- Scan QR Code / Take picture
 
i. The code opens up the phone’s camera for a picture.
- Read QR Code
 
i. The QR  Code API stores the image url and uploads it to its database to read.
- Display Website
 
i. The QR API changes the website text to a link
- Make website clickable
 
i. The code makes the QR Code link clickable and opens it up.

- I actually wanted this test to reflect how I would truly use my application. So what I did was got dressed and hopped in my car. While I was waiting in my driveway I opened up the app and wanted to look for a restaurant near me. I wanted something close and not cheap but not too expensive, so my settings where 7 miles and $$ (11-30$). Then I wanted to test each of the different features to make sure they worked. So I made sure the color wheel displays the color and the restaurant and then hides the buttonfor spin and moves onto the next screen. Then I tried to make sure the "More Info", "Get Directions", "Reroll", and the "QR Code Scanner" works. I also went through each screen to make sure the home button worked throughout the project. Finally I wanted to see if my QR Code Scanner button works  from the main menu.
- The best way that I can summarize this is that I am able to get 95% of my code to work, I am still having trouble getting my food search filter to work in the testing. I put it as a text variable for later in the code to output to work and it can display the type of restaurant is selected but it will only display one choice. Like for IHOP it actually listed it as "ComfortFood" rather than "breakfast". I wasn't sure on why it wasn't displaying a bunch of results and it left me confused.
