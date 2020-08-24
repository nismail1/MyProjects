# MyProjects

Within this repository, you will find my Pacman and Sketchy projects in this repository.

Pacman -

My game Pacman is made up of several classes where the main logic is defined in a class calles Pacman. This class
sets up a board and it moves the Pacman along this board checking for whether it is encountering a wall and
eating dots along the way and gaining points. In order to check for collision with multiple types of different
objects, I created an interface called Smart Objects that all implement the method collision. It allows each
square to have an array of SmartObjects so that whenever there is a collision, the method collision can be
called on all SmartObjects in the array. There is also multiple ghost in a pen that
are being released periodically and chasing the Pacman based on a Breadth First Algorithm implemented
in the Ghosts class.

Sketchy -

My game Sketchy has a Sketchy class, Command classes and Layer bean class that handled game logic and undo/redo
that helped raise and lower shapes. I chose to use interfaces because each class implemented methods 
differently and so it allowed me to code abstractly. I used undo and redo stack because it was easy to keep
track of commands when there is a simple pop and push between data structures. The way that my lines are colored in is a little odd because color is selected after the line has been drawn.

