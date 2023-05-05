Download Link: https://assignmentchef.com/product/solved-cse100-lab3-max-subarray-problem-via-divide-and-conquer
<br>
<strong>Solving the Max Subarray Problem via Divide-and-conquer</strong>

<strong>Description </strong>In this lab assignment, your job is to implement the <em>O</em>(<em>n</em>log<em>n</em>) time divideand-conquer algorithm for the Max Subarray Problem; for the pseudo-code, see page 72 in the textbook or the lecture slides. Recall that in the problem, we are given as input an array <em>A</em>[1···<em>n</em>] of <em>n </em>integers, and would like to find <em>i</em><sup>∗ </sup>and <em>j</em><sup>∗ </sup>(1 ≤ <em>i</em><sup>∗ </sup>≤ <em>j</em><sup>∗ </sup>≤ <em>n</em>) such that <em>A</em>[<em>i</em><sup>∗</sup>] + <em>A</em>[<em>i</em><sup>∗ </sup>+ 1] + ··· + <em>A</em>[<em>j</em><sup>∗</sup>] is maximized.

<strong>Input structure </strong>The input starts with an integer number <em>n</em>, which indicates the array size. Then, the integers, <em>A</em>[1]<em>,A</em>[2]<em>,</em>···<em>,A</em>[<em>n</em>]<em>, </em>follow, one per line.

<strong>Output structure </strong>Output the sum of integers in the max subarray, i.e., <em>A</em>[<em>i</em><sup>∗</sup>] + <em>A</em>[<em>i</em><sup>∗ </sup>+ 1] + ··· + <em>A</em>[<em>j</em><sup>∗</sup>].

<strong>Examples of input and output:</strong>

<em>Input</em>

6

-3 11

-2 -3

10

-5 <em>Output</em>

16

Note that in this example, the max subarray is <em>A</em>[2···5]. So, we output <em>A</em>[<em>i</em><sup>∗</sup>] + ··· + <em>A</em>[<em>j</em><sup>∗</sup>] = 11 − 2 − 3 + 10 = 16. The output is only one number and has no white space.

See the lab guidelines for submission/grading, etc., which can be found in Files/Labs.