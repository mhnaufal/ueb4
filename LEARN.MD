# Learning Notes

## Fundamental

1. Unreal consists of **Actor** and actor has **Component**
2. **Pawn:** a physical class that can be controlled by player or AI. Pawn is
   not connected to **Controller** by default, need to connect it manually
   through Blueprint. 
3. **Character:** a pawn that can _walk around_. Can handle input event. To be
   use as the "main object" that the player controls.
4. **Controller:** is an actor that can _control/possess_ a pawn in order to
   manage the pawn's action. https://docs.unrealengine.com/4.27/en-US/InteractiveExperiences/Framework/Controller/PlayerController/
5. **Player Controller:** handles the player input. Also act as the primary
   point for networking multiplayer. In multiplayer, each player can only
   control their corresponding Player Controller, and must be responsible to
   the server.
6. **Game Mode:** how the game should behave (3rd/1st person, spesific game
   behaviour, etc). Only one Game Mode allowed in each level, and Game Mode
   only exists on game server.
7. **Game State:** state of the current game. Unlike Game Mode, we can have
   multiple Game State inside the game.

