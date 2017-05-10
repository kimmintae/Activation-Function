[sigmoid]: figure/sigmoid.png
[tanh]: figure/tanh.png
[relu]: figure/relu.png
[lrelu]: figure/lrelu.png
[prelu]: figure/prelu.png
[elu]: figure/elu.png


Activation Function in Neural Network
=======================================



Sigmoid
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=f(x)&space;=&space;\frac{1}{1&space;&plus;&space;e^-x}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?f(x)&space;=&space;\frac{1}{1&space;&plus;&space;e^-x}" title="f(x) = \frac{1}{1 + e^-x}" /></a>

![sigmoid]

Hyperbolic Tangent(tanh)
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=tanh(x)&space;=&space;\frac{e^x&space;-&space;e^{-x}}{e^x&space;&plus;&space;e^{-x}}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?tanh(x)&space;=&space;\frac{e^x&space;-&space;e^{-x}}{e^x&space;&plus;&space;e^{-x}}" title="tanh(x) = \frac{e^x - e^{-x}}{e^x + e^{-x}}" /></a>

![tanh]

Rectified linear unit (ReLU)
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=$$f(x)&space;=&space;max(0,&space;x)$$" target="_blank"><img src="https://latex.codecogs.com/gif.latex?$$f(x)&space;=&space;max(0,&space;x)$$" title="$$f(x) = max(0, x)$$" /></a>

![relu]

Leaky Rectified Linear Unit(Leaky ReLU)
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=f(x)&space;=&space;max(ax,&space;x)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?f(x)&space;=&space;max(0.01x,&space;x)" title="f(x) = max(0.01x, x)" /></a>

![lrelu]

Parametric Rectified Linear Unit (PReLU)
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=f(x)&space;=&space;max(ax,&space;x)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?f(x)&space;=&space;max(ax,&space;x)" title="f(x) = max(ax, x)" /></a>

![prelu]

Exponential Linear Unit(ELU)
----------------------------------
<a href="https://www.codecogs.com/eqnedit.php?latex=f(x)&space;=&space;\begin{cases}&space;&x&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\text{&space;if&space;}&space;x>0&space;\\&space;&a(e^x-1)&space;\text{&space;if&space;}&space;x\leq&space;0&space;\end{cases}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?f(x)&space;=&space;\begin{cases}&space;&x&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\&space;\text{&space;if&space;}&space;x>0&space;\\&space;&a(e^x-1)&space;\text{&space;if&space;}&space;x\leq&space;0&space;\end{cases}" title="f(x) = \begin{cases} &x \ \ \ \ \ \ \ \ \ \ \text{ if } x>0 \\ &a(e^x-1) \text{ if } x\leq 0 \end{cases}" /></a>

![elu]
