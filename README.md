# Guide to ISART 2024 Tutorial <br/> Building and Evaluating a Statistical Propagation Model

## Introduction

The purpose of this tutorial is to guide you through building your own statistical propagation model based on clutter metrics derived from LiDAR. Once you've developed your model, you'll compare it with clutter loss predictions from the [ITU-R P.2108](https://github.com/NTIA/p2108) model. Finally, you will assess your model's generalizability against five newly released measurement datasets.

**If you are not an experienced coder, don't worry!** All of the code you will need is provided for you. We invite you to read along with the lessons, run all of the code, and analyze the model outputs. There is much to learn, and assessing your model's accuracy on different measurement datasets from different clutter environments is a good place to start.  

**If you do have experience coding, we want you!** We have released five measurement datasets in five different clutter environments. With the release of these datasets we are inviting you to collaborate with ITS on new clutter-based propagation models. Our aim is that tutorial and code provided here will be a launching point for a collaborative effort on a new generation of clutter models. 

The model you'll create in this tutorial was developed by W. Kozma and M. Cotton in "[A Proposed Mid-band Statistical Clutter Propagation Model Utilizing Lidar Data](https://its.ntia.gov/umbraco/surface/download/publication?reportNumber=KozmaEuCAP2023.pdf)," 2023, EuCAP.

## Quick Start

1. **Send your Github username to mhollingsworth@NTIA.gov** and for access to the course materials and coding environment. Once we receive your email, we will confirm you are an ISART attendee create your account. If you do not have a GitHub account, [create one](https://github.com). 

2. Go to [www.isartmax.com](https://isartmax.com) to access your personal JupyterLab account.
   
   JupyterLab is a cloud programming environment that ISART attendees can use for the duration of ISART 2024.

3. Run the lessons.

   All of the course materials are pre-loaded in your JupyterLab account. Once you've logged in, double click on the `course-materials/` folder to access them. 

  * `course-materials/Lesson1.ipynb` is a Jupyter Notebook containing Lesson 1 on determining clutter metrics from LiDAR.

  * `course-materials/Lesson2.ipynb` is a Jupyter Notebook containing Lesson 2 on comparing your clutter model to P.2108.

  * `course-materials/Lesson3.ipynb` is a Jupyter Notebook containing Lesson 3 on analyzing your clutter model against measurement data from other clutter environments.

  * `course-materials/data/` is a directory containing LiDAR and propagation measurement datasets.

---

## Additional Reading

### Introduction to JupyterLab


