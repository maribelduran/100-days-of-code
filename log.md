# 100 Days Of Code - Log

### Day 1: January 3rd, 2017

**Today's Progress**:  Styled twitch streamer statuses. Created a new meta div using vanilla js.

**Thoughts:** Today was my first day doing the 100 Days of Code challenge and didn't realize that working on FCC algorithms did not count as time coding. So I pushed myself to work on my Twitch Streamers App. I am currently working on styling the Twitch users' statuses and streaming information. It is taking me a little longer to complete because I am doing this using vanilla js. 

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)




### Day 2: January 4, 2017 

**Today's Progress**: Created a separate codepen to work on creating an overlay on single pens. Will be integrating the overlay to my Twitch Streamers App when completed.

**Thoughts**: I created single pens where I could work on creating overlays. The overlays will have a description of what the Twitch streamer is currently streaming. Still have work to do on getting the correct height for the thumbnails inside the pens, but the overlay is working properly. 

**Link(s) to work on codepen**: [Single Pens With Overlays](https://codepen.io/maribelduran/pen/qREZmw)




### Day 3: January 5, 2017 

**Today's Progress**: Attempted to make single pens responsive.

**Thoughts**: Attempted to make the single pens responsive. However, adding flex display, is not allowing the width % to update as I want it to. Will look more into what display flex actually does.

**Link to github:** [single-pens-with-overlay](https://github.com/maribelduran/single-pens-with-overlay)

**Link(s) to work on codepen**: [Single Pens With Overlays](https://codepen.io/maribelduran/pen/qREZmw)




### Day 4: January 6, 2017 

**Today's Progress**: Added wrapping to the flex container and made pens more mobile responsive.

**Thoughts**: Added wrapping to the flex container. This fixed the issue I was having yesterday where the width % was not changing on different media widths. Single pens are now more mobile responsive.

**Link to github:** [single-pens-with-overlay](https://github.com/maribelduran/single-pens-with-overlay)

**Link(s) to work on codepen**: [Single Pens With Overlays](https://codepen.io/maribelduran/pen/qREZmw)


### Day 5: January 7, 2017 

**Today's Progress**: Experimented with different media queries for tablet and phone. Made pens more mobile responsive.

**Thoughts**: Was able to get my two new media queries to work on desktop. However, when I checked the app on my mobile device, the pens widths were not changing. I then realized that I had not yet included the <meta> viewport inside the head element. The issue was resolved after declaring the meta viewport onto my page.

**Link to github:** [single-pens-with-overlay](https://github.com/maribelduran/single-pens-with-overlay)

**Link(s) to work on codepen**: [Single Pens With Overlays](https://codepen.io/maribelduran/pen/qREZmw)



### Day 6: January 8, 2017 

**Today's Progress**: Worked on styling Single-Pens-With-Overlay project.

**Thoughts**: Added an anchor tag to each single_channel item. Removed the need of cover-link class. Styled elements in single_channel-header.

**Link to github:** [single-pens-with-overlay](https://github.com/maribelduran/single-pens-with-overlay)

**Link(s) to work on codepen**: [Single Pens With Overlays](https://codepen.io/maribelduran/pen/qREZmw)



### Day 7: January 9, 2017 

**Today's Progress**:  Moved back to my Twitch Streamers app and continued styling.

**Thoughts**: Continued styling my Twitch Streamers app. However, I worked on this through codepen and didn't get a chance to copy my changes over to my local folder (thus not commiting to github). This is why I should start getting used to my code editor and try to move away from codepen. Additionally, I was able to attend my first meetup of the year @ HackReactor where we had a JS Study Group session on JS algorithms. Overall, a very code-productive day! 

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)


### Day 8: January 10, 2017 

**Today's Progress**: Merged single-pen-overlay project to Twitch Streamers App. Each single_channel item now contains an overlay that informs what is streaming.

**Thoughts**: My Twitch Streamers app is almost complete. Almost slacked today because I went to a Warriors Game, but managed to do an hour of coding. 

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 9: January 11, 2017 

**Today's Progress**: Removed view.filterUsers from my Twitch Streamers App. Instead filtered users inside the button eventListeners before passing the users array to view.displayUsers().


**Thoughts**: Figured a way to remove a method and was able to use the filter method to display users.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)


### Day 10: January 12, 2017 

**Today's Progress**: Continued styling Twitch Streamers app. Added bottom border color to the cover-overlays based on the user being online (green) or offline (red).


**Thoughts**: I love styling this application, but will give it a break so I can start working on a new project.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 11: January 13, 2017 

**Today's Progress**: Continued Twitch Streamers App. Added a sortUsers() function  that orders users by alphabetical order. Moved nav buttons to header.

**Thoughts**: Before sorting the users in alphabetical order, the single_channel list was displaying randomly whenever the app was refreshed. Also moved the buttons outside the purple well so that users can distinguish the buttons between the single_channels pens.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 12: January 14, 2017 

**Today's Progress**: Continued Twitch Streamers App. Moved the channel preview image into a div. This removed the unecessary border whenever a channel does not have a preview image.


**Thoughts**: Through this issue/fix, I found out that an img element will always have a border and very difficult to get rid of. So instead of having an img with empty src string, I created a div that holds the image that way I can control the border styling whenever a twitch user does not have a preview image.


**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 13: January 15, 2017 

**Today's Progress**: First time I did not get a chance to code for an hour :(


**Thoughts**: Spent the day traveling back home after our Tahoe vacation. Will make up for it soon.


### Day 14: January 16, 2017 

**Today's Progress**: Worked on styling nav buttons based on the user's current status.

**Thoughts**: The border color of the buttons change fine in Chrome. However, they are not showing up properly on mobile. I started moving this week and it's been hard to put more than one hour of coding.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 15: January 17, 2017 

**Today's Progress**: Still struggling with getting button:focus border color to work on mobile, Firefox, and Safari.

**Thoughts**: I feel like I need more than one hour to figure this issue. Moving and cleaning the new house has been rough, but still managing to stare at code for an hour.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)




### Day 16: January 18, 2017 

**Today's Progress**: Reviewed Twitch Streamer's app code. Optimized functions in my view class.

**Thoughts**: I am happy with how my code is looking. Need to continue refactoring the displayUsers method. 

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)




### Day 17: January 19, 2017 

**Today's Progress**: Fixed button's active color styling through javascript instead of css. Added a footer. Also made up for my hour missed on Day 13.

**Thoughts**: Was having difficulties figuring out how to style the buttons active state through css so I ended up doing it through javascript.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 18: January 20, 2017 

**Today's Progress**: Made project code more readable. Moved button color style updates from setupEventListeners method into a new updateActiveButton method in the view object.

**Thoughts**: Realized I could make my project more readable by adding new view methods. This allows someone to see what all happens when a button is clicked.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)



### Day 19: January 21, 2017 

**Today's Progress**: Continued making project code more readable. Divdided displayUsers methods into more view methods that create html elements. Finished updating javascript code and was able to share it with twitter friends!

**Thoughts**: Originally the view object had a displayUsers method that looped through each user and created the necessary html elements and classes for each user. However, I realized the method was sloppy and repetatitve. So I decided to divide the tasks into smallers view methods. I created a view.createAnchor, view.createPreviewImg, view.createOverlay, and view.createInfoDiv method that allows someone to see what exactly is being performed within the view.displayUsers method.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/bgexzL)




### Day 20: January 22, 2017 

**Today's Progress**: Fixed issue where footer was not showing properly on mobile or large desktop devices. Also fixed issue where footer was showing in the middle of the page because the rest of the page was still loading.

**Thoughts**: Footer was not showing on mobile device because I had footer's parent div min width of 100%. Removed this css declaration and this resolved the issue. Then I noticed that the footer was not staying at the bottom of desktop devices so I increased the footer's parent div padding-bottom from 150px to 200px. Finally, realized that the footer was loading first and sometimes briefly showing in the middle of the page because the rest of the footer's parent div data was still loading. So i create a showFooter method that will run after the container (footer's parent div) data has loaded onto the page.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)




### Day 21: January 23, 2017 

**Today's Progress**: Did not get to code. Moving and being call for 8 days straight finally caught up to me :/ Will make up for the hour soon! 

**Thoughts**: I will be making up for this hour soon :) No worries :)



