![](http://latex.codecogs.com/gif.latex?hidden1(x)=ConvStep(W_h1^{3*1},x))

![](http://latex.codecogs.com/gif.latex?hidden2(x)=x+ConvStep(W_h2^{3*1},hidden1(x)))

![](http://latex.codecogs.com/gif.latex?hidden3(x)=ConvStep(W_h3^{15*1},hidden2(x)))

![](http://latex.codecogs.com/gif.latex?hidden3(x)=x+ConvStep_{d==8}(W_h4^{15*1},hidden3(x)))

![](http://latex.codecogs.com/gif.latex?ConvBlock(x)=\left\{\begin{matrix}Dropout(hidden4(x),0.4)&during\; training\\ hidden4(x)&otherwise\end{matrix}\right.)
