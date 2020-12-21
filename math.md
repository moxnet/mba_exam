

# 一,代数

==待补充==



# 二, 数列

## 1. 数列

普通数列前N项和:

$S_n=a_1+a_2+…+a_n=\sum_{i=1}^nx_i$

普通数列通项:

$a_n=\begin{cases}S_1, n=1\\S_n-S_{n-1}, n≥2\end{cases}$

## 2. 等差数列

### 1. 定义

数列$\{a_n\}$为等差数列 $\Leftrightarrow a_n-a_{n-1}=d$

### 2. 通项公式

$a_n=a_1+(n-1)d=a_m+(n-m)d (n≥m)$

$\displaystyle d=\frac{a_n-a_m}{n-m}, (n≠m)$

### 3. 求和公式

$\displaystyle S_n=\frac{a_1+a_n}{2}n=\frac{d}{2}n^2+(a_1-\frac{d}{2}n)$

(==重要==:求和公式为n的二次函数,且无常数项,则可断定为等差数列)

当 $n=-\frac{a_1-d/2}{2d/2}=\frac{1}{2}-\frac{a_1}{d}$ 时，$S_n$ 取极值。（这个如果记不住，可根据上式现推）

<img src="/Users/moxnet/Desktop/math-02-sn-chart.png" alt="math-02-sn-chart" style="zoom:33%;" />



### 4. 等差中项

$\displaystyle \{a,b,c\}\mbox{为等差数列} \Leftrightarrow 2b=a+c \Leftrightarrow b=\frac{a+c}{2}$

即,如果 $a,b,c$ 为等差数列,则 $2b=a+c$，反之也成立,即如果 $2b=a+c$ 则 $ a,b,c$成等差数列。

### 5. 性质

* 当 $m+n=p+q$ 时，$a_m+a_n=a_p+a_q$
    同时，$S_n=\frac{(a_1+a_n)}{2}n=\frac{(a_2+a_{n-1})}{2}n=…$

* $S_n, S_{2n}-S_n, S_{3n}-S_{2n},…$ 仍为等差数列，公差为 $n^2d$

* 通项比与和之比关系
    若$\{a_n\}$与$\{b_n\}$为等差数列，前n项和分别为$S_n, T_n$，则
    $$
    \displaystyle \frac{a_n}{b_n}=\frac{S_{2n-1}}{T_{2n-1}}
    $$
    即，前n项和(n为奇数)之比，等于中间项之比

* 若 $a_n=m, a_m=n$，则 $a_{m+n}=0$

* 若 $S_m=S_n(m≠n)$，则 $S_{m+n}=0$
    （由根据二次函数图象辅助理解。$S_n=S_n$ 是两个y值相等，如(3)中的图像，若$S_1=S_7$，则7+1=8，正好 m+n 为一个二次函数的0值点）

* 若 $S_n=m, S_m=n$，则 $S_{m+n}=-(m+n)$

* 设 $S_\mbox{奇}=a_1+a_3+a_5+…$，$S_\mbox{偶}=a_2+a_4+…$，则：

    * 若数列共有$2n$项，则有 $S_\mbox{奇}-S_\mbox{偶}=nd$

    * 若数列共有$2n+1$项，则有 $S_\mbox{偶}-S_\mbox{奇}=a_{n+1}$ (即中间项)
        同时，
        $$
        \displaystyle \frac{S_\mbox{偶}}{S_\mbox{奇}}=\frac{n}{n+1}
        $$
        

## 3. 等比数列

### 1. 定义

如果数列 $\{a_n\}$ 满足 $\frac{a_{n+1}}{a_n}=q (q\mbox{为常数})$ ，则称 $\{a_n\}$ 为等比数列

### 2. 通项公式

$a_n=a_1q^{n-1}$

$a_n=a_mq^{n-m} (n>m)$

### 3. 求和公式

* 求和公式

