# cc-m9-let-it-snowglobe
Computational Creativity Assignment M9. A Casual Creator that simulates a snow globe that can be shaken and suspended. The user can draw on a canvas with glittering snowflakes following their mouse that fall as if they were in a snow globe. 

## How to Run
1. Bring `creator.pjs` into a IDE like https://openprocessing.org/
2. Press play
3. Hold the mouse down to draw snowflakes
4. Press the 's' key to stop the snowflakes from falling, press any other key to start snowflakes falling again
5. Press the space key to shake the snow globe, press any other key to stop the shaking
7. When you want to save your work, press 's' to stop the motion and take a screenshot

## Brainstorming
(1) What are your users casually creating?
My users are casually creating an art piece inspired by the flow of a snow globe. They can draw a design and then watch it slowly fall to the bottom of the screen. 

(2) How do you keep them engaged and excited to create?
I keep them engaged with the calming sparkling of the snowflakes and their movement. The designs made are erased by the fall of the snowflakes, so
the user is encouraged to redesign their work. They can also shake the snowglobe and watch their design transform as the snowflakes are mixed around. 

(3) How do you help them make something they are proud to share?
I give the option to suspend the fall of the snowflakes so that the user can concentrate on making something beautiful without worrying about their
work drifting away. Once they have created something they like, they can screenshot their work. Or, the user could un-suspend the snow globe so their design falls, and 
capture the movement of their falling design. There is another possibility to design while the snowflakes are falling to create a dynamic, flowing piece and then suspend 
the snow globe to capture the moment. With all of these possibilities, let-it-snowglobe offers many different ways for the user to create something that they are
proud to share. 

## Personal Meaning 
I have always enjoyed snowglobes and found myself mesmerized by the falling glitter. Last winter, I made one myself and spent way too much time flipping it back and forth to watch the snowflakes fall. I wanted to re-create this peaceful fascination with my casual creator (1) because we could all use some relaxation during finals period and 
(2) a snow globe fits the current season and mood. I am also learning in one of my other classes how relaxing scenes of nature can be for our minds. So, I felt that recreating something
that resembles nature would be a soothing art experience. I don't believe that creating art should be stressful, so the pretty glitter as well as the option to shake the snowglobe and start 
over again offer the user an easy and stress-free way to make something beautiful. 

## Challenge 
I pushed myself out of my comfort zone by including options for the user to stop the fall of snowflakes and shake the snowglobe. I had to figure out where these variables would need to be passed in order to actually start and stop the movement of the snowflakes. At first, I thought that making a global variable would work, but ended up deciding that it was necessary to keep track of each individual snowflake. I then had to figure out how the user could shake or suspend. Through looking examples of processing, I was able to figure out that I could use the keyboard to interact with the program. This was an important challenge for me because it taught me how to look through documentation and examples for a language that I was completely unfamiliar with. Going forward, I could have implemented a feature where your drawing impacts the surrounding snowflakes and makes them move.


### Credit
I learned how to interact with the program using the keyboard from this example: https://editor.p5js.org/ehagan/sketches/dlcBuy7NC
