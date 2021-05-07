Hello! Welcome to my Github Pages website. Here you will find information about me and the projects I have completed.

## About me
I am currently an engineering student at York University and am in the process of declaring a major in software engineering.
I excelled in coding the courses I took in high school and university.
I have been coding as a hobby for a few years, mostly making small applications with GUIs in Python and experimenting with website development with Python and the standard HTML, CSS, and JavaScript.
To make my larger projects available online, and to practice using Git, I have been making GitHub repositories for these projects.
They are listed below.

## My Projects

### Sorting Visualization
Link to GitHub repository: <https://github.com/Danpythonman/sorting_visualizer>

This project is a graphical user interface made with the Tkinter library in Python.
It was made after learning about sorting algorithms in a high school computer science course.
To visualize sorting algorithms, the user clicks a button to generate a random list of 64 numbers.
On screen, these numbers are represented by rectangles, with their heights being proportional to the size of the number.
The user can then click a button to sort the list with a specified sorting algorithm.
The list is sorted in real time which can be seen as the rectangles are sorted from shortest to tallest.
Here is merge sort visualized:

![Merge sort visualized by sorting rectangles of differnt heights](images\merge_sort_visualization.gif)

And here is selection sort:

![Selection sort visualized by sorting rectangles of differnt heights](images\selection_sort_visualization.gif)


### Inspirational Website
Link to GitHub repository: <https://github.com/Danpythonman/t_web1>

This project is an inspirational website in HTML, CSS, and JavaScript that displays a new motivational quote every day.
The user enters their name when prompted and the site remembers this name.
A welcome message is displayed, along with the current time.
Under that is the quote of the day.
The quote is from the [They Said So Quotes REST API](https://quotes.rest/).
The background image also changes daily, which the website gets from [NASA's Astronomy Picture of the Day API](https://api.nasa.gov/).
Each time the user accesses the site, the two APIs are contacted to get the quote and picture, which are then displayed.
This is done through JavaScript.

### Automated Plant Watering
Link to GitHub repository: <https://github.com/Danpythonman/automated_plant_watering>

This project, designed to run on an Arduino-compatible board, monitors and waters a plant automatically.
This was originally a university project done in C++ and Java where the board would be connected to a computer, which sent, processed, and received information through a Java program.
I have since refactored it to run without the second computer, so it is now entirely in C++.

The Arduino-compatible board is connected to a moisture sensor and a pump.
The sensor is put into the soil and the pump is submerged in water, with the tube outlet pointing to the soil.
Among other things, like displaying information about the soil's moisture on an OLED screen, the program monitors the moisture level of the soil, recognizes when the soil is dry, and activates the pump, watering the plant.

Here is a picture of the setup (when it still required the second computer):
![Automated plant watering system](images\automated_plant_watering_system.jpg)

