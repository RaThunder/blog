## 数学

**从零开始攻略高数的生活**

* 映射：映射的对映，包含关系，还有满射、单射、一一映射，变换形成的逆映射（类似反函数？），复合映射
* 从映射引出函数，符号函数

$$
y=sgnx
\begin{cases}
1,x>0 \\
0,x=0 \\
-1.x<0 \\
\end{cases}
$$

**从零开始攻略线代的生活**

* 二阶行列式：

$$
\begin{vmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{vmatrix} = a_{11}a_{22} - a_{12}a_{21}
$$

* 克莱姆法则推二元线性方程：

$$
\begin{cases}
a_{11}x_1 + a_{12}x_2 = b_1 \\
a_{21}x_1 + a_{22}x_2 = b_2 \\
\end{cases}
$$

$$
x = \frac{
\begin{vmatrix}
b_1 & a_{12} \\
b_2 & a_{22}
\end{vmatrix}
}{
\begin{vmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{vmatrix}
}
,\quad
y = \frac{
\begin{vmatrix}
a_{11} & b_1 \\
a_{21} & b_2
\end{vmatrix}
}{
\begin{vmatrix}
a_{11} & a_{12} \\
a_{21} & a_{22}
\end{vmatrix}
}
$$

（底层为四个系数， $b_1$ , $b_2$ 写到 $D_x$ 左边 , $D_y$ 右边，然后 $D_x$ , $D_y$其他数与 $D$ 的同位置相同）

* 三阶行列式：

$$
\begin{vmatrix}
a_{11} & a_{12} & a_{13} \\
a_{21} & a_{22} & a_{23} \\
a_{31} & a_{32} & a_{33}
\end{vmatrix} = a_{11}a_{22}a_{33} + a_{12}a_{23}a_{31} + a_{13}a_{21}a_{32} - a_{13}a_{22}a_{31} - a_{11}a_{23}a_{32} - a_{12}a_{21}a_{33}
$$

(主对角线方向为加，副对角线方向为减)

* 三角行列式：

上三角行列式

$$
\begin{vmatrix}
a_{11} & a_{12} & \cdots & a_{1n} \\
0 & a_{22} & \cdots & a_{2n} \\
\vdots & \vdots & \ddots & \vdots \\
0 & 0 & \cdots & a_{nn}
\end{vmatrix} = a_{11} a_{22} \cdots a_{nn}
$$

下三角行列式

$$
\begin{vmatrix}
a_{11} & 0 & \cdots & 0 \\
\vdots & a_{22} & \cdots & 0 \\
\vdots & \vdots & \ddots & 0 \\
a_{n1} & a_{n2} & \cdots & a_{nn}
\end{vmatrix} = a_{11} a_{22} \cdots a_{nn}
$$

对角行列式

$$
\begin{vmatrix}
a_{11} & 0 & \cdots & 0 \\
0 & a_{22} & \cdots & 0 \\
\vdots & \vdots & \ddots & 0 \\
0 & 0 & \cdots & a_{nn}
\end{vmatrix}
= a_{11} a_{22} \cdots a_{nn}
$$
