# Frackalackin

+ **Development Time:** 6 Days
+ **Development Platform:** Unity
+ **Inspiration:** [Kurzgesagt - Fracking explained: opportunity or danger](https://www.youtube.com/watch?v=Uti2niW2BRA)

### Initial Goals
+ ***Flat UI Style*** - Due to the inspiration for the prototype, I wanted to emulate the same style that the creators at Kurzgesagt use. Based on their creation methods and tools, I've decided to again use the open-source software Inkscape.
+ ***Tweening*** - My last project Heliosphere was quite successful when tweening was implemented to "spice" up the gameplay. I would like to practice with and explore the tweening engine DOTween.
+ ***Algorithmic Terrain Generation*** - I want to create an algorithm that will randomly create the terrain based on the economy of the drilling location. The location will have a certain amount of resources and a threshold for pollution that results in the driller being evicted if crossed. Each location will have unique economy resource levels that would determine the drilling gameplay.

### Successes
+ ***Base Gameplay*** - Due to familiarity with the Unity Engine and C#, many base parts of this prototype came together extremely fast. I had a working game by the end of day two. If I was able to maintain focus for the later half of development, the base gameplay could have expanded into something fun.
+ ***Cohesive Art Style*** - The art process was uniquely quick and easy for this project. Much of it was inspired from the video, and the end result looks much better than most project I've worked on.

### Failures
+ ***Drill Controller*** - The base foundation for creating the drill came together incredibly quickly, but I never got past that. Once I moved on to the terrain and economy side of things, the main gameplay was neglected. The final state of the drill was no more than functional. The drill gameplay would need to be the key gameplay ingredient if this project was to continue.
+ ***Static Level Design*** - Due to time constraints, I fell into a design trap. I wanted to get gameplay going and make sure input felt right before moving on to the randomized terrain design. In order to do this, I started setting up a static level that I could test gameplay in. I spent far too much time setting up this level when it would have almost zero influence on the actual terrain algorithm.
+ ***Economy vs. Gameplay*** - My terrain design shrunk horizontally through development. At first, the player could explore in almost any direction he/she wanted to. The result was a controller that felt slow and encumbered within the camera view. I decided to limit the scope of movement and shrink the terrain. This felt more like a Downwell type game which completely destroyed the tie in with the location economy. It's important not to end a run when they've simply collected all available resources. Two important core functions of my game did not work together.

### Lessons Learned
+ ***Stay the Course*** - I'm finally starting to feel very comfortable within the engine, and I can confidentely work on almost any task without a strenuous detour into Tutorial Town. This makes many base gameplay elements very easy to implement and I can usually start to see some interesting effects within several hours. However, I need to flesh out these elements to become more than familiar and repetetive cliches. Much of this project was spent wandering from easy thing to another easy thing. The games I want to make have interesting and challenging features which I would like to focus on for future projects.
+ ***Randomness*** - When a core feature of the game is based on a randomized algorithm, precious hours should not be spent meticulously placing objects into a static level playground. I need to start identifying when my current task is not useful, or at least not placed on a productive path.

+ ***Final Thought*** - I'm very happy with how this game started. I can only hope that future projects come together as well as this one did. However, there needs to be more momentum that can carry this effective development style onto more creative and polished sections of the game. The biggest hurdle will be mitigating risks that could potentially halt any productive development. Identifying these risks will certainly help the train keep on rolling towards it's ideal destination.
