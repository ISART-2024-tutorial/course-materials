# Guide to ISART 2024 Tutorial <br/> Building and Evaluating a Statistical Propagation Model

## Introduction

The purpose of this tutorial is to guide you through building your own statistical propagation model based on clutter metrics derived from LiDAR. Once you've developed your model, you'll compare it with clutter loss predictions from the [ITU-R P.2108](https://github.com/NTIA/p2108) model. Finally, you will assess your model's generalizability against five newly released measurement datasets.

**If you are not an experienced coder, don't worry!** All of the code you will need is provided for you. We invite you to read along with the lessons, run all of the code, and analyze the model outputs. There is much to learn, and assessing your model's accuracy on different measurement datasets from different clutter environments is a good place to start.  

**If you do have experience coding, we want you!** We have released five measurement datasets in five different clutter environments. With the release of these datasets we are inviting you to collaborate with ITS on new clutter-based propagation models. Our aim is that tutorial and code provided here will be a launching point for a collaborative effort on a new generation of clutter models. 

The model you'll create in this tutorial was developed by W. Kozma and M. Cotton in "[A Proposed Mid-band Statistical Clutter Propagation Model Utilizing Lidar Data](https://its.ntia.gov/umbraco/surface/download/publication?reportNumber=KozmaEuCAP2023.pdf)," 2023, EuCAP.

## Quick Start

1. **Send your GitHub username to mhollingsworth@NTIA.gov** and for access to the course materials and coding environment. Once we receive your email, we will confirm you are an ISART attendee and create your account. If you do not have a GitHub account, [create one](https://github.com)!

2. Go to [www.isartmax.com](https://isartmax.com) to access your personal JupyterLab account.
   
   JupyterLab is a cloud programming environment that ISART attendees can use for the duration of ISART 2024.

3. Run the lessons.

   All of the course materials are pre-loaded in your JupyterLab account. Once you've logged in, double click on the `course-materials/` folder to access them. 

- [**`course-materials/Lesson1.ipynb`**](Lesson1.ipynb) is a quick introduction to using Jupyter Notebooks.

- [**`course-materials/Lesson2.ipynb`**](Lesson2.ipynb) notebook contains Lesson 2 on determining clutter metrics from LiDAR.

- [**`course-materials/Lesson3.ipynb`**](Lesson3.ipynb) notebook contains Lesson 3 on comparing your clutter model to P.2108.

- [**`course-materials/Lesson4.ipynb`**](Lesson4.ipynb) notebook contains Lesson 4 on analyzing your clutter model against measurement data from other clutter environments.

- [**`course-materials/data/`**](./data) is a directory containing LiDAR and propagation measurement datasets.

---

## Additional Reading

### JupyterLab

JupyterLab is a web-based coding environment that allows you to work with program files (such as Jupyter Notebooks) and command line terminals. Following the instructions above, in Quick Start, to have an ISART JupyterLab account created for you. Your JupyterLab account is for you to experiment with and is only accessable to you. Any changes that you make to files will be saved for the next time you login.

### Jupyter Notebooks

A Jupyter Notebook (.ipynb file) is an interactive computing document that brings together coding, computation, outputs, explanatory text, and images. Each lesson of this tutorial is contained within a Jupyter Notebook. The Lesson1.ipynb notebook contains Python code and explanatory text for running Jupyter Noteboks.

**How to run your first Jupyter Notebook**

1. Go to [www.isartmax.com](https://isartmax.com) to access your personal JupyterLab account.

2. Log in with your GitHub account. If you haven't sent us you're GitHub username, then go back to **Quick Start** and perform step 1.

3. Double click on the `course-materials/` folder on the panel to the left. 

4. Double click on `Lesson1.ipynb`.

   The first cell of Lesson1.ipynb should look like this.

   ![alt text](./images/hello_world.png "Hello, World!")

   Select this cell and press "Shift-Enter" on the keyboard to execute the code within the cell (alternatively, you can also press the "play button" at the top of the page). "Hello, ISART World!" should output just below the cell. You've executed your first bit of Python code.

5. Continue executing the cells in Lesson1 until you reach the end. Now it's time to dive into clutter modeling with lessons 2, 3, and 4. Happy modeling!

### LiDAR data

The LiDAR data used in this tutorial comes from [OpenTopography](https://opentopography.org). You can create an account for free and download terrain and surface rasters for your area of interest. 

TODO describe raster data and how to download it. What's the difference between terrain and surface rasters?

### Measurement data

TODO Link to the github page with the released data.