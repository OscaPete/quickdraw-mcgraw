# quickdraw-mcgraw
A quickdraw game inspired by the skit, "Quickdraw McGraw"

# requirements
- The program may be any type of game or interactive simulation.
- The program should use classes and instances.
- The program should apply the four principles of programming with classes.
- The program should use the libraries chosen in the course.
- The program should be delivered through a version control system.
- The program should be able to be run from the command line.

# design
- controls would only be the spacebar for the quickdraw
- needs to draw 2 actors, quickdraw mcgraw and the player
- needs a "Ready?" prompt, and a "DRAW!" prompt
- video support obviously needed
- mcgraw runs on a timer, to win you need to press spacebar before the timer expends
- gunshot noises haha
- "You Win" and "You Lose" prompts necessary

# organization
- Casting
 - Actor
 - Player
 - McGraw

- Prompting
 - Ready
 - Draw
 - Win
 - Lose

- Directing
 - Director

- Assets
 - This folder should contain needed images and sounds

- Services
 - video and keyboard service to allow gameplay

- Shared
 - a point file to allow placement

