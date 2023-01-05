---
layout: page
title: OhneDriver Bus System
description: a project with a background image
img: assets/img/12.jpg
importance: 1
category: work
created: 2022-12-31T20:55:12-06:00
updated: 2022-12-31T20:55:12-06:00
---
# OhneDriver Bus Automation

## Introduction

This project is an attempt to automate the bus movement in the campus. The buses are currently monitored by the driver and the driver is responsible for the movement of the bus. The driver is responsible for the movement of the bus and also for the safety of the passengers. We are trying to automate the bus movement by using the sensors and the camera installed in the bus. The sensors are used to monitor the movement of the bus and the camera is used to monitor the passengers. The driver will be responsible for the safety of the passengers and the bus movement will be monitored by the system.

## Objectives

The objectives of the project are as follows:

* To automate the bus movement in the campus
* To monitor the movement of the bus using the sensors
* To monitor the passengers using the camera
* To monitor the speed of the bus using the GPS

## Scope

The scope of the project is limited to the movement of the bus in the campus. The system will be able to monitor the movement of the bus and the passengers. The system will not be able to monitor the movement of the bus outside the campus.

## System Architecture

The system architecture of the project is shown below:

![System Architecture](/assets/img/system_architecture.png)

## Technologies Used

The technologies used in the project are as follows:

* Python
* HTML
* CSS
* JavaScript
* OpenCV
* Arduino
* Raspberry Pi
* GPS

## Hardware

The hardware used in the project are as follows:

* Raspberry Pi
* Arduino
* GPS
* Camera
* Sensors

## Software

The software used in the project are as follows:

* Python
* HTML
* CSS
* JavaScript
* OpenCV

## Team Members

The team members are as follows:

* [Karthik](
To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/1.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/3.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Caption photos easily. On the left, a road goes through a tunnel. Middle, leaves artistically fall in a hipster photoshoot. Right, in another hipster photoshoot, a lumberjack grasps a handful of pine needles.
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, *bled* for your project, and then... you reveal its glory in the next row of images.


<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>


The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:

{% raw %}
```html
<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.html path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
```
{% endraw %}
