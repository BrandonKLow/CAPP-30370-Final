Web Design Final Project
===================
Brandon Low's Website
---------------------
### Website Purpose
The purpose of this website is to provide a website for the bass section of the Notre Dame marching band catered more to incoming freshmen. There is some description about marching band and the bass section on the home page. This will inform incoming freshman what it would be like to be part of the bass section in the marching band. On the members page, there are pictures of all the current members of 2013-2014 marching band season. The songs page contains all the lyrics to the songs the basses sing on game dame and the incoming freshmen are required to memorize all of the songs. Freshmen in the past had a hard time finding the lyrics, so this website will make it easier for them to find the songs they need to memorize. I had many questions when considering joining the band, so I hope this website could be implemented for incoming freshmen that had similar questions. 

### Include at least two breakpoints*
There are break points for the he tablet (700px) and desktop (1000px) sizes. In the members page there is visibly change where the images change from 4 columns to 2 rows when going from desktop to tablet size. Using the flex box commands (display: flex and flex-wrap:wrap), I displayed the images of the members at 50% in the tablet view to have two columns. In the desktop view I reduced the widths to 25% to create 4 columns for the images of the members. In the mobile size the member images are in one long column. Additionally, in the table and desktop size the navigation links are in a row at a width of 32%. The navigation section is listed in a column when the screen is at the mobile size.

### Include at least one page with a three-up or more column layout when viewed at desktop size*
The members page contains images of all the members in the bass section. The images are in 4 columns in the desktop view. See above for same explanation about implementation using flex box commands.

### Include one CSS animation that runs on a continuous loop*
On the bottom of the songs page there is a image of the leprechaun with the tuba rotating in the y axis continuously. I used the keyframes with the transform: rotateY command to implement this action. At 0% (the beginning) the image is at 0 degrees on the page, then at 50% the image is rotated 90 degrees, and lastly at 100% the image is at 180 degrees. With the animation command  (-webkit-animation:) I had the action take 2 seconds that runs infinitely in an alternating fashion.


### Include one CSS animation that runs on user interaction*
When the user hovers their mouse over the image of the leprechaun with the tuba on the home screen the image spins. I used the keyframes with the transform: rotate command to implement this action. Then using the #lep1:hover (lep1 id of image)and animation (-webkit-animation:) commands I had the image spin 360 degrees in span of 5 seconds when the user hovers their mouse over the image. 

###One background image*
I wanted to have a light and older style background, so I got the old_wall.png as my background image. Using the  background-image:url() command, I used an image I downloaded online (old_wall.png) as my background and I repeated that image across the screen with the  background-repeat:repeat command.

###jQuery interaction*
I created a button and used the fadeToggle() command to hide/show the Bass Group Picture on the Members page. This will be helpful if the user just wants to see the pictures of the members.



