# LAB - 01
##  Gradient of a Vector 
The gradient of a vector is a mathematical concept that represents a vector containing the partial derivatives of a multivariable function with respect to each of its input variables. In other words, it quantifies how the function changes as you move in different directions in its input space.

$$
\begin{bmatrix}
  \frac{\partial f_1}{\partial x_1} & \frac{\partial f_1}{\partial x_2} & \cdots & \frac{\partial f_1}{\partial x_n} \\
  \frac{\partial f_2}{\partial x_1} & \frac{\partial f_2}{\partial x_2} & \cdots & \frac{\partial f_2}{\partial x_n} \\
  \vdots & \vdots & \ddots & \vdots \\
  \frac{\partial f_m}{\partial x_1} & \frac{\partial f_m}{\partial x_2} & \cdots & \frac{\partial f_m}{\partial x_n} \\
\end{bmatrix}
$$

$f(x)$ is a vector-valued function with $m$ components ($f_1, f_2, \ldots, f_m$).

$\mathbf{x}$ is a vector of $n$ input variables ($x_1, x_2, \ldots, x_n$).

$\frac{\partial f_i}{\partial x_j}$ represents the partial derivative of the $i$-th component of $f$ with respect to the $j$-th input variable.

The result is a matrix where each row corresponds to the gradient (vector of partial derivatives) of one component of $f$ with respect to all input variables.

The gradient is a fundamental concept in calculus and is widely used in various fields, especially in optimization, machine learning, and physics, where it helps determine how to update parameters or variables to minimize or maximize a given function.

For scalar-valued functions (where $f(x)$ returns a single value), the gradient simplifies to the gradient of a scalar function, which is a vector containing the partial derivatives of that function with respect to each input variable.


## Divergence of Vector
The divergence of a vector field is a mathematical operation that represents a scalar quantity. It provides a measure of the rate at which the vector field's vectors spread out or converge at a given point in space. The divergence is often denoted by the symbol ∇· or div and is applied to a vector field V.

## Curl of Vector
The curl of a vector field is a mathematical operation that results in a vector quantity. It describes the rotation or circulation of a vector field at a specific point in space. The curl is often denoted by the symbol ∇× or curl and is applied to a vector field V.

## Greens Theoram 

Green's theorem is a fundamental theorem in vector calculus that relates line integrals around a closed curve to double integrals over the plane region enclosed by that curve. It is named after the British mathematician George Green and is a generalization of the two-dimensional version of the Fundamental Theorem of Calculus.

If P (x, y) and Q(x, y) be two continuous functions having continuous partial derivatives in a region R of the xy-plane,
bounded by a simple closed curve C, 
