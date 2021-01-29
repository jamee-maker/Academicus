# Academicus
Text-Based Adventure Game.


### 1. Running the application
Click link to go to game repo: https://github.com/jamee-maker/FSW-Text-Based-Adventure
<ul>
  <li>Clone the repo</li>
  <li>In your terminal, cd to the cloned repo and run npm install</li>
  <li>Run node textBasedAdventure.js to begin the adventure!</li>
  </ul>
  
### 2. Description of the application
<div>
<p>
This is a text-based adventure game in which a user is able to make decisions that have an impact on the storyline.
  </p>  

<img src="Assets/Intro.gif" width="700" height="400">


</div>



<div>


<p>
Throughout the game, the user has to navigate and solve problems that allow the user to advance further. 
</p>

<img src="Assets/navigate.gif" width="700" height="400">
</div>

### 3. Remarks
<div>
  
  This was the first time I had ever used javascript to create an application. With that being said, I am extremely pleased with the work.
  I spent a lot of time on the code and in particular, I wanted to give the user as many options as possible, so as to simulate actually going on an adventure     where anything could happen. One of my favorite snippets of code is in the dice roll function. In the game, there are two scenarios where the user has to guess   a number between 1 and 6:
  
   Dice roll scenario 1
   
   <img src="Assets/stationary dice .gif" width="700" height="400">
   
   In this scenario the dice is laying stationary on the ground, which means that the number the user has to guess remains constant.
   
   <img src="Assets/stat dice.png" width="700" height="400">
   
   
   Therefore the dice roll function has to be called before the while loop executes, so that the number remains the same throughout the game loop.
   
   
   Dice roll scenario 2
   
   <img src="Assets/var dice.gif" width="700" height="400">
   
   
   However in this scenario, the dice is moving constantly. That means that the number to be guessed is in fact changing through every iteration.
   
   
   <img src="Assets/var dice snap.png" width="700" height="400"> 
   
   
   Therefore here, as you can see above, we need to place our dice roll function within the while loop to reflect the change in circumstance.
   </div>
   
   
   <div>
   
   
   I really enjoyed coming up with different scenarios and solving the problems that came with them accordingly.
   Another favorite snippet of mine is a feedback survey I added to the game whenever the user reaches the gameover function:
   
   
   <img src="Assets/feedback loop.gif" width="700" height="400">
   
  
  
  I got the idea for this from my google home assistant. It periodically asks me for feedback in such a manner, and then it hit me that somebody at google probably writes the code for that.
  
  
  
  <img src="Assets/feedback pic.png" width="700" height="400">
  
  
  
  As you can see in the code above, the user is asked to rate the game from 1 to 10. If their rating is 5 or more, it will log "Thanks" and exit.
  However, if it is less than 5 it will ask them "How can we improve the game?". If their input is 5 letters or more, the user will be thanked for taking the       time to leave feedback. Otherwise it will just exit.
   
   </div>
   
   ### 4. Acknowledgements 
   
This was pretty much all me. From what I understood, the project was mostly about creating a story, so once I figured out the skeleton of my code, adding the meat to the matter was straightforward so I didnt have to use anything too fancy. I used what I learned at Pursuit 7.1 module 1. I have to say thanks to Jimmy Byess and Myra Smith for being awesome instructors! I used everthing they taught us, and they did a great job of teaching the classes.
   
   
  


