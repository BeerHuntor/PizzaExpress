Pizza Express! 

A game developed in unity.  This is the first game of I hope many that I am developing in the Unity Game Engine with C#. 

You play as a pizza shop worker, who has to feed the hungry horde before they get to the counter and break it down - 
still in early development, but planned features include: 

* Full Shop Upgrade System
* Quirky boost system.  - Introduced in V0.3
* Highscores

Play a very early version at: V0.2 https://connect.unity.com/p/pizza-express-1


Changelog:
v0.5 - 
* Game will now be restarted completley when restarted from the game over screen. - v0.4.1

---BUG FIXES---
* Fixed a bug which allowed the player to press the pause keys and subtract days from the game over screen - v0.4.1
* Fixed a bug which allowed the player to pick up another delivery with no pizza when double slices delivery was activated - v0.4.1
* Fixed a bug causing the player to not be able to restart the game from the game over screen. - v0.4.1
* Fixed a bug where the fed customers collide with the hungry customers and hit them causing the game to sometimes become unfinishable --- again! - v0.4.1

v0.4 - 
 * Added pause menu ui and an options menu from the main menu screen 
 * Added menu and game music -- Im sorry! 
 * Removed menu button animations and made them change colour. 
 * Added sound queues' for delivery crates and for fed customers
 * Added voice over sounds to accompany the new delivery icons. 
 * Added independant audio sliders for music and sfx - Still a little janky.
 * Re-added particle system to show when you have fed a customer. 
    
-- Gameplay Changes --
* Reduced starting money from 100 to 50 - Which was the original intended amount. 

---BUG FIXES---
* Fixed a bug where one of the delivery icons was not de activating
* Fixed a bug where the above delivery was not being called and activated. 


v0.3 -
 * Added a pause feature where the game stops when you press the ESC or P keys.
 * Added a delivery system into the game, where you collect the deliveries and they can boost you or give you a negative effect. 
 * Implemented a money system - Pizzas when cooked cost money, earn money from feeding the customers.  New delivery system complements this feature.
 * Designed And Added new UI icons to represent the counter health, and the customers remaining and money earned.
 * Pizza slices now despawn after going out of the game view.  And also when they hit the ground. 
 * Reworked main menu and game over screens -- Added Day Count as game over stat. 
 * Added a tutorial 'how to play screen' 
 * Added particle system to show when you have fed a customer. 
 * Retextured the pizza models to give them a more uniform look. 

 ---BUG FIXES---
 * Fixed a bug where the counter health was not calculating correctly causing the game to end prematurely. 
 * Fixed a bug that allowed the player to despawn the pizza they were holding, and have infinate pizza slices
 * Fixed a bug that when happy customers spawn they collide with the hungry customers and bad things happen -- Not 100% Fixed - Can sometimes still happen.
 

v0.2 -
 * Added pizza slice equivelant models and made them spawn whenever you fire. 
 * Fixed the bug where the hungrycustomers jump over one another when they collide. 
 * Removed old primitive models that were used to prototype. 

v0.1 - 
 * First Version

KNOWN ISSUES:  
~~Counter health sometimes gets multiple collisions from one customer causing the counter to lose health rapidly and the game to end -- Ends game on 2 lives~~ - FIXED V0.3
After you have hit another object in the game, when you stop the movement of the player,  you glitch out and constantly rotate and move. 
When pressing Resume from the pause menu, it wont actually allow you to move - Get around this by using ESC and P keys. 
