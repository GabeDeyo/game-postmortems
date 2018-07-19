# Poop Chute

+ **Development Time:** 7 Days
+ **Development Platform:** Unity
+ **Inspiration:** [Beeple - Florence](https://www.facebook.com/beeple/posts/10154735418391781?comment_tracking=%7B%22tn%22%3A%22O%22%7D)

### Initial Goals
+ ***Procedural Gameplay*** - I wanted this game to be able to play multiple or endless "levels" within one scene. Where gameplay can continue forever or until the player fails.
+ ***Mobile Input*** - I have been recently experimenting with game ideas that would work well with and I wanted to be able to utilize mobile input for several various situations in this project.
+ ***Lighting*** - I'm a huge fan of volumetric lighting in 3D environments and I wanted to implement some sort of variation of that lighting technique in this game.

### Successes
+ ***Triggers/Collisions*** - I had no problems in this project setting up triggers and collisions for any objects in the scene that needed it. I was then able to easily and quickly apply scripting to make these events work the way I wanted them to.
+ ***Mobile Input*** - Luckily for me, Unity provides a very nice Input API that is simple and powerful to work with. With a little testing and expirimentation, I was able to get various mobile input methods working on my phone very quickly.
+ ***Object Pooling*** - This was my first time working with a more advanced scripting technique like object pooling. After a couple tutorials, I had a great custom system working for the various tubes that were spawned in the levels.

### Failures
+ ***Volume Lighting*** - I struggled to find an effective way to create great looking volumetric fog or lighting. I eventually took it out and replaced with the closest thing. I'll keep looking into it, however, as it's one of my favorite graphical treats.
+ ***Camera Rig*** - The rig and camera I used for this project had two major downsides. 1) They could'nt follow the object I wanted them to with the strictness I neede them to. 2) The perspective and distance were completely off. This made my original vision very different from the finished product. This definitly has something to do with the next point.
+ ***Scale*** - Almost all object scales and their distances form one another, alongside the camera perspective, created gameplay that was vastly different from my intented goals. I will need to do a bit of research into composing scenes correctly.

### Lessons Learned
+ ***Scale Matters*** - Things started off well in this game. Once the scale started to become off, the game started to spiral. I need to figure out more effective ways to create better perspective and unified scales. This goes for UI as well.
+ ***Thinking About Memory*** - When I started thinking about how many objects were going to be spawned in and out of the game during levels, I needed to think about the best way to do this without throttling the users device. This is were object pooling came in and I was very happy that I got to learn and utilize them.
+ ***Thinking About Coroutines*** - Along with memory, I started to realize, I can't simple spawn hundreds of objects at once or perform complex proccesses in just one frame. I planned out sequences where coroutines would handle smaller subsets of these large instantiations or processes. This mindset has got me thinking how else coroutines could be successfully implemented.
+ ***Final Thought*** - This game was a huge eye opener for me in the realms of memory usage and optimizing scripts. The game did not turn out even close to my initial vision because of scaling and perspective issues, however, more imporant lessons were learned that will be greatly considered for future projects.
