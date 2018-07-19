# Heaven to Hell

+ **Development Time:** 7 Days
+ **Development Platform:** Unity

### Initial Goals
+ ***Progressive Difficulty*** - I wanted this project to have a progressive difficulty from start to finish. This would be visually described through asset changes and additional obstacles.
+ ***Simple Input*** - I only wanted the player to have to focus on one task. This action would take place through one source of input.
+ ***Low Poly Art*** - Low poly art that's done well can look really interesting and have a huge impact on the feel of a game. With very little experience in modeling, I wanted to try this style out because it feels easier than any other style (other than maybe voxel art).

### Successes
+ ***Creation Algorithm*** - The algorithm I implemented to pick and place pieces of the tube had a really good start. With a bit more experimentation and testing, the gameplay would surely follow suit.
+ ***Low Poly Modeling*** - This art style was genuinely interesting to work in. I think there are quite a few constraints with low poly modeling, which was a good thing for me. If there were not, I would have sunk even more time into modeling than I had already intended. Luckily, I got several pieces finished for the game relatively quickly.
+ ***Simplistic Input*** - Input to control the tube was very simple and set up almost immediately. This was by far the easiest part of the project.

### Failures
+ ***Modeling Time*** - I got incredibly deep into modeling during this project. A lot of time was taken from programming and design in order to produce more models. This feels like a huge failure because a lot of that art either wasn't put in or can't be seen well at all. All the while, neglected design, and programming are apparent everywhere.
+ ***Natural Difficulty*** - The game's difficulty feels like it goes from the easiest difficulty to hardest within a very short period of time. This is due to the restriction that specific models have a higher chance of spawning as the difficulty rises. With only a handful of models to choose from, the difficulty skyrockets quickly. With more time and models, this system could work nicely.
+ ***Unnatural Physics*** - This was a simple but costly mistake. I created a head model which is supposed to serve as the object which rolls down the pipe. Where I went wrong was with both the pipe creation and the head collider. I didn't realize until long down the road that the collision mesh placed on the head was a polygon collider rather than a spherical shape. This resulted in clunky physics and strange collisions.

### Lessons Learned
+ ***Constraining Progressive Games*** - It's hard to plan for edge cases and outlying issues. When it comes to progressive games, I find setting hard constraints are the best way to avoid any unforeseen problems. These games interest me so I will definitely need to research better ways to implement constraint strategies.
+ ***Art Time Hog*** - I need to start focusing on design and scripting in my games. The time it takes to get even functional art in the game costs me far too much time. I'm willing and able to obtain assets in other ways, so I should focus more on other areas.
+ ***Color Theory*** - The environments I envisioned for this game were very colorful and descriptive. Each environment would be represented by color and unique art. The end result was more in the gray palette than anything. It's hard to identify what's what in the environments. This is a huge issue when you can't even tell that deadly obstacles are in fact deadly. Many games use color to represent specific ideas in their games, and I'll certainly be keeping an eye out to identify ways that inspire me.
+ ***Final Thought*** - I had a great time working with low poly modeling, but I did not get very far on the gameplay side of things. If I'm going to make as much progress as I intend in future games, I need to drastically decrease the time spent on art and instead focus on design and gameplay. If I'm doing this whole iterative prototype project in order to become a better gameplay programmer, then gameplay programming is what I need to focus on. It would benefit myself and others to pay people for their art instead.
