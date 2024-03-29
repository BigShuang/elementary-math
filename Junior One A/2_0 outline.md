## 第二章 整式的加减
### 1 整式
**用字母表示数或数量关系**
用字母表示数，字母和数一样可以参与运算，可以用式子把数量关系简明的表示出来。

优点：形式简单，具有一般性。

书写要求
- 字母相乘，乘号省略或用`·`, 除法写成分数形式。
- 数字与字母相乘时，数字通常写在字母前面
- 相除时，要写成分数形式
- 带分数要化成假分数

举例如下
$$
a \times b \;要写成 \; a \cdot b \;  或 \; ab \\
x \times 3 \;要写成 \;3x \\
x \div 3 要写成 \frac x 3 \;,\quad s \div v 要写成 \frac s v \\
3 \frac 1 3 \times x \;要写成\; \frac {10} 3 x
$$

#### 单项式
**数或字母的乘积**组成的式子为单项式。

相关概念:
- 单项式中的数字因数叫做这个单项式的**系数**，
- 所有字母的指数的和叫做这个单项式的**次数**

详细解读:
- 数和字母相乘时，数写前面
- 单独一个数或一个字母也是单项式
- 单项式中不能含加减运算
- 系数为1或-1时，可省略

举例
$$
\frac 1 2 m^2n^3 是单项式，系数为\frac 1 2, 次数为5\\
a^2bc^3 是单项式，系数为1, 次数为6
$$

补充：
$$
圆周率\pi是一个常数，算数字而非字母。\\
单项式必须是数或字母的乘积，\\
\frac x 3 是单项式，可以看作分数\frac 1 3和x 的积；\\
\frac 3 x 不是单项式，它无法看作数与字母的乘积。\\
$$

#### 多项式
**多个单项式的和**叫做多项式

相关概念:
- 每个单项式叫做多项式的**项**
- 不含字母的项叫做**常数项**
- 次数最高项的次数，叫做这个多项式的**次数**
- 根据最高次数和项数，可以确定多项式为几次几项式

详细解读:
- 多项式的每一项搜必须是单项式
- 多项式中的减号，要理解成加上负的。
  （减一个数等于加上这个数的相反数）
- 常数项的次数为0

举例说明
$$
多项式 \quad -\frac 3 4 x^3y^2 - \frac 1 2 x^2y - x + 1 \quad 可以看作 \\
(-\frac 3 4 x^3y^2) + (-\frac 1 2 x^2y) + (-x) + 1 \\
该多项式总共有4项\\
分别是\;-\frac 3 4 x^3y^2\;, \;-\frac 1 2 x^2y\;,\;-x\;,\;1\\
-\frac 3 4 x^3y^2 \; 的系数是 -\frac 3 4, 次数是5\\
-\frac 1 2 x^2y \; 的系数是 -\frac 1 2, 次数是3\\
-x \; 的系数是 - 1, 次数是1\\
1 是常数项 \\
最高次数为5 ， 所以原多项式为5次4项式\\
$$

补充示例
$$
\frac {1+a} 5 是多项式，不是单项式\\
因为\; \frac {1+a} 5 \; 可以看作 \;  \frac 1 5 + \frac a 5\\
\frac 2 {x-y} 不是多项式，也不是单项式
$$

#### 整式
**单项式与多项式统称整式**

解读：
整式可以分为单项式和多项式。
一个整式，要么是单项式，要么就是多项式。

**整式的值**
用具体的数值代替整式里的字母，并按照整式中指明的运算顺序计算出的结果，叫做**整式的值**。

例题
$$
\begin{aligned}
求多项式 & xy^2+8x^2-2的值, 其中x=\frac 1 2 , y = -1\\
解: 当 &x = \frac 1 2 ,y = -1时\\
&xy^2+8x^2-2 \\
=&  \frac 1 2 \times (-1)^2 + 8 \times (\frac 1 2)^2 - 2 \\
=& \frac 1 2 + 8 \times \frac 1 4 - 2 \\
=& \frac 1 2
\end{aligned}
$$

### 2 整式的加减
#### 同类项
所含字母相同，相同字母的次数也相同的项，叫做**同类项**

解读
- 判断方法：字母相同，每个字母的次数相同
- 系数和字母的顺序不影响
  （前提是系数不为0）

举例
$$
-2a^2 b^3\;和\;3b^3a^2\;是同类项\\
因为都含字母a和b\\
a的次数都是2，b的次数都是3\\
系数不同和字母顺序不同,并不影响
$$

#### 合并同类项
把多项式中的同类项合并成一项，叫做**合并同类项**。

同类项合并规则：
- 系数相加
- 字母和其指数不变

具体步骤：
1. 找出同类项
2. 把同类项放一起
  根据加法交换律和结合率
3. 按规则合并

举例
$$
\begin{aligned}
\quad &2x^2-3x+4x^2-6x-5\\
= \; & (2x^2 + 4x^2) + (-3x -6x) -5\\
= \; & (2 + 4)x^2 + (-3 -6)x -5\\
= \; & 6x^2 -9x -5\\
\end{aligned}
$$
$$
\begin{aligned}
\quad & -2a^2b + 3a^2b - 3ab^2 - 5ab^2\\
= \; & (-2 + 3)a^2b + (-3-5)ab^2 \\
= \; & a^2b - 8ab^2
\end{aligned}
$$
#### 去括号
规则
- 如果括号外的因数是正数，去括号后，符号不变
- 如果括号外的因数是负数，去括号后，符号变成相反的

举例

$$
\begin{aligned}
&\; 5a - (2a-4b)\\
= &\; 5a - 2a + 4b \\
= &\; 3a + 4b \\
\end{aligned}
$$
$$
\begin{aligned}
&\; 2x^2 + 3(2x-x^2)\\
= &\; 2x^2 + 6x -3x^2 \\
= &\; -x^2 + 6x \\
\end{aligned}
$$

#### 整式加减的运算法则
整式加减的运算规则：
先去括号，再合并同类项

整式求值的过程
1. 化简
   通过加减运算
2. 代入
3. 计算

举例
$$
\begin{aligned}
&\; 先化简，后求值：\\
&\; \frac 1 3 x^2 - 3(x^2+xy-\frac 1 5 y^2) + (\frac 8 3 x^2 + 3xy + \frac 2 5 y^2)\\
&\; 其中  \; x=-\frac 1 2, y = -2 .\\
解: &\; \frac 1 3 x^2 - 3(x^2+xy-\frac 1 5 y^2) + (\frac 8 3 x^2 + 3xy + \frac 2 5 y^2) \\
= &\; \frac 1 3 x^2 - 3x^2-3xy + \frac 3 5 y^2 + \frac 8 3 x^2 + 3xy + \frac 2 5 y^2\\
= &\; \frac 1 3 x^2  - 3x^2 + \frac 8 3 x^2 -3xy  + 3xy  + \frac 3 5 y^2 + \frac 2 5 y^2\\
= &\; (\frac 1 3 - 3 + \frac 8 3) x^2 + (-3 + 3)xy  + (\frac 3 5+ \frac 2 5) y^2\\
= &\; y^2\\
当 &\; x=-\frac 1 2, y = -2 时, \\
原式 = &\; (-2)^2 = 4
\end{aligned}
$$
