# Distance_Between_Two_Points

#### Why do we care?

Distance between two points is used in many ways in machine learning. Depending how far the two points are relative to eachother, we can cluster them as one class or divide them into different groups. There are many types of measures of distance, and they are selected uniquely depending on its purpose.
<br>

---

### Let's see some types of distances
#### 1. Euclidean distance
Euclidean distance is the line segment connecting the two points in Euclidean space(finite dimensional space). Without additional contraints, the answer is the magnitude of a straight line intersecting the two points.

#### 1.1 How it's defined(cartesian coordinate system):

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;1D&space;=&space;\sqrt{\left&space;(&space;x-y&space;\right&space;)^2&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;1D&space;=&space;\sqrt{\left&space;(&space;x-y&space;\right&space;)^2&space;}" title="Euclidean \ Distance \ in \ 1D = \sqrt{\left ( x-y \right )^2 }" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;2D&space;=&space;\sqrt{\left&space;(&space;x_{1}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{2}-y_{2}&space;\right&space;)^2&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;2D&space;=&space;\sqrt{\left&space;(&space;x_{1}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{2}-y_{2}&space;\right&space;)^2&space;}" title="Euclidean \ Distance \ in \ 2D = \sqrt{\left ( x_{1}-y_{1} \right )^2 + \left ( x_{2}-y_{2} \right )^2 }" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;3D&space;=&space;\sqrt{\left&space;(&space;x_{1}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{2}-y_{2}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{3}-y_{3}&space;\right&space;)^2&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;3D&space;=&space;\sqrt{\left&space;(&space;x_{1}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{2}-y_{2}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;x_{3}-y_{3}&space;\right&space;)^2&space;}" title="Euclidean \ Distance \ in \ 3D = \sqrt{\left ( x_{1}-y_{1} \right )^2 + \left ( x_{2}-y_{2} \right )^2 + \left ( x_{3}-y_{3} \right )^2 }" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;n&space;\&space;dimensions&space;=&space;\sqrt{\sum_{i}^{n}\left&space;(&space;x_{i}-y_{i}&space;\right&space;)^2&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean&space;\&space;Distance&space;\&space;in&space;\&space;n&space;\&space;dimensions&space;=&space;\sqrt{\sum_{i}^{n}\left&space;(&space;x_{i}-y_{i}&space;\right&space;)^2&space;}" title="Euclidean \ Distance \ in \ n \ dimensions = \sqrt{\sum_{i}^{n}\left ( x_{i}-y_{i} \right )^2 }" /></a>
</p>

<p align="center">
Here, x and y are points on the same ith axis
</p>

<br>

#### 1.1 Where is Euclidean distance used?
As we can see from the formulea, Euclidean distance gives a sphereically symmetric  straight line distance measure from the point of reference to any other point of interest. This is used in KNN as well as K means in terms for clustering a neighborhood of a reference, classifying the cluster as the same class.






2. Manhattan distance 
3. Minkowski  distance
4. Cosine Similarity 

