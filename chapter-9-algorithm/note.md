# 九章算法

#### 最长回文串(Longest Palindromic Substring)

[lettcode 5](https://leetcode.cn/problems/longest-palindromic-substring/description/) <br/>

子串(sub-string)和子序列(sub-sequence)区别: <br/>
abcd <br/>
子串必须要是连续取的 bc O(2^n) <br/>
子序列可以跳着取比如 ac O(n^2)<br/>

判断一个字符串是否是回文串 <br/>
abca <br/>
L&nbsp;&nbsp;&nbsp;&nbsp;R <br/>
L-><-R<br/>
双指针算法(同向双指针) O(n)<br/>

暴力枚举复杂度 O(n^3) <br/>

Manacher's Algorithm(马拉车算法)O(n):<br/>
