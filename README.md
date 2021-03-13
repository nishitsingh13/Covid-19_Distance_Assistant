<h2 align="center">
      COVID-19 DISTANCE ASSISTANT
</h2>


A social distancing detector built with OpenCV using YOLO(COCO model) object detector


<h3 align="center">
      MOTIVATION
</h3>


<p>
Social distancing is a method used to control the spread of contagious diseases. It implies that people physically distance themselves from one another, reducing close contact, and thereby reducing the spread of a contagious disease (such as the COVID-19 Disease). Social distancing is not a new concept, dating back to the fifth century, and has even been referenced in religious text such as the Bible.
</p>

<br><br><br>

<p align="center">
  <img src="res/social_distance_detector_spread.gif">
</p>

<p align="center">
   Social distancing is crucial to the prevention of the spread of disease.
</p>
<br><br>

## Features:
* Object detection using the YOLO COCO model to detect only people in a video stream.
* Computes the pairwise distances between all detected people.
* Based on the computed distances, we determine whether social distancing rule is being violated or not.
