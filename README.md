![](http://latex.codecogs.com/gif.latex?hidden1(x)=ConvStep(W_h1^{3*1},x))

![](http://latex.codecogs.com/gif.latex?hidden2(x)=x+ConvStep(W_h2^{3*1},hidden1(x)))

![](http://latex.codecogs.com/gif.latex?hidden3(x)=ConvStep(W_h3^{15*1},hidden2(x)))

![](http://latex.codecogs.com/gif.latex?hidden3(x)=x+ConvStep_{d==8}(W_h4^{15*1},hidden3(x)))

![](https://latex.codecogs.com/gif.latex?ConvBlock%28x%29%3D%5Cleft%5C%7B%5Cbegin%7Bmatrix%7DDropout%28hidden4%28x%29%2C0.4%29%26during%5C%3B%20training%5C%5C%20hidden4%28x%29%26otherwise%5Cend%7Bmatrix%7D%5Cright.)
