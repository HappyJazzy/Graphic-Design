
### About the Game

This game was developed as part of a bachelor level course. While models, textures, sound effects and music were sourced online, I animated the bee's wings using Blender, sculpted the terrain, and colored the 3D models.

### Gameplay

The objective is to deliver a specific number of lollipops to a cookie. The required amount is randomly determined each game, directly influencing the length of the "day-night" cycle. Lollipops are worth 1 to 3 points, but higher-scoring lollipops are heavier, which will slow your bee down.



### Challenges and Strategy

A persistent wasp will constantly chase your bee (using a `look.at` function to follow it). If it catches you, you'll drop the lollipop you're carrying. To evade the wasp, you can collect donuts scattered across the terrain, which provide a stackable 3 second speed boost. Or you can fly into the "chocolate syrup" river, which will slow the wasp down but your speed is unaffected.

### Game Cycle

The game's duration is tied to a unique day-night cycle, controlled by a dynamic skybox and a timer. This timer adjusts based on the number of lollipops you need to collect, making the environment gradually shift from lighter to darker as the cycle progresses.

