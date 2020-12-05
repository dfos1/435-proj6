# 435-proj6
This is David Foster's project 6 results


This is the README for project 6 by David Foster

This project tasks us with implementing Seam Carving on an input image. This project involves taking an input image and determining the energy or importance
of each pixel with an energy function, chosen either from the provided paper or implemented ourself.

Once the energy of each pixel has been determined we use dynamic programming to find the lowest-importance seam across the horizontal or vertical orientation and remove it.

To use this program supply the input file (arg 1), the output filename (arg2), the width (arg3) and the height (arg4).

Statement of help:
- Help from the project page
- Help from the provided paper
- Help from the lecture code provided in class
- Help from a fellow student who gave me a good input file to test with
- Help from a friend who reminded me to use valgrind to hunt for segfault errors
