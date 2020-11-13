# Distance_Between_Two_Points

#### Why do we care?

Distance between two points is used in many ways in machine learning. Depending how far the two points are relative to eachother, we can cluster them as one class or divide them into different groups. There are many types of measures of distance, and they are selected uniquely depending on its purpose.

---

#### Let's see some types of distances
##### 1. Euclidean distance
Euclidean distance is the line segment connecting the two points in Euclidean space(finite dimensional space). Without additional contraints, the answer is the magnitude of a straight line intersecting the two points.

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean\&space;Distance&space;\1D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean\&space;Distance&space;\1D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2}" title="Euclidean\ Distance \1D=\sqrt{\left ( x_{2}-x_{1} \right )^2}" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean\&space;Distance&space;\2D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;y_{2}-y_{1}&space;\right&space;)^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean\&space;Distance&space;\2D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;y_{2}-y_{1}&space;\right&space;)^2}" title="Euclidean\ Distance \2D=\sqrt{\left ( x_{2}-x_{1} \right )^2 + \left ( y_{2}-y_{1} \right )^2}" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=Euclidean\&space;Distance&space;\3D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;y_{2}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;z_{2}-z_{1}&space;\right&space;)^2}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?Euclidean\&space;Distance&space;\3D=\sqrt{\left&space;(&space;x_{2}-x_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;y_{2}-y_{1}&space;\right&space;)^2&space;&plus;&space;\left&space;(&space;z_{2}-z_{1}&space;\right&space;)^2}" title="Euclidean\ Distance \3D=\sqrt{\left ( x_{2}-x_{1} \right )^2 + \left ( y_{2}-y_{1} \right )^2 + \left ( z_{2}-z_{1} \right )^2}" /></a>
</p>

<p align="center">
<a href="https://www.codecogs.com/eqnedit.php?latex=n-dimentional&space;\&space;Euclidean&space;\&space;space&space;=&space;\sum_{i}^{n}\sqrt{\left&space;(&space;x_{i}-y_{i}&space;\right&space;)^2&space;}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?n-dimentional&space;\&space;Euclidean&space;\&space;space&space;=&space;\sum_{i}^{n}\sqrt{\left&space;(&space;x_{i}-y_{i}&space;\right&space;)^2&space;}" title="n-dimentional \ Euclidean \ space = \sum_{i}^{n}\sqrt{\left ( x_{i}-y_{i} \right )^2 }" /></a>
</p>

<p align="center">
here, x and y are points on the same ith axis
</p>

2. Manhattan distance 
3. Minkowski  distance
4. Cosine Similarity 

