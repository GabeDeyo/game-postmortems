# Heliosphere
![alt text](https://lh3.googleusercontent.com/A9dELr2dRGCWCu6_HeQai88viOJDUquAtKDGAICnKdwJpG7V5gkfDOysUtQdj0_Y=w720-h310-rw "Heliosphere")

+ [Google Play Store](https://play.google.com/store/apps/details?id=com.StrixStudio.Heliosphere)
+ **Development Time:** 3 Months, 13 Days
+ **Development Platform:** Unity

**Members -**

* Gabe Deyo - Producer, Designer, Programmer
* William Brereton - Programmer
* Zack Pasterski - Artist

***

![alt text](https://lh3.googleusercontent.com/21T5G4Z3nraBWtU4_lCT73L-lXvfvA8-ukpg2X0TB9aMHZqmVXfFT6LMOTkt3QTcsvvj=s180-rw "Logo")

**Initial Goals -**
+ Implement Tweening
+ Sequenced Events
+ Mobile Environment

**Inspiration -**
+ [Kurzgesagt - The Solar System](https://www.youtube.com/watch?v=KsF_hdjWJjo)
+ [Juice it or Lose it](https://www.youtube.com/watch?v=Fy0aCDmgnxg)
+ [Vlambeer - "The art of screenshake"](https://www.youtube.com/watch?v=AJdEqssNZ-U)

***

### Successes

+ ***Sequenced Events*** - I split the initialization of the Solar System into separate unique co-routines. Each routine handles complex initialization and processing over several frames before moving onto the next routine. This ensured each level could be loaded up in a smooth manner, and helps give time to show off important details like a checkpoint flag appearing.
+ ***Tweening*** - I used a tweening engine called [DOTween](http://dotween.demigiant.com/) to provide simple yet elegant easing functions for object transformations, color/object fading, and functional lambda easing. This engine helped with the initial distribution of planets for each level.
+ ***Pooling*** - For this game, I created an easy and effective object pooler to manage the creation and distribution of the planet objects. The planet pooler instantiates objects during the initial game load, when users are expecting a loading screen. The objects are never destroyed throughout a play session, and planets are only added when a scene needs them.

![alt text](https://lh3.googleusercontent.com/mU8W1ZIDurcFYE7zlHdWyYJ-j1IOsDhlwxAzLvBgHIvqicLBcJlqxQ5VTjOSkOG-R28=w720-h310-rw "Gameplay")
***

### Failures
+ ***UI Scaling*** - My first real delve into mobile ready UX was a difficult venture. Canvas scaling and element anchoring became a critical solution for most of my issues. However, with a limited device test group, I often felt apprehensive that the UI would scale correctly on all the devices I was targeting.
+ ***Scriptable Objects*** - I watched several Unity presentations on this new feature, and I was very excited to experiment. First implementations worked on a base level, but their usefulness was quickly lost on me. As the game came closer to final stages, I dropped the more complicated features of SOs and left the base implementation in. Regardless of the failed attempt, I am still eager to fix my mistakes and try again in the next project.
+ ***Procedural Considerations*** - One design decision which was grossly overlooked was how levels change in procedural games. With two of my modes being essentially endless, there are two limitations that users are bound to hit. Too many planets, and a wide camera angle. As more and more objects are rendered on the device, the camera needs to back up to fit everything in. Eventually the camera has to zoom out so far that the scene can hardly be viewed. Also, eventually there will be too many objects in the scene for the device to handle. Both of these situations will result in difficult or impossible gameplay, so I will need to design around these hurdles in the future.

![alt text](https://lh3.googleusercontent.com/KOPjmXLWDKQNTwv76UMxbKIIPnSIFc41uk14Vckh4I7A53RGx2qq2lDfLZzN6hWpLBM=w720-h310-rw "Logo")
***

### Lessons Learned
+ ***Intuitive Input*** - When testing with new users, the first observation I needed to make was how the player interacted with the game. I realized quickly that most testers first reaction was equivalent to button mashing in a fighting game. I did not want any text describing how to play in-game, or any pause from game play to give a tutorial. Many games require this, mine does not. This was an eye opening experience that showed me how important intuitive player actions can be.
+ ***Distribute Processing*** - I started trying to think about how my game was handling numerous instantiations and complex processes. The solution for these issues was distributing large instantiations or processes into sequenced co-routines. A co-routine in the sequence would handle a subset of the entire process over several frames, then move on to the next sequence. This practice drove me to start thinking how to move data and processes around to optimize my games.
+ ***Player Feedback*** - After watching that "Game Feel" inspiration videos, I was really aiming at clear and effective feedback. Feedback for input, success, failure, and whatever else I could manage. Overall, I'm split with the end result. I would like success and failure states to feel more natural, on the other hand, input started to feel really good personally.