### Day 22: January 24, 2017 

**Today's Progress**: Started a new project! Building a Javascript Calculator for FCC. Began implementing the model layer.

**Thoughts**: Today was the first project that I started locally without having to use codepen! I started implementing my model layer which I created a controller object for. I am so excited to continue this project!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 23: January 25, 2017 

**Today's Progress**: Was able to run my code locally! Continued on model layer and started view layer.

**Thoughts**: Did not have wifi on the airplane, but realized I could run my code locally! I created index.html and set up all the necessary buttons. Today felt like a really successful day! 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 24: January 26, 2017 

**Today's Progress**: Did not get to code today! Wok up really early and was on to the go exploring Vancouver's nature. Will make up for it soon! Currently two hours that I need to make up,

**Thoughts**: Would have been a good idea to wake up early, but didn't get to Vancouver until 3am and had to wake up at 9am. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 25: January 27, 2017 

**Today's Progress**: Created event listeners for buttons 1-9 and started the controller layer.

**Thoughts**: Setup my controller object to call calculator methods and view methods. Started wondering whether the controller should be the place to validate user input. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 26: January 28, 2017 

**Today's Progress**: Had trouble implementing input validations for some buttons. Hoping tomorrow will be a more productive day. 

**Thoughts**: Updated a few calculator methods Not sure if I will be keeping the methods this way, but it is a start.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 27: January 29, 2017 

