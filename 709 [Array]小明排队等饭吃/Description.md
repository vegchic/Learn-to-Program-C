# [Array]小明排队等饭吃

# 题目描述
小明在饭堂窗口处排队，队列不长，但偶尔会有人插队。求小明排队到窗口的时间。
# Input
输出有**(3+N)**行。
- 第一行是队列中位于小明前面的人数。
- 第二行是小明前面的人打饭需要花的时间。
- 第三行是插队的人数**N**
- 下面每行是分别是插队的人**插入的位置**以及插队的人的**打饭时间**。

**假设插队的人在一开始就插入队伍中**

**队伍的第一个位置是0**

**输入保证队伍长度和插队人数都不超过100**

# output
输出轮到小明打饭时所过去的时间。
# Sample Input
3

1 2 3

2

0 4

1 3

# Sample Output
13

# Hint
给出的样例输入中，插队结束后，队伍情况为
4 3 1 2 3

**注意：插队的人可能在小明后面，因为小明不一定是队伍最后一个人**