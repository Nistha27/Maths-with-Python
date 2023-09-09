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

**Divergence of a Vector**

$\nabla \cdot \mathbf{V}$.

Mathematically, for a three-dimensional vector field $\mathbf{V} = \langle V_x, V_y, V_z \rangle$, the divergence is defined as follows:

$$
\text{div}(\mathbf{V}) = \nabla \cdot \mathbf{V} = \frac{\partial V_x}{\partial x} + \frac{\partial V_y}{\partial y} + \frac{\partial V_z}{\partial z}
$$

Here:

- $\nabla$ (pronounced "del") is the gradient operator, which represents the vector of partial derivatives with respect to the spatial coordinates ($x$, $y$, $z$).
- $\frac{\partial V_x}{\partial x}$, $\frac{\partial V_y}{\partial y}$, and $\frac{\partial V_z}{\partial z}$ are the partial derivatives of the vector field components with respect to their respective coordinates.

The result of the divergence operation is a scalar quantity that indicates whether the vector field at a specific point is a source (positive divergence), a sink (negative divergence), or neither (zero divergence). In physical terms, it helps describe how much of a vector quantity (e.g., fluid flow or electric field) is entering or leaving a small volume surrounding a point.

If the divergence of a vector field is zero at all points in a region, the field is said to be "divergence-free" or "incompressible" in that region. Such vector fields are often encountered in fluid dynamics and electromagnetism.

The concept of divergence plays a significant role in various areas of science and engineering, including fluid mechanics, electromagnetism, and the study of vector fields in general.


## Curl of Vector
The curl of a vector field is a mathematical operation that results in a vector quantity. It describes the rotation or circulation of a vector field at a specific point in space. The curl is often denoted by the symbol ∇× or curl and is applied to a vector field V.


For a three-dimensional vector field $\mathbf{V} = \langle V_x, V_y, V_z \rangle$, the curl is defined as follows:

\
$\text{curl}(\mathbf{V}) = \nabla \times \mathbf{V}$ = $$\begin{vmatrix}
\mathbf{i} & \mathbf{j} & \mathbf{k} \\
\frac{\partial}{\partial x} & \frac{\partial}{\partial y} & \frac{\partial}{\partial z} \\
V_x & V_y & V_z
\end{vmatrix}$$


Here:

- $\nabla$ (pronounced "del") is the gradient operator, which represents the vector of partial derivatives with respect to the spatial coordinates ($x$, $y$, $z$).
- $\mathbf{i}$, $\mathbf{j}$, and $\mathbf{k}$ are the unit vectors along the $x$, $y$, and $z$ axes, respectively.
- $\frac{\partial}{\partial x}$, $\frac{\partial}{\partial y}$, and $\frac{\partial}{\partial z}$ are the partial derivative operators with respect to their respective coordinates.

The result of the curl operation is a vector that points in the direction of the axis of rotation or circulation at a given point and whose magnitude represents the strength of the rotation. In physical terms, it helps describe the circulation of a vector field, such as the flow of a fluid or the rotation of an electromagnetic field.

The curl of a vector field is used in various areas of physics and engineering, including fluid dynamics, electromagnetism (where it plays a crucial role in describing electromagnetic induction and electromagnetic waves), and the study of rotational phenomena in general.

In summary, the curl of a vector field characterizes the local rotation or circulation of that field and provides valuable information about its behavior in three-dimensional space.


## Greens Theoram 

Green's theorem is a fundamental theorem in vector calculus that relates line integrals around a closed curve to double integrals over the plane region enclosed by that curve. It is named after the British mathematician George Green and is a generalization of the two-dimensional version of the Fundamental Theorem of Calculus.

If P (x, y) and Q(x, y) be two continuous functions having continuous partial derivatives in a region R of the xy-plane,
bounded by a simple closed curve C, 
