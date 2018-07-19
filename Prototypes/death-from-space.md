# Death From Space

+ **Development Time:** 6 Days
+ **Development Platform:** Unity
+ **Inspiration:** [Kurzgesagt - Death from Space - Gamma Rays Explained](https://www.youtube.com/watch?v=RLykC1VN7NY)

### Initial Goals
+ ***Explore Vector Graphics*** - The inspiration video features prominent and defined vector art that is very characteristic of the channel. I think this art would be really interesting to work in to an interactive environment.
+ ***Test Animations vs. (S)Lerping*** - I have had some past successes and failures with both of these methods. I want to figure out the best way and situation to use each respectively.
+ ***Tweening Methods*** - Easing engines have been a large topic of interest for me recently. My recent purchase of [DOTween Pro](http://dotween.demigiant.com/) has inspired me to put the engine to use and test out its many uses.

### Successes
+ ***Easing Method*** - I had moderate success with the DOTween engine. Learning started slow, however, I started to grasp some of the intricate functions that the engine uses and when they are useful. This will definitely be a solid tool to use in the future and I'm already thinking of ways to use it next.
+ ***SVG Tests*** - I started off the project by downloading [Inkscape](https://inkscape.org/en/) and learning the basics of vector art. Even though the art was at best sub-par, I had a great time trying out the program. However, I'll be more excited once Unity or Unreal support vector graphics natively.
+ ***S.O.L.I.D.*** - I've been concerned with project architecture after my last few projects. Of course, I haven't run into problems yet, but I can see how issues in scalability and maintainability would be an issue when the project got bigger. Applying S.O.L.I.D principles to this project helped me technically and mentally organize the project much better.

### Failures
+ ***Art Scope*** - I cut myself a bit of slack for the art in this project because I was learning a new program. This still did not keep me from spending several hours (maybe days) working on art that would either not benefit the project, or be used at all! I realized this time would have been best spent elsewhere.
+ ***Character Controller*** - I have mostly been copying/pasting huge chunks of a previous character controller into current projects. This gives me a good starting point. After I implemented the "laser" functionality for the UFO, the laser and the CC conflicted in a bad way. I neglected to fix the issue before the project was finished. It felt horrible to control, which in turn, made me feel like a horrible person.
+ ***Platform Considerations*** - I hopped into this project with no real platform goals at all. This became apparent when the project was coming to an end. There was desktop specific code right alongside the mobile-specific code. The game became a some bastardized hybrid that would never find a home.

### Lessons Learned
+ ***Easing Works*** - Easing done right can feel incredibly good. It can give that sense of feedback and motion that are natural and intuitive for players. I am feeling more comfortable implementing tweening methods into games and tweaking until things feel just right.
+ ***Plan Platform Early*** - Designing for a single or similar platforms can be helpful to weed out issues that would arise later on in the project. Even taking considerations for how the game will be played will have a huge impact on many design decisions in the future.
+ ***Controlling Character*** - One behavior that can make or break a game, for me, is the character controller. If the character doesn't move in a fluid and comfortable manner, or if the player input does not have clear and natural feedback, the game as a whole does not feel intuitive. I would like to start defining and perfecting my character controllers.
+ ***Final Thought*** - The final result does not look like much, but the lessons learned from this project were surprisingly helpful and important. I'm starting to lean towards practices which make sense to me and that I'm excited about. I want to explore these options more and compare them with alternative methods other developers use.
