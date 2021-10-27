## 二次函数 基础
$y = ax^2 + bx + c (a \neq 0) $
### 表达式
三种表现形式
其中 $a \neq 0$

- 一般式: $y = ax^2 + bx + c  $
- 顶点式: $y = a(x-h)^2 + k $
- 分解式: $y = a(x-x_1)(x-x_2) $

三种形式优点
一般式: 知道y轴交点
顶点式: 知道对称轴与顶点
分解式: 知道x轴两个交点


### 配方法
一般式 使用配方法 变换成 顶点式
$$
\begin{align}
y & = ax^2 + bx + c \\
& = a(x^2 + \frac {b} {a}x) + c \\
& = a(x^2 + 2 \frac {b} {2a}x + \frac {b^2} {4a^2})  + c - \frac {b^2} {4a} \\
& = a(x + \frac {b} {2a})^2  + \frac {4ac - b^2} {4a} \\
& (h=-\frac{b} {2a }, k = \frac {4ac - b^2} {4a})\\
& = a(x - h )^2  + k \\
\end{align}
$$

所以
对称轴： $x = - \frac {b} {2a} $
顶点： $( - \frac {b} {2a}, \frac {4ac - b ^2} {4a}) $
### a、b、c作用

#### a
决定开口大小和方向
a > 0 开口向上
a < 0 开口向下
a的绝对值越大，开口越小（二次函数变化速度越快）

#### b
a和b共同决定抛物线对称轴的位置

#### c
决定与y轴的交点。(通俗的来讲，就是决定上下)


### 一般式交点
#### 与y轴的交点
$x = 0$ 时
$y = ax^2 + bx + c = 0 + 0 + c = c$
所以与y轴的交点是(0, c)
#### 与x轴的交点
$y=0$时
$$
\begin{align}
0 & = ax^2 + bx + c \\
0 & = a(x^2 + \frac {b} {a}x) + c \\
0 & = a(x^2 + 2 \frac {b} {2a}x + \frac {b^2} {4a^2})  + c - \frac {b^2} {4a} \\
a(x + \frac {b} {2a})^2 & = \frac {b^2 - 4ac} {4a} \\
(x + \frac {b} {2a})^2 & = \frac {b^2 - 4ac} {4a^2} \\
当b^2 - 4ac >=0 时&，有\\
x + \frac {b} {2a} & = \pm \frac {\sqrt {b^2 - 4ac}} {2a} \\
x  & = \frac {-b \pm \sqrt {b^2 - 4ac}} {2a} \\
\end{align}
$$

故当判别式$\Delta = b^2 - 4ac > 0$ 时
二次函数和x轴有两个交点，分别为
$(\frac {-b - \sqrt {b^2 - 4ac}} {2a}, 0)$、$(\frac {-b + \sqrt {b^2 - 4ac}} {2a}, 0)$

故当判别式$\Delta = b^2 - 4ac = 0$ 时
二次函数和x轴有一个交点，为
$(\frac {-b} {2a}, 0)$
