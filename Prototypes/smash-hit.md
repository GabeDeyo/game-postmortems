# Smash Hit

+ **Development Time:** 6 Days
+ **Development Platform:** Unity
+ **Inspiration: [Space Frontier](https://play.google.com/store/apps/details?id=com.ketchapp.spacefrontier)

### Initial Goals
+ ***Animation/Spline Path*** - I wanted to have a baseball swing based on both input timing and location. I wanted to create a custom animation or spline path after or during user input. The bat would begin at the start of the user input location and then the swing through following the path of their input.
+ ***3D Model Coherence*** - For consistency sake, I wanted all the models to look similar and be unified in scale. I was hoping this would help the next goal, Physics Responses, where all objects would collide appropriately.
+ ***Upgrade System*** - My main goal was to have an upgrade system where players could earn currency by playing ball, the spend that currency upgrading the pitcher, the batter, the balls, the stadium, etc. I think it would be fun if the game started simple and got more insane as the player progressed.

### Successes
+ ***Trajectory Input*** - The batter has a similar trajectory system to Angry Birds slingshot system. This worked pretty well, considering the difficult mathematics involved. If there was more time to work on UI, I think this system would have looked really great.
+ ***Camera Rig*** - I've been working on a camera system that has been working well. This system can smoothly follow objects and keep them within an appropriate view. It responds accurately when it's told to look at new objects or look away from others.

### Failures
+ ***Custom Animation Values*** - After multiple failed attempts, I had to move on from custom animations and spline paths. The final result is simply a static animation that plays on input. It doesn't feel good and doesn't result in appropriate physics responses.
+ ***Input Feedback*** - With a lack of gameplay in the final result, I am starting to feel as though this game would need some short tutorial which typically bugs me with such simple systems.
+ ***Design Mistake*** - From the start, the systems in this game did not feel or look good. I had always considered a mobile design for this game, yet I designed for a wide desktop design because the systems couldn't work on mobile. I should have realized this sooner and made changes to either the design or the platform consideration.

### Lessons Learned
+ ***Time Management*** - This project ultimately came down to poor planning and poor time management. I spent several days trying to get around three systems complete. Most of the time, the system was complete in several hours, but I spent the majority of my time tweaking and playing around. Lots of productive time was lost this way.
+ ***Intuitive Feedback System*** - I need to start thinking and researching how to make simple systems, like the ones in this game, easy and fun to interact with. I like Vlambeers techniques, but I can't seem to put them into use just yet. I like minimal in-game UI and zero immersion hits, so this is going to be an interesting challenge for me.
+ ***Iterate and Remove Early*** - I dug myself into several holes during this game. I started designing systems around limitations that I thought were set but failed to change them when most features didn't match up. I know I could have gotten farther along if I hadn't put on blinders. It's hard to iterate and remove early in a prototype, but there were some glaring issues with the initial design that could have easily been removed.
+ ***Final Thought*** - I don't know if it was a really off week, or if planning as a whole went sour. Almost no system worked how I wanted it to, and I struggled to get things finished or even working well enough to move on. I am starting to pick out some of my biggest design flaws and I would like to consider these first for my next few projects.
