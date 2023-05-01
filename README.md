Download Link: https://assignmentchef.com/product/solved-ch08-320201-homework-3-fibonacci-numbers-and-divide-conquer-and-solving-recurrences
<br>
<strong>Problem 1: Fibonacci numbers                                                                                                                         </strong>

<ul>

 <li>Implement all four methods to compute Fibonacci numbers that were discussed in class: (1) naive recursive, (2) bottom up, (3) closed form, and (4) using a matrix representation.</li>

 <li>Sample and measure the running times of all four methods for increasing <em>n</em>. For each method, stop the sampling when the running time exceeds 5 seconds. Create a table with your results (max. 1 page).</li>

</ul>

<em>Tip</em>: the “space” between samples should increase the larger <em>n </em>gets, e.g. <em>n </em>∈{1<em>,</em>2<em>,</em>3<em>,</em>4<em>,</em>5<em>,</em>6<em>,</em>8<em>,</em>10<em>,</em>13<em>,</em>16<em>,</em>20<em>,</em>25<em>,</em>32<em>,</em>40<em>,</em>50<em>,</em>63<em>,…</em>}.

<ul>

 <li>For the same <em>n</em>, do all methods always return the same Fibonacci number? Justify your answer.</li>

 <li>Plot your results in a line plot, so that the four approaches can be easily compared. Briefly interpret your results.</li>

</ul>

<em>Tip</em>: Use log scales for your plot.

<strong>Problem 2: Divide &amp; Conquer and Solving Recurrences                                                                                </strong>

Consider the problem of multiplying large integers <em>a </em>and <em>b </em>with <em>n </em>bits each. You can assume that addition, substraction, and bit shifting can be done in linear time, i.e., in Θ(<em>n</em>).

<ul>

 <li>Derive the asymptotic time complexity in the number of bits <em>n </em>for a brute-force implementation of the multiplication.</li>

 <li>Derive a divide &amp; conquer algorithm for the given problem by splitting the problem into two subproblems. For simplicity you can assume <em>n </em>to be a power of 2.</li>

 <li>Derive a recurrence for the time complexity of the divide &amp; conquer algorithm in (b).</li>

 <li>Solve the recurrence in (c) using the recursion tree method.</li>

 <li>Validate the solution in (d) by using the master theorem to solve the recurrence.</li>

</ul>