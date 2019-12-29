# ML4--nonlinear_logistic_regression

<p align="center">
  <img width=400 src="demo_images/raw_data.jpg" >
</p>

1000 datapoints, each with 2-dimensional input ![](http://latex.codecogs.com/gif.latex?x_1%2C%20x_2%20%5Cin%20%5Cmathbb%7BR%7D) and binary class output ![](http://latex.codecogs.com/gif.latex?y%20%5Cin%20%7B0%2C1%7D) have **non-linear class boundaries** as shown above. In order to train a classifier with such boundaries, the input of each datapoint was feature-expanded through a set of **radial basis functions** centred on the training datapoints, giving expanded input ![](http://latex.codecogs.com/gif.latex?%5Cunderline%7B%5Ctilde%7Bx%7D%7D%20%3D%20%5B%5Ctilde%7Bx%7D_1%2C%20...%2C%20%5Ctilde%7Bx%7D_%7B801%7D%5D%5ET).

<p align="center">
  <img width=400 src="demo_images/feature_expansion.png" >
</p>

