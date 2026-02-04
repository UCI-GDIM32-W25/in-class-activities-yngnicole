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