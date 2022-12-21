# SatelliteCD
Bounding Box-based Satellite Image Change Detection

- Left and right are bitemporal images and orange boxes are predicted changes.
<img src="https://user-images.githubusercontent.com/16814077/208929986-185eb955-db17-4815-99c7-ab21bc0d3c38.gif" width=70% height=70%>

Introduction
------------
- We introduce Bounding Box-based Change Detection Method on satellite images/remote sensing images.
- Our method largely reduce labeling burden compared with segmentation based change detection methods.

Dataset
-------------
- We tested our method on LEVIR-CD dataset which is large-scale remote sensing binary change detection dataset.
(https://justchenhao.github.io/LEVIR/)
- For training, we made bounding box annotations from their change maps.
   (x1,y1,...,x4,y4,category,difficulty)
<p float="left">  
  <img src="https://user-images.githubusercontent.com/16814077/208937426-6439efd5-4e3e-4f0d-a48f-1b025707cf10.png" width=30% height=30%>
  <img src="https://user-images.githubusercontent.com/16814077/208936388-f9074bb5-5ca8-4bb8-8e5c-c11033e0f520.PNG" width=30% height=30%>  
</p>



