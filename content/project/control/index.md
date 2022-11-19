---
title: Feedforward Tracking Control of Nonminimum Phase Systems using Filtered Basis Function 
summary: A brief introduction to my works in this project
tags:
  - Control
date: '2022-08-27T00:00:00Z'

# Optional external URL for project (replaces project detail page).
external_link: ''

image:
  caption: Diagram for the General Methodology
  focal_point: Smart

links:
  - icon: youtube
    icon_pack: fab
    name: Follow
    url: https://www.youtube.com/watch?v=6sN71fx9frk
url_code: ''
url_pdf: ''
url_slides: ''
url_video: ''

---
This project is based on the filtered B-spline (FBS) approach developed by Prof. Okwudire's lab for feedforward compensation of vibration. This method has allowed Cartesian 3D printers to do the printing smoothly, without sacrificing too much quality due to vibration at the high speed. The goal of this project is to extend this FBS to non-Cartesian robots. Especially, one important challenge in the project is how to adapt the FBS method designed for linear systems to robots with nonlinear dynamics.
In this project, my works involve:
1. study their proposed FBS method in reducing the vibrations in 3D printing for linear systems;
2. propose to use Newton-Gaussian methods to extend the method to reduce the vibrations for nonlinear systems;
3. write up Matlab codes for some starting tests on this method; 
