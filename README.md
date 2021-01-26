# -AntiFaceDetectionCovidMaskProject
A course final project for CS 5821 Computational Intelligence

The goal of the project was to create a facemask design that looked interesting and reduced probability of face detection for the wearer. Masks were generated using a compositional pattern producing network (CPPN), with parameters modified by a genetic algorithm to minimize a histogram of gradients (HOG) face detector score. A 1000 image subset of the Flickr Faces dataset was used to provide training examples. A HOG face feature detector was used to automatically apply the mask to the various faces.

![sample masked face](https://github.com/evan-person/AntiFaceDetectionCovidMaskProject/blob/main/andyWarholMasked2.png)


Directions for use:

Run the Jupyter notebook cell by cell.

You will need to download a folder of face images to your google drive or otherwise upload a selection of faces. A link to the Flickr Faces dataset is available with the submission. 