**Today's Progress**: Decided to implement input validations in the model layer. Worked on adding functionality for  0-9 button inputs.

**Thoughts**: Currently buttons 0-9 are able to create numbers. Will begin implementing functionality for operator buttons.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 28: January 30, 2017 

**Today's Progress**: Continued Javascript Calculator: Added functionality to my addition button. However, this broke functionality for buttons 0-9. 

**Thoughts**: Will continue working on addition button only to make sure the rest of the operators can use the same function.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 29: January 31, 2017 

**Today's Progress**: Updated functionality for buttons C (ClearEntry) and AC (AllClear). Continued working on addition button functionality.

**Thoughts**: Having some trouble on how to effectively check when the currentEntry is empty. I think I am going to keep the currentEntry as "0" when no entries have been entered. This means that the calculator will not be able to add "0". Check other calculators and it looks like adding "0" is not necessary.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 30: February 1, 2017 

**Today's Progress**:  Calculator now accepts inputs for decimal, and operators (+,-,/, x). Input values becomes buggy when I use clear button and then try to add more values to the current math operation.

**Thoughts**: Currently working on validating input values for all my buttons in the updateCurrentEntry method, but will eventually split the values into different methods. The code is also very repetitive, but will make it more readable once I get to correctly generat the current operation string. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 31: February 2, 2017 

**Today's Progress**:  Fixed clearEntry method to only remove current entry from the current operation string.

**Thoughts**: Before, every time the Clear (C) button was pressed, it would remove an entry from the current operator string so eventually you could clear the whole string. Now, it will only remove the current entry. Have alot of bugs to fix, but have noted and will work on each of them more tomorrow.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)




### Day 32: February 3, 2017 

**Today's Progress**: Fixed bug that wasn't allowing me to switch operators. Before when the current active entry was an operator value, the code would not allow to switch to a different operator.

**Thoughts**: Fixed the 🐜 that wasn't letting my calculator switch operator after one was selected. A few more 🐜 to go. Was super busy today, but managed to keep up with the coding before the vacation trip crazyness starts tomorrow.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 33: February 4, 2017 

**Today's Progress**: Still working on fixing value entries for JS Calculator.Can't wait to actually start calculating the math operations:) 

**Thoughts**: Coded for about 2 hours tonight during my flight to Hawaii! It's going to be tough to an hour in everyday during my week here, but will do my best to not fall behind!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)




### Day 34: February 5, 2017 

**Today's Progress**: JS Calculator App does not allow digit or decimal inputs after an operator was just cleared. 

