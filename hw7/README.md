# 第七次作业

## 1：与指定数字相同的数的个数

> 总时间限制: 1000ms
>
> 内存限制: 65536kB

### 描述

输出一个整数序列中与指定数字相同的数的个数。

### 输入

输入包含2行：
第1行为N和m，表示整数序列的长度(N <= 100)和指定的数字， 中间用一个空格分开；
第2行为N个整数，整数之间以一个空格分开。

### 输出

输出为N个数中与m相同的数的个数。

### 样例输入

```
3 2
2 3 2
```

### 样例输出

```
2
```

---

## 2：最近点对

> 总时间限制: 1000ms
>
> 内存限制: 65536kB

### 描述

给定一系列二维空间的点坐标，求距离最近的两个点之间的距离的平方。 两点间的距离的平方为(x1-x2)**2+(y1-y2)**2。 (x**y表示x的二次方)

### 输入

第一行 T,表示有T组数据  对于每组数据：  第一行N，表示N个点。 接下来N行，每一行两个整数，表示该点的x,y坐标。

### 输出

对每组数据，输出一个整数，最近点对间的距离的平方。

### 样例输入

```
2
3
1 1
0 0 
2 1
4
1 4
3 5
2 7
9 10
```

### 样例输出

```
1
5
```

来源：金旭统

---

## 3：找第一个只出现一次的字符

> 总时间限制: 1000ms
>
> 内存限制: 65536kB
>

### 描述

给定一个只包含小写字母的字符串，请你找到第一个仅出现一次的字符。如果没有，输出no。

### 输入

一个字符串，长度小于100000。

### 输出

输出第一个仅出现一次的字符，若没有则输出no。

### 样例输入

```
abcabd
```

### 样例输出

```
c
```

---
