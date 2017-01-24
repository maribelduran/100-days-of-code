# 100 Days Of Code - Log

### Day 1: January 3rd, 2017

**Today's Progress**:  Styled twitch streamer statuses. Created a new meta div using vanilla js.

**Thoughts:** Today was my first day doing the 100 Days of Code challenge and didn't realize that working on FCC algorithms did not count as time coding. So I pushed myself to work on my Twitch Streamers App. I am currently working on styling the Twitch users' statuses and streaming information. It is taking me a little longer to complete because I am doing this using vanilla js. 


**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)





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

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)


### Day 8: January 10, 2017 

**Today's Progress**: Merged single-pen-overlay project to Twitch Streamers App. Each single_channel item now contains an overlay that informs what is streaming.

**Thoughts**: My Twitch Streamers app is almost complete. Almost slacked today because I went to a Warriors Game, but managed to do an hour of coding. 

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)



### Day 9: January 11, 2017 

**Today's Progress**: Removed view.filterUsers from my Twitch Streamers App. Instead filtered users inside the button eventListeners before passing the users array to view.displayUsers().


**Thoughts**: Figured a way to remove a method and was able to use the filter method to display users.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)


### Day 10: January 12, 2017 

**Today's Progress**: Continued styling Twitch Streamers app. Added bottom border color to the cover-overlays based on the user being online (green) or offline (red).


**Thoughts**: I love styling this application, but will give it a break so I can start working on a new project.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)



### Day 11: January 13, 2017 

**Today's Progress**: Continued Twitch Streamers App. Added a sortUsers() function  that orders users by alphabetical order. Moved nav buttons to header.


**Thoughts**: Before sorting the users in alphabetical order, the single_channel list was displaying randomly whenever the app was refreshed. Also moved the buttons outside the purple well so that users can distinguish the buttons between the single_channels pens.

**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)


### Day 12: January 14, 2017 

**Today's Progress**: Continued Twitch Streamers App. Moved the channel preview image into a div. This removed the unecessary border whenever a channel does not have a preview image.


**Thoughts**: Through this issue/fix, I found out that an img element will always have a border and very difficult to get rid of. So instead of having an img with empty src string, I created a div that holds the image that way I can control the border styling whenever a twitch user does not have a preview image.


**Link to github:** [Twitch Streamers](https://github.com/maribelduran/twitch_streamers)

**Link to codepen:** [Twitch Streamers App](https://codepen.io/maribelduran/full/LbvpOK/)



### Day 13: January 15, 2017 

**Today's Progress**: First time I did not get a chance to code for an hour :(


**Thoughts**: Spent the day traveling back home after our Tahoe vacation. Will make up for it soon.


### Day 14: January 16, 2017 

**Today's Progress**: Worked on styling nav buttons based on the user's current status.

**Thoughts**: The border color of the buttons change fine in Chrome. However, they are not showing up properly on mobile. I started moving this week and it's been hard to put more than one hour of coding.



### Day 15: January 17, 2017 

**Today's Progress**: Still struggling with getting button:focus border color to work on mobile, Firefox, and Safari.

**Thoughts**: I feel like I need more than one hour to figure this issue. Moving and cleaning the new house has been rough, but still managing to stare at code for an hour.


### Day 16: January 18, 2017 

**Today's Progress**: Reviewed Twitch Streamer's app code. Optimized functions in my view class.

**Thoughts**: I am happy with how my code is looking. Need to continue refactoring the displayUsers method. 


### Day 17: January 19, 2017 

**Today's Progress**: Fixed button's active color styling through javascript instead of css. Added a footer. Also made up for my hour missed on Day 13.

**Thoughts**: Was having difficulties figuring out how to style the buttons active state through css so I ended up doing it through javascript.


### Day 18: January 20, 2017 

**Today's Progress**: Made project code more readable. Moved button color style updates from setupEventListeners method into a new updateActiveButton method in the view object.

**Thoughts**: Realized I could make my project more readable by adding new view methods. This allows someone to see what all happens when a button is clicked.


### Day 19: January 21, 2017 

**Today's Progress**: Continued making project code more readable. Divdided displayUsers methods into more view methods that create html elements. Finished updating javascript code and was able to share it with twitter friends!

**Thoughts**: Originally the view object had a displayUsers method that looped through each user and created the necessary html elements and classes for each user. However, I realized the method was sloppy and repetatitve. So I decided to divide the tasks into smallers view methods. I created a view.createAnchor, view.createPreviewImg, view.createOverlay, and view.createInfoDiv method that allows someone to see what exactly is being performed within the view.displayUsers method.



### Day 20: January 22, 2017 

**Today's Progress**: Fixed issue where footer was not showing on mobile or large desktop devices. Also fixed issue where footer was showing in the middle of the page because the rest of the page was still loading.

**Thoughts**: Footer was not showing on mobile device because I had footer's parent div min width of 100%. Removed this css declaration and this resolved the issue. Then I noticed that the footer was not staying at the bottom of desktop devices so I increased the footer's parent div padding-bottom from 150px to 200px. Finally, realized that the footer was loading first and sometimes briefly showing in the middle of the page because the rest of the footer's parent div data was still loading. So i create a showFooter method that will run after the container (footer's parent div) data has loaded onto the page.



