**Thoughts**: This was a big bug to fix and was able to do this by adding a justClearedOperator flag. Will be adding a similar flag to able to tell when a number entry has just been cleared.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 35: February 6, 2017 

**Today's Progress**: Calculator now accepts an operator entry after an operator was just cleared. Keep running into logical errors.

**Thoughts**: I keep running into small logical errors with input values. But really want to be able to verify that input values are free of errors, before computing the math operations.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)




### Day 36: February 7, 2017 

**Today's Progress**: Didn't get to code:( Woke up @ 4am to catch the Haleakala Sunrise and was out all day. Will make up for it soon! 

**Thoughts**: I really tried to get an hour in, but I really needed this day to be able to destress and enjoy every minute of my vacation. I know that I will be able to make up for this hour on the flight back home this weekend. 




### Day 37: February 8, 2017 

**Today's Progress**: Continued working on Calculator JS App. Things fixed were nothing too exciting. 

**Thoughts**: Still running into issues with having current Entry be set to "0" when we clear an entry. But hoping to figure a better way to show that a value was just cleared. Maybe I can try setting another flag or use the two flags justClearedOperation and justClearedNumber.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 38: February 9, 2017 

**Today's Progress**: JS Calculator App does not allow operator inputs after an number entry has just been cleared.

**Thoughts**: This was really easy to fix after adding the justClearedNumber flag. Now I just have two small bugs to fix that deal with not being able to add "0" after an entry has just been cleared. Also cannot clear a "0" entry."

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 39: February 10, 2017 

**Today's Progress**: Can correctly chain math operations together. Will finally be able to work on the equals button functionality.

**Thoughts**: Fixed the last few input validations. Can clear a "0" entry and add "0" after a number entry has just been cleared. I think I am going to run into a few more inputs that I will have to validate, but will be moving on to adding functionality to the equals button.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 40: February 11, 2017 

**Today's Progress**: Was traveling all day and was only to make up for yesterday's hour. Will make up for this hour soon!

**Thoughts**: I am really proud of myself for trying my best in not getting behind with the 100 Days Of Code Challenge while on vacation. I will be putting alot of effort into the rest of my front end dev projects in the next two months as well as my personal portfolio!



### Day 41: February 12, 2017 

**Today's Progress**: Continued working on JS Calculator. Equals button is somewhat functional.

**Thoughts** Equals button knows whether operator expresion is valid. Started investigating whether I should create my own functions to add, multiply, subtract, divide, or if I should use built in eval() function.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 42: February 13, 2017 

**Today's Progress**: JS Calculator equals button is now functional! Steered away from using eval() and isntead used th math.js library.

**Thoughts** Read that eval() is slow and should not be used to calculate expressions. I decided to go with a library that already calculates string expressions to save some time, but to also get comfortable with using other libraries. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 43: February 14, 2017 

**Today's Progress**: Completed functionality for JS Calculator equals button. 

**Thoughts** My equals button is fully functional. I had to add justCalculated variable to help with more input validations that i have to check for operators, decimals, and numbers.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 44: February 15, 2017 

**Today's Progress**: Updated input validation checks for operator, number, and decimal entries. 

**Thoughts** Input validation is almost complete. Only thing to fix is vaildating decimal entries. Wish I had some time to set up some until testing. Really hoping to learn this in Watch and Code so I can come back and test my apps. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 45: February 16, 2017 

**Today's Progress**: Made up for lost hours from Day 36 and 40! Continued working on JS Calculator App model layer.

**Thoughts** Stayed in on Thursday night and made up for the lost hours that I missed last week. I was so tired and with no energy, but I just kept coding. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 46: February 17, 2017 

**Today's Progress**: Continued working on model view for JS Calculator App. Trying to update how to update currentOperation string value.

**Thoughts** Keep seeing slight logical errors for inputs. Trying to remove previousEntry array that is no longer needed.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 47: February 18, 2017 

**Today's Progress**: Removed previousEntry variable from calculator object in JS Calculator App. No longer needed.

**Thoughts** Removed previousEntry array which was used to generate the currentOperation string. This helped clean up the code.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 48: February 19, 2017 

**Today's Progress**: Started refactoring code! Current code is a bit sloppy.

**Thoughts** My calculator is now fully functional. Want to clean up code before I start designing the calculator. Code can be alot more shorter. Could potentially use Jquery to help with this.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 49: February 20, 2017 

**Today's Progress**: Continued refactoring calculator.updatEntry method for JS Calculator App.

**Thoughts**: updateEntry is not fully functional as well as more readable.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 50: February 21, 2017 

**Today's Progress**: Refactored view.addEventListers method for JS Calculator App.

**Thoughts**: Created an button object that contains button id as key and its entry input as the value. This allowed me to loop through each button and create event listeners for each. 


### Day 51: February 22, 2017 

**Today's Progress**: Started styling Calculator App! Feels good to use Bootstrap again after not using a framework on my last two projects 

**Thoughts**: Created row divs to organize buttons. Also started playing around with the boostrap columns. Forgot how they work since its been a while that I've used them. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 52: February 23, 2017 

**Today's Progress**: Continued messing with boostrap rows and columns. So tired today.

**Thoughts**: Played around a bit styling with boostrap, but didn't get too far.Spent my free time running to SF to attend a Prototypal Inheritance JS lecture :)

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 53: February 24, 2017 

**Today's Progress**: Continued styling JS Calculator App. Decided to not use boostrap because I don't need the rows to be responsive.

**Thoughts**: Realized that I didn't need boostrap for this project because the button rows are not going to collapse for any device width. Used some of my css code from Twitch Streamers to align the buttons properly.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 54: February 25, 2017 

**Today's Progress**: Created a good css layout. All I have to do is size my buttons, and choose out some nice colors.

**Thoughts**: Happy to see that my calculator app design is starting to look the way I want it. Hoping to get pretty far with this tomorrow during the FCC meetup.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 55: February 26, 2017 

**Today's Progress**: Attended an FCC Meetup and coded away on a beautiful Sunday afternoon. Met some pretty cool FCC campers and continued styling app! 

**Thoughts**: This morning I woke up and drove to Oakland for an FCC Meetup. Had to stand outside in the cold becuase the coffee shop was a bit full. Nonetheless, it was an amazing experience. There was a pregnant lady learning how to code and then had a guy who owned a startup. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 56: February 27, 2017 

**Today's Progress**: Found some cools icons for my C and AC buttons. CSS can be pretty addicting 

**Thoughts**: Downloaded icons into my images folder. Calculator is looking very clean!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 57: February 28, 2017 

**Today's Progress**: Added a ripple click effect on buttons. Decided I want to change the colors I originally chose.

**Thoughts**: Downloaded a ripple effect from github. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 58: March 1, 2017 

**Today's Progress**: Published my JS Calc App to Github pages! First time completing  a project without CodePen.

**Thoughts**: This is another great advancement for me. Starting to develop like a real developer!

**Link to github:** [Javascript Caculator](https://maribelduran.github.io/javascript-calculator/)




### Day 59: March 2, 2017 

**Today's Progress**: Added media queries to make Calc App mobile responsive.  

**Thoughts**: Added width change for landscape orientation for mobile devices. This might be a minor change, but want my apps to be user friendly.          

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 60: March 3, 2017 

**Today's Progress**: Added new % button and worked on its functionality.

**Thoughts**: Really wanted to get the percent functionality into this project. It was a little more tedious than the other operators, but was able to come up with a fair use case.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 61: March 4, 2017 

**Today's Progress**: Didn't get a chance to work on my Calc App. Spent my Saturday afternoon at Rithm's School JavaScript: The Tricky Parts Meetup.

**Thoughts**: Got home after spending 6 hours at Rithm's School The Tricky Parts Meetup. Then I got home and cleaned up everything in the house so that I could come back from Ohio with no more things to do around the house. Overall still a very productive programming day. We learned about closures, the heap, const,callstack, assign(), scope, destructoring. I haven't dived into ES2016 yet, but a great introduction.



### Day 62: March 5, 2017 

**Today's Progress**: Worked on creating a digit limit. Display screen is currently overflowing in my Calc App.

**Thoughts**: Wanted a way to limit the amount of digits a user can enter. I started experimenting on how many digits could be inputted before overflow occured on the entry screen.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 63: March 6, 2017

**Today's Progress**: Stuck on creating a digit limit. Code started breaking many places due to this.

**Thoughts**: I was having a hard time deciding where I was supposed to check the number of digit values. I kept going back in forth between the view and controller object. Ended up leavig it in the view layer.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 64: March 7, 2017

**Today's Progress**: Chose to display a max of 11 characters. Display value will have a precision of 9 decimal places.

**Thoughts**: Chose to display a max of 11 characters. This was the largest number of characters before the entry screen started overflowing. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 65: March 8, 2017

**Today's Progress**:  Fixed overflow on large screen display, but not working on mobile. Fixed by keeping the well div one size.

**Thoughts**: Previously, I was decreasing the width of the well by 20px on mobile resolutions. So the overflow was happening before the 11 digits. Once I removed the width resize, the overflow was gone.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 66: March 9, 2017

**Today's Progress**: Worked all night and then traveled all day to get to Ohio. Will make up for the hour soon!

**Thoughts**: This was one of the busiest days of the year so far! After having worked until 5:30AM, I went straight to the airport and had two connecting flights to Ohio. By the time I got home, it was 6pm! I was so tired!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 67: March 10, 2017

**Today's Progress**: Tried to fix overflow of operation string. Got stuck so working on adding footer.

**Thoughts**: Tried to find the max number of characters before the Operation value started overflowing from its div. Realized that characters takes up different amout of space. Worked on adding a footer instead.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 68: March 11, 2017

**Today's Progress**: Again stuck on operation string. Was in West Viriginia visiting Kevin, so I only worked on this for about 10 minutes.

**Thoughts**: Commited to git and pushed to github. Tested that my work looked good on mobile phone.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)



### Day 69: March 12, 2017

**Today's Progress**: Figured out to overcome overflow in the operation screen. FLOAT RIGHT worked! 

**Thoughts**: Updated the operation string and entry screen values to be span instead of heading elements. This allowed me to increase the size of the font size without it changing it's div size. I looked a Google's calculator to find the clue that I could use FLOAT RIGHT to accomplish what I've been looking for!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 70: March 13, 2017

**Today's Progress**: Cleaned up code and manually performed more tests on mobile phone. Finally complete woo!!
**Thoughts**: I was trying to add a jquery shake effect to my entry screen, but figured i'd put this project to rest for now. I am so happy on both the UI and functionality of the calculator. The code can definitely use a good clean up, but hopefully with more experience I can come back and make it more readable and maintainable. Time to Celebrate!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/javascript-calculator)


### Day 71: March 14, 2017

**Today's Progress**: Started the Pomodoro Timer App Project!
**Thoughts**: Started looking into what the functionality of the pomodoro app and the use cases that I will be using. Created both a Trello project and Pinterest board to set/get ideas.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 72: March 15, 2017

**Today's Progress**: Worked on the model layer of my Pomodoro Timer App.
**Thoughts**: Now that i have a better idea of what the functionality for this app, I created a timer object that contains the basic data needed. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 73: March 16, 2017

**Today's Progress**:Continued working on the model layer for my Pomodoro Timer App. Learning about the setInterval function 

**Thoughts**: Started figuring out how the setInterval function works. Looks like I will need to keep a record of the returne ID in order to stop the function.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 74: March 17, 2017

**Today's Progress**: Moved setInterval function from my model layer to the controller layer.

**Thoughts**: Realized that setInterval should be called by the controller so that it could control when to stop the timer. The model should only keep the ID for the returned setInterval value. This helped me realize the power of the controller and to try to keep consistency between my projects.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 75: March 18, 2017

**Today's Progress**: Continued working on the controller for my Pomodoro Timer. Learned a bit about JS prototype and attended an FCC Meetup.

**Thoughts**: Attended an FCC Meetup to code along other FCC members. I continued testing my controller.startTimer and controller.stopTimer which call setInterval() and clearInterval(), respectively. Learned more about JS prototypes because I realized that I needed to different Timers, but both having similar data types. That's when I realized I needed to use a constructor and add methods through the object's prototype. This was a huge discovery for me! Everything that I have been learning is starting to come together and make more sense :)

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 76: March 19, 2017

