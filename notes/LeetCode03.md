<!-- TOC -->

- [动态规划和贪心算法的区别](#动态规划和贪心算法的区别)
- [[@@@@72. 编辑距离](https://leetcode-cn.com/problems/edit-distance/)](#72-编辑距离httpsleetcode-cncomproblemsedit-distance)
- [[@1143. 最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/)](#1143-最长公共子序列httpsleetcode-cncomproblemslongest-common-subsequence)
- [@删除最少字符变成回文串](#删除最少字符变成回文串)
- [[@@647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings/)(数量)](#647-回文子串httpsleetcode-cncomproblemspalindromic-substrings数量)
- [[@@5. 最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/)(长度)](#5-最长回文子串httpsleetcode-cncomproblemslongest-palindromic-substring长度)
- [用少来表示多](#用少来表示多)
- [@[253. 会议室 II](https://leetcode-cn.com/problems/meeting-rooms-ii/)](#253-会议室-iihttpsleetcode-cncomproblemsmeeting-rooms-ii)
- [@@@[435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/)](#435-无重叠区间httpsleetcode-cncomproblemsnon-overlapping-intervals)
- [[@@@@@452. 用最少数量的箭引爆气球](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/)](#452-用最少数量的箭引爆气球httpsleetcode-cncomproblemsminimum-number-of-arrows-to-burst-balloons)
- [[443. 压缩字符串](https://leetcode-cn.com/problems/string-compression/)](#443-压缩字符串httpsleetcode-cncomproblemsstring-compression)
- [@@@[43. 字符串相乘](https://leetcode-cn.com/problems/multiply-strings/)](#43-字符串相乘httpsleetcode-cncomproblemsmultiply-strings)
- [字符移位](#字符移位)
- [[295. 数据流的中位数](https://leetcode-cn.com/problems/find-median-from-data-stream/)](#295-数据流的中位数httpsleetcode-cncomproblemsfind-median-from-data-stream)
- [@@@@图的m着色问题(dfs)](#图的m着色问题dfs)
- [](#)
- [100亿数字排序,求中位数,平均数,求和](#100亿数字排序求中位数平均数求和)
    - [方法1](#方法1)
    - [方法2:](#方法2)
    - [思维拓展](#思维拓展)
- [[113. 路径总和 II](https://leetcode-cn.com/problems/path-sum-ii/)](#113-路径总和-iihttpsleetcode-cncomproblemspath-sum-ii)
- [[@@@547. 朋友圈](https://leetcode-cn.com/problems/friend-circles/)](#547-朋友圈httpsleetcode-cncomproblemsfriend-circles)
- [[@@@200. 岛屿数量](https://leetcode-cn.com/problems/number-of-islands/)](#200-岛屿数量httpsleetcode-cncomproblemsnumber-of-islands)
- [[@@@1319. 连通网络的操作次数](https://leetcode-cn.com/problems/number-of-operations-to-make-network-connected/)](#1319-连通网络的操作次数httpsleetcode-cncomproblemsnumber-of-operations-to-make-network-connected)
- [找到二叉搜索树中与target之差的绝对值最小的node](#找到二叉搜索树中与target之差的绝对值最小的node)
- [@@@@二叉树的非递归后序遍历](#二叉树的非递归后序遍历)
- [@@@有序数组重建平衡二叉树](#有序数组重建平衡二叉树)
- [一个数组里找任意两个数之和的绝对值最小值](#一个数组里找任意两个数之和的绝对值最小值)
- [一个整数数组找任意两数的最小差](#一个整数数组找任意两数的最小差)
- [[@@208. 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree/)](#208-实现-trie-前缀树httpsleetcode-cncomproblemsimplement-trie-prefix-tree)
- [[@209. 长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum/)](#209-长度最小的子数组httpsleetcode-cncomproblemsminimum-size-subarray-sum)
- [[@@60. 第k个排列](https://leetcode-cn.com/problems/permutation-sequence/)](#60-第k个排列httpsleetcode-cncomproblemspermutation-sequence)
- [[@@@@162. 寻找峰值](https://leetcode-cn.com/problems/find-peak-element/)](#162-寻找峰值httpsleetcode-cncomproblemsfind-peak-element)
- [[@@@@127. 单词接龙](https://leetcode-cn.com/problems/word-ladder/)](#127-单词接龙httpsleetcode-cncomproblemsword-ladder)
- [IP重复攻击](#ip重复攻击)
- [ab替换成c,b替换成ef](#ab替换成cb替换成ef)
- [[@@@4. 寻找两个有序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/)](#4-寻找两个有序数组的中位数httpsleetcode-cncomproblemsmedian-of-two-sorted-arrays)
- [[@@@@@701. 二叉搜索树中的插入操作](https://leetcode-cn.com/problems/insert-into-a-binary-search-tree/)](#701-二叉搜索树中的插入操作httpsleetcode-cncomproblemsinsert-into-a-binary-search-tree)
- [[@@@@@@@@@@450. 删除二叉搜索树中的节点](https://leetcode-cn.com/problems/delete-node-in-a-bst/)](#450-删除二叉搜索树中的节点httpsleetcode-cncomproblemsdelete-node-in-a-bst)
- [[654. 最大二叉树](https://leetcode-cn.com/problems/maximum-binary-tree/)](#654-最大二叉树httpsleetcode-cncomproblemsmaximum-binary-tree)
- [[@@@273. 整数转换英文表示](https://leetcode-cn.com/problems/integer-to-english-words/)](#273-整数转换英文表示httpsleetcode-cncomproblemsinteger-to-english-words)
- [[272. 最接近的二叉搜索树值 II](https://leetcode-cn.com/problems/closest-binary-search-tree-value-ii/)](#272-最接近的二叉搜索树值-iihttpsleetcode-cncomproblemsclosest-binary-search-tree-value-ii)
- [@@@**拓扑排序**](#拓扑排序)
- [[@@210. 课程表 II](https://leetcode-cn.com/problems/course-schedule-ii/)](#210-课程表-iihttpsleetcode-cncomproblemscourse-schedule-ii)
- [[@207. 课程表](https://leetcode-cn.com/problems/course-schedule/)](#207-课程表httpsleetcode-cncomproblemscourse-schedule)
- [[@leetcode.298 二叉树的最长连续子序列](https://blog.csdn.net/jmspan/article/details/51171217)](#leetcode298-二叉树的最长连续子序列httpsblogcsdnnetjmspanarticledetails51171217)
- [[@@面试题51. 数组中的逆序对](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/)](#面试题51-数组中的逆序对httpsleetcode-cncomproblemsshu-zu-zhong-de-ni-xu-dui-lcof)
- [[@@63. 不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii/)](#63-不同路径-iihttpsleetcode-cncomproblemsunique-paths-ii)
- [[单位圆能框住的最多节点数](https://blog.csdn.net/Ramay7/article/details/51147778)](#单位圆能框住的最多节点数httpsblogcsdnnetramay7articledetails51147778)
- [[@@@四种操作求A的最大次数](https://blog.csdn.net/qq_40147449/article/details/93376889)](#四种操作求a的最大次数httpsblogcsdnnetqq_40147449articledetails93376889)
- [点集旋转](#点集旋转)
- [[@@面试题 16.06. 最小差](https://leetcode-cn.com/problems/smallest-difference-lcci/)](#面试题-1606-最小差httpsleetcode-cncomproblemssmallest-difference-lcci)
- [[@670. 最大交换](https://leetcode-cn.com/problems/maximum-swap/)](#670-最大交换httpsleetcode-cncomproblemsmaximum-swap)
- [[@@@@50. Pow(x, n)](https://leetcode-cn.com/problems/powx-n/)](#50-powx-nhttpsleetcode-cncomproblemspowx-n)
- [[@@89. 格雷编码](https://leetcode-cn.com/problems/gray-code/)](#89-格雷编码httpsleetcode-cncomproblemsgray-code)
- [[@53. 最大子序和](https://leetcode-cn.com/problems/maximum-subarray/)](#53-最大子序和httpsleetcode-cncomproblemsmaximum-subarray)
- [单例模式](#单例模式)
- [[@@@@@752. 打开转盘锁](https://leetcode-cn.com/problems/open-the-lock/)](#752-打开转盘锁httpsleetcode-cncomproblemsopen-the-lock)
- [[掷骰子的数学期望](https://www.zhihu.com/question/30470526)](#掷骰子的数学期望httpswwwzhihucomquestion30470526)
- [[915. 分割数组](https://leetcode-cn.com/problems/partition-array-into-disjoint-intervals/)](#915-分割数组httpsleetcode-cncomproblemspartition-array-into-disjoint-intervals)
- [[@@@@991. 坏了的计算器](https://leetcode-cn.com/problems/broken-calculator/)](#991-坏了的计算器httpsleetcode-cncomproblemsbroken-calculator)
- [[@@@@@227. 基本计算器 II](https://leetcode-cn.com/problems/basic-calculator-ii/)](#227-基本计算器-iihttpsleetcode-cncomproblemsbasic-calculator-ii)
- [[@@删除回文子序列](https://leetcode-cn.com/problems/remove-palindromic-subsequences/)](#删除回文子序列httpsleetcode-cncomproblemsremove-palindromic-subsequences)
- [@@@@[Leetcode 1246：删除回文子数组](https://coordinate.wang/index.php/archives/2737/)](#leetcode-1246删除回文子数组httpscoordinatewangindexphparchives2737)
- [[328. 奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/)](#328-奇偶链表httpsleetcode-cncomproblemsodd-even-linked-list)
- [[@@179. 最大数](https://leetcode-cn.com/problems/largest-number/)](#179-最大数httpsleetcode-cncomproblemslargest-number)
- [[@@@69. x 的平方根](https://leetcode-cn.com/problems/sqrtx/)](#69-x-的平方根httpsleetcode-cncomproblemssqrtx)
- [@@@@@@从十亿数字中,求第k位数字,用快排.](#从十亿数字中求第k位数字用快排)
- [[@@973. 最接近原点的 K 个点](https://leetcode-cn.com/problems/k-closest-points-to-origin/)](#973-最接近原点的-k-个点httpsleetcode-cncomproblemsk-closest-points-to-origin)
- [[1375. 灯泡开关 III](https://leetcode-cn.com/problems/bulb-switcher-iii/)](#1375-灯泡开关-iiihttpsleetcode-cncomproblemsbulb-switcher-iii)
- [[@@581. 最短无序连续子数组](https://leetcode-cn.com/problems/shortest-unsorted-continuous-subarray/)](#581-最短无序连续子数组httpsleetcode-cncomproblemsshortest-unsorted-continuous-subarray)
- [[@@@@@@769. 最多能完成排序的块](https://leetcode-cn.com/problems/max-chunks-to-make-sorted/)](#769-最多能完成排序的块httpsleetcode-cncomproblemsmax-chunks-to-make-sorted)
- [@@元素的技巧(如果大于左边最大值,小于右边最小值,该元素排序后依然在该位置上)](#元素的技巧如果大于左边最大值小于右边最小值该元素排序后依然在该位置上)
- [@@缝隙的技巧(如果大于前缀最大值,小于后缀最小值,则是分界元素)](#缝隙的技巧如果大于前缀最大值小于后缀最小值则是分界元素)
- [@@@@划分最多的最短无序连续子数组](#划分最多的最短无序连续子数组)
- [[@@292. Nim 游戏](https://leetcode-cn.com/problems/nim-game/)](#292-nim-游戏httpsleetcode-cncomproblemsnim-game)
- [[36. 有效的数独](https://leetcode-cn.com/problems/valid-sudoku/)](#36-有效的数独httpsleetcode-cncomproblemsvalid-sudoku)
- [[150. 逆波兰表达式求值](https://leetcode-cn.com/problems/evaluate-reverse-polish-notation/)](#150-逆波兰表达式求值httpsleetcode-cncomproblemsevaluate-reverse-polish-notation)
- [[@@@@659. 分割数组为连续子序列](https://leetcode-cn.com/problems/split-array-into-consecutive-subsequences/)](#659-分割数组为连续子序列httpsleetcode-cncomproblemssplit-array-into-consecutive-subsequences)
- [[@@@@@@877. 石子游戏](https://leetcode-cn.com/problems/stone-game/)](#877-石子游戏httpsleetcode-cncomproblemsstone-game)
- [[@@编程算法题—硬币游戏](https://blog.csdn.net/guangyacyb/article/details/80173509)](#编程算法题硬币游戏httpsblogcsdnnetguangyacybarticledetails80173509)
- [[5369. 统计作战单位数](https://leetcode-cn.com/problems/count-number-of-teams/)](#5369-统计作战单位数httpsleetcode-cncomproblemscount-number-of-teams)
- [[5370. 设计地铁系统](https://leetcode-cn.com/problems/design-underground-system/)](#5370-设计地铁系统httpsleetcode-cncomproblemsdesign-underground-system)
- [海量数据的排序](#海量数据的排序)
- [[@@@146. LRU缓存机制](https://leetcode-cn.com/problems/lru-cache/)](#146-lru缓存机制httpsleetcode-cncomproblemslru-cache)
- [[@@@@140. 单词拆分 II](https://leetcode-cn.com/problems/word-break-ii/)](#140-单词拆分-iihttpsleetcode-cncomproblemsword-break-ii)
- [把字符串中重复的子串删除](#把字符串中重复的子串删除)
- [时光倒流](#时光倒流)
- [正四面体游走](#正四面体游走)

<!-- /TOC -->



#### 动态规划和贪心算法的区别

动态规划和贪心算法都是一种递推算法 
均有局部最优解来推导全局最优解 

不同点： 
贪心算法： 
1.贪心算法中，作出的每步贪心决策都无法改变，因为贪心策略是由上一步的最优解推导下一步的最优解，而上一部之前的最优解则不作保留。 
2.由（1）中的介绍，可以知道贪心法正确的条件是：每一步的最优解一定包含上一步的最优解。 



#### [@@@@72. 编辑距离](https://leetcode-cn.com/problems/edit-distance/)

@如果有一个字符串长度为0

@初始化边界的方式

@如果i和j相等,取的不是 `math.min(dp[i][j],dp[i-1][j-1])`;而是直接取`dp[i-1][j-1],因为dp[i][j]此时为0`

@@@@@@@删除 插入 替换都是针对word1而言的

```
讲一下我自己对状态转移方程的理解,麻烦大家看看我说得对不对有没有道理:
(一)、当word1[i]==word2[j]时,由于遍历到了i和j,说明word1的0~i-1和word2的0~j-1的匹配结果已经生成,
由于当前两个字符相同,因此无需做任何操作,dp[i][j]=dp[i-1][j-1]
(二)、当word1[i]!=word2[j]时,可以进行的操作有3个:
      ① 替换操作:可能word1的0~i-1位置与word2的0~j-1位置的字符都相同,
           只是当前位置的字符不匹配,进行替换操作后两者变得相同,
           所以此时dp[i][j]=dp[i-1][j-1]+1(这个加1代表执行替换操作)
      ②删除操作:若此时word1的0~i-1位置与word2的0~j位置已经匹配了,
         此时多出了word1的i位置字符,应把它删除掉,才能使此时word1的0~i(这个i是执行了删除操作后新的i)
         和word2的0~j位置匹配,因此此时dp[i][j]=dp[i-1][j]+1(这个加1代表执行删除操作)
      ③插入操作:若此时word1的0~i位置只是和word2的0~j-1位置匹配,
          此时只需要在原来的i位置后面插入一个和word2的j位置相同的字符使得
          此时的word1的0~i(这个i是执行了插入操作后新的i)和word2的0~j匹配得上,
          所以此时dp[i][j]=dp[i][j-1]+1(这个加1代表执行插入操作)
      ④由于题目所要求的是要最少的操作数:所以当word1[i] != word2[j] 时,
          需要在这三个操作中选取一个最小的值赋格当前的dp[i][j]
```



```JAVA
public int minDistance(String word1, String word2) {
    if (word1 == null || word2 == null) {
        return 0;
    }
    int len1 = word1.length();
    int len2 = word2.length();
    //如果其中有一个字符串长度为0
    if (len1 * len2 == 0) {
        return len1 + len2;
    }
    int[][] dp = new int[len1 + 1][len2 + 1];
    //边界的初始化
    for (int i = 0; i <= len1; i++) {
        dp[i][0] = i;
    }
    for (int j = 0; j <= len2; j++) {
        dp[0][j] = j;
    }
    //如果i和j的字符相等,则ij的编辑距离等于 i-1 j-1
    //如果i j的字符不等,则ij的编辑距离取决于删除i-1 还是删除 j-1的字符会让编辑距离小一点
    for (int i = 1; i <= len1; i++) {
        for (int j = 1; j <= len2; j++) {
            if (word1.charAt(i - 1) == word2.charAt(j - 1)) {
                dp[i][j] = dp[i - 1][j - 1];
            } else {
                dp[i][j] = Math.min(Math.min(dp[i - 1][j - 1], dp[i][j - 1]), dp[i - 1][j]) + 1;
            }
        }
    }
    return dp[len1][len2];
}
```

#### [@1143. 最长公共子序列](https://leetcode-cn.com/problems/longest-common-subsequence/)

```java
public int longestCommonSubsequence(String text1, String text2) {
        if (text1 == null || text2 == null) {
            return 0;
        }
        int len1 = text1.length();
        int len2 = text2.length();
        int[][] dp = new int[len1 + 1][len2 + 1];
        for (int i = 1; i <= len1; i++) {
            for (int j = 1; j <= len2; j++) {
                if (text1.charAt(i - 1) == text2.charAt(j - 1)) {
                    dp[i][j] = dp[i - 1][j - 1] + 1;
                } else {
                    //如果此处的字符不匹配,则考虑删除t1一个 或者 t2一个
                    dp[i][j] = Math.max(dp[i][j - 1], dp[i - 1][j]);
                }
            }
        }
        return dp[len1][len2];
    }
```



#### @删除最少字符变成回文串

<img src="pictures/LeetCode03/image-20200309172717801.png" alt="image-20200309172717801" style="zoom:50%;" />

题目描述：给定一字符串s,求最少删除多少个字符可以使得s成为回文串。例如：s="abca",答案是1.

思路:把自身翻转, 自身和翻转的lcs,就是最大回文长度,str.length()-lcs 即为要删除的字符.

```java
public int minChange(String str) {
        int lcs = longestCommonSubsequence(str, null);
        return str.length() - lcs;
    }

    public int longestCommonSubsequence(String text1, String text2) {
        int len1 = text1.length();
        StringBuffer stringBuffer = new StringBuffer(text1);
        text2 = stringBuffer.reverse().toString();
        int len2 = text2.length();
        int[][] dp = new int[len1 + 1][len2 + 1];
        for (int i = 0; i <= len1; i++) {
            for (int j = 0; j <= len2; j++) {
                if (j == 0 || i == 0) {
                    dp[i][j] = 0;
                    continue;
                }
                if (text1.charAt(i - 1) == text2.charAt(j - 1)) {
                    dp[i][j] = dp[i - 1][j - 1] + 1;
                } else {
                    dp[i][j] = Math.max(dp[i - 1][j], dp[i][j - 1]);
                }
            }
        }
        return dp[len1][len2];
    }
```



#### [@@647. 回文子串](https://leetcode-cn.com/problems/palindromic-substrings/)(数量)

本题可以看成是字符串类的动态规划

中心扩展法比动态规划效率高.

因为动态规划是从短串到长串都要判断,不好剪枝

中心扩展从短串到长串的过程中,如果短串不成立,则长串终止.

```java
改进:动态规划的做法
     i-j<2  在i-j为0的时候,i和j为同一个值;i-j为1的时候由于前面的
     s.charAt(i)==s.charAt(j)也决定了它们是相等的
public int countSubstrings(String s) {
    int len = s.length();
    boolean[][] dp = new boolean[len][len];
    int ret = 0;
    for (int i = 0; i < len; i++) {
        for (int j = i; j >= 0; j--) {
            //i-j<2  在i-j为0的时候,i和j为同一个值;i-j为1的时候由于前面的
            //s.charAt(i)==s.charAt(j)也决定了它们是相等的
            if (s.charAt(i) == s.charAt(j) && ((i - j < 2) || dp[i - 1][j + 1])) {
                dp[i][j] = true;
                ret++;
            }
        }
    }
    return ret;
}
改进: 从中间往两边扩展,注意拓展方式有两种,  aba 以b为对称线  和 aa以两个a之间为对称线
    对应的代码是  int left = i;
           		 int right = left;
				left = i;
           		 right = left + 1;
	
     public int countSubstrings(String s) {
        int len = s.length();
        int res = 0;
        for (int i = 0; i < len; i++) {
            int left = i;
            int right = left;
            while (left >= 0 && right < len && s.charAt(left) == s.charAt(right)) {
                left--;
                right++;
                res++;
            }
            left = i;
            right = left + 1;
            while (left >= 0 && right < len && s.charAt(left) == s.charAt(right)) {
                left--;
                right++;
                res++;
            }

        }
        return res;
    }
```



#### [@@5. 最长回文子串](https://leetcode-cn.com/problems/longest-palindromic-substring/)(长度)

```java
改进:利用动规:dp[i][j] = dp[i-1][j+1] +1 (如果len>2的情况下,并且char[i] == char[j])
    dp[i][j]的含义是 以为i终点,j为起点的字符串中对称字符的长度.

public String longestPalindrome(String s) {
    if (s == null || s.length() == 0) {
        return "";
    }
    int maxLen = 0;
    int maxRow = 0;
    int maxCol = 0;
    int len = s.length();
    int[][] dp = new int[len][len];
    for (int i = 0; i < len; i++) {
        for (int j = i; j >= 0; j--) {

            if (s.charAt(i) == s.charAt(j)) {
                if (i == j) {//长度为1
                    dp[i][j] = 1;
                } else if (i == j + 1) {//长度为2
                    dp[i][j] = 2;
                } else { //长度大于2
                    if (dp[i - 1][j + 1] != 0) {
                        dp[i][j] = dp[i - 1][j + 1] + 2;

                    } else {
                        dp[i][j] = 0;
                    }
                }
                if (maxLen < dp[i][j]) {
                    maxLen = dp[i][j];
                    maxRow = i;
                    maxCol = j;
                }
            } else {
                //char i  与 char j 不相等
                dp[i][j] = 0;
            }
        }
    }
    return s.substring(maxCol, maxRow + 1);
}
```

#### 用少来表示多

​	

给一串只包含0~9的数字串，每个数字出现的概率相同（比如32978417506），现在告诉你（1,3,5,7）这四个数字不可用，即只能用（0,2,4,6,8,9）这6个数，如何表示原数字串？

* **00表示0**, 02表示1, 04表示3， 06表示5， 08表示7

* 15位表示以前的10位，所以存储多出来0.5倍

    

#### @[253. 会议室 II](https://leetcode-cn.com/problems/meeting-rooms-ii/)



```java
思路:startTime排序,每到一个startTime,usedRoom就+1.如果在该时间之前有结束的会议室(endTime[endPointer]<=startTime[startPointer]).usedRoom就-1;
public int minMeetingRooms(int[][] intervals) {
        int len = intervals.length;

        int max = 0;
        int[] startTime = new int[len];
        int[] endTime = new int[len];
        for (int i = 0; i < len; i++) {
            startTime[i] = intervals[i][0];
            endTime[i] = intervals[i][1];
        }
        Arrays.sort(startTime);
        Arrays.sort(endTime);
        int usedRooms = 0;
        int endPointer = 0;
        for (int startPointer = 0; startPointer < len; ) {
            if (endTime[endPointer] <= startTime[startPointer]) {
                usedRooms--;
                endPointer++;
            }
            usedRooms++;
            startPointer++;
        }
        return usedRooms;
    }
```





#### @@@[435. 无重叠区间](https://leetcode-cn.com/problems/non-overlapping-intervals/)



求无重叠区间cnt,然后用len-ret就是需要移除的最少区间数

把区间按照endTime从小到大排序. 然后往后找,如果后面的区间的startTime<该endTime,则有重叠.

如果endTIme>=startTime无重叠,此时endTime更新到下个区间,cnt++



 @按照开始时间排序的贪心算法

@@@  //按照开始时间排序,如果有交叉,则如果pre的end比较大,则删除掉pre, pre赋值为i
        //如果pre的end比i的end小,pre还是原来的,删除掉i这个区间

```java
public int eraseOverlapIntervals(int[][] intervals) {
    if (intervals == null) {
        return 0;
    }
    int len = intervals.length;
    Comparator<int[]> c = new Comparator<int[]>() {
        public int compare(int[] i1, int[] i2) {
            return i1[0] - i2[0];
        }
    };
    Arrays.sort(intervals, c);
    int count = 0;
    int pre = 0;
    for (int i = 1; i < len; i++) {
        //如果有交叉,则如果pre的end比较大,则删除掉pre, pre赋值为i
        //如果pre的end比i的end小,pre还是原来的,删除掉i这个区间
        if (intervals[pre][1] > intervals[i][0]) {
            if (intervals[pre][1] > intervals[i][1]) {
                count++;
                pre = i;
            } else {
                count++;
            }
         //如果没交叉,就直接下一个
        } else {
            pre = i;
        }
    }
    return count;
}
```





```java
@按照结束时间排序的  贪心算法
从区间集合 intvs 中选择一个区间 x，这个 x 是在当前所有区间中结束最早的（end 最小）。
把所有与 x 区间相交的区间从区间集合 intvs 中删除。
重复步骤 1 和 2，直到 intvs 为空为止。之前选出的那些 x 就是最大不相交子集。

    
public int eraseOverlapIntervals(int[][] intervals) {
        if (intervals == null || intervals.length == 0) {
            return 0;
        }
        Comparator<int[]> c = new Comparator<int[]>() {
            public int compare(int[] a, int[] b) {
                return a[1] - b[1];
            }
        };
        int len = intervals.length;
        Arrays.sort(intervals, c);
        int cnt = 1;
        int endTime = intervals[0][1];
        for (int i = 1; i < intervals.length; i++) {
            int startTime = intervals[i][0];
            if (endTime > startTime) {
                continue;
            } else if (endTime <= startTime) {
                cnt++;
                endTime = intervals[i][1];
            }
        }
        return len - cnt;
    }
```





#### [@@@@@452. 用最少数量的箭引爆气球](https://leetcode-cn.com/problems/minimum-number-of-arrows-to-burst-balloons/)

@@贪心算法

@把区间按照startTime排序,

先规定一个气球的end.然后找在这个end之内的气球.直到找不到了.

就end改为下一个新气球的end.count++

```java
public int findMinArrowShots(int[][] intervals) {
    if (intervals == null || intervals.length == 0) {
        return 0;
    }
    int len = intervals.length;
    Comparator<int[]> c = new Comparator<int[]>() {
        public int compare(int[] i1, int[] i2) {
            return i1[0] - i2[0];
        }
    };
    Arrays.sort(intervals, c);
    int count = 1;
    int pre = 0;
    int end = intervals[pre][1];
    for (int i = 1; i < intervals.length; i++) {
        if (end >= intervals[i][0]) {
            end = Math.min(end, intervals[i][1]);
        } else if (end < intervals[i][0]) {
            end = intervals[i][1];
            count++;
        }
    }
    return count;
}
```

#### [443. 压缩字符串](https://leetcode-cn.com/problems/string-compression/)



write read,chBegin的妙用

if (read == chars.length - 1 || chars[read] != chars[read + 1])  这两个条件很重要

```java
 public int compress(char[] chars) {
        if (chars == null) {
            return 0;
        }
        int left = 0;
        int write = 0;
        int len = chars.length;
        for (int right = 0; right < len; ) {
            char cur = chars[left];
            while (right + 1 < len && chars[right] == chars[right + 1]) {
                right++;
            }
            chars[write++] = cur;
            int cnt = right - left + 1;
            if (cnt > 1) {
                String temp = cnt + "";
                for (int i = 0; i < temp.length(); i++) {
                    chars[write++] = temp.charAt(i);
                }
            }
            left = right + 1;
            right++;
        }
        return write;
    }
```





#### @@@[43. 字符串相乘](https://leetcode-cn.com/problems/multiply-strings/)

ret的长度是len1+len2  ;  a*b放在的位置是 **i+j+1**



@i 和 j长的数字 乘出来的最大长度是 i+j 所以创建数组 new int[i+j]

 @i和 j 都是从len1-1   len2-1 开始往小走, 乘出来的数据放在i+j+1的地方

```java
 public String multiply(String num1, String num2) {
        if (num1.equals("0") || num2.equals("0")) {
            return "0";
        }
        int[] ret = new int[num1.length() + num2.length()];
        for (int i = num1.length() - 1; i >= 0; i--) {
            int a = num1.charAt(i) - '0';
            for (int j = num2.length() - 1; j >= 0; j--) {
                
                int b = num2.charAt(j) - '0';
                int sum = a * b + ret[i + j + 1];
                
                ret[i + j + 1] = sum % 10;
                ret[i + j] += sum / 10;
            }
        }
        StringBuilder retStr = new StringBuilder();
        for (int i = 0; i < ret.length; i++) {
            if (i == 0 && ret[i] == 0) {
                while (ret[i] == 0) {
                    i++;
                }
            }
            retStr.append(ret[i] + "");
        }
        return retStr.toString();
    }
```





#### 字符移位

链接：https://www.nowcoder.com/questionTerminal/7e8aa3f9873046d08899e0b44dac5e43
来源：牛客网

小Q最近遇到了一个难题：把一个字符串的大写字母放到字符串的后面，各个字符的相对位置不变，且不能申请额外的空间。
  你能帮帮小Q吗？ 

**输入描述:**

```
输入数据有多组，每组包含一个字符串s，且保证:1<=s.length<=1000.
  
```

**输出描述:**

```
对于每组数据，输出移位后的字符串。
```

```java
思路1
冒泡:
@@@@@@@@@@@@@@@
@要交换 i 0~len-1次
@每次  j从 len-1  到  i进行扫描;逐渐冒泡,把一个小写字母冒到i的位置上.

 public String func(String str) {
        char[] chars = str.toCharArray();
        for (int i = 0; i < chars.length; i++) {
            for (int j = chars.length - 2; j >= i; j--) {
                if (chars[j] >= 'A' && chars[j] <= 'Z' && chars[j + 1] >= 'a' && chars[j + 1] <= 'z') {
                    char temp = chars[j];
                    chars[j] = chars[j + 1];
                    chars[j + 1] = temp;
                }
            }
        }
        return new String(chars);
    }



思路2:
选择排序:
@@@@@@@@@@@@@@@@@@@
@littleIndex代表下一个要插入小写字母的位置
@i往后找,找到一个小写字母. 然后从littleIndex 到 i之间的字母往后移一位
@然后把i处的字母插入到littleIndex处.

 public String func(String str) {
        char[] chars = str.toCharArray();
        int littleIndex = 0;
        for (int i = 0; i < chars.length; i++) {
            if (chars[i] >= 'a' && chars[i] <= 'z') {
                char temp = chars[i];
                for (int j = i; j >= littleIndex + 1; j--) {
                    chars[j] = chars[j - 1];
                }
                chars[littleIndex] = temp;
                littleIndex++;
            }
        }
        return new String(chars);
    }

思路3:

public static String getResult(String str) {
        return str.replaceAll("[A-Z]", "") + str.replaceAll("[a-z]", "");
    }
```





#### [295. 数据流的中位数](https://leetcode-cn.com/problems/find-median-from-data-stream/)

@优先队列是log(n)的复杂度.

@当两个优先队 列中都有数字的时候,新插入的数字无论是插在左边还是右边,都是导致整体无序的隐患,

所以每次插入都需要判断和交换顶部的元素

```java

class MedianFinder {
    PriorityQueue<Integer> leftNums = null;
    PriorityQueue<Integer> rightNums = null;

    public MedianFinder() {
        leftNums = new PriorityQueue<Integer>(10, (o2, o1) -> (o1 - o2));
        rightNums = new PriorityQueue<Integer>(10, (o1, o2) -> (o1 - o2));

    }

    public void addNum(int num) {
        if (leftNums.size() > rightNums.size()) {
            rightNums.add(num);
        } else {
            leftNums.add(num);
        }
        if (!rightNums.isEmpty() && rightNums.peek() < leftNums.peek()) {
            int leftNum = leftNums.poll();
            int rightNum = rightNums.poll();
            leftNums.add(rightNum);
            rightNums.add(leftNum);
        }
    }

    public double findMedian() {
        if (leftNums.size() == rightNums.size()) {
            return (double) (leftNums.peek() + rightNums.peek()) / 2;
        }
        return leftNums.peek();
    }
}
```



#### @@@@图的m着色问题(dfs)

@color数组,0代表还未染色,并且可以用来当visited数组

@先染色,染色后找到第一个未访问的point进行dfs.

@如果图中任意两点都是连通的，那么图被称作连通图。 如果有图如下,5那里在我的代码里不适用原因是

1.我用回溯的cnt作为ret++的条件,应该改成cnt为全量,并且1节点每换一次颜色,cnt置零

2.backtracing往下走的时候,只会选择第一个联通point,后续point会被抛弃,比如图中5

<img src="pictures/LeetCode03/image-20200309235552816.png" alt="image-20200309235552816" style="zoom:50%;" />

[问题描述]

给定无向连通图G和m种不同的颜色，用这些颜色给图的各个顶点着一种颜色，若某种方案使得图中每条边的2个顶点的颜色都不相同，则是一个满足的方案，找出所有的方案。

输入格式
 第一行有3个正整数n，k和m，分别表示n个顶点，k条边，m种颜色
接下来k行，每行2个正整数，保送一条边的两个顶点

所有不同的着色方案数
输入样例】
5 8 4 
1 2
1 3 
1 4
2 3
2 4
2 5
3 4
4 5
输出样例
48

```java
  public class Main {
    static int[][] matrix = null;
    int[] pointColor = null;
    int len = 0;
    int numPoint = 0;
    int numEdge = 0;
    int ret = 0;
    int numColor = 0;

    public int getResult(int numPoint, int numEdge, int numColor) {
        len = numPoint;
        this.numColor = numColor;
        this.numEdge = numEdge;
        this.numPoint = numPoint;
//        this.matrix = new int[numPoint + 1][numPoint + 1];
        pointColor = new int[numPoint + 1];
        backtracing(1, 1);
        return ret;
    }

    private boolean uniqueColor(int index) {
        for (int i = 1; i <= numPoint; i++) {
            if (matrix[index][i] == 1 && pointColor[index] == pointColor[i]) {
                return false;
            }
        }
        return true;
    }

    private void backtracing(int index, int cnt) {
        if (cnt >= numPoint + 1) {
            return;
        }
        //先染色
        for (int j = 1; j <= numColor; j++) {
            pointColor[index] = j;
            //如果颜色符合要求
            if (uniqueColor(index)) {
                if (cnt == numPoint) {
                    ret++;
                }
                //从与index相连的  第一个没有被访问过的 顶点开始染色
                //为什么是第一个,假设1与2,3相连,我给1染颜色1,2染颜色2,3染颜色3.
                //1->2->3  和  1->3->2  其实是同一种颜色组合.
                for (int k = 1; k <= numPoint; k++) {
                    if (matrix[index][k] == 1 && pointColor[k] == 0) {
                        backtracing(k, cnt + 1);
                        break;
                    }
                }
            }
            pointColor[index] = 0;
        }
    }

    private void initialMatrix(String str) {
        for (int i = 0; i < str.length(); i = i + 2) {
            int x = str.charAt(i) - '0';
            int y = str.charAt(i + 1) - '0';
            matrix[x][y] = 1;
            matrix[y][x] = 1;
        }
    }

    public static void main(String[] args) {
        Main main = new Main();
        String str = "1213142324253445";
        matrix = new int[6][6];
        main.initialMatrix(str);

        int func = main.getResult(5, 8, 4);
        System.out.println(func);

    }
}
```



```java
 下面的做法错误的原因是  
 1->2->3和
 1->3->2 假设1涂红,2涂蓝,3涂绿,这被认为是两种情况了.
 
 static int[][] matrix = null;
    int[] pointColor = null;
    int len = 0;
    int numPoint = 0;
    int numEdge = 0;
    int ret = 0;
    int numColor = 0;

    public int func(int numPoint, int numEdge, int numColor) {
        len = numPoint;
        this.numColor = numColor;
        this.numEdge = numEdge;
        this.numPoint = numPoint;
//        this.matrix = new int[numPoint + 1][numPoint + 1];
        pointColor = new int[numPoint + 1];
        backtracing(1, 1);
        return ret;
    }

    private boolean uniqueColor(int index) {
        for (int i = 1; i <= numPoint; i++) {
            if (matrix[index][i] == 1 && pointColor[index] == pointColor[i]) {
                return false;
            }
        }
        return true;
    }

    private void backtracing(int index, int cnt) {
        if (cnt >= numPoint + 1) {
            return;
        }
        for (int j = 1; j <= numColor; j++) {
            pointColor[index] = j;
            if (uniqueColor(index)) {
                if (cnt == numPoint) {
                    ret++;
                }
                for (int k = 1; k <= numPoint; k++) {
                    if (matrix[index][k] == 1 && pointColor[k] == 0) {
                        backtracing(k, cnt + 1);
                    }
                }
            }
            pointColor[index] = 0;
        }
    }
```



#### 

#### 100亿数字排序,求中位数,平均数,求和

##### 方法1

今天要给100亿个数字排序，100亿个 int 型数字放在文件里面大概有 37.2GB，非常大，内存一次装不下了。那么肯定是要拆分成小的文件一个一个来处理，最终在合并成一个排好序的大文件。

实现思路

1.把这个37GB的大文件，用哈希分成1000个小文件，每个小文件平均38MB左右（理想情况），把100亿个数字对1000取模，模出来的结果在0到999之间，每个结果对应一个文件，所以我这里取的哈希函数是 h = x % 1000，哈希函数取得"好"，能使冲突减小，结果分布均匀。

2.拆分完了之后，得到一些几十MB的小文件，那么就可以放进内存里排序了，可以用快速排序，归并排序，堆排序等等。

3.1000个小文件内部排好序之后，就要把这些内部有序的小文件，合并成一个大的文件，可以用**二叉堆**来做1000路合并的操作，每个小文件是一路，合并后的大文件仍然有序。

- 首先遍历1000个文件，每个文件里面取第一个数字，组成 (数字, 文件号) 这样的组合加入到堆里（假设是从小到大排序，用小顶堆），遍历完后堆里有1000个 (数字，文件号) 这样的元素
- 然后不断从堆顶拿元素出来，每拿出一个元素，把它的文件号读取出来，然后去对应的文件里，加一个元素进入堆，直到那个文件被读取完。拿出来的元素当然追加到最终结果的文件里。
- 按照上面的操作，直到堆被取空了，此时最终结果文件里的全部数字就是有序的了。

最后我用c++写了个实验程序，具体代码在[这里](https://link.jianshu.com?t=https://github.com/hehe520/Data-structure-and-algorithm/blob/master/海量数据处理/外部归并排序 - 分治.cpp)可以看到。

##### 方法2:

*1个int=4Byte   1亿个数字int = 4亿B/1024/1024=370MB*

位图是一个bit数组,遵循数组的最大长度,length的类型是int,所以最长是Integer.value.

*为什么使用位图？答：直接从1亿数据里面找Top100效率很低，通过构建位图，然后倒序输出位图就可以快速找到Top100.或者TopN*

1. 找最大值:14ms
2. 构建位图:149ms
3. 倒序输出:84m
4. 累计耗时:234ms



##### 思维拓展

类似的100亿个数字求和，求中位数，求平均数，套路就是一样的了。
 求和：统计每个小文件的和，返回给master再求和就可以了。
 求平均数：上面能求和了，再除以100亿就是平均数了
 求中位数：在排序的基础上，遍历到中间的那个数就是中位数了

#### [113. 路径总和 II](https://leetcode-cn.com/problems/path-sum-ii/)

```java
List<List<Integer>> ret = new ArrayList<>();

    public List<List<Integer>> pathSum(TreeNode root, int sum) {
        preOrder(root, sum, 0, new ArrayList<Integer>());
        return ret;
    }

    public void preOrder(TreeNode root, int sum, int pathSum, List<Integer> path) {
        if (root == null) {
            return;
        }
        path.add(root.val);
        pathSum += root.val;
        if (root.left == null && root.right == null && pathSum == sum) {
            ret.add(new ArrayList<Integer>(path));
            path.remove(path.size() - 1);
            return;
        }
        preOrder(root.left, sum, pathSum, path);
        preOrder(root.right, sum, pathSum, path);
        path.remove(path.size() - 1);
    }
```





#### [@@@547. 朋友圈](https://leetcode-cn.com/problems/friend-circles/)

@count,parent[],size[]

@union ,getParent;

@union的时候往根节点上union

```
if (size[rootP] > size[rootQ]) {
            parent[rootQ] = rootP;
            size[rootP] += size[rootQ];
            count--;
        } else {
            parent[rootP] = rootQ;
            size[rootQ] += size[rootP];
            count--;
        }
```

代码:

```java

public class Solution {
    public int findCircleNum(int[][] M) {
        if (M == null || M.length == 0) {
            return 0;
        }
        int len = M.length;
        UF u = new UF(len);
        for (int i = 0; i < len; i++) {
            for (int j = 0; j < len; j++) {
                if (M[i][j] == 1) {
                    u.union(i, j);
                }
            }
        }
        return u.getCount();
    }
}

class UF {
    private int count;
    private int[] parent;
    private int[] size;

    public UF(int len) {
        this.count = len;
        this.parent = new int[len];
        this.size = new int[len];
        for (int i = 0; i < len; i++) {
            size[i] = 1;
            parent[i] = i;
        }
    }
    public void union(int p, int q) {
        int rootP = findParent(p);
        int rootQ = findParent(q);
        if (rootP == rootQ)
            return;
        if (size[rootP] > size[rootQ]) {
            parent[rootQ] = rootP;
            size[rootP] += size[rootQ];
            count--;
        } else {
            parent[rootP] = rootQ;
            size[rootQ] += size[rootP];
            count--;
        }
    }
    //路径压缩+寻找根节点
    public int findParent(int p) {
        while (parent[p] != p) {
            //把 p的爷爷 替换成  p的爸爸
            parent[p] = parent[parent[p]];
            //把p变成p的爷爷
            p = parent[p];
        }
        return p;
    }

    public int getCount() {
        return count;
    }
     public boolean connected(int p, int q) {
        int rootP = findParent(p);
        int rootQ = findParent(q);
        return rootP == rootQ;
    }

}
```





#### [@@@200. 岛屿数量](https://leetcode-cn.com/problems/number-of-islands/)

@uf的初始化  

i*col + j

如果`gird[i][j]=='0'` 那`parent[i*col][j]=0 和 size[i*col][j]=0`

@小岛的合并 

如果`grid[i][j]=='1',先设为'0',然后跟右方和下方的岛合并`



@@查并集做法

```java
class Solution {
    public int numIslands(char[][] grid) {
        if (grid == null || grid.length == 0) {
            return 0;
        }
        int row = grid.length;
        int col = grid[0].length;
        UF uf = new UF(grid, grid.length, grid[0].length);
        for (int i = 0; i < row; i++) {
            for (int j = 0; j < col; j++) {
                //如果某个坐标是一座岛,就把这座岛与右边或者下边的连接岛 合并
                //为什么没有左和上的岛,i,j是按照从左上往右下的顺序移动
                // 合并前会把grid[i][j]置为0,所以左上的岛永远是空的
                if (grid[i][j] == '1') {
                    //不置零也行   grid[i][j] = '0';
                    if (j + 1 < col && grid[i][j + 1] == '1') {
                        uf.union(i * col + j, i * col + j + 1);
                    }
                    if (i + 1 < row && grid[i + 1][j] == '1') {
                        uf.union(i * col + j, (i + 1) * col + j);
                    }
                }
            }
        }
        return uf.getCount();
    }
}

class UF {
    int count;
    int[] parent;
    int[] size;

    public UF(char[][] grid, int row, int col) {
        this.parent = new int[row * col];
        this.size = new int[row * col];
        for (int i = 0; i < row; i++) {
            for (int j = 0; j < col; j++) {
                //如果某个坐标是导,就count++, parent初始化成自己,size初始化为1.
                if (grid[i][j] == '1') {
                    parent[i * col + j] = i * col + j;
                    ++count;
                    size[i * col + j] = 1;
                }
            }
        }
    }

    public int getCount() {
        return this.count;
    }

    public boolean connected(int p, int q) {
        int rootP = findParent(p);
        int rootQ = findParent(q);
        if (rootP == rootQ) {
            return true;
        }
        return false;
    }

    public int findParent(int p) {
        while (p != parent[p]) {
            parent[p] = parent[parent[p]];
            p = parent[p];
        }
        return p;
    }

    public void union(int p, int q) {
        int rootP = findParent(p);
        int rootQ = findParent(q);
        if (rootQ == rootP) {
            return;
        }
        if (size[rootP] > size[rootQ]) {
            size[rootP] += size[rootQ];
            parent[rootQ] = rootP;
        } else {
            size[rootQ] += size[rootP];
            parent[rootP] = rootQ;
        }
        count--;
    }

}
```



#### [@@@1319. 连通网络的操作次数](https://leetcode-cn.com/problems/number-of-operations-to-make-network-connected/)

创建查并集

如果一根网线两端已经连在一起,则空闲网线加一

如果没有连在一起,则相连,空闲网线数量不变



最后连通分量 num  和 空闲网线数作比较

```java

class Solution {
    //count密封
    public int makeConnected(int n, int[][] connections) {
        Union u = new Union(n);
        int remainLink = 0;

        for (int i = 0; i < connections.length; i++) {
            int from = connections[i][0];
            int to = connections[i][1];
            if (u.isConnected(from, to)) {
                remainLink++;
            }else{
                u.union(from, to);
            }
        }
        int groupCount = u.count;
        if (groupCount - 1 <= remainLink) {
            return groupCount - 1;
        }
        return -1;
    }

}

class Union {
    int count = 0;
    int[] size = null;
    int[] parent = null;

    public Union(int count) {
        this.count = count;
        size = new int[count];
        parent = new int[count];
        for (int i = 0; i < count; i++) {
            size[i] = 1;
            parent[i] = i;
        }
    }

    public int getParent(int x) {
        while (x != parent[x]) {
            parent[x] = parent[parent[x]];
            x = parent[x];
        }
        return x;
    }

    public boolean isConnected(int x, int y) {
        int xP = getParent(x);
        int yP = getParent(y);
        return xP == yP;
    }

    public void union(int x, int y) {
        if (isConnected(x, y)) {
            return;
        }
        int xP = getParent(x);
        int yP = getParent(y);
        if (size[xP] >= size[yP]) {
            parent[yP] = xP;
            size[xP] += size[yP];
        } else {
            parent[xP] = yP;
            size[yP] += size[xP];
        }
        count--;
    }
}
```



#### 找到二叉搜索树中与target之差的绝对值最小的node

@如果node处的值小于target,则node左边的值跟target的差距只会越来越大

比如target是10,如果node=9,则node左边的值,跟10的差距只会越来越大

<img src="pictures/LeetCode03/image-20200303225244927.png" alt="image-20200303225244927" style="zoom:50%;" />

在二叉查找树中，[查找与目标值最接近的节点并返回](https://www.geeksforgeeks.org/find-closest-element-binary-search-tree/)。如果有多个节点都符合要求，返回其中一个即可

```java
 private int minDiff = Integer.MAX_VALUE;
    public void maxDiffUtil(TreeNode root, int target) {
        if (root == null) {
            return;
        }
        if (root.val == target) {
            minDiff = 0;
            return;
        }
        int abs = Math.abs(root.val - target);

        minDiff = Math.min(minDiff, abs);
        if (target > root.val) {
            maxDiffUtil(root.right, target);
        } else {
            maxDiffUtil(root.left, target);
        }
    }
```





#### @@@@二叉树的非递归后序遍历





```java
private void lastOrder(TreeNode root) {
        if (root == null) {
            return;
        }
        TreeNode lastVisited = null;
        TreeNode nodeCur = root;
        Stack<TreeNode> stack = new Stack<>();
        while (nodeCur != null) {
            stack.add(nodeCur);
            nodeCur = nodeCur.left;
        }
        while (!stack.isEmpty()) {
            nodeCur = stack.pop();
            if (nodeCur.right == null || lastVisited == nodeCur.right) {
                System.out.println(nodeCur.val);
                lastVisited = nodeCur;
            } else if (lastVisited == nodeCur.left) {
                stack.add(nodeCur);
                nodeCur = nodeCur.right;
                while (nodeCur != null) {
                    stack.add(nodeCur);
                    nodeCur = nodeCur.left;
                }
            }
        }
    }
```



#### @@@有序数组重建平衡二叉树

```java
public TreeNode rebuildBST(int[] nums, int start, int end) {
        if (start > end || start < 0 || end > nums.length - 1) {
            return null;
        }
        int mid = start + (end - start) / 2;
        TreeNode treeNode = new TreeNode(nums[mid]);
        treeNode.left = rebuildBST(nums, start, mid - 1);
        treeNode.right = rebuildBST(nums, mid + 1, end);
        return treeNode;
    }
```

#### 一个数组里找任意两个数之和的绝对值最小值

```
排序,left= 0,right = len-1, sum>0 right--,sum<0,left++.
```

#### 一个整数数组找任意两数的最小差

```
排序,相邻的数的差最小
```

#### [@@208. 实现 Trie (前缀树)](https://leetcode-cn.com/problems/implement-trie-prefix-tree/)

```java

class Trie {
    private TreeNode root = null;

    /**
     * Initialize your data structure here.
     */
    public Trie() {
        root = new TreeNode();
    }

    public TreeNode getPrefixEnd(String word) {
        TreeNode node = root;
        for (int i = 0; i < word.length(); i++) {
            char ch = word.charAt(i);
            if (node.containsKey(ch)) {
                node = node.get(ch);
            } else {
                return null;
            }
        }
        return node;
    }

    /**
     * Inserts a word into the trie.
     */
    public void insert(String word) {
        TreeNode node = root;
        for (int i = 0; i < word.length(); i++) {
            char ch = word.charAt(i);
            if (!node.containsKey(ch)) {
                node.put(ch, new TreeNode());
            }
            node = node.get(ch);
        }
        node.setEnd();
    }


    /**
     * Returns if the word is in the trie.
     */
    public boolean search(String word) {
        TreeNode node = getPrefixEnd(word);
        return node != null && node.isEnd();
    }

    /**
     * Returns if there is any word in the trie that starts with the given prefix.
     */
    public boolean startsWith(String prefix) {
        TreeNode node = getPrefixEnd(prefix);
        return node != null;
    }
}

class TreeNode {
    private int len = 26;
    private TreeNode[] links = null;
    private boolean isEnd = false;

    public TreeNode() {
        links = new TreeNode[len];
    }

    public void put(char ch, TreeNode node) {
        links[ch - 'a'] = node;
    }

    public TreeNode get(char ch) {
        return links[ch - 'a'];
    }

    public boolean containsKey(char ch) {
        return links[ch - 'a'] != null;
    }

    public boolean isEnd() {
        return isEnd;
    }

    public void setEnd() {
        isEnd = true;
    }

}
```



#### [@209. 长度最小的子数组](https://leetcode-cn.com/problems/minimum-size-subarray-sum/)



思路一:滑动窗口  复杂度 O(n)

@@@思路二:二分长度法   len = 8 先搜len=4,如果sum>s,搜len=2,如果sum<s,搜len=6.  在长度上用二分法





#### [@@60. 第k个排列](https://leetcode-cn.com/problems/permutation-sequence/)

@@特别注意使用  



```java
 public String getPermutation(int n, int k) {
        int[] factor = new int[n];
        StringBuilder ret = new StringBuilder();
        ArrayList<Integer> numList = new ArrayList<Integer>();
        //k以0为初始
        k = k - 1;
        //n=5,k=11
        //factor为[0,1,2,0,0]
        //位次是 0*4!+ 1*3!+2*2!+0*1!+0*0! = 10.
        //  4   3   2   1   0
        //  4!  3!  2!  1!  0!
     //从前往后构造factor,即每一位的顺序
        for (int i = 0, j = n - 1; i < n; i++, j--) {
            int weight = weight(j);
            factor[i] = k / weight;
            k = k % weight;
        }
        for (int i = 1; i <= n; i++) {
            numList.add(i);
        }
        //从前往后构造排列
        for (int i = 0; i < n; i++) {
            int num = numList.get(factor[i]);
            ret.append(num);
            numList.remove(factor[i]);
        }
        return ret.toString();
    }
    //返回n的阶乘
    private int weight(int n) {
        int sum = 1;
        while (n >= 1) {
            sum = sum * n;
            n--;
        }
        return sum;
    }
```





#### [@@@@162. 寻找峰值](https://leetcode-cn.com/problems/find-peak-element/)

迭代法:

@@@mid和mid+1的比较是很有水平的.因为while里面是left<right.所以mid求出来之后,mid+1不会越界,但mid-1会越界

所以可以

```java
 if (nums[mid] > nums[mid + 1]) {
            right = mid;
        } else if (nums[mid] <= nums[mid + 1]) {
            left = mid + 1;
        }
```

但是不能用

```java
if(nums[mid-1]<nums[mid]){
    left = mid;
}else if(nums[mid-1]>=nums[mid]){
    right = mid-1;
}
```

```java
public int findPeakElement(int[] nums) {
    int left = 0;
    int right = nums.length - 1;
    while (left < right) {
        int mid = left + (right - left) / 2;
        if (nums[mid] > nums[mid + 1]) {
            right = mid;
        } else if (nums[mid] <= nums[mid + 1]) {
            left = mid + 1;
        }
    }
    return left;
}
```

递归法:边界的判断.

```java
 public int findPeakElement(int[] nums) {
        return func(nums, 0, nums.length - 1);
    }

    private int func(int[] nums, int left, int right) {
        if (left == right) {
            return left;
        }
        int mid = left + (right - left) / 2;
        if (nums[mid] > nums[mid + 1]) {
            right = mid;
            return func(nums, left, right);
        } else {
            left = mid + 1;
            return func(nums, left, right);
        }
    }
```









#### [@@@@127. 单词接龙](https://leetcode-cn.com/problems/word-ladder/)

这个题不能用dfs来做,假设dict是100.那么dfs要遍历所有的路径,复杂度是100的100次方,大概就是1*10的200次方,复杂度是指数级别的



用BFS来做,就可以找到最少的转换次数,因为有level层来控制.复杂度变成了  dict表长*字符串的len



```java
   boolean[] visited = null;
    String target = null;
    List<String> wordList = null;

    public int ladderLength(String beginWord, String endWord, List<String> wordList) {
        target = endWord;
        this.wordList = wordList;
        visited = new boolean[wordList.size()];

        if (!wordList.contains(endWord)) {
            return 0;
        }

        for (int i = 0; i < wordList.size(); i++) {
            if (beginWord.equals(wordList.get(i))) {
                visited[i] = true;
            }
        }

        LinkedList<Pair<String, Integer>> queue = new LinkedList<>();
        queue.add(new Pair(beginWord, 1));
        while (!queue.isEmpty()) {
            //每一层
            for (int queueIndex = 0; queueIndex < queue.size(); queueIndex++) {
                String curStr = queue.peek().getKey();
                int level = queue.poll().getValue();
                //每一层的某个string,能否往下转换
                for (int i = 0; i < wordList.size(); i++) {
                    String nextStr = wordList.get(i);
                    if (visited[i] == false && canTrans(curStr, nextStr)) {
                        if (nextStr.equals(endWord)) {
                            return level + 1;
                        }
                        queue.add(new Pair<>(nextStr, level + 1));
                        visited[i] = true;
                    }
                }
            }

        }

        return 0;
    }


    private boolean canTrans(String curStr, String nextStr) {
        int diffCount = 0;
        if (curStr.equals(nextStr)) {
            return false;
        }
        for (int i = 0; i < curStr.length(); i++) {
            if (curStr.charAt(i) != nextStr.charAt(i)) {
                diffCount++;
            }
            if (diffCount > 1) {
                return false;
            }
        }
        return diffCount == 1;
    }
```









#### IP重复攻击

实现一个数据结构，判断某个IP是否在1秒内请求了>=100次，用来在服务器上防止拒绝服务攻击

```
用循环数组，只需要长度为100，后来的请求覆盖掉之前的请求，然后判断最新的一个请求和队列中最早的请求时间差是否>=1。
```





#### ab替换成c,b替换成ef

输入一个char\[\] str，要求把str中所有的"ab"都替换成"c"，把所有单个的"b"都替换成"ef"。要求in-place，并且保证str中"ab"的个数 &gt;"b"的个数（也就是str的长度足够放下替换后的结果）

```java
//ab替换成c
//b替换成ef

private String handleStr(char[] chars) {
    int fillIndex = 0;
    int countB = 0;
    for (int i = 0; i < chars.length; ) {
        char ch = chars[i];
        if (ch == 'a') {
            if (i + 1 < chars.length && chars[i + 1] == 'b') {
                i++;
                chars[fillIndex++] = 'c';
            }
            i++;
        } else {
            if (ch == 'b') {
                countB++;
            }
            chars[fillIndex++] = chars[i++];
        }
    }
    for (int j = fillIndex; j < chars.length; j++) {
        chars[j] = 0;

    }
    int rightIndex = fillIndex + countB - 1;
    for (int i = fillIndex - 1; i >= 0; ) {
        char ch = chars[i];
        if (ch == 'b') {
            chars[rightIndex--] = 'f';
            chars[rightIndex--] = 'e';
            i--;
        } else {
            chars[rightIndex--] = chars[i--];
        }
    }
    return new String(chars);
}
```





#### [@@@4. 寻找两个有序数组的中位数](https://leetcode-cn.com/problems/median-of-two-sorted-arrays/)

@@@各种边界 非常麻烦

```java
思路1:log(m+n)的算法
public double findMedianSortedArrays(int[] nums1, int[] nums2) {
    int len1 = nums1.length;
    int len2 = nums2.length;
    int sum = len1 + len2;
    if (sum % 2 == 1) {
        return findKth(nums1, 0, len1 - 1, nums2, 0, len2 - 1, sum / 2 + 1);
    } else {
        return (findKth(nums1, 0, len1 - 1, nums2, 0, len2 - 1, sum / 2) + findKth(nums1, 0, len1 - 1, nums2, 0, len2 - 1, sum / 2 + 1)) * 0.5;
    }
}

public int findKth(int[] nums1, int left1, int right1, int[] nums2, int left2, int right2, int k) {
    int len1 = right1 - left1 + 1;
    int len2 = right2 - left2 + 1;
    //让len1始终保持最小
    if (len1 > len2) {
        return findKth(nums2, left2, right2, nums1, left1, right1, k);
    }
    if (len1 == 0) {
        return nums2[left2 + k - 1];
    }
    if (k == 1) {
        return Math.min(nums1[left1], nums2[left2]);
    }
    //找到left 加 k/2长度处的两个数组的值进行比较
    int index1 = left1 + Math.min(len1, k / 2) - 1;
    int index2 = left2 + Math.min(len2, k / 2) - 1;
    if (nums1[index1] < nums2[index2]) {
        return findKth(nums1, index1 + 1, right1, nums2, left2, right2, k - (index1 - left1 + 1));
    } else {
        return findKth(nums1, left1, right1, nums2, index2 + 1, right2, k - (index2 - left2 + 1));
    }
}

思路2:往优先队列里面添加元组,直到添加(m+n)/2个
```

#### [@@@@@701. 二叉搜索树中的插入操作](https://leetcode-cn.com/problems/insert-into-a-binary-search-tree/)

@插入操作的思想:

找到null,就创建并返回

修改左子树或者右子树,就通过返回值来做更新

最后把整个root返回回去,更新root的root.

```java
递归写法:

public TreeNode insertIntoBST(TreeNode root, int val) {
    if (root == null) {
        return new TreeNode(val);
    }
    if(root.val==val){
            return root;
    }else if (root.val < val) {
        root.right = insertIntoBST(root.right, val);
    } else {
        root.left = insertIntoBST(root.left, val);
    }
    return root;
}


迭代写法:

 public TreeNode insertIntoBST(TreeNode root, int val) {
        if (root == null) {
            return new TreeNode(val);
        }
        TreeNode node = root;
        while (node != null) {
            if (node.val == val) {
                return root;
            } else if (node.val > val) {
                if (node.left == null) {
                    node.left = new TreeNode(val);
                    return root;
                }
                node = node.left;
            } else {
                if (node.right == null) {
                    node.right = new TreeNode(val);
                    return root;
                }
                node = node.right;
            }
        }

        return root;
    }
```



#### [@@@@@@@@@@450. 删除二叉搜索树中的节点](https://leetcode-cn.com/problems/delete-node-in-a-bst/)



@@@最难的部分 (换了一下两个if else的顺序,变得好理解多了)

```java
private TreeNode delLeftMaxChild(TreeNode node) {
    if( node.right !=null){
         node.right = delLeftMaxChild(node.right);
   		 return node;
    }else if (node.right == null) {
        TreeNode left = node.left;
        node.left = null;
        return left;
    }
}
```



```java
public TreeNode deleteNode(TreeNode root, int key) {
        if (root == null) {
            return null;
        }
        if (root.val == key) {
            root = getDeletedLeftMaxChildTree(root, key);
        } else if (root.val > key) {
            root.left = deleteNode(root.left, key);
        } else {
            root.right = deleteNode(root.right, key);
        }
        return root;
    }

    private TreeNode getDeletedLeftMaxChildTree(TreeNode root) {
        if (root.left == null && root.right == null) {
            return null;
        } else if (root.left != null && root.right == null) {
            TreeNode left = root.left;
            root.left = null;
            return left;
        } else if (root.left == null && root.right != null) {
            TreeNode right = root.right;
            root.right = null;
            return right;
        } else {
            TreeNode leftMaxChild = findMaxLeftChild(root);
            TreeNode copyRootTree = new TreeNode(leftMaxChild.val);
            copyRootTree.left = delLeftMaxTree(root.left);
            copyRootTree.right = root.right;
            return copyRootTree;
        }
    }

    private TreeNode delLeftMaxTree(TreeNode root) {
        if (root.right != null) {
            root.right = delLeftMaxTree(root.right);
            return root;
        } else {
            TreeNode left = root.left;
            root.left = null;
            return left;
        }
    }

 	//仅用于左右子树都存在的情况
    private TreeNode findMaxChild(TreeNode root){

        TreeNode left = root.left;
        while(left.right!=null){
            left = left.right;
        }
        return left;
    }
```





#### [654. 最大二叉树](https://leetcode-cn.com/problems/maximum-binary-tree/)

没办法用排序来做,本题不能破坏原来的左右子树的关系.如果可以破坏该关系的话,则

```java
int[] nums = null;

    public TreeNode constructMaximumBinaryTree(int[] nums) {
        this.nums = nums;
        Arrays.sort(nums);
        TreeNode root = buildTree();
        return root;
    }

    private TreeNode buildTree(int start, int end) {
        if (start > end) {
            return null;
        }
        TreeNode root = new TreeNode(nums[start]);
        int mid = start + (end - start) / 2;
        root.left = buildTree(...);
        root.right = buildTree(..);
        return root;
    }
```



@inOrder  +   数组递归建树的诀窍: left,maxIndex-1   和  maxIndex+1,right

```java
public TreeNode constructMaximumBinaryTree(int[] nums) {
    if (nums == null || nums.length == 0) {
        return null;
    }
    return construct(nums, 0, nums.length - 1);
}

private TreeNode construct(int[] nums, int left, int right) {
    if (left > right) {
        return null;
    }
    int[] ret = findMax(nums, left, right);
    TreeNode node = new TreeNode(ret[0]);
    node.left = construct(nums, left, ret[1] - 1);
    node.right = construct(nums, ret[1] + 1, right);
    return node;
}

private int[] findMax(int[] nums, int left, int right) {
    if (left > right) {
        return new int[]{};
    }
    int max = Integer.MIN_VALUE;
    int maxIndex = -1;
    for (int i = left; i <= right; i++) {
        if (nums[i] > max) {
            max = nums[i];
            maxIndex = i;
        }
    }
    return new int[]{max, maxIndex};
}
```







#### [@@@273. 整数转换英文表示](https://leetcode-cn.com/problems/integer-to-english-words/)



@one里面没有0的返回

```java
class Solution {
    public String numberToWords(int num) {
        if (num == 0) {
            return "Zero";
        }
        int billion = num / 1000000000;
        int million = (num % 1000000000) / 1000000;
        int thousand = (num % 1000000) / 1000;
        int rest = num % 1000;

        String ret = "";
        if (billion != 0) {
            ret = three(billion) + " " + "Billion";
        }
        if (million != 0) {
            if (!ret.isEmpty()) {
                ret += " ";
            }
            ret += three(million) + " " + "Million";
        }
        if (thousand != 0) {
            if (!ret.isEmpty()) {
                ret += " ";
            }
            ret += three(thousand) + " " + "Thousand";
        }
        if (rest != 0) {
            if (!ret.isEmpty()) {
                ret += " ";
            }
            ret += three(rest);
        }
        return ret;
    }

    public String one(int num) {
        switch (num) {
            case 1:
                return "One";
            case 2:
                return "Two";
            case 3:
                return "Three";
            case 4:
                return "Four";
            case 5:
                return "Five";
            case 6:
                return "Six";
            case 7:
                return "Seven";
            case 8:
                return "Eight";
            case 9:
                return "Nine";
        }
        return "";
    }

    public String twoLessThan20(int num) {
        switch (num) {
            case 10:
                return "Ten";
            case 11:
                return "Eleven";
            case 12:
                return "Twelve";
            case 13:
                return "Thirteen";
            case 14:
                return "Fourteen";
            case 15:
                return "Fifteen";
            case 16:
                return "Sixteen";
            case 17:
                return "Seventeen";
            case 18:
                return "Eighteen";
            case 19:
                return "Nineteen";
        }
        return "";
    }

    public String ten(int num) {
        switch (num) {
            case 2:
                return "Twenty";
            case 3:
                return "Thirty";
            case 4:
                return "Forty";
            case 5:
                return "Fifty";
            case 6:
                return "Sixty";
            case 7:
                return "Seventy";
            case 8:
                return "Eighty";
            case 9:
                return "Ninety";
        }
        return "";
    }

    public String two(int num) {
        if (num == 0) {
            return "";
        }
        int two = num / 10;
        int rest = num % 10;
        if (num < 10) {
            return one(num);
        } else if (num < 20) {
            return twoLessThan20(num);
        } else {
            if (two != 0 && rest != 0) {
                return ten(two) + " " + one(rest);
            } else if (two != 0 && rest == 0) {
                return ten(two);
            } 
        }
        return "";
    }

    public String three(int num) {
        if (num == 0) {
            return "";
        }
        int hundred = num / 100;
        int rest = num % 100;
        String ret = "";
        if (rest != 0 && hundred != 0) {
            return one(hundred) + " " + "Hundred" + " " + two(rest);
        } else if (hundred != 0) {
            return one(hundred) + " " + "Hundred";
        } else if (rest != 0) {
            return two(rest);
        }
        return "";
    }

    public static void main(String[] args) {
        Solution solution = new Solution();
        String s = solution.numberToWords(10);
        System.out.println(s);
    }
}
```







#### [272. 最接近的二叉搜索树值 II](https://leetcode-cn.com/problems/closest-binary-search-tree-value-ii/)

```java
private PriorityQueue<Pair<Double, Integer>> queue = null;
int k = 0;
public List<Integer> closestKValues(TreeNode root, double target, int k) {
    Comparator<Pair<Double, Integer>> c = new Comparator<Pair<Double, Integer>>() {
        public int compare(Pair<Double, Integer> p1, Pair<Double, Integer> p2) {
            if ((p1.getKey() - p2.getKey()) < 0) {
                return 1;
            }
            return -1;
        }
    };
    queue = new PriorityQueue<Pair<Double, Integer>>(10, c);
    this.k = k;
    inOrder(root, target);
    ArrayList<Integer> ret = new ArrayList<Integer>();
    while (!queue.isEmpty()) {
        ret.add(queue.poll().getValue());
    }
    return ret;
}

public void inOrder(TreeNode root, double target) {

    if (root == null) {
        return;
    }
    inOrder(root.left, target);
    double diff = Math.abs((double) root.val - target);
    if (queue.size() < k) {
        queue.add(new Pair(diff, root.val));
    } else {
        if (queue.peek().getKey() > diff) {
            queue.poll();
            queue.add(new Pair(diff, root.val));
        }
    }
    inOrder(root.right, target);
}
```

#### @@@**拓扑排序**

拓扑排序有dfs和bfs(kahn)两种.

bfs可以判断有环无环

dfs麻烦一点





#### [@@210. 课程表 II](https://leetcode-cn.com/problems/course-schedule-ii/)

@@@

<img src="pictures/LeetCode03/image-20200324175541265.png" alt="image-20200324175541265" style="zoom:50%;" />

@思路1 拓扑排序(BFS)
建立一个**入度表**  和 一个**邻接矩阵**.

如果不涉及权值,为了节省空间和提升遍历效率,**邻接矩阵可以用 set数组代替,HashSet<Integer>[]**    

```java


int[] inCount = null;
int[][] grid = null;
int[] ret = null;
ArrayList<Integer> retList = null;
Queue<Integer> queue = new LinkedList<Integer>();

public int[] findOrder(int numCourses, int[][] prerequisites) {
    if (numCourses <= 0) {
        return new int[]{};
    }
    int len = numCourses;
    inCount = new int[len];
    grid = new int[len][len];
    retList = new ArrayList<>();
    ret = new int[len];

    for (int i = 0; i < prerequisites.length; i++) {
        int to = prerequisites[i][0];
        int from = prerequisites[i][1];
        grid[from][to] = 1;
        inCount[to]++;
    }

    for (int i = 0; i < len; i++) {
        if (inCount[i] == 0) {
            queue.add(i);
            retList.add(i);
        }
    }
    while (!queue.isEmpty()) {
        Integer node = queue.poll();
        for (int i = 0; i < len; i++) {
            if (grid[node][i] == 1) {
                grid[node][i] = 0;
                inCount[i]--;
                if (inCount[i] == 0) {
                    queue.add(i);
                    retList.add(i);
                }
            }
        }
    }
    System.out.println(retList);
    //如果节点没有被全部遍历,则代表有环
    if (retList.size() == len) {
        for (int i = 0; i < len; i++) {
            ret[i] = retList.get(i);
        }
        return ret;
    }
    return new int[]{};
}
```





#### [@207. 课程表](https://leetcode-cn.com/problems/course-schedule/)

@思路1 

BFS

@思路2  DFS  这不是排序,而是用flags的0,-1,1代表三种状态,来判断是否有环,如果没有环的话,那一定能满足拓扑排序.

```java
private int[] flags = null;
private int[][] grid = null;
int len = 0;

public boolean canFinish(int numCourses, int[][] prerequisites) {
    this.len = numCourses;
    grid = new int[len][len];
    flags = new int[len];
    for (int i = 0; i < prerequisites.length; i++) {
        int to = prerequisites[i][0];
        int from = prerequisites[i][1];
        grid[from][to] = 1;
    }
    for (int i = 0; i < len; i++) {
        if (!dfs(grid, flags, i)) {
            return false;
        }
    }
    return true;
}

private boolean dfs(int[][] grid, int[] flags, int start) {
    if (flags[start] == 1) {
        return false;
    }
    if (flags[start] == -1) {
        return true;
    }
    flags[start] = 1;
    for (int i = 0; i < len; i++) {
        if (grid[start][i] == 1) {
            if (!dfs(grid, flags, i)) {
                return false;
            }
        }
    }
    flags[start] = -1;
    return true;
}
```



#### [@leetcode.298 二叉树的最长连续子序列](https://blog.csdn.net/jmspan/article/details/51171217)



  

```
@@@@这个题也许可以用动规的思路来做,对于二叉树 2 4 3 5 6 7 8
dp[root] = dp[left] or dp[right]  + 1   ;   if root.val = left.val-1 || right.val-1   

如果4的左右子树里有节点值为 4+1 = 5,那么node.val为4的树的长度序列为 该子树序列长度+1.
这个过程可以被记录进memo
```



```java
int maxLen = 0;

public int longestConsecutive(TreeNode root) {
    if (root == null) {
        return 0;
    }
    int len = 1;
    maxLen = Math.max(len, maxLen);
    TreeNode left = root.left;
    TreeNode right = root.right;
    if (left != null) {
        inOrder(left, len, root.val);
    }
    if (right != null) {
        inOrder(right, len, root.val);
    }
    return maxLen;
}

private void inOrder(TreeNode root, int len, int preVal) {
    if (root == null) {
        return;
    }
    if (root.val != preVal + 1) {
        len = 1;
    } else {
        len = len + 1;
    }
    maxLen = Math.max(len, maxLen);
    TreeNode left = root.left;
    TreeNode right = root.right;
    if (left != null) {
        inOrder(left, len, root.val);
    }
    if (right != null) {
        inOrder(right, len, root.val);
    }
}


public static void main(String[] args) {
    Solution solution = new Solution();
    TreeNode t1 = new TreeNode(1);
    TreeNode t2 = new TreeNode(-1);
    TreeNode t3 = new TreeNode(2);
    TreeNode t4 = new TreeNode(1);
    TreeNode t5 = new TreeNode(4);
    TreeNode t6 = new TreeNode(5);
    t1.right = t2;
    t2.left = t3;
    t3.left = t4;
    t2.right = t5;
    t5.right = t6;
    int i = solution.longestConsecutive(t1);
    System.out.println(i);

}
```









#### [@@面试题51. 数组中的逆序对](https://leetcode-cn.com/problems/shu-zu-zhong-de-ni-xu-dui-lcof/)



```
@@@逆序对的个数 在 nums[leftIndex]>nums[rightIndex]的时候出发
count+=mid-leftIndex+1;意思是,如果左半边的数 5  比右半边的 4  大,则5右边的 6 7 8 都比4大,都能组成逆序对
```



```java
int count = 0;

public int reversePairs(int[] nums) {
    if (nums == null || nums.length == 0) {
        return 0;
    }
    mergeSort(nums, 0, nums.length - 1);
    return count;
}

private void mergeSort(int[] nums, int left, int right) {
    if (left >= right) {
        return;
    }
    int mid = left + (right - left) / 2;
    mergeSort(nums, left, mid);
    mergeSort(nums, mid + 1, right);
    merge(nums, left, right);
}

private void merge(int[] nums, int left, int right) {
    if (left >= right) {
        return;
    }
    int mid = left + (right - left) / 2;
    int len = right - left + 1;
    int index = 0;
    int[] tempNums = new int[len];
    int leftIndex = left;
    int rightIndex = mid + 1;
    while (leftIndex <= mid && rightIndex <= right) {
        if (nums[leftIndex] <= nums[rightIndex]) {
            tempNums[index++] = nums[leftIndex++];
        } else {
            count += mid - leftIndex + 1;
            tempNums[index++] = nums[rightIndex++];
        }
    }
    while (leftIndex <= mid) {
        tempNums[index++] = nums[leftIndex++];
    }
    while (rightIndex <= right) {
        tempNums[index++] = nums[rightIndex++];
    }
    for (int i = 0, j = left; i < len; j++, i++) {
        nums[j] = tempNums[i];
    }
    return;
}
```

#### [@@63. 不同路径 II](https://leetcode-cn.com/problems/unique-paths-ii/)



```
@@思路1.带cache的dfs.需要再写几遍熟练

@@思路2.dp[i][j]代表到达这个位置有多少可能,取决于dp[i-1][j]+dp[i][j-1]  自底向上
@@@@@@@当时还用了另一种搞笑的自底向上: dp[rowCount-1][colCount-1]定为了1,这种想法是错误的!!!!!!
```



```java
//1. cache初始化为-1. 因为cache在等于0的时候依然可能是缓存数据
//2. 不需要visited[][],因为只往右或者往下走
int rowCount = 0;
int colCount = 0;
int[][] loc = new int[][]{{1, 0}, {0, 1}};
int[][] cache = null;
int[][] matrix = null;

public int uniquePathsWithObstacles(int[][] obstacleGrid) {
    if (obstacleGrid == null) {
        return 0;
    }
    matrix = obstacleGrid;
    if (matrix[0][0] == 1) {
        return 0;
    }
    rowCount = matrix.length;
    colCount = matrix[0].length;
    cache = new int[rowCount][colCount];
    for (int i = 0; i < rowCount; i++) {
        for (int j = 0; j < colCount; j++) {
            cache[i][j] = -1;
        }
    }
    return backtracing(0, 0);
}

private int backtracing(int x, int y) {
    int retTemp = 0;
    if (x == rowCount - 1 && y == colCount - 1) {
        return 1;
    }
    if (cache[x][y] != -1) {
        return cache[x][y];
    }
    for (int i = 0; i < loc.length; i++) {
        int newX = x + loc[i][0];
        int newY = y + loc[i][1];
        if (newX >= 0 && newY >= 0 && newX <= rowCount - 1 && newY <= colCount - 1 && matrix[newX][newY] != 1) {
            retTemp += backtracing(newX, newY);
        }
    }
    cache[x][y] = retTemp;
    return cache[x][y];
}




```



```java
int rowCount = 0;
int colCount = 0;
int[][] loc = new int[][]{{1, 0}, {0, 1}};
int[][] dp = null;
int[][] matrix = null;

public int uniquePathsWithObstacles(int[][] obstacleGrid) {
    if (obstacleGrid == null) {
        return 0;
    }
    matrix = obstacleGrid;
    if (matrix[0][0] == 1) {
        return 0;
    }
    rowCount = matrix.length;
    colCount = matrix[0].length;
    dp = new int[rowCount][colCount];
    dp[0][0] = 1;
    for (int i = 1; i < colCount; i++) {
        if (matrix[0][i] == 1) {
            dp[0][i] = 0;
        } else {
            dp[0][i] += dp[0][i - 1];
        }
    }
    for (int i = 1; i < rowCount; i++) {
        if (matrix[i][0] == 1) {
            dp[i][0] = 0;
        } else {
            dp[i][0] += dp[i - 1][0];
        }
    }
    for (int i = 1; i < rowCount; i++) {
        for (int j = 1; j < colCount; j++) {
            if (matrix[i][j] == 1) {
                dp[i][j] = 0;
            } else {
                dp[i][j] = dp[i - 1][j] + dp[i][j - 1];
            }
        }
    }
    return dp[rowCount - 1][colCount - 1];
}
```







#### [单位圆能框住的最多节点数](https://blog.csdn.net/Ramay7/article/details/51147778)

题目：
POJ 1981 Circle and Points
HDU 1077 Catching Fish
题意：
给出n个点的二维点坐标，问单位圆最多能覆盖多少点？
分析：
①：
最优的情况一定是有两个点在圆弧上。先枚举两个点，计算两点在圆弧上的单位圆（一般会有两个）
但是可以统一取一个方向的（也就是AB取一个然后BA取另外一个）.然后枚举所有点,计算在这个单位圆内的点的个数。
这样做的时间复杂度是O(n^3).
②：
对每个点以R为半径画圆，对N个圆两两求交。这一步O(N^2)。问题转化为求被覆盖次数最多的弧。
因为如果最优圆覆盖A点那么最优圆一定在以A点为圆心的圆弧上。那么圆弧倍覆盖多少次也就意味着
以这条圆弧为上任意一点为圆心花园能覆盖多少点。
对每一个圆，求其上的每段弧重叠次数。假如A圆与B圆相交。A上[PI/3, PI/2]的区间被B覆盖(PI为圆周率)。
那么对于A圆，我们在PI/3处做一个+1标记，在PI/2处做一个-1标记。
对于[PI*5/3, PI*7/3]这样横跨0点的区间只要在0点处拆成两段即可。
将一个圆上的所有标记排序，从头开始扫描。初始total=0，碰到+1标记给total++，碰到-1标记total–。
扫描过程中total的最大值就是圆上被覆盖最多的弧。求所有圆的total的最大值就是答案。
极角排序需要2*n*logn，总复杂度O(N^2 * logN)



```python
//1264K 1357MS
#include <iostream>
#include <cstdio>
#include <cstring>
#include <algorithm>
#include <climits>
#include <cmath>
using namespace std;
const int MAX_N=310;
const double eps=1e-6;
const double R=1.0;//定义覆盖圆半径为R

int T,n;

struct Point{
    double x,y;
}point[MAX_N];

inline double dis(Point a,Point b)
{
    return sqrt((a.x-b.x)*(a.x-b.x)+(a.y-b.y)*(a.y-b.y));
}

inline Point GetCenter(Point a,Point b)
{//获取a,b两点在圆周上的单元圆圆心,单位圆圆心有两个
    struct Point mid,res;
    mid.x=(a.x+b.x)/2,mid.y=(a.y+b.y)/2;//mid是a,b中点坐标
    double angle=atan2(b.y-a.y,b.x-a.x);//angle是直线ab的倾斜角
    double tmp=dis(a,b)/2;//tmp是线段ab长度的一半
    double d=sqrt(1.0-tmp*tmp);//d是ab中点到圆心的距离
    res.x=mid.x-d*sin(angle);//res是直线ab左边的那个圆心
    res.y=mid.y+d*cos(angle);
    //下面的res是直线ab右边的那个圆心
    //res.x=mid.x+d*sin(angle);
    //res.y=mid.y-d*cos(angle);
    return res;
}

int main()
{
    scanf("%d",&T);
    while(T--){
        scanf("%d",&n);
        for(int i=0;i<n;i++){
            scanf("%lf%lf",&point[i].x,&point[i].y);
        }
        int ans=1;//初始化至少能覆盖一个点！！！
        for(int i=0;i<n;i++){
            for(int j=0;j<n;j++){
                if(i==j||dis(point[i],point[j])-2*R>eps) continue;
                int cnt=0;
                struct Point center=GetCenter(point[i],point[j]);
                for(int k=0;k<n;k++){
                    if(dis(point[k],center)-R<=eps) cnt++;
                }
                ans=max(ans,cnt);
            }
        }
        printf("%d\n",ans);
    }
    return 0;
}
```



#### [@@@四种操作求A的最大次数](https://blog.csdn.net/qq_40147449/article/details/93376889)

```
思路 
@ i为2之前  dp[i]max  = i
@ dp[i] 的状态过程有三类   一种是从j开始全选,复制 一直粘贴,二种是i-2开始打印两个,三种是i-1开始 打印一个
dp[i] = Max(dp[i-1]+1,dp[i-2]+2,dp[j]*(i-j+1)); j从2到i-2;

@@dp[i] 初始化为 i
```



```
描述
假设你有一个特殊的键盘，键盘上有如下键:

键1: (A): 在屏幕上打印一个’A’。
键2: (Ctrl-A): 选择整个屏幕。
键3: (Ctrl-C): 复制选择到缓冲区。
键4: (Ctrl-V): 在屏幕上已有的内容后面追加打印缓冲区的内容。
现在，你只能按键盘上N次(使用以上四个键)，找出你可以在屏幕上打印的“A”的最大数量

样例
1
输入: 3
输出: 3
解释: A, A, A

2
输入: 7
输出: 9
解释: A, A, A, Ctrl A, Ctrl C, Ctrl V, Ctrl V

注意事项
1 <= N <= 50
答案将在32位有符号整数的范围内。

思路
动态规划
dpi表示i个操作所能得到的最多的A的个数
初始状态下 dpi=0，当i<=6的时候容易得到dpi=i
对于任意dpi 可以省去j个操作
j=1 dpi=1+dpi-1
j=2 dpi=2+dpi-2
当j>2的时候，可以全选 复制 粘贴，所以dpi = j * dp(i-1-j)
取其中最大值即可
```



```java
public int maxA(int n) {
    if (n <= 0) {
        return 0;
    }
    int[] dp = new int[n + 1];
    for (int i = 0; i <= n; i++) {
        if (i <= 2) {
            dp[i] = i;
            continue;
        }else{
            //初始化一个状态,dp[i]处的至少有这么多个字母
            dp[i] = i;
        }
        //全选,复制,粘贴至少从第二位开始
        //最多提前两位操作   比如 i= 8  6全选,7复制,8粘贴
        //j从第二位,开始.依次计算全选,复制,粘贴,粘贴...粘贴一共 (i-j-1)次 ,
        // 粘贴量为dp[j]处A的个数
        for (int j = 2; j <= i - 2; j++) {
            dp[i] = Math.max(dp[i], (i - j - 1) * dp[j]);
        }
        int preTwoEasyAdd = Math.max(dp[i - 1] + 1, dp[i - 2] + 2);
        dp[i] = Math.max(dp[i], preTwoEasyAdd);
    }
    System.out.println(dp[n]);
    return dp[n];
}
```



#### 点集旋转

作者：Ire1ia
链接：https://www.nowcoder.com/discuss/373413?type=post&order=time&pos=&page=2
来源：牛客网

二维平面上有一个点集P, 另外点集外有一个点P0, 现在令P中的所有点绕P0旋转，求旋转的角度为多少时, P中的所有点能与原位置重合. 我的答案是将P中的点按照与P0的距离划分成一些子集, 每个子集分别枚举可能的旋转角度, 判断是否与初始位置重合, 最后各个子集的答案求一个最小公倍数即可.

比如正方形四个角为点集,中心点为P0



#### [@@面试题 16.06. 最小差](https://leetcode-cn.com/problems/smallest-difference-lcci/)

```
@binarySearch返回的值  如果是0~len-1 则找到了target.如果是负数,则负数结果为  -insertPositon-1  可以用

insetPostion = -(  -insertPositon-1 ) -1;还原.

还原之后,因为insertPostion代表第一个大于tartget的数字的位置.所以,  
如果是 0 则 只需要计算b[0]-target;
如果结果是len,则只需要计算target - b[len -1].
其他1~len-1,左右两边都需要计算.

diff要判断是否大于0,是为了防止 
[-2147483648,1]
[0,2147483647]
当target = -2147483648时,index = 0.
但是b[index]-target 不是整数(2147483648会被淘汰),而是负数了,负数就会被取到,就不符合题意了.
```



```java
public int smallestDifference(int[] a, int[] b) {
    if (a == null || b == null) {
        return 0;
    }
    int ret = Integer.MAX_VALUE;
    Arrays.sort(a);
    Arrays.sort(b);
    for (int i = 0; i < a.length; i++) {
        int target = a[i];
        int index = Arrays.binarySearch(b, target);
        int len = b.length;
        if (index >= 0) {
            return 0;
        }
        index = -index - 1;
        if (index == 0) {
            int diff = b[index] - target;
            if (diff > 0) {
                ret = Math.min(ret, diff);
            }
        } else if (index == len) {
            int diff = target - b[index - 1];
            if (diff > 0) {
                ret = Math.min(ret, diff);
            }
        } else {
            int diff = b[index] - target;
            if (diff > 0) {
                ret = Math.min(ret, diff);
            }
            diff = target - b[index - 1];
            if (diff > 0) {
                ret = Math.min(ret, diff);
            }
        }
    }
    return ret;
}
```



#### [@670. 最大交换](https://leetcode-cn.com/problems/maximum-swap/)

```java
public int maximumSwap(int num) {
    PriorityQueue<Integer> queue = new PriorityQueue<Integer>(10, (o1, o2) -> (o2 - o1));
    int numLen = 0;
    List<Integer> list = new ArrayList<Integer>();
    while (num != 0) {
        list.add(0, num % 10);
        queue.add(num % 10);
        num = num / 10;

    }
    for (int i = 0; i < list.size(); i++) {
        if (list.get(i) == queue.peek()) {
            queue.poll();
        } else {
            for (int j = list.size() - 1; j > i; j--) {
                if (list.get(j) == queue.peek()) {
                    int temp = list.get(j);
                    list.set(j, list.get(i));
                    list.set(i, temp);
                    break;
                }
            }
            break;
        }
    }
    num = 0;
    for (int i = 0; i < list.size(); i++) {
        num = num * 10 + list.get(i);
    }
    return num;
}
```





#### [@@@@50. Pow(x, n)](https://leetcode-cn.com/problems/powx-n/)

@@@看注释,此题细节非常多

//优化  @@对半计算  1 和 0 和 -1 可以优化  

```java
//指数:
//  -1 -2 -3
//   1  2  3


//底数
// 正  负  0

//越界 n 的 负数越界问题

//重复数字  用优先队列来解决

//优化  @@对半计算  1 和 0 和 -1 可以优化  2也可以优化左移

public double myPow(double x, int n) {
    //x 为正
    //n为负数,就一定要去 分之一
    //x为负 且n为奇数  考虑符号
    boolean isNegative = false;
    boolean oneDivid = false;
    if (n == 0) {
        return 1;
    }

    long N = n;
    if (n < 0) {
        oneDivid = true;
        //负的Integer.MIN_VALUE依然为负,所以这里不可以用N = -n
        N = -N;
    }
    if (x < 0) {
        x = -x;
        if (N % 2 == 1) {
            isNegative = true;
        }
    }

    double curRet = x;
    double ret = 1;
    //拿N= 7 举例
    // ret 是 x的7次方
    //i=7时,进入循环 可以把 x的7次方拆分成  一个x(放入ret) 和 3个 x*x
    //i = 3. 此时可以把 3个x*x  拆分成  一个 x*x(放入ret)  和  1个 x*x*x*x
    //此时i= 1.此时 把 1个 x*x*x*x放入ret. 
    //i=0跳出循环
    for (long i = N; i > 0; i /= 2) {
        if ((i % 2) == 1) {
            ret = ret * curRet;
        }
        curRet = curRet * curRet;
    }


    ret = isNegative ? -ret : ret;
    ret = oneDivid ? 1 / ret : ret;
    return ret;
}
```







#### [@@89. 格雷编码](https://leetcode-cn.com/problems/gray-code/)

镜像  01

00  01  |  在首位添1,同时镜像添加数据  11  10 

00  01  11 10 |  110 111 101 100  

```java
public List<Integer> grayCode(int n) {
    List<Integer> ret = new ArrayList<Integer>();
    if (n <= 0) {
        ret.add(0);
        return ret;
    }

    int headAdd = 1;
    ret.add(0);
    ret.add(1);

    for (int i = 2; i <= n; i++) {
        headAdd = headAdd * 2;
        for (int j = ret.size() - 1; j >= 0; j--) {
            ret.add(ret.get(j) + headAdd);
        }
    }
    return ret;
}
```





#### [@53. 最大子序和](https://leetcode-cn.com/problems/maximum-subarray/)

dp[i]表示以nums[i]结尾的和的最大值,而且前面丢不丢弃已经设置好了

```java
   public int maxSubArray(int[] nums) {
        if(nums==null||nums.length==0){
            return 0;
        }
        int len = nums.length;
        int [] dp = new int[len];
        dp[0] = nums[0];
        int max = nums[0];
        for(int i =1;i<len;i++){
            dp[i] =Math.max(dp[i-1]+nums[i],nums[i]);
            max = Math.max(dp[i],max);
        }
        return max;
    }
```



#### 单例模式

@构造器私有化

@双重校验+一个类锁

@内部遍历加volatile,static,private

volatile是为了防止指令重排,导致内存分配了,但是没有初始化,就把单例返回了回去

@获取单例的函数式static的

```java
private static volatile Singleton uniqueSingleton;

private Singleton() {
}

public static Singleton getUniqueSingleton() {
    if (uniqueSingleton == null) {
        synchronized (Singleton.class) {
            if (uniqueSingleton == null) {
                uniqueSingleton = new Singleton();
            }
        }
    }
    return uniqueSingleton;
}

public static void main(String[] args) {
    FileTypeMap defaultFileTypeMap = MimetypesFileTypeMap.getDefaultFileTypeMap();
    MimeType mimeType = new MimeType();
    mimeType.getBaseType();
}

```







#### [@@@@@752. 打开转盘锁](https://leetcode-cn.com/problems/open-the-lock/)

@@@@@@这种不求全部路径,而是求最短路径长度类的题目,一般是BFS.

因为找到最短路径的长度就可以退出了

带条件的BFS

用提前插入一个null来区分层次

```java
public int openLock(String[] deadends, String target) {

        HashSet<String> used = new HashSet<>();
        HashSet<String> dead = new HashSet<>();
        Queue<String> queue = new LinkedList<String>();
        for (int i = 0; i < deadends.length; i++) {
            dead.add(deadends[i]);
        }
        if (dead.contains("0000") || dead.contains(target)) {
            return -1;
        }
        int depth = 0;
        queue.add("0000");
        used.add("0000");
    //添加null,分开层数
        queue.add(null);
        while (!queue.isEmpty()) {
            String node = queue.poll();
            //如果node为空
            //加层数
            //如果queue里面还有node,加一个null来区分
            if (node == null) {
                depth++;
                if (!queue.isEmpty()) {
                    queue.add(null);
                } else {
                    break;
                }
            } else if (node.equals(target)) {
                return depth;
            } else {
                for (int i = 0; i < target.length(); i++) {
                    for (int d = -1; d <= 1; d = d + 2) {
                        int tempNum = node.charAt(i) - '0' + d;
                        //+10  再 %10
                        tempNum = (tempNum + 10) % 10;
                        //substring(0,0)也可以
                        String temp = node.substring(0, i) + tempNum + node.substring(i + 1);
                        //如果used  dead都符合条件
                        if (!used.contains(temp) && !dead.contains(temp)) {
                            used.add(temp);
                            queue.add(temp);
                        }
                    }
                }
            }
        }
        return -1;
    }
```







#### [掷骰子的数学期望](https://www.zhihu.com/question/30470526)

```
掷骰子，掷到几点就给几块钱，你觉得掷得小可以重来，但不能反悔，最多九次机会可以重来。掷骰子的人想获得最好的收益，什么样的策略最科学？
问题发散：骰子是1到6确定的数字，如果是一个不确定的随机范围，想获得最好的收益，什么样的策略比较科学？（人生中好多选择就类似这种模型，并不是同时提供所有的选择供你比较，而是当你拒绝一个选择，才会给你第二个选择，有的时候第二次随机的结果不如第一次，但是已经没有机会了）
```

```
从后往前想,
当我只剩最后一次掷骰子的时候,数学期望是3.5  ( 1+2+3+4+5+6)* 1/6
那我剩余两次的时候的数学期望是  (4+5+6) * 1/6  再加上  (3.5+3.5+3.5)*1/6  因为我如果掷出来1,2,3
由于下一次的数学期望高于1,2,3所以我遇到1,2,3会选择扔最后一次,最后一次的期望是3.5.  
最后求出来,剩余两次的期望是4.25 


```

公式为设剩余次数 n 时, 预期的点数期望为dp[n]

只要本次点数比剩余期望大就行.

<img src="pictures/LeetCode03/image-20200323141458248.png" alt="image-20200323141458248" style="zoom:55%;" />

<img src="pictures/LeetCode03/image-20200323141541535.png" alt="image-20200323141541535" style="zoom:50%;" />















#### [915. 分割数组](https://leetcode-cn.com/problems/partition-array-into-disjoint-intervals/)



```java
class Solution {
    public int partitionDisjoint(int[] A) {
        int N = A.length;
        int[] maxleft = new int[N];
        int[] minright = new int[N];

        int m = A[0];
        for (int i = 0; i < N; ++i) {
            m = Math.max(m, A[i]);
            maxleft[i] = m;
        }

        m = A[N-1];
        for (int i = N-1; i >= 0; --i) {
            m = Math.min(m, A[i]);
            minright[i] = m;
        }

        for (int i = 1; i < N; ++i)
            if (maxleft[i-1] <= minright[i])
                return i;

        throw null;
    }
}
```







#### [@@@@991. 坏了的计算器](https://leetcode-cn.com/problems/broken-calculator/)

这个题的贪心算法太取巧了,

@也可以用BFS来做

```java
public int brokenCalc(int X, int Y) {
    int ret = 0;
    while (Y > X) {
        ret++;
        if (Y % 2 == 1) {
            Y++;
        } else {
            Y /= 2;
        }
    }
    ret = ret + (X - Y);
    return ret;
}
```





#### [@@@@@227. 基本计算器 II](https://leetcode-cn.com/problems/basic-calculator-ii/)

```java
 public int calculate(String s) {
        int index = 0;
        int num = 0;
        char preCal = '+';
        int len = s.length();

        if (s.charAt(0) == '-') {
            index++;
        } else if (s.charAt(0) == '+') {
            index++;
        }
        Stack<Integer> stack = new Stack<Integer>();
        while (index <= len) {
            if (index < len && s.charAt(index) == ' ') {
                index++;
                continue;
            }
            if (index < len && s.charAt(index) >= '0' && s.charAt(index) <= '9') {
                num = num * 10 + s.charAt(index) - '0';
            } else {
                if (preCal == '-') {
                    stack.push(-num);
                } else if (preCal == '+') {
                    stack.push(num);
                } else if (preCal == '/') {
                    int temp = stack.pop();
                    stack.push(temp / num);
                } else if (preCal == '*') {
                    int temp = stack.pop();
                    stack.push(temp * num);
                }
                if (index < len) {
                    preCal = s.charAt(index);
                }
                num = 0;
            }
            index++;
        }
        int ret = 0;
        while (!stack.isEmpty()) {
            ret += stack.pop();
        }
        return ret;
    }
```



#### [@@删除回文子序列](https://leetcode-cn.com/problems/remove-palindromic-subsequences/)

```
回文子序列而非回文子串,先删除aaaa... 如果还有b就删除b
```





#### @@@@[Leetcode 1246：删除回文子数组](https://coordinate.wang/index.php/archives/2737/)

状态转移方程



```
 a  ****  a  cde

dp[start][end] = Math.min(dp[start][end],dp[start+1][k-1]+dp[k+1][end])

若start处的a等于k处的a.则删除k处的a和start处的a,可以被附加到子串start+1 ~k-1上,因为哪怕start+1~k-1
一个回文串也没有,比如只有cdf 此时dp[start+1][k-1] =3.  两个a依然可以被附加到 cdf任意一个回文串上来
删除.


```





<img src="pictures/LeetCode03/image-20200327193550768.png" alt="image-20200327193550768" style="zoom:50%;" />

```java
class Solution {
    private static int func(int[] nums) {
        int n = nums.length;
        int[][] dp = new int[n + 1][n + 1];
        for (int i = 0; i <= n; i++) {
            dp[i][i] = 1;
        }
        for (int l = 1; l <= n; l++) {
            for (int start = 0, end = l - 1; end < n; start++, end++) {
                for (int k = start; k <= end; k++) {
                    if (k == start) {
                        dp[start][end] = 1 + dp[start + 1][end];
                        continue;
                    } else if (k == start + 1 && nums[k] == nums[start]) {
                        dp[start][end] = Math.min(dp[start][end], 1 + dp[k + 1][end]);
                    } else if (k >= start + 2 && nums[k] == nums[start]) {
                        dp[start][end] = Math.min(dp[start][end], dp[start + 1][k - 1] + dp[k + 1][end]);
                    }
                }
            }

        }
        return dp[0][n - 1];
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        int[] nums = new int[]{5, 9, 1, 3, 4, 1, 5};
        System.out.println(func(nums));
    }
}
```



#### [328. 奇偶链表](https://leetcode-cn.com/problems/odd-even-linked-list/)

<img src="pictures/LeetCode03/image-20200327193829378.png" alt="image-20200327193829378" style="zoom:50%;" />





#### [@@179. 最大数](https://leetcode-cn.com/problems/largest-number/)



```
错误!!!
public int compare(int n1,int n2){
	String num1 = ""+n1;
	String num2 = ""+n2;
	return num2.compareTo(num1);
}
```



**这样写是为了杜绝   50   和 5 的排序,**

**上面的写法,因为 5 小于50   所以排序为 505** 

**下面的写法,因为505 小于 550  所以排序为 550**

```
public int compare(int n1,int n2){
	String order1 = ""+n1+n2;
	String order2 = ""+n2+n1;
	return order2.compareTo(order1);
}
```





#### [@@@69. x 的平方根](https://leetcode-cn.com/problems/sqrtx/)

@@ long square =  int * int.得到的依然是溢出的int 

所以需要 long square = (long) mid * (long) mid;



 @@小于的时候,是mid本身
 left = mid;



@@二分法的思路

```java
public int mySqrt(int x) {
        if (x == 0) {
            return 0;
        }
        int left = 1;
        int right = x / 2;
        while (left < right) {
            int mid = left + (right - left) / 2 + 1;
            long square = (long) mid * (long) mid;
            if (square == x) {
                return mid;
            } else if (square > x) {
                right = mid - 1;
            } else {
                //小于的时候,是mid本身
                left = mid;
            }
        }
        return left;
    }
```



#### @@@@@@从十亿数字中,求第k位数字,用快排.

从十亿数字中,求第k位数字,用**快排**

求前k位大的数字,用一个大小为k的**小顶堆**  或者 **快排**





#### [@@973. 最接近原点的 K 个点](https://leetcode-cn.com/problems/k-closest-points-to-origin/)



1.求平方和用long来存储.

2.只求平方和就行,不需要sqrt

3.总体思路: 求平方和,排序,求第k大的平方和,再扫一遍求出前k个.





#### [1375. 灯泡开关 III](https://leetcode-cn.com/problems/bulb-switcher-iii/)

```java
思路1:模拟
public int numTimesAllBlue(int[] light) {
    int onCutIndex = 0;
    int blueMomentCount = 0;
    PriorityQueue<Integer> queue = new PriorityQueue<Integer>(10, (o1, o2) -> (o1 - o2));
    for (int i = 0; i < light.length; i++) {
        int curLight = light[i];
        if (curLight == onCutIndex + 1) {
            onCutIndex++;
            while (!queue.isEmpty() && onCutIndex + 1 == queue.peek()) {
                queue.poll();
                onCutIndex++;
            }
            if (queue.isEmpty()) {
                blueMomentCount++;
            }
        } else {
            queue.add(curLight);
        }
    }
    return blueMomentCount;
}


思路2: // 若点亮最远的灯的位置大于此时点亮灯的个数，则意味着在点亮最远的灯的位置之前存在着未点亮的灯。

class Solution {
    //这题关键是读懂题目含义，
    // 让所有开着的灯都变成蓝色的时刻的性质是：此时点亮最远的灯的位置恰巧等于点亮灯的个数。
    // 若点亮最远的灯的位置大于此时点亮灯的个数，则意味着在点亮最远的灯的位置之前存在着未点亮的灯。
    public int numTimesAllBlue(int[] light) {
        int size = light.length;
        int count = 0, maxReachingPoint = 0;
        for (int i = 0 ; i < size; i++){
            maxReachingPoint = Math.max(maxReachingPoint, light[i]);
            if ( i + 1 == maxReachingPoint){
                count += 1;
            }
        }
        return count;
    }
```





#### [@@581. 最短无序连续子数组](https://leetcode-cn.com/problems/shortest-unsorted-continuous-subarray/)

```java
public int findUnsortedSubarray(int[] nums) {
    int len = nums.length;
    int[] leftMax = new int[len];
    int[] rightMin = new int[len];
    int max = nums[0];
    int min = nums[len - 1];
    leftMax[0] = max;
    rightMin[len - 1] = min;
    for (int i = 0; i < len; i++) {
        if (nums[i] > max) {
            max = nums[i];

        }
        leftMax[i] = max;
    }
    for (int i = len - 1; i >= 0; i--) {
        if (nums[i] < min) {
            min = nums[i];
        }
        rightMin[i] = min;
    }
    int leftCut = 0;
    int rightCut = len - 1;
    for (int i = 0; i < len; i++) {
        if (leftMax[i] > rightMin[i]) {
            leftCut = i;
            break;
        }
    }
    for (int i = len - 1; i >= 0; i--) {
        if (rightMin[i] < leftMax[i]) {
            rightCut = i;
            //应对 3  2  1
            return rightCut - leftCut + 1;
        }
    }
    //应对  1 2  3
    return 0;
}
```



#### [@@@@@@769. 最多能完成排序的块](https://leetcode-cn.com/problems/max-chunks-to-make-sorted/)

一个区间内最大的数字，不应该大于这个区间最右边的index。因此我们从左向右遍历，如果已经观测到的最大值小于等于这个区间的index，则可以划分区间。

```java
class Solution {
    public int maxChunksToSorted(int[] arr) {
        int ans = 0, max = 0;
        for (int i = 0; i < arr.length; ++i) {
            max = Math.max(max, arr[i]);
            if (max == i) ans++;
        }
        return ans;
    }
}

```





#### @@元素的技巧(如果大于左边最大值,小于右边最小值,该元素排序后依然在该位置上)

#### @@缝隙的技巧(如果大于前缀最大值,小于后缀最小值,则是分界元素)



#### @@@@划分最多的最短无序连续子数组

作者：Ire1ia
链接：https://www.nowcoder.com/discuss/373413?type=post&order=create&pos=&page=2
来源：牛客网

算法题: 一个整数数组, 将这个数组划分为一些连续的子数组, 将各个子数组内部元素进行排序后，整个数组是有序的，问最多能切成多少个子数组. 这题确实没见过, 不知道是不是leetcode上的, 我先是用dp写了个O(n^2)的, 面试官在看我的代码, 我趁这个时间又思考了几分钟, 发现这题可以用O(n)的贪心解决(对于每个缝隙, 如果前缀的最大值小于等于后缀的最小值, 那么就可以在这里切), 



```java
 public int findUnsortedSubarray(int[] nums) {
        int len = nums.length;
        //len个数字,有len-1个缝隙,在每个缝隙处,如果左边的最大值小于右边的最小值,就可以从这里切分
        //原因:缝隙两边的数字不会越过缝隙,
        int[] leftMax = new int[len - 1];
        int[] rightMin = new int[len - 1];
        int max = nums[0];
        int min = nums[len - 1];
    
        leftMax[0] = max;
        for (int i = 1; i <= len - 2; i++) {
            if (nums[i] > max) {
                max = nums[i];
            }
            leftMax[i] = max;
        }

        //缝隙是0~len-2
        // 缝隙为i的时候,缝隙右边的数字为i+1
        rightMin[len - 2] = min;
        for (int i = len - 3; i >= 0; i--) {
            if (nums[i + 1] < min) {
                min = nums[i + 1];
            }
            rightMin[i] = min;
        }

        List<Integer> list = new ArrayList<>();
        int cnt = 0;
        //如果缝隙处,如果左边的最大值 小于等于  右边的最小值,就可以从这里切分
        //原因:缝隙两边的数字不会越过缝隙,
        for (int i = 0; i <= len - 2; i++) {
            if (leftMax[i] <= rightMin[i]) {
                list.add(i);
                cnt++;
            }
        }
        //输出切分的缝隙
        for (int temp : list) {
            System.out.println(temp);
        }
        return cnt + 1;
    }

    public static void main(String[] args) {
        Scanner sc = new Scanner(System.in);
        Solution solution = new Solution();
        int i = solution.findUnsortedSubarray(new int[]{3, 9, 9});
        System.out.println(i);
    }
```





#### [@@292. Nim 游戏](https://leetcode-cn.com/problems/nim-game/)

```
推理

让我们考虑一些小例子。显而易见的是，如果石头堆中只有一块、两块、或是三块石头，那么在你的回合，你就可以把全部石子拿走，从而在游戏中取胜。而如果就像题目描述那样，堆中恰好有四块石头，你就会失败。因为在这种情况下不管你取走多少石头，总会为你的对手留下几块，使得他可以在游戏中打败你。因此，要想获胜，在你的回合中，必须避免石头堆中的石子数为 4 的情况。

同样地，如果有五块、六块、或是七块石头，你可以控制自己拿取的石头数，总是恰好给你的对手留下四块石头，使他输掉这场比赛。但是如果石头堆里有八块石头，你就不可避免地会输掉，因为不管你从一堆石头中挑出一块、两块还是三块，你的对手都可以选择三块、两块或一块，以确保在再一次轮到你的时候，你会面对四块石头。

显然，它以相同的模式不断重复 n=4,8,12,16,\dotsn=4,8,12,16,…，基本可以看出是 44 的倍数。

作者：LeetCode
链接：https://leetcode-cn.com/problems/nim-game/solution/nimyou-xi-by-leetcode/
来源：力扣（LeetCode）
著作权归作者所有。商业转载请联系作者获得授权，非商业转载请注明出处。
```



#### [36. 有效的数独](https://leetcode-cn.com/problems/valid-sudoku/)



9个行map,9个列map,9个boxmap,

```java
HashMap<Integer, Integer> [] rows = new HashMap[9];
    HashMap<Integer, Integer> [] columns = new HashMap[9];
    HashMap<Integer, Integer> [] boxes = new HashMap[9];
    for (int i = 0; i < 9; i++) {
      rows[i] = new HashMap<Integer, Integer>();
      columns[i] = new HashMap<Integer, Integer>();
      boxes[i] = new HashMap<Integer, Integer>();
    }

```



#### [150. 逆波兰表达式求值](https://leetcode-cn.com/problems/evaluate-reverse-polish-notation/)

```java
挺简单的,主要注意 
    乘法要考虑溢出问题
    
public int evalRPN(String[] tokens) {
        Stack<Integer> stack = new Stack<>();
        Integer op1, op2;
        for (String s : tokens) {
            if (s.equals("+")) {
                op2 = stack.pop();
                op1 = stack.pop();
                stack.push(op1 + op2);

            } else if (s.equals("-")) {
                op2 = stack.pop();
                op1 = stack.pop();
                stack.push(op1 - op2);
            } else if (s.equals("*")) {
                op2 = stack.pop();
                op1 = stack.pop();
                stack.push(op1 * op2);
            } else if (s.equals("/")) {
                op2 = stack.pop();
                op1 = stack.pop();
                stack.push(op1 / op2);
            } else {
                stack.push(Integer.valueOf(s));
            }
        }
        return stack.pop();
    }
```





#### [@@@@659. 分割数组为连续子序列](https://leetcode-cn.com/problems/split-array-into-consecutive-subsequences/)



```java
@@@@@注意要先从小数字开始!!!!!!!!!!
思路:如果tail[cur-1]存在,则把cur接到后面,如果不存在,则观察 cur+1  cur+2 存在则 tain[cur+2]+1

public boolean isPossible(int[] nums) {
    HashMap<Integer, Integer> numCount = new HashMap<>();
    HashMap<Integer, Integer> tailMemo = new HashMap<>();
    for (int cur : nums) {
        numCount.put(cur, numCount.getOrDefault(cur, 0) + 1);
    }
    for (int cur : nums) {
        if (numCount.getOrDefault(cur, 0) == 0) {
            continue;
        } else if (tailMemo.getOrDefault(cur - 1, 0) > 0) {
            numCount.put(cur, numCount.get(cur) - 1);

            tailMemo.put(cur - 1, tailMemo.get(cur - 1) - 1);
            tailMemo.put(cur, tailMemo.getOrDefault(cur, 0) + 1);
        } else if (numCount.getOrDefault(cur + 1, 0) > 0 && numCount.getOrDefault(cur + 2, 0) > 0) {
            numCount.put(cur, numCount.get(cur) - 1);
            numCount.put(cur + 1, numCount.get(cur + 1) - 1);
            numCount.put(cur + 2, numCount.get(cur + 2) - 1);

            tailMemo.put(cur + 2, tailMemo.getOrDefault(cur + 2, 0) + 1);
        } else {
            return false;
        }
    }
    return true;
}


比较清晰的写法
    
    class Solution {
    public boolean isPossible(int[] nums) {
        Counter count = new Counter();
        Counter tails = new Counter();
        for (int x: nums) count.add(x, 1);

        for (int x: nums) {
            if (count.get(x) == 0) {
                continue;
            } else if (tails.get(x) > 0) {
                tails.add(x, -1);
                tails.add(x+1, 1);
            } else if (count.get(x+1) > 0 && count.get(x+2) > 0) {
                count.add(x+1, -1);
                count.add(x+2, -1);
                tails.add(x+3, 1);
            } else {
                return false;
            }
            count.add(x, -1);
        }
        return true;
    }
}

class Counter extends HashMap<Integer, Integer> {
    public int get(int k) {
        return containsKey(k) ? super.get(k) : 0;
    }

    public void add(int k, int v) {
        put(k, get(k) + v);
    }
}
```





#### [@@@@@@877. 石子游戏](https://leetcode-cn.com/problems/stone-game/)



```java
博弈题目

  //  状态转移:先手:
dp[i][j].fir = max(piles[i] + dp[i+1][j].sec, piles[j] + dp[i][j-1].sec)
dp[i][j].fir = max(    选择最左边的石头堆     ,     选择最右边的石头堆     )
# 解释：我作为先手，面对 piles[i...j] 时，有两种选择：
# 要么我选择最左边的那一堆石头，然后面对 piles[i+1...j]
# 但是此时轮到对方，相当于我变成了后手；
# 要么我选择最右边的那一堆石头，然后面对 piles[i...j-1]
# 但是此时轮到对方，相当于我变成了后手。

  //  状态转义:后手:
if 先手选择左边:
    dp[i][j].sec = dp[i+1][j].fir
if 先手选择右边:
    dp[i][j].sec = dp[i][j-1].fir
# 解释：我作为后手，要等先手先选择，有两种情况：
# 如果先手选择了最左边那堆，给我剩下了 piles[i+1...j]
# 此时轮到我，我变成了先手；
# 如果先手选择了最右边那堆，给我剩下了 piles[i...j-1]
# 此时轮到我，我变成了先手。

 //base  case
     
dp[i][j].fir = piles[i]
dp[i][j].sec = 0
其中 0 <= i == j < n
# 解释：i 和 j 相等就是说面前只有一堆石头 piles[i]
# 那么显然先手的得分为 piles[i]
# 后手没有石头拿了，得分为 0



public boolean stoneGame(int[] piles) {
        int n = piles.length;
        int[][][] dp = new int[n][n][2];
        //边界
        for (int i = 0; i < n; i++) {
            dp[i][i][0] = piles[i];
            dp[i][i][1] = 0;
        }
        for (int l = 2; l <= n; l++) {
            //n - l
            for (int i = 0; i <= n - l; i++) {
                int j = l + i - 1;
                int left = piles[i] + dp[i + 1][j][1];
                int right = piles[j] + dp[i][j - 1][1];
                if (left > right) {
                    dp[i][j][0] = left;
                    dp[i][j][1] = dp[i + 1][j][0];
                } else {
                    dp[i][j][0] = right;
                    dp[i][j][1] = dp[i][j - 1][0];
                }
            }
        }
        return (dp[0][n - 1][0] - dp[0][n - 1][1]) > 0 ? true : false;
    }
```





#### [@@编程算法题—硬币游戏](https://blog.csdn.net/guangyacyb/article/details/80173509)

```java
题目：两个玩家（甲，乙）玩游戏，有一个长度为n的乱序数组（数组每个元素代表一个硬币，数值代表硬币面值），甲乙轮流拿硬币（可以拿走最左边的一个或者两个硬币，拿走不放回），问先玩的玩家是否一定能赢



这种题目的思路一般是动态规划：

假设存有硬币的数组为a，并且双方都会取当前情况下能取到的最多数值！！！

为了方便，a[i]表示从末尾开始的第i枚硬币的数值

用sum[i]表示从0开始到下标i的硬币数字和

best[i]表示当取到剩下i枚硬币时最优的取法能取到的数值

所以有：

best[1]是第1枚硬币的数值

best[2]是第1+2枚硬币的数值之和

best[3]是第2+3枚硬币的数值之和

best[4]有两种取法，一种是取a[4]，然后因为对方也不是吃素的，所以他会取best[3]，所以我能取到的只能是sum[3]-best[3]；另一种取法是取a[4]+a[3]，然后对方取best[2]，我取sum[2]-best[2]，这就基本是动态规划的情况了

以上归纳为：

best[k]（k>4）有两种取法:

1：取a[k] +sum[k-1]-best[k-1]

2： 取a[k] + a[k-1] + sum[k-2] + best[k-2]

则best[k]等于这两个取法的较大值，最后求出best[n]，如果best[n] > sum[n] / 2的话，则先取的人赢了，否则会输。至于是否先取就能赢，还没想到，烦请路过的网友给点提示~\
```



#### [5369. 统计作战单位数](https://leetcode-cn.com/problems/count-number-of-teams/)

```JAVA
public int numTeams(int[] rating) {
    int ret = 0;
    for (int i = 1; i <= rating.length - 2; i++) {
        int biggerLeft = 0;
        int smallerLeft = 0;
        int biggerRight = 0;
        int smallerRight = 0;
        int curRate = rating[i];
        for (int j = 0; j < i; j++) {
            if (rating[j] > curRate) {
                biggerLeft++;
            } else {
                smallerLeft++;
            }
        }
        for (int j = rating.length - 1; j > i; j--) {
            if (rating[j] > curRate) {
                biggerRight++;
            } else {
                smallerRight++;
            }
        }
        ret += biggerLeft * smallerRight + smallerLeft * biggerRight;
    }
    return ret;
}
```



#### [5370. 设计地铁系统](https://leetcode-cn.com/problems/design-underground-system/)



```java
class UndergroundSystem {
    private HashMap<Integer, String> id_stationName = new HashMap<>();
    private HashMap<Integer, Integer> id_t = new HashMap<>();
    private HashMap<String, Double> trip_TimeSum = new HashMap<>();
    private HashMap<String, Integer> trip_CountSum = new HashMap<>();

    public UndergroundSystem() {

    }

    public void checkIn(int id, String stationName, int t) {
        id_t.put(id, t);
        id_stationName.put(id, stationName);
    }

    public void checkOut(int id, String stationName, int t) {
        String startStation = id_stationName.get(id);
        Integer startTime = id_t.get(id);

        String tripName = startStation + "#" + stationName;
        Integer tripTime = t - startTime;

        if (trip_TimeSum.containsKey(tripName)) {
            trip_TimeSum.put(tripName, trip_TimeSum.get(tripName) + (double) tripTime);
            trip_CountSum.put(tripName, trip_CountSum.get(tripName) + 1);
        } else {
            trip_TimeSum.put(tripName, (double) tripTime);
            trip_CountSum.put(tripName, 1);
        }
    }

    public double getAverageTime(String startStation, String endStation) {
        String tripName = startStation + "#" + endStation;
        if (trip_TimeSum.containsKey(tripName)) {
            Double tripTime = trip_TimeSum.get(tripName);
            Integer count = trip_CountSum.get(tripName);
            return tripTime / count;
        }
        return 0;
    }
}
```







#### 海量数据的排序

分成几份,每份快排

8路合并  合成 5 路

5路再做合并合成一路

```
1、外排序
　　传统的排序算法一般指内排序算法，针对的是数据可以一次全部载入内存中的情况。但是面对海量数据，即数据不可能一次全部载入内存，需要用到外排序的方法。外排序采用分块的方法（分而治之），首先将数据分块，对块内数据按选择一种高效的内排序策略进行排序。然后采用归并排序的思想对于所有的块进行排序，得到所有数据的一个有序序列。

　　例如，考虑一个1G文件，可用内存100M的排序方法。首先将文件分成10个100M，并依次载入内存中进行排序，最后结果存入硬盘。得到的是10个分别排序的文件。接着从每个文件载入9M的数据到输入缓存区，输出缓存区大小为10M。对输入缓存区的数据进行归并排序，输出缓存区写满之后写在硬盘上，缓存区清空继续写接下来的数据。对于输入缓存区，当一个块的9M数据全部使用完，载入该块接下来的9M数据，一直到所有的9个块的所有数据都已经被载入到内存中被处理过。最后我们得到的是一个1G的排序好的存在硬盘上的文件。

2、1TB数据使用32GB内存如何排序
　　①、把磁盘上的1TB数据分割为40块（chunks），每份25GB。（注意，要留一些系统空间！）
　　②、顺序将每份25GB数据读入内存，使用quick sort算法排序。
　　③、把排序好的数据（也是25GB）存放回磁盘。
　　④、循环40次，现在，所有的40个块都已经各自排序了。（剩下的工作就是如何把它们合并排序！）
　　⑤、从40个块中分别读取25G/40=0.625G入内存（40 input buffers）。
　　⑥、执行40路合并，并将合并结果临时存储于2GB 基于内存的输出缓冲区中。当缓冲区写满2GB时，写入硬盘上最终文件，并清空输出缓冲区；当40个输入缓冲区中任何一个处理完毕时，写入该缓冲区所对应的块中的下一个0.625GB，直到全部处理完成。

3、继续优化
　　磁盘I/O通常是越少越好（最好完全没有），那么如何降低磁盘I/O操作呢？关键就在第5和第6步中的40路输入缓冲区，我们可以先做8路merge sort，把每8个块合并为1路，然后再做5-to-1的合并操作。
　　再深入思考一下，如果有多余的硬件，如何继续优化呢？有三个方向可以考虑：
　　使用并发：如多磁盘（并发I/O提高）、多线程、使用异步I/O、使用多台主机集群计算。
　　提升硬件性能：如更大内存、更高RPM的磁盘、升级为SSD、Flash、使用更多核的CPU。
　　提高软件性能：比如采用radix sort、压缩文件（提高I/O效率）等。
————————————————
版权声明：本文为CSDN博主「无鞋童鞋」的原创文章，遵循 CC 4.0 BY-SA 版权协议，转载请附上原文出处链接及本声明。
原文链接：https://blog.csdn.net/FX677588/article/details/72471357
```





#### [@@@146. LRU缓存机制](https://leetcode-cn.com/problems/lru-cache/)

@@注意head和tail在初始化的时候,要连接起来

```java
class LRUCache {
    int capacity = 0;
    DoubleList list = null;
    HashMap<Integer, Node> map = null;

    public LRUCache(int capacity) {
        this.capacity = capacity;
        list = new DoubleList();
        map = new HashMap<>();
    }

    public int get(int key) {
        if (!map.containsKey(key)) {
            return -1;
        }
        Node node = map.get(key);
        list.remove(node);
        list.addFirst(node);
        return node.val;
    }

    public void put(int key, int val) {
        if (map.containsKey(key)) {
            Node node = map.get(key);
            node.key = key;
            node.val = val;
            list.remove(node);
            list.addFirst(node);
            return;
        }
        Node node = new Node(key, val);
        list.addFirst(node);
        map.put(key, node);
        if (list.size > capacity) {
            Node toDel = list.removeLast();
            map.remove(toDel.key);
        }
    }
}

class DoubleList {
    int size;
    Node head, tail;

    public DoubleList() {
        head = new Node(0, 0);
        tail = new Node(0, 0);
        head.next = tail;
        tail.pre = head;
        size = 0;

    }

    public void addFirst(Node node) {
        Node nextNode = head.next;
        node.pre = head;
        node.next = nextNode;
        head.next = node;
        nextNode.pre = node;
        size++;
    }

    public void remove(Node node) {
        node.pre.next = node.next;
        node.next.pre = node.pre;
        size--;
    }

    public Node removeLast() {
        if (tail.pre == head) {
            return null;
        }
        Node toDel = tail.pre;
        remove(toDel);
        return toDel;
    }
}

class Node {
    Node pre, next;
    int key, val;
    public Node(int key, int val) {
        this.key = key;
        this.val = val;
    }
}
```



#### [@@@@140. 单词拆分 II](https://leetcode-cn.com/problems/word-break-ii/)

```java
public class Solution {
   public List<String> wordBreak(String s, Set<String> wordDict) {
       LinkedList<String>[] dp = new LinkedList[s.length() + 1];
       LinkedList<String> initial = new LinkedList<>();
       initial.add("");
       dp[0] = initial;
       for (int i = 1; i <= s.length(); i++) {
           LinkedList<String> list = new LinkedList<>();
           for (int j = 0; j < i; j++) {
               if (dp[j].size() > 0 && wordDict.contains(s.substring(j, i))) {
                   for (String l : dp[j]) {
                       list.add(l + (l.equals("") ? "" : " ") + s.substring(j, i));
                   }
               }
           }
           dp[i] = list;
       }
       return dp[s.length()];
   }
}

```





#### 把字符串中重复的子串删除



```java
//思路

 
//ssabxx

left  pre 
left left+1

//case
//12313
//11123
//23111
//ssxx
//空
//xxxx
//

//优化
stringbuilder ret 

//left pre = left+1
//sx11121
//
public String deleteDuplicateChar(String s){
   if(s==null||s.length()==0){
       return "";
   }
   if(s.length()==1){
      return s;
   }
   StringBuilder ret = new StringBuilder();
   char[] chs  = s.toCharArray();
   
   int left = 0;
   int len = chs.length();
    //ab
   while(left<len){
       if(left+1<len&&chs[left]==chs[left+1]){
           char deadCh = chs[left];
           while(chs[left]==deadCh&&left<len){
               left++;
           }
       }else{
           ret.append(chs[left]); 
           left++;
       }    
   }
   return ret.toString();
}
```



#### 时光倒流

给出周时分,和要倒流的分钟数k,

求倒流之后的时间是多少

举例:

输入 

2 09:50  60

输出

2 08:50

解释

周二九点五十,倒流60分钟,是周二八点五十



```java
public static void main(String[] args) {
    int[] pre = new int[3];
    int[] now = new int[3];
    int[] deta = new int[3];
    Scanner scanner = new Scanner(System.in);
    int week = scanner.nextInt();
    String str = scanner.next();
    int minDeta = scanner.nextInt();
    int hour = Integer.parseInt(str.substring(0, 2));
    int min = Integer.parseInt(str.substring(3, 5));
    now[0] = week;
    now[1] = hour;
    now[2] = min;
    deta[2] = minDeta % 60;
    deta[1] = minDeta / 60 % 24;
    deta[0] = minDeta / (60 * 24) % 7;

    if (now[2] >= deta[2]) {
        pre[2] = now[2] - deta[2];
    } else {
        pre[2] = (now[2] + 60 - deta[2]);
        now[1]--;
    }
    if (now[1] >= deta[1]) {
        pre[1] = now[1] - deta[1];
    } else {
        pre[1] = (now[1] + 24 - deta[1]);
        now[0]--;
        if (now[0] == 0) {
            now[0] = 7;
        }
    }

    if (now[0] >= deta[0]) {
        pre[0] = now[0] - deta[0];
    } else {
        pre[0] = (now[0] + 7 - deta[0]);
    }
    System.out.println(pre[0]);
    StringBuilder time = new StringBuilder();
    if (pre[1] <= 9) {
        time.append("0" + pre[1] + ":");
    } else {
        time.append(pre[1] + ":");
    }
    if (pre[2] <= 9) {
        time.append("0" + pre[2]);
    } else {
        time.append(pre[2]);
    }
    System.out.println(time);

}
```



#### 正四面体游走

（四个顶点六条边）四个点为 ABCS，每条边可以走无数次,从顶点S出发K次能到达S点的可能性（K=1e6，对p=1e9+7取模）

比如 k =3,路径可以有

SBAS

SABS

SCBS

SBCS

SCAS

SACS





```java

    public static void main(String[] args) {
        Scanner scanner = new Scanner(System.in);
        int k = scanner.nextInt();
        if (k == 0) {
            System.out.println(1);
            return;
        }
        int mod = 1000000000 + 7;
        //012 abc 3 s
        int[][] dp = new int[k + 1][4];
        dp[1][0] = 1;
        dp[1][1] = 1;
        dp[1][2] = 1;
        dp[1][3] = 0;
        for (int i = 2; i <= k; i++) {
            for (int j = 0; j < 4; j++) {
                for (int m = 0; m < 4; m++) {
                    if (m != j) {
                        dp[i][j] = (dp[i][j] % mod + dp[i - 1][m] % mod) % mod;
                    }
                }
            }
        }
        System.out.println(dp[k][3]);

    }
```































































































