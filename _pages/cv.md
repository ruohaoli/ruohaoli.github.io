---
layout: archive
title: "CV - Ruohao Li"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D Student in Hong Kong University of Science and Technology, Computational Media  &nbsp;&nbsp;&nbsp;&nbsp; 2024-2028 (expected)
* M.S. in University of Pennsylvania (quit), Smart Cities &nbsp;&nbsp;&nbsp;&nbsp; 2023-2024
* B.S. in Zhejiang University &nbsp;&nbsp;&nbsp;&nbsp; 2019-2023

Research Experience
======
* Computer Vision & Cloud-based research: Hurricane damage area prediction by YOLO  
* University of Pennsylvania &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; March 2024-May 2024
  * Split large Satellite Images into 10000 patches, performed image annotation for 1000 images in OpenCV, classified land use into 4 types.
  * Conducted data wrangling, cleaning, then wrote a data pipe and create table with SQL to prompt data into cloud storage.
  * Fine-tuned pretrained YOLOv9 model on cloud platform with image and json-text file, create the cloud bucket to store all results.

* Machine learning-based research: Los Angeles Fire Risk Prediction  
* University of Pennsylvania &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Nov. 2023-Dec. 2023
  * Performed data cleaning, exploratory analysis, and visualization with fire perimeter, water, vegetation, and heat island.
  * Conducted data wrangling, including creating a fishnet with spatial data, aggregating fire, water cover, vegetation, and heat island data into fishnet, and counting risk factors by grid cell. Finished feature engineering through KNN, employed Local Moran's I to identify spatial autocorrelation within grid cells.
  * Performed regression analyses, adopting both random k-fold and Leave-One-Group-Out cross-validation to evaluate model's performance, visualized and decreased the distribution of MAE by 30%, got the model accuracy of 0.84.
  * Designed an app including real-time detection and fire risk prediction for citizens.

* Machine learning-based research: Habitat protection in metropolitan fringe areas  
* Zhejiang University &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; June 2023-Aug 2023
  * Delimited urban areas based on 76 iterations of the K-means clustering algorithm, identified land features and vegetation types to classify fringe habitats through Python and machine learning, yielded 4,576 data points, categorized 14 significant and 22 smaller sources from 0.67 hm2 to 8276.390 hm2.
  * Conducted in-depth analysis on distribution and Characteristics of the Metropolitan Fringe Area as a 40 m Morphological Spatial Pattern Analysis edge width and a 1.5 hm² minimum area threshold.
  * Completed the paper “Habitat protection in metropolitan fringe areas: An ecological network approach in China’s territorial spatial planning” independently, being reviewed by “Sustainable Cities and Society” (If 11.7).

* Urban Landscape, Daily Travel and Air Pollution with machine learning   
* Zhejiang University &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Apr 2020 - June 2021
  * Analyzed the impacts of street greenery described by the green view index (GVI) on active travel (AT) with road classification defined by road flow and function as a moderating variable.
  * Calculated roads’ GVI based on 500 thousand photos through machine learning, then quantified the impacts of street greenery by multilevel logistic regression and multilevel linear regression.
  * Reported the moderating role of road class for the impacts of street greenery on AT and emphasized the importance of low-class road greenery.

Skills
======
* Programming language: Python (PyTorch, Pandas, NumPy, TensorFlow, Keras), SQL, R, Java (Web)，html
* Framework and Tools: Linux, Twinmotion, Unity, Latex, OpenStreetMap, PostSQL, PostGIS, CPLEX, OpenCV, ArcGIS