**Today's Progress**: Continued working on controller for Pomodoro Timer. Having some difficulties figuring out where to create new Break and Session timers.

**Thoughts**: Had to decide if I wanted to create the new Break and Session timer objects after the button Start has been pressed or as soon as the application started. I decided to create both timers as soon as the application started and modify any changes the users made to the timer's properties.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 77: March 20, 2017

**Today's Progress**: Worked on buttons that allow customizing session and break length.

**Thoughts**: Created buttons that would decrease and or increase both the Session and Break lengths. This will be a moved to a popup menu when the Settings button is clicked. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 78: March 21, 2017

**Today's Progress**: Struggling on how to design my Pomodoro Timer App, but continued adding ideas to the Pinterest board. 

**Thoughts**: Continued working a bit on the functionailty because I got stuck on the design aspect of the project.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 79: March 22, 2017

**Today's Progress**: Still struggling on the design aspect of my  Pomodoro Timer App :/ Again, scrolled through my Pinterest board to try to get enlightened. I think I need some inspiration. 

**Thoughts**: Hopefully going on vacation to a new place will help :)

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 80: March 23, 2017

**Today's Progress**: Added a counter for sessions completed on my Pomodoro App.

**Thoughts**: Wanted a way for the user to see how many Sessions were completed even though that wasn't part of the use case. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 81: March 24, 2017

