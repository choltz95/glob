# glob
Global optimization of Lipschitz functions

The authors provide theoretical bounds for a gradient and parameter-free global optimizer. They propose a very simple algorithm called LIPO to jointly approximate the Lipschitz constant of a function and learn a piecewise linear upperbound based on the approximated constant.

They derive several nice theoretical properties, but the most important one in my opinion is that their algorithm is superior to random search in several cases. They also empirically demonstrate that their algorithm performs comparably to other popular black box optimizers like Baysian Optimization.
