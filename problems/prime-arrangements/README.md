<!--|This file generated by command(leetcode description); DO NOT EDIT.    |-->
<!--+----------------------------------------------------------------------+-->
<!--|@author    Openset <openset.wang@gmail.com>                           |-->
<!--|@link      https://github.com/openset                                 |-->
<!--|@home      https://github.com/openset/leetcode                        |-->
<!--+----------------------------------------------------------------------+-->

[< Previous](https://github.com/openset/leetcode/tree/master/problems/immediate-food-delivery-ii "Immediate Food Delivery II")
　　　　　　　　　　　　　　　　
[Next >](https://github.com/openset/leetcode/tree/master/problems/diet-plan-performance "Diet Plan Performance")

## 1175. Prime Arrangements (Easy)

<p>Return the number of permutations of 1 to <code>n</code> so that prime numbers are at prime indices (1-indexed.)</p>

<p><em>(Recall that an integer&nbsp;is prime if and only if it is greater than 1, and cannot be written as a product of two positive integers&nbsp;both smaller than it.)</em></p>

<p>Since the answer may be large, return the answer <strong>modulo <code>10^9 + 7</code></strong>.</p>

<p>&nbsp;</p>
<p><strong>Example 1:</strong></p>

<pre>
<strong>Input:</strong> n = 5
<strong>Output:</strong> 12
<strong>Explanation:</strong> For example [1,2,5,4,3] is a valid permutation, but [5,2,3,4,1] is not because the prime number 5 is at index 1.
</pre>

<p><strong>Example 2:</strong></p>

<pre>
<strong>Input:</strong> n = 100
<strong>Output:</strong> 682289015
</pre>

<p>&nbsp;</p>
<p><strong>Constraints:</strong></p>

<ul>
	<li><code>1 &lt;= n &lt;= 100</code></li>
</ul>

### Related Topics
  [[Math](https://github.com/openset/leetcode/tree/master/tag/math/README.md)]

### Hints
<details>
<summary>Hint 1</summary>
Solve the problem for prime numbers and composite numbers separately.
</details>

<details>
<summary>Hint 2</summary>
Multiply the number of permutations of prime numbers over prime indices with the number of permutations of composite numbers over composite indices.
</details>

<details>
<summary>Hint 3</summary>
The number of permutations equals the factorial.
</details>