**Today's Progress**: Fixed counter for sessions completd and reset button functionality.

**Thoughts**: Counter for sessions completed was not updating properly, but fixed by consoling out the actual element. Fixed reset button functionality to set the counter for sessions completed back to 0.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 82: March 25, 2017

**Today's Progress**: Made code more readable. And learned more about prototypal inheritance because I realized I could be using prototypes 

**Thoughts**: Still having a little road block on the design aspect of the project, but I figured to could clean up my code.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 83: March 26, 2017

**Today's Progress**: Did not get to code. Got sick! :(

**Thoughts**: Hoping to make up for this over the weekend!


### Day 84: March 27, 2017

**Today's Progress**: Did not get to code. Got sick! :(

**Thoughts**: Hoping to make up for this over the weekend!

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 85: March 28, 2017

**Today's Progress**: Styling Pomodoro App. Created necessary bootstrap rows, columns, and divs. Going for a minimalist look

**Thoughts**: This was a big breakthrough for me. I think I was thinking about the project way too hard. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 86: March 29, 2017

**Today's Progress**: Removed constructor methods and added the methods to the object's prototype instead! 

**Thoughts**: Attended an Meetup at Rithm School where we used prototype and I remembered I had to move my methods to the object's prototype. 

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 87: March 30, 2017

