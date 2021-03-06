# Neural Network From Scratch

> <h2>Python Libraries Requirements</h2>

```javascript
pip install -r requirements.txt
```

---

## <h1>**How Neural Networks Work?**</h1>

_Steps to be followed for creating any neural network:-_

1. Forward Propagation
2. Calculating Loss
3. Back Propagation

<p align="center">

<img src="https://www.researchgate.net/publication/329216193/figure/fig3/AS:697582816870406@1543328112943/Architecture-of-multilayer-artificial-neural-network-with-error-backpropagation.png" width="350">

## </p>

 ## <h1>Forward Propagation</h1>

<p align="center">
  
![Formula](https://latex.codecogs.com/png.latex?%5Cdpi%7B100%7D%20%5Cfn_phv%20%5Clarge%20Z%5E%7B%5Bl%5D%7D_%7Bj%7D%20%3D%20%5Csum%5E%7Bi%3Dn%7D_%7Bi%7D%20W%5E%7B%5Bl%5D%7D_%7Bi%2Cj%7DA%5E%7B%5Bl-1%5D%7D_%7Bi%7D%20+%20bias)

## </p>

**\*W** = Weights, **A** = Activation Function\*

## Activation Functions

_Some most used activation functions are as follows:-_

- **ReLu**
- **Sigmoid**
- **TanH**
- **softmax**

---
 ## Loss Functions

_Some most used Loss functions are as follows:-_

- **mean_squared_error**
- **crossentropy**
- **Hinge**

---

 ## Back Propagation

<p align="center">
  
![Backprop](http://neuralnetworksanddeeplearning.com/images/tikz21.png)

![Weight](http://hmkcode.github.io/images/ai/bp_update_formula.png)
## </p>

