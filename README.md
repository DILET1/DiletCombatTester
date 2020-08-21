# DiletCombatTester
A Combat tester for the mechanics of a game I'm working on. Uses Java and processing 3.5.3. 
Controls: Dilet is WASD and Z to attack, Telid is IJKL and M to attack. Two hits to die!
Graphics: Made with Piskel. 

//Current To-Dos
Animations for Telid have not been implemented yet, but Dilet is done. The reason there 
is a white square is so the player knows where their character is, and so there are no 
remnants of old animations.

Arenas do not have hitboxes yet.

Need to create some sort of inventory system, map, and AI Enemies for a story campaign. 
And especially the actual play area. Thinking about a class, MapTile with variables 
(PImage, access code for north exit, south, west, east, then object ID's.) Then with
a function to load the map using the access code, generate items, enemies, etc.
Edit 8/21/20 Finally packaged it in a .jar file. Back to working on content after figuring that absolute disaster out :)
