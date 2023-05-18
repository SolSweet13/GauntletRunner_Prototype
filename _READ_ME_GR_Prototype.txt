Gauntlet Runner Prototype READ ME Version 1.0
This is a work-in-progress (WIP) project and so some features may not be complete or handle all possible scenarios for end-users. However, the project should showcase the idea being presented for the game and should not crash.

This is a prototype game meant to:
1. Showcase work that I (Shaun Martin) was able to do in Unreal Engine 5 with both C++ and Blueprints
2. Create a prototype of a family fun game that allows players to compete in indirect competition (asymetrical competition)
3. Allow the game idea to be pitched in order to find help and funding for the project

What I (Shaun Martin) did not do:
1. Create the skeletal meshes and animations used during gameplay

Things I was able to accomplish (everything else):
1. A front-end menu that allows players to create LAN sessions which allow other instances of the game find and connect to in order to play
1a. The current LAN sessions are limited to allowing 3 clients to join so a total of 4 people can play
2. Allow Players to select a role to play, they can either choose an RTS or FPS player; the prototype has RTS and FPS players compete with each other
3. The game is networked, RTS Units should properly update their health, prevent players from trying to control them and play a death animation when their health reaches zero 
3a. RTS Player Characters intentionally do not die or have health
4. FPS Players will die, be destroyed and respawn after a timer

Planned improvements:
1. Allow the RTS Player to spawn RTS Units
2. Better level to play on, currently using a test map
3. Better handling of joining online (LAN) sessions (currently trying to host a session then join one will fail)

In The Future:
Future plans are to create a vertical slice of the game that has win/loss conditions and a full game mode loop.