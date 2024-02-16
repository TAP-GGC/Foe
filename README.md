# Foes - Teaching JavaScript Fundamentals Through a MultiPlayer Fighting Game
## Description
* Difficulty Level: Intermediate
* Target Audience: High School - College
* Duration of Workshop: 45 min - 1 hr
* Needed Materials: Computer, Internet Access
* The goal of this project is to educate others about JavaScript basics while building a HTML/CSS webpage.
* Foes is a web-hosted project. This project is curated to peak the interest of non-IT and beginning IT majors.
By participating in the workshop, student will get to experiment with JavaScript, HTML, and CSS code to immediately view their changes on their browser.
* The Technology Ambassador Program ([TAP](https://www.ggc.edu/academics/school-of-science-and-technology/research-internships-service-learning/technology-ambassador-program)) at GGC strives to break the misconceptions of the IT field by providing fun workshops for students of all backgrounds. TAP students design engaging and fun outreach workshops to encourage interest in IT and STEM.

## Team
* Alex Shaklee
* Alec Burns
## Advisors
* Dr. Wei Jin
* Dr. Xu Xin <br><br>
### Team Photo
<img src= "Media/createSymposium2.jpg" width="400" height="300"> <br>
(Left: Alec Burns, Right: Alex Shaklee) <br>

## Publications
1. Alex Shaklee, Alec Burns, Wei Jin, Xin Xu. Foes - Teaching JavaScript Fundamentals Through a MultiPlayer Fighting Game, CREATE Symposium, April 25, 2023, Georgia Gwinnett College.
2. Alex Shaklee, Alec Burns, Wei Jin, Xin Xu. Foes: Sparking Programming Interest in Non-IT students Through a JavaScript Fighting Game. Extended Abstract and Poster Presentation, SIGITE 2023, October 2023, Kennesaw State University.

## Outreach Activities
1. Atlanta Science Festival, March 18, GGC - To promote IT field and the TAP program to college students and faculty
2. TAP EXPO, March 21, GGC - To promote IT field and the TAP program to college students and faculty
3. Atlanta Science Festival, March 25, Piedmont Park - To promote/introduce IT as a interest to K-12 children 
4. STARS, April 13, GGC - Presentation meant to peak interest in TAP and IT through the evaluation of survey results
5. Class Workshops - 

## Similar Projects
## Technology
This project and the following workshop uses HTML, CSS and JavaScript.

## Project Setup/Installation
### Description
Taking inspiration from the game ROUNDS on Steam, we set out to make a fighting game that creates a state of tug of war. While each layer starts off with equal power, each time a player loses a round they are offered a powerup. These powerups are randomly generated and stack with each other, meaning that winning too frequently often results in losing, which in turn powers up the former winner. The first player to win 5 rounds wins the game.
### Play Game
1. Click the following link: [aburns10.AlterVista.org](https://aburns10.altervista.org/)
2. Click the "Please Click Here To Play Foes" link displayed on the page, which will take you to the main page where the game is being hosted.
3. To play, grab a friend and pick either Player 1 or Player 2.
4. Click the 'Start Game' button and use the designated keys for each player to play the game, until the end of the level is reached.
5. When the end of the level is reached the game will pause and a message at the bottom of the game screen will be displayed allowing the "loser" of the current level to pick a powerup for the next round.
6. After a power up is picked the game will continue. Keep playing and repeating step 5 until the end game screen is displayed.
7. Once the game is over click the 'Reset Game' button at the top of the screen to play again or close the browser to quit.

## Short Demo Videos
[Foes - Demo Video Workshop 1](https://youtu.be/crpZIvLSENI) <br>
[Foes - Demo Video Game](https://youtu.be/qYuCzIq-tyI) <br>
[Foes - Demo Video CodePen](https://youtu.be/MgPB31GBtHE)

## Workshop Access 
### Workshop 1 - CodePen
1. Click the following link to be taken to the first page of the Workshop on Code Pen: [CodePen.Workshop1](https://codepen.io/Alreeshid/pen/xxyGwWp)
2. You should be taken to a webpage that is seperated in four sections/mini-screens (if on computer). During this workshop refrain from hitting the refresh button as it will cause all your changes to disappear as CodePen requires an account to save any changes made during a session.
3. The three screens at the top of the page represent the different coding languages. For this workshop HTML, CSS, and JS should be displayed. 
4. Any and all changes on the programming (HTML/CSS/JS) screens will change what will be displayed on the bottom half of your screen entitled: "Something Something Clever Page Title". Before we begin let's format our pages. On the HTML screen there will be an down arrow in the upper right corner next to a gear. Click the down arrow and press "Format HTML", this will ensure that your code is easier to read for our workshop. Repeat this step for the CSS "Format CSS" and JS "Format JavaScript" mini screens. 
5. The first part of the workshop will be to change the title of the webpage from "Something Something Clever Page Title" to your name. 
6. To change the title navigate to the HTML coding screen and find line 12 of your code, it should have id="<strong>header</strong>" included.
7. Carefully highlight and delete the words "Something Something Clever Page Title" and replace it with your name (ie "Alec Burns"). When you are done do not refresh the page, but wait for CodePen to review your changes.
8. Once the changes are reviewed CodePen will generate your changes and you should see them appear on the bottom half of your screen.
9. Congratulations! You have now titled your very own webpage. The next step of our workshop is to change the color of our page.
10. To do that go to the mini-screen entitled CSS and at line 1 you should see the words <strong>body</strong> with an opening curly brace ({) next to it. This curly brace lets CSS know that you are starting a block of code. To find where that block ends you can place your cursor after the y of the word body (line 1), and a small little line will appear under the opening curly brace (line 1) and closing curly brace (}) (line 6). 
11. All of the code between lines 1-6 changes the background of your webpage, but right now we only want to change the background color.
12. To change the background color find where it says <strong>background-color:</strong> on the CSS screen, highlight the words "limegreen", delete it, and change the name to a color you like. If you know any Hexi-Decimal colors feel free to use then but if not stick to colors such as red, blue, green, black, orange, yellow, pink, purple, coral, rosequartz and brown as other colors may result in just an all white background.
13. When you are done do not refresh the page, but wait for CodePen to review your changes. Once the changes are reviewed CodePen will generate your changes and you should see the background of your page change.
14. Next let's check out some of the functionality on our webpage already. 
15. At the bottom of the screen there should be a box under your title called "Change The Below Text". When you click that button you should see some hidden text. The box you just clicked is known as a button and to add the functionality that allows us to see the change in text we just saw, JavaScript is used. In the JS mini screen scroll until you see the function called <strong>bodyText</strong>. This is what controlled the change you saw on our webpage.
16. To code your own working button with JavaScript we are going to start by adding a function in the JS mini screen at the far right corner of your screen.
17. Under the function bodyText (place cursor at end curly braces and hit enter) type:  <strong>function bodyText2(){}</strong>. Place your cursor in between the two curly braces and press enter. This is where you will place your changes. 
18. In your new function type: <strong>text.innerHTML = "";</strong>. In between, the quotation marks type in whatever sentence or phrase you want to appear when your function is called. Ex: text.innerHTML = "Welcome to the Foe's Workshop!";
19. Right now there is no functionality, but to add some go to your HTML mini screen and find line 14. This section of code deals with the creation of the buttons for our webpage. To create our own, copy line 15 and paste it on line 16, and when our page refreshes two buttons named "Change The Below Text" will now appear.
20. To make the second button work we need to implement our new function we just created, so that way when the user clicks our second button we won't see the "Bababooey." message, but instead our custom one. Change the second onclick by setting it equal to "bodyText2", so that the inside of your new button looks similar to this: "button onclick="bodyText2()"".
21. Next change the name of your button to anything you want such as "My Welcome Message". Wait for CodePen to run your changes and then click the new button you created. If done correctly you should now see your new message in the same place "Bababooey." appeared.
22. For the final change in Workshop 1 we are going to change the background of our webpage to something more dynamic. Just like we did before go to the JS mini screen and scroll till you find the variables rainBG, cityScape, and snowyCity. These are the various backgrounds we can use to change the background of our program.
23. Under the last variable snowyCity lets add a new function on line 19. Type: <strong>function changeBG(){}</strong>. Place your cursor in between the two curly braces and press enter. This is where you will place your changes.
24. In your new function type: <strong>body.style.backgroundImage = rainBG;</strong>. 
25. Right now there is no functionality, but to add some go to your HTML mini screen and find line 17. We will add our new button to change the background of our page here. Just like before copy line 15 and paste it on line 17, and when our page refreshes we will now see three buttons "Change The Below Text", "My Welcome Message", and "Change The Below Text".
26. On line 17 change the value of onclick to equal the changeBG function we just created.  The inside of your new button should now look similar to this: "button onclick="changeBG()"". Next change the name of your button to anything you want such as "Change Webpage Background". Wait for CodePen to run your changes and then click te new button you created. If done correctly you should now see the background of your webpage turn purple and have some rain falling across the page.
27. To the program a little interesting lets by change the frog picture to one from the internet.
28. Open your web browser to a new tab and search for a random picture such as a man walking, a cat, a dog, or a bow. Click on the photo of your choosing, right-click and select "Copy image link" or "Copy image address". Navigate back to CodePen and find the html tag <strong>img</strong> and find <strong>src</strong>. Src stands for source which HTML is trying to find the source of an image.
29. Highlight and remove the link that already exists and replace it with the copy of the link/address of the photo we really want. Wait for CodePen to load your changes and scroll to see your new picture has replaced the frog one. Play around with the other backgrounds under the JS mini screen by changing the value of <strong>body.style.backgroundImage</strong> to be any of the other backgrounds or try creating new functions and buttons that will allow a user to switch between any of the backgrounds on the webpage. To do this follow instructions 22-26.
30. Happy Coding!


### Workshop 2 - CodePen
1. To access part 2 of the workshop either click the following link to be taken to the second page of the Workshop on Code Pen: [CodePen.Workshop2](https://codepen.io/Alreeshid/pen/wvYaKjw), or click on the bottom link of your webpage for Workshop 1 where it says "Click Here For Exercise 2".
2. The new webpage on CodePen should take you to a site almost identical to Workshop 1. There should be three coding screens (HTML, CSS, JS) and a webpage on the bottom with the title "Exercise 2".
3. Here we will be working more with JavaScript to make objects animate in the three canvas's on our webpage on the bottom (scroll to view all black/gray canvas boxes).
4. During this workshop refrain from hitting the refresh button as it will cause all your changes to disappear as CodePen requires an account to save any changes made during a session. Before we begin let's format our pages. On the HTML screen there will be an down arrow in the upper right corner next to a gear. Click the down arrow and press "Format HTML", this will ensure that your code is easier to read for our workshop. Repeat this step for the CSS "Format CSS" and JS "Format JavaScript" mini screens.
5. For the first part of our workshop we will focus on animation 1. Right now when we click the "Run animation 1" button a red box appears but the red box has no movement. To fix this we want to go to the JS mini screen and scroll until we see the function <strong>runAnimationFrames</strong> (line 85). This function will be where we change the majority of our code to add functionality.
6. Under the first if statement (line 86) we will change <strong>box1X += 0.0;</strong> to <strong>box1X += 2.0;</strong>. By changing the value to 2, we are letting JS know that everytime this method is called for the first animation we are going to change the x position of the boxes' coordinate system by 2, thus allowing the box to move across the screen. Ex: (0, 0) -> (2, 0) -> (4, 0), etc
7. Let CodePen save and approve our changes and click the "Run animation 1" button again. What happened to the box? Instead of the box moving across the screen it just grows wider and wider. To change that go back to your JS mini screen and remove the two slashes on line 89 to uncomment our code. Let CodePen save and approve our changes and click the "Run animation 1" button again. Now what happened to the box? It moved! This is because the clearRect method is constantly erasing our canvas after we re-draw our box giving it the appearance that it's moving accross the screen. So everytime we see the box again it's in a new position.
8. Now lets move on to the second part of our workshop - animation 2. Under the JS mini screen scoll down to lines 103/104 and replace 1000 with canvas2.width then click the "Run animation 2" button on your webpage and watch as a red box quickly moves across the page just like our first program. But now we want to make sure our box does not go off our canvas. Under the function <strong>runAnimationFrames</strong> (line 85) we want to change the code under the second if statement (line 95).
9. Inside the second if statement (line 95) there should be a smaller one at line 103. Right now our code wants the box to stop when the box2X coordinates becomes greater than or equal to canvas2.width, but the problem we run into is that the box is still appearing off the screen.
10. So in the parentheses of the if statement (line 103) after the canvas2.width add <strong>-boxWidth</strong>, this will fix our problem of the box running of the screen. Let CodePen save and approve our changes and click the "Run animation 2" button again. Now what happened to the box? It stopped right before it ran off the screen but why? When we created our box in the canvas we didn't create it at the coordinates (0, 0) but instead at (20, 10), and we initalized the height and width of the box to be 100. So these are things we have to consider that when we make animations. Also, remember that when we run an animation the x coordinate in the upper left corner is the one that matters the most to JS, so by the time our box2X equaled to canvas2.width the rest of our box was already off the page.
11. Last let's allow the user to change th boxes location using our keyboard. In the JS mini screen scroll to line 23 and uncomment out that chunk of code by removing the slash and star characters; do the same on line 38 so that our code will run with no errors.
12. Once your code is fully commented out try pressing the keys: W, A, S, and D. What do each of the keys do to the box? The code we uncommented in our code allows JavaScript to "listen" to what keys a user presses on the keyboard and based on that input we will either add or subtract 5 from the box3X and box3Y values.
13. Try changing the amount we subtract. Now, try changing the amount we add.
14. Lastly for lines 25, 28, 31, and 34. Try changing the keyCode numbers by using this website: [KeyCodes.com](https://www.exeideas.com/2014/05/javascript-char-codes-key-codes.html) to chnge what keys you can use to move the box.
15. Happy coding!
