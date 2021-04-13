## MNIST_MLP
**Design and implementation of a Multi Layer Perceptron (MLP).**

---

Generally, in the ML world, a feedforward neural network architecture is referred to as a Multi-layer perceptron (MLP) it is mainly composed of an input layer associated with one or more hidden and output layers
A closer look at a specific hidden or output layer shows the computation process operated once the input is received from the previous layer. it appears in the figure below that, the node computes the weighted sum of the received input following by the application of the non-linear activation function over the weighted sum and finally passes the result to the next connected node. The iteration of this process over the entire network results in the final output.

![NN](https://user-images.githubusercontent.com/52790721/114578496-833db000-9caf-11eb-8750-2a7596701681.jpg)

The basic transformation that takes place between layers, is simply a change of one vector space to another. The following formula results in a dot product of vectors on n inputs. 
![first equation](https://latex.codecogs.com/gif.latex?z%3Df%28b&plus;x%5Ccenterdot%20w%29%3Df%28b&plus;%5Csum%5Climits_%7Bi%3D1%7D%5E%7Bn%7D%7B%28%7B%7Bx%7D_%7Bi%7D%7D%7B%7Bw%7D_%7Bi%7D%7D%29%7D%29%3B%5C%7Bx%5Cin%20%7B%7Bd%7D_%7B%281*n%29%7D%7D%2Cw%5Cin%20%7B%7Bd%7D_%7B%28n*1%29%7D%7D%2Cb%5Cin%20%7B%7Bd%7D_%7B%281*1%29%7D%7D%2Cz%5Cin%20%7B%7Bd%7D_%7B%281*1%29%7D%7D%5C%7D%5C)

The implementation of the multi-layer perceptron that classifies the MNIST handwritten digit and Fashion MNIST dataset is explained in the python notebook.
>For further information about multilayer perceptron networks, please read [Link](https://en.wikipedia.org/wiki/Multilayer_perceptron "Multilayer_perceptron ")

---
**Implementation results**

![2](https://user-images.githubusercontent.com/52790721/114577459-97cd7880-9cae-11eb-9cfd-17617493022d.PNG)
![1](https://user-images.githubusercontent.com/52790721/114577840-f5fa5b80-9cae-11eb-9dfd-06a5ce8c244e.png)
---