**Today's Progress**: Continued styling Pomodoro App. Added a settings button to show and hide the Break and Sessions Length buttons. 

**Thoughts**: Create two equal columns of col-xs-6. Then created a row within each of the two col-xs-6's and added 4 columns of size col-xs-3. This gave me a total of 8 columns needed for Boostrap's 12 column layout.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)



### Day 88: March 31, 2017

**Today's Progress**: Continued styling Pomodoro App. Added a settings button to show and hide the Break and Sessions Length buttons

**Thoughts**: Want to have the Break and Sessions length options pop up on a menu instead of having it within the nav element.

**Link to github:** [Javascript Caculator](https://github.com/maribelduran/pomodoro-timer)


### Day 89: April 1, 2017

**Today's Progress**: Did not get to code.

**Thoughts**:  Will make up for this soon.


### Day 89: April 2, 2017

**Today's Progress**: Added font awesome icons to Settings and Reset button and tested boostrap column layouts.

**Thoughts**: Took me some time to remember how to embed the font awesome icons. Looked through previous projects and realized I am going to use the same layout as the Weather App in completed a while back.


### Day 90: April 3, 2017

**Today's Progress**: Updated color schema. Brainstormed a way to show the settings options.

**Thoughts**: Found a good example of creating a popup menu to allow changing settings. 