$$
\displaystyle S_n=\begin{cases}a_1   (n=1)\\
\frac{a_1(1-q^{n})}{1-q}=\frac{a_1-a_nq}{1-q} (n≠1)
\end{cases}
$$

* 当 $|q|<1$，且 $n \rightarrow +∞$ 时，
    $$
    S_n=\lim_{n\to∞}{S_n}=\lim_{n\to∞}\frac{a_1(1-q^n)}{1-q}=\frac{a_1}{1-q}
    $$

### 4. 性质

* 当 $m+n=p+q$时，$a_ma_n=a_pa_q$
* $S_n, S_{2n}-S_n, S_{3n}-S_{2n},…$ 也为等比数列，公比为 $q^n$



## 4. 去年(2020)真题选

1. (2020-5) 等差数列 $\{a_n\}$ 满足 $a_1=8$，且 $a_2+a_4=a_1$，则 $\{a_n\}$ 前n项和最大值为 ：
    A.16    B.17   C.18   D.19   E.20
    (此题难度偏容易。根据两个等量关系，可求得 $a_1,d$ ，可直接写出前面有数的大于0的几项，相加即可)、
2. (2020-11) 已知数列 $\{a_n\}$ 满足 $a_1=1, a_2=2$，且 $a_{n+2}=a_{n+1}-a_n(n=1,2,3,…)$，则 $a_{100}$=(   )
    A.1.   B.-1.   C.2    D.-2    E.0
    (此题难度偏容易。根据前2项，及给出的推导公式，写出几项，可观察出数列规律。根据规律，可知第100项与前某项相等，可知答案)

# 三, 几何及立体几何

## 1. 几种平面图形公式

* 三角形：
    $S=\frac{1}{2}ah=\frac{1}{2}absinC=\sqrt{p(p-a)(p-b)(p-c)}=pr$     (其中 $p=\frac{a+b+c}{2}$，即周长的一半)

* 四边形
    $S=\frac{1}{2}ah$
    $S_1{\times}S_2=S_3{\times}S_4$  （如下图，对任意四边形，画对角线，两对相对三角形的面积的积相同）

    ![math-03-q](/Users/moxnet/Desktop/math-03-q.jpeg)

* 棱形
    $S=\frac{1}{2}ah=\frac{1}{2}cd$    (其中 $a,h$为底和高，$c,d$为两条对角线)

* 圆相关($r$ 为半径)

    * 圆
        $S={\pi}r^2$
        $l=2{\pi}r={\pi}d$      (其中, $l$为周长，$d$为直径)
    * 扇形
        $S=\frac{1}{2}lr=\frac{1}{2}{\theta}r^2$    (其中, $l$为弧长, $\theta$ 为扇形弧度)
        $l={\theta}r$    (其中, $\theta$为扇形弧度角，$l$为弧长)

* 梯形
    $S=\frac{1}{2}(a+b)h$   (其中，$a,b$分别为上底和下底，$h$为高)
    $S_1{\times}S_2=S_3{\times}S_4=(S_3)^2=(S_4)^2$  (即$S_3=S_4$)     (如下图)

    ![math-03-q](/Users/moxnet/Desktop/math-03-q.jpeg)

## 2. 几个特殊角的三角函数值

|                      | sin                | con                | tan                | cot                |
| -------------------- | ------------------ | ------------------ | ------------------ | ------------------ |
| $30˚(\frac{\pi}{6})$ | $\frac{1}{2}$      | $\frac{\sqrt3}{2}$ | $\frac{\sqrt3}{3}$ | $\sqrt3$           |
| $45˚(\frac{\pi}{4})$ | $\frac{\sqrt2}{2}$ | $\frac{\sqrt2}{2}$ | 1                  | 1                  |
| $60˚(\frac{\pi}{3})$ | $\frac{\sqrt3}{2}$ | $\frac{1}{2}$      | $\sqrt3$           | $\frac{\sqrt3}{3}$ |

==待补充==

# 四, 排列,组合,概率

==待补充==

