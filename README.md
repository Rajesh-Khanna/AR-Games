# Augmented reality games

[![Python 3.6](https://img.shields.io/badge/python-3.6-blue.svg)](https://www.python.org/downloads/release/python-360/)

![Snake AR](snake.jpeg?raw=true "Snake AR")
![Pong AR](pong.jpeg?raw=true "Pong AR")


## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages.
```bash
sudo apt-get install python3-pip
```

Install pygame
```bash
pip install pygame
```
If opencv is already installed use this command to uninstall it.

```bash
pip install pip uninstall opencv-python
```
Install opencv-contrib
this package provides aruco which we require for 2D to 3D projection.
```bash
pip install opencv-contrib-python
```

### Requirements

* A4 Printout of the templates provided. 
  * `checks.jpg`
  * `marker_board.jpg`

![Checks board](checks.jpg?raw=true "Checks board")
![Marker board](marker_board.jpg?raw=true "Marker Board")

* Clone this code to you local machine
```bash
git clone https://github.com/Rajesh-Khanna/AR-Games.git
```

### Running the code

* To run the snake game
```bash
python3 snake.py
```
* To run ping pong
```bash
python3 pong.py
```

	* Two new windows pop up one to display the 2D game and another to display the AR.
	* First we need to initaly calibrate to you cameras distortions. For that place `checks.jpg` image infront of the camera and  move the paper freely for the program to calibrate from different angles till the you see `marker_board.jpg`. 
	![Checks_running board](checks.jpeg?raw=true "Checks_running board")
	![Marker_running board](marker.jpeg?raw=true "Marker_running board")

	* Now place the `checks.jpg` board aside and hold the `marker_board.jpg` you can see the game starts running.

### Controls : 
  *Snake game:
    * The 4 direction arrows on the key board have their own meaning the snake moves in the direction you press the arrow.
  * Pong :
    * Use left and right arrows to movie the bottom plank
    * Use A and D keys  to move top plank.


 * To stop the game use `ctrl + c` on the terminal.
`If the keys are not working just click on the 2D display once`.

---

These Games are a fun project. main emphasis was on implementaion sorry for having not a very user friendly interface.