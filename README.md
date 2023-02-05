# iDroidBuild
The Build With Assets And Scripts For My Project

The purpose of this simulation/game was to showcase my skills as a software developer. This was made within a process of 4 days using the Unity Engine mixed with C# scripts and therefore published onto both GameJolt and Simmer.io.

CONTROLS
- Place: Allows you to place drone on grid. Hints are in the placeholders of what to add in the fields in order to place the drone. If incorrect, it throws out an error.
- Move: Moves drone forward 1 unit in the direction it is facing. Does NOT proceed pass boundary.
- Rotate Left and Right: Rotates the drone 90 degrees either to the left or to the right.
- Report: Shows the location of the drone.
- Attack: Fires a bomb 2 units in front of the drone but does NOT fire while near facing the edge of the grid.

• How would you select which automation tool is best suited for a project?
> I chose Unity as it was the Game Engine I was the most familiar with.
• How will you go about automating the Movement of the drone?
> Using if statement and onclick button functions and referencing the positioning and rotation of the drone.

• How will your automation confirm that the drone has moved successfully to the correct location?
> Can do so by utilizing the grid locations of each cell block and referencing the values with the positions of the grid. Same goes for the direction of the drone.

• How will you automate and confirm that no other sequence of commands can be used before the Place command has been executed?
> A simple use of boolean expressions was able to suffice. Through nested SetActive commands multiple GameObjects are made false or active either by script or OnClick button commands.

• How will you go about automating and verifying that the drone does not go out of the boundary?
> Validation checks of the move drone + the place drone commands and script were neccessary. Used if statements in this regard.

• Based on your Assessment requirements and your solution, what other automatable test scenarios can you identify?
> If a drone would have to fly (3D based environments) how would you be able to depict the min and max height the drone could travel?
