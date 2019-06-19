# SpookyDungeonBreak
CS447: Game Design Project

Spooky Dungeon Break 3D is a horror first-person perspective 3D game created by a team of computer science students.
The game was built in Unreal Engine ver. 4.22.1. 

NUX MODE:
To enable "Nux Mode", which renders the guards immobile, open up SDB3D in the Unreal editor,
in the content browser click on the "AI" folder, click on the "Guard" blueprint. In the Guard's event graph,
find the "Event Beginplay" red box. Delete the "PatrolToPoint" node, and replace it with the "NuxMode" node. 
Connect the "Event Beginplay" box to the "NuxMode" box, compile, and play the game.
