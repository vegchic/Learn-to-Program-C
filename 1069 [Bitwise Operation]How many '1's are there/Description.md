# [Bitwise Operation]How many '1's are there

# How many '1's are there

## Problem

第一行输入数字n（n<=50)，表示有n组测试用例，第2到第n+1行每行输入数m（m为整数），统计并输出m用二进制表示时，1的个数。

例如：m=9时，二进制表示为1001，则输出2.

### Sample Input

```
2
3
7

```

### Sample Output

```
2
3

```

## Hint

利用位运算

回忆软导课程关于**位**的内容

位运算符
+ `>>` 右移 如`1 >> 1`会将`1`右移一位，变成`0`
+ `<<` 左移 如`1 << 2`会将`1`左移一位，变成`2`
+ `>>=`
+ `<<=`
+ `&` 与
+ `|` 或
+ `^` 异或
+ `~` 按位取非(与`!`区分)

> 本题搬运自原eden
