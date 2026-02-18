# GDIM32 In Class Activities
## Week 1
### Activity 1
- Making sure your itch page is actually published.
- Start your minigame earlier instead of two days before the deadline
- Make sure to finish all minigames or code because you can use previous code to help with future assignments instead of rewriting completely new code. 

### Activity 2 
- 10
- 2
- These lines of code prints the message "hello world" every frame.  
- Monobehavior
- These lines of code prints the message x = 10 upon the start of the game. 
- The 10 highlighted is an argument and the second highlighted part is a parameter. The purpose of it is to call upon the argument and pass it through the method.  
- The Translate is calling upon the class
- The Translate should call upon the _playerTransform instead. 

### Activity 3 
[MG1 Breakdown Google Doc](https://docs.google.com/document/d/1FBSt1IHePMj8a95307bpUR8aoZhdvcjZGS16ntWBc2M/edit?tab=t.0)

## Week 2
### Activity 1 
![unnamed](https://github.com/user-attachments/assets/e5bbdc17-bb7d-4f86-9cd7-e9b98ee88d38)

### Activity 2
[MG2 Repository Link](https://github.com/UCI-GDIM32-W25/mg2-yngnicole/commit/558cc7e4cc74ba566067ebc85d79c8bb6ba201e9)

I created a coin prefab, created a ground for the penguin sprite to be on, and put colliders on both the penguin and ground so that the penguin won't fall through the map. I also set up 
the outline of three scripts, PenguinPlayer, GameController, and coin with comments about what attributes and actions the GameObject needs. 

## Week 3
### Activity 0-2
Audrey Hu

### Activity 3
![unnamed](https://github.com/user-attachments/assets/231094aa-5e1d-4886-834f-5afe5133b4d3)

## Week 4
### Activity 0 
Ransom Liu 

### Activity 1 
When we added multiple Locator objects in the Scene and ran the game, only one of the Locator objects had the locator script. 
This is because in the Locator script, we wrote code to ensure that the Locator object doesn't repeat twice and that if it does, it
is destroyed. 

### Activity 2 
![unnamed](https://github.com/user-attachments/assets/901da98f-e109-4641-b886-41ba9f5b749c)

### Activity 3
I created a Unity project and uploaded the spritesheets. I also created the scripts for Seagul Player, GameController, UI, Audio, and Pipes. 
[MG4 Repository Link](https://github.com/yngnicole/HW4/commit/7db441a97d9a5d789bc79cd506c4c6f44f4419d5)

## Week 5
### Activity 1 
I think that the design is mostly efficient. If I had to write it in a different way, I would change the Use method in Item class into a non-abstract method so that the methody body
doesn't need to be repeated in the child classes. Also I would write the variable private float _durability in the Use() class and have child classes inherit it.

### Activity 2
- model
	- scriptable object: item, enemy stats
- view
	- enemy dialouge
- controller
	- player

### Activity 3
Design Patterns
Model-View-Controller with C# events
Inheritance with polymorphism
Basic parent class, abstract class, and/or interface
Finite State Machine with C# enums
Singleton
ScriptableObjects

Scenario 1:
- model
- view
- controller
- inheritance
- finite state machine with c# enums
- singleton
- scriptableobjects 
	- starting timing
	- sprites
	- prefab


Scenario 2:
- Model: 
	- data about abilities
	- data about gun (recoil, spray..)
- View: 
	- The gun skins, gun buddies, knife skins, gun animations, 
	- animations, character animations, sound, game ui point text
- Controller: 
	- points earned by players(money for gun)
	- killing enemies
	- planting spike
	- actions
- Inheritance with polymorphism (basic parent class, abstract class, interface)
	- abstract player class: died, movement, using abilities, shooting 
	- interface: pickup gun, pickup spike
- finite state machine with c# enums 
	- animation: walk, run, crouch, shoot, using abilities
- singleton 
	- GameController
	- Player
- scriptableObjects 
	- weapons
	- health
	- knife

Scenario 3: 
- finite state machine enums
	- mining behavior
	- plant grow states, seed, sapling, tree 
	- actions that player is in

### Activity 4
Attendance: Evelina Wang, Ziying Huang, Nicole Yang

[Proposal](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?tab=t.0)

## Week 6
### Activity 1 
- The merge conflict tool is going to help with the final project so that if multiple people write code in the same line, it won't break the game. We can see 
what code overlaps and change or delete whatever is not needed.
- The profiler tool can help figure out what method is taking longer to execute and causing frame drops. For our final project, it can ensure that the game runs smoothly. 
- The gizmos tool can help visualize the direction a gameobject is faciing towards when it collides with an object. It can help in our final project to figure out when the player is in the line of sight of the scary object to trigger an animation.
- Breakpoints can be used in our final project to figure out specifically what code is not working and where. 


### Activity 2 
Attendance: Evelina Wang, Ziying Huang, Nicole Yang

[Final Draft](https://docs.google.com/document/d/10HReV1LS2bKpFumSkCfVwM0uvrhOadVoLUmLjYf7iTk/edit?tab=t.0)

## Week 7
### Activity 1
We learn that raycasting is useful to check is a gameobject is aggroed due to the line of site to the player. Once the player is in the line of site of the gameObject, then that gameObject will start chasing
it. We learn that NPC state machine is useful to check if an NPC is in what states. Such as if the duck is in wandering or aggroed state. State machine is useful because it makes sure that the duck can only
be in one state at a time. 

### Activity 2 
Attendance: Evelina Wang, Ziying Huang, Nicole Yang

### Activity 3