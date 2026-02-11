# GDIM32 In Class Activities


## W1 Devlog

### Activity 1 

Make sure to always publish your itch link as public, so that when the graders go in to look at your work, they can actually see and play your game. I know a lot of people kept it as a private draft by action


Others by my group are to always start early on your assignments, and to always have other people constantly play testing your games

### Activity 2

1. x = 10

2. x = 2

3. For every frame, hello world will be printed to the console

4. You would use MonoBehavior

5. It prints "x = 10" into your console as soon as the code starts to run 

6. They are arguments, they are variables that are used to change your code, they let different things happen, allowing you to branch into different meathods, and just let you customize and use the code better. It lets you pass a perameter into your code. 

7. You cannot call transform of this object, as you are not specifying that you want to translate the object the script is attached to, in this instance you have to specify it. 

8. You would change transform to _playerTransform, thats it. 



### Activity 3


[MG1 Breakdown](https://docs.google.com/document/d/1FBSt1IHePMj8a95307bpUR8aoZhdvcjZGS16ntWBc2M/edit?tab=t.0)



## W2 Devlog


### Activity 1

<img width="454" height="565" alt="Screenshot 2026-01-13 at 6 08 51 PM" src="https://github.com/user-attachments/assets/5658144f-afdf-493c-8e82-91e3bd3bc83d" />

### Activity 2


[MG2 Repository proof](https://github.com/UCI-GDIM32-W25/mg2-oop-review-JNightmareC/commit/b7629814301fb467d9eafda414feeee61f70fb32)

I got a lot of progress done so far in my opinion! Today I was able to create all the game objects onto the scene along with the coin prefab, and I also added the appropriate colliders and triggers so that I can pick up easily when I continue my assignment. The other thing that I did today was creating the ability to jump for the penguin, and set up all other scripts to again, be able to start up quickly the next time my file gets opened in the upcoming days. 


## W3 Devlog

### Activity 0

Giovanni Solorio

### Activity 1

The code for this section has been finished!

### Activity 2

This code has been finished as well

### Activity 3

![IMG_6072](https://github.com/user-attachments/assets/9c61dda1-431b-4789-bff9-660726c2a400)

## W4 Devlog

### Activity 0
Giovanni Solorio

### Activity 1
When multiple locators are added to the script, it can be noticed that all scripts save for one are randomly deleted (again until there is one left). The game objects still remain, but only one script stays on one of the empty game objects. 

### Activity 2
![IMG_6134](https://github.com/user-attachments/assets/26e35a0f-a79f-416b-a611-1651677eb754)

### Activity 3
I was able to make the entire enviroment already! Along with the prefabs of each item, a ceiling so that the player can't jump out of bounds, a locator, a spawn point, and a destroy point. I was also able to code the player's jump. All scripts are ready to be coded in as well, that is what I have done. 

## W5 Devlog:

### Activity 1
I thought that the design was simple enough, and way more simplified than having to copy and paste things ov er and over, it would have overcomplicated everything. Everyhting overall looks sleek. If I were to use this while building a project (which I probably would, this helps me orgnnize everything into somehing that is easier for me, and possible other coders to read), I would seperate everything into different scripts, it was a bit confusion that everything wasn't seperated. 

### Activity 2
In the second demo, the model is represended by the scriptable object that holds a few types of data that effect everything else (specifics), the view is represented by the text that is prompted to be shown by the player (along with the inventory they have), and the controler is the classes that control both the players, and the enemies (whether that be movement).

### Activity 3
Beat system:

- each beat needs a prefab for each transform, sprite renderer, and a scriptable object for each bit of data that corrosponds to it (like keybinds, key length)
- each beat/ beat type needs a point in which it starts at, how fast it moves, and how its timed within a script that is abstract. That abstract class corrosponds to beats in general since theyre all the same type of object they're attached to, but do different things. 
- there would also be inheritance within that abstract script for methods, with a singleton it uses for events like hitting notes, and missing notes, all of this would be sending updates to other scripts like the audio and ui to change score, and noises made
- There would be a finite state machine that is atached to a timer. That timer dictates what state of wellness you are in with notes you hit. The closer to that 0 (or perfect you reach), it changes your score accordingly


Team Shooter:

Model View Controler:
    - Stats for abilities are models
    - gameplay code that carries out those abilities like causing damage is the controler
    - view is our UI for activating the ability, and all visual results of seeing things happen


Farming sim:

states relevant;
    - plants or players with mining behavior
    - growth state for plants
    - enums for diffeent types of items 

### Activity 4

Attendance: Eli Gutierrez, Jasmine Caicedo, Giovanni Solorio

[The Final proposal](https://docs.google.com/document/d/1GxlGKB6HPG_Q6x96TOvyybNU5x_lLUS-DKCN9NGH8AQ/edit?tab=t.0)



## W5 Devlog

### Activity 1


Gizmos: 

- We can on draw gizmos like an update or start so that we can draw a circle and orient it around an object
- I think my team can use a draw gizmos line attached to the fire particle of the flamethrower of our game, this will let us see what direction it is effecting in
- We want to make sure that the fire melts the ice in the right distance 
- It will show trajectory of the particles going out 
- They are not visible in the main view 
- We can make it show us where we clicked, where we last went, where objects collided, or where something could go


Breakpoints: 

- Stop a game on specific lines of codes with no conditions, or conditions if you'd like, so that you can debug things and check what they're doing
- We could use this for debugging literally anything, like to make sure specific states of our ice are meeting the correct conditions to melt, and see if the flamethrowers code is doing anything wrong


### Activity 2

Attendance: Eli Gutierrez, Jasmine Caicedo, Giovanni Solorio

