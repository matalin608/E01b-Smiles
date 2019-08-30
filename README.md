# E01b-Smiles

This is a project for Indiana University. The exercise is mostly centered around the creation of a smiley face, which is done by assigning coordinates to shapes in the program. In main1.py, I have been given a pre-determined window size in which I create the smiley face. The bakcground color, smiley face color, and variable names have already been set by the program creator. for the variable draw_circle_filled, I edited the numbers in place so that the yellow circle would sit in the middle of the screen. I assigned the same values to draw_circle_outline so that the outline, which is not technically part of the yellow shape, will sit directly on top of the yellow shape. For the remaining variables, I assigned random values until each individual shape came together to create a "smiley face" in the window. When this file is run, an image should appear that resembles a smiley face. In main2.py, I am given variables face_x and face_y, which are to be assigned values that represent the very center of the shape created. From this, numbers are added to each following variable, which represent the eyes, catches, and the smile. These are edited so that the picture created when the file is run is exactly the same as the picture that appears when main1.py is run. Main3.py uses the same idea of adding values to the center coordinate, but each shape has its own variable assigned in this file. These are labeled smile_x, eye1_x, and so on. Here, I entered the exact same calculated values to the variables given (face_x and face_Y) as I did in the previous file. This file performs a very similar function, but contains much simpler variable assignments. In main4.py, I repeated the added variables, as I did in main3.py. Here, a condition is given for x in the range of the window, the shape will be drawn over and over again. It also assigns the condition that, for y in range of the window, the shape will be drawn over and over again using the values from main3 and main2, which had to be reentered in this file. 

An exercise exploring variables and loops using Python Arcade.

This repository contains several files that you will need to alter to complete the assignment. The instructions for the exercise are also on Canvas.

Comments in Python are marked by a # sign (for single-line comments) or three matching quotation marks (''' or """) if a comment requires more than one line. They should also appear in a different color in VS Code. The Python Interpreter ignores comments, so you can safely include any information you want there.

As with your assignments, please edit the LICENSE file (replace the [year] [fullname] with the current year and your name); you will also be expected to edit README.md (this file) to describe what you have accomplished.

---

As always, Fork this repository, and then Clone it to your local computer.

Before you begin, you will need to install Python Arcade, the graphics library we will be using for the first half of the semester. Open the Terminal (either by clicking on the magnifying glass and searching for CMD, or open the Terminal in VS Code) and type the following:

*pip install arcade --user*

pip is a tool for downloading and installing Python packages. arcade is the name of the package we will be using. When you type the command, you should see the components it is installing (with corresponding progress bars).

When arcade has been installed, we can get to work:

First, open main1.py. I am drawing several shapes that, if properly assembled, can form a smiley face. Right now, the shapes are all being drawn at (0,0), which is the bottom-left corner of the window. See if you can use those shapes to draw a smiley face in the center of the window. The small gray dots are catch lights for the eyes.

The end result should look something like this:

![Smile!](https://github.com/BL-MSCH-C220-F19/E01b-Smiles/blob/master/smile.png)

When you have placed the shapes correctly, save the file and open main2.py. The only change I have made is to define coordinates (face_x and face_y) that represent the center of the circle. Figure out offsets for the other shapes in relation to face_x and face_y. Use face_x and face_y to move all the shapes to the middle of the window. Save your changes.

Next, in main3.py, I have created several new coordinates to represent each of the shapes: smile, eye1, eye2, catch1, and catch2. Use what you learned in main2.py to define each of those coordinates in relation to face_x and face_y. Move the face to the middle of the window. You should only have to edit lines 13 through 18. Save your changes.

Open main4.py. You will now be drawing many faces in the window. Editing lines 20 through 24, draw a grid of overlapping faces. Now, play with the values on lines 16 and 18. What happens when you adjust those numbers? Save your changes.

When you have completed the exercise, commit your changes and push them back to GitHub. Turn in the URL of your repository on canvas.

*Extra credit:* 

main5.py is much more complicated, but it allows the smiley face to track mouse movements. Add a comment to every line describing what is happening. Save those changes.

If you want to further explore Python Arcade, the API and some sample projects are available at [arcade.academy](http://arcade.academy).

---

The grading criteria will be as follows:

* [1 point] Repository contains an appropriate software license
* [1 point] Repository contains a descriptive README.md
* [8] Accomplishes the objective of the exercise

10 points total
