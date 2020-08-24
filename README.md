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

