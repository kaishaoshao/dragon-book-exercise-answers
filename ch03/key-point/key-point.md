# 第3章要点

### 1. 从 NFA、DFA 到正则表达式的转换

http://courses.engr.illinois.edu/cs373/sp2009/lectures/lect_08.pdf

### 2. KMP 及其扩展算法(p87)

参考 matrix 的博文 [KMP算法详解](http://www.matrix67.com/blog/archives/115)。文中提供了例子，比较容易理解。

### 3. 字符串处理算法的效率(p103)

对于每个构造得到的 DFA 状态，我们最多必须构造 4|r| 个新状态

### 4. DFA 模拟中的时间和空间的权衡(p116)

图 3-66 表示的算法

### 5. 最小化一个 DFA 的状态数量（p115）

注意图 3-64 的第 4 行：“状态 s 和 t 在 a 上的转换都到达 Π 中的同一组”，而不是到达同一个状态。如果通过是否到达同一个状态来判定，那么如果 s 和 t 在 a 上的转换到了两个不同但不能区分的状态时，就会认为 s 和 t 是可区分的。