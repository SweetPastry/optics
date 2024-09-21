# 光学绪论, 对 Maxwell 方程组讨论

## 波动方程的导出

先默写一下 Maxwell 方程组镇楼:

$$
\begin{align*}
\nabla \cdot \boldsymbol{D}&={\rho _e}_f,
\\\\
\nabla \cdot \boldsymbol{B}&=\rho _{mf},
\\\\
\nabla \times \boldsymbol{E}&=-\partial _t\boldsymbol{B}-\boldsymbol{J}_{mf},
\\\\
\nabla \times \boldsymbol{H}&=\partial _t\boldsymbol{D}+\boldsymbol{J}_{ef}.
\end{align*}
$$

此处, 我们暂且先谈论自由空间, 接受宇宙里没有磁单极子的假设 (事实), 得到

$$
\begin{align*}
\nabla \cdot \boldsymbol{E}&=0,\tag{1}
\\\\
\nabla \cdot \boldsymbol{H}&=0,\tag{2}
\\\\
\nabla \times \boldsymbol{E}&=-\mu _0\partial _t\boldsymbol{H},\tag{3}
\\\\
\nabla \times \boldsymbol{H}&=\varepsilon _0\partial _t\boldsymbol{E}.\tag{4}
\end{align*}
$$

对 (3) (或者 (4)) 取旋度后代入 (1) 与 (4) (或者 (2) 与 (3)) 得到

$$
\nabla ^2\boldsymbol{E}-\varepsilon _0\mu _0\partial _{t}^{2}\boldsymbol{E}=0,\tag{5}
$$

或者

$$
\nabla ^2\boldsymbol{H}-\varepsilon _0\mu _0\partial _{t}^{2}\boldsymbol{H}=0.\tag{6}
$$

这里的操作用到了

$$
\nabla \times \left( \nabla \times \boldsymbol{F} \right) =\nabla \left( \nabla \cdot \boldsymbol{F} \right) -\nabla ^2\boldsymbol{F},
$$

$$
\nabla \times \partial _t\boldsymbol{F}=\partial _t\nabla \times \boldsymbol{F}.
$$

第一个式子是高等数学的内容, 第二个式子也是高等数学的内容, 严谨地, 学名叫做 Clairaut-Schwartz 定理, 讲的是二阶混合偏导数连续的函数交换求偏导的顺序不影响结果. 或者可以粗暴地把此处这样干的依据归结于函数时空无关.

但不管数学上的依据怎么说, 我们得到了 (5) 与 (6) 两个波动方程, 说明自由空间中电场与磁场相互激励, 形成电磁波传递出去.

## 一种比较重要的特解: 平面波

我们都知道波动方程有很多很多解, 但是这里我们只讨论平面波解, 因为大多数情况下我们研究光线都是准直性比较良好的情况, 而且这个解可讨论的地方也比较多.

> (命题) 平面波解是横波.

在推导出波动方程的时候, 我们不断地把方程相互代入, 这个过程实际上我们丢失了不少信息. 继续盯着波动方程看也无济于事, 所以我们回头看 Maxwell 方程组, 为了获得更多的信息, 我们把方程组在 Descaretes 坐标系中写开成标量的形式:

$$

$$