# 两个重要极限
$$\lim _{x\rightarrow0} {\frac{\sin x}{x}}=1$$
$$\lim _{x\rightarrow\infty}{(1+\frac{1}{x})}^{x}=e$$
# 几个常用等价无穷小
$$\sin x\sim x$$
$$\tan x\sim x$$
$$\arcsin x\sim x$$
$$\arctan x\sim x$$
$$\ln(1+x)\sim x$$
$$e^x-1\sim x$$
$$1-\cos x\sim \frac{1}{2}x^2$$
$$(1+x)^\alpha-1\sim \alpha x$$
$$\sqrt[n]{1+x}-1\sim \frac{1}{n}x$$
```cpp
#include<iostream>
using namespace std;
int main()
{
    cout<<"Hello, world!"<<endl;
    return 0;
}
```
# 矩阵
## 单位矩阵
$$E=\begin{pmatrix}
1 & 0 \\
0 & 1 \\
\end{pmatrix}
$$
## 一般矩阵
$$A=\begin{pmatrix}
a_{11} & a_{12} & \cdots & a_{1n}\\
a_{21} & a_{22} & \cdots & a_{2n}\\
\vdots & \vdots & \ddots & \vdots\\
a_{1m} & a_{2m} & \cdots & a_{mn}
\end{pmatrix}
$$
# 行列式
$$D=\begin{vmatrix}
1 & 2 & 3\\
4 & 5 & 6\\
7 & 8 & 9\\
\end{vmatrix}
$$