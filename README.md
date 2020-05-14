# **Finding Lane Lines on the Road** 
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)

<!-- <img src="examples/laneLines_thirdPass.jpg" width="480" alt="Combined Image" /> -->
<video width="960" height="540" autoplay>
  <source src="./test_videos_output/solidWhiteRight.mp4" type="video/mp4">
</video>

Overview
---

When we drive, we use our eyes to decide where to go.  The lines on the road that show us where the lanes are act as our constant reference for where to steer the vehicle.  Naturally, one of the first things we would like to do in developing a self-driving car is to automatically detect lane lines using an algorithm.

In this project you will detect lane lines in images using Python and OpenCV.  OpenCV means "Open-Source Computer Vision", which is a package that has many useful tools for analyzing images.  

The project meets specification as describe in the [project rubric](https://review.udacity.com/#!/rubrics/322/view)



Installation
---


To set up your python environment to run the code in this repository, follow the instructions below.

1. Create (and activate) a new environment with Python 3.6.

    * Linux or Mac:
    ```
    conda create --name envname python=3.6
    source activate envname
    ```

    * Windows
    ```
    conda create --name envname python=3.6 
    activate envname
    ```

Install dependencies from the requirements file
```
pip install -r requirements.txt
```

Activate Jupyter notebook and run the P1.ipynb.

