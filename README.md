Download Link: https://assignmentchef.com/product/solved-csci-570-homework5
<br>
<ol>

 <li><strong> Maximizing Profit </strong></li>

</ol>

A furniture company produces three types of couches. The first type uses 1 foot of framing wood and 3 feet of cabinet wood. The second type uses 2 feet of framing wood and 2 feet of cabinet wood. The third type uses 2 feet of framing wood and 1 foot of cabinet wood. The profit of the three types of couches is $10, $8, and $5, respectively. The factory produces 500 couches each month of the first type, 300 of the second type, and 200 of the third type. However, this month there is a shortage of cabinet wood and the supply to the factory will have to be reduced by 600 feet, but the supply of framing wood is increased by 100 feet.

How should the production of the three types of couches be adjusted to minimize the decrease in profit?

Formulate this problem as a linear programming problem.

<ol start="2">

 <li><strong>Dual Program </strong></li>

</ol>

Consider the following linear program:

<em>max</em>(3<em>x</em><sub>1 </sub>+ 2<em>x</em><sub>2 </sub>+ <em>x</em><sub>3</sub>)

Subject to,

<em>x</em><sub>1 </sub>− <em>x</em><sub>2 </sub>+ <em>x</em><sub>3 </sub>≤ 4 2<em>x</em><sub>1 </sub>+ <em>x</em><sub>2 </sub>+ 3<em>x</em><sub>3 </sub>≤ 6 − <em>x</em><sub>1 </sub>+ 2<em>x</em><sub>3 </sub>= 3 <em>x</em><sub>1 </sub>+ <em>x</em><sub>2 </sub>+ <em>x</em><sub>3 </sub>≤ 8 <em>x</em><sub>1</sub>,<em>x</em><sub>2</sub>,<em>x</em><sub>3 </sub>≥ 0

Write the dual problem.

<ol start="3">

 <li><strong> Spectrum Management </strong></li>

</ol>

Spectrum management is the process of regulating the use of radio frequencies to promote efficient use and gain a net social benefit. Given a set of broadcast emitting stations s1​ ,…,s<sub>​ </sub>n​ , a list of frequencies f<sub>​                     </sub>1​ ,…,f<sub>​ </sub>m​ ,<sub>​</sub> where m ≥ n, and the set of adjacent stations E = {(si​ ,s<sub>​ </sub>j​ )}<sub>​ </sub>. The goal is to assign a frequency to each station so that adjacent stations use different frequencies and the number of used frequencies is minimized.

Formulate this problem as an integer linear programming problem.

<ol start="4">

 <li><strong>Short Questions </strong></li>

</ol>

<strong>True or false? Shortly explain your answers.                             </strong>

<strong> </strong>

<ol>

 <li><em>If</em> <em>A</em>≤<em><sub>p</sub>B</em> <em>and</em> <em>B</em> <em>is</em> <em>in</em> <em>NP </em>− <em>Hard</em>, <em>then</em> <em>A</em> <em>is</em> <em>in</em> <em>NP </em>− <em>Hard</em>.</li>

 <li><em>If</em> <em>A</em>≤<em><sub>p</sub>B</em> <em>and</em> <em>B</em> <em>is</em> <em>in</em> <em>NP</em>, <em>then</em> <em>A</em> <em>is</em> <em>in</em> <em>NP</em>.</li>

 <li><em>If</em> 3 − <em>SAT</em>≤<em><sub>p</sub></em>2 − <em>SAT</em>, <em>then</em> <em>P </em>= <em>NP</em>.</li>

 <li><em>Any</em> <em>NP</em> <em>problem</em> <em>can</em> <em>be</em> <em>solved</em> <em>in</em> <em>time</em> <em>O</em> <sup>(2<em>poly</em>(<em>n</em>))</sup>, <em>where</em> <em>n</em> <em>is</em> <em>the</em> <em>input</em> <em>size</em> <em>and</em> <em>poly</em>(<em>n</em>) <em>is</em> <em>a</em> <em>polynomial</em>.</li>

 <li><em>If</em> <em>a</em> <em>problem</em> <em>A</em>≤<em><sub>p</sub>B</em> <em>then</em> <em>it</em> <em>follows</em> <em>that</em> <em>B</em>≤<em><sub>p</sub>A</em>.</li>

 <li><strong>              5. Finding a satisfying assignment </strong></li>

</ol>

Assume that you are given a polynomial time algorithm that given a 3-SAT instance decides in polynomial time if it has a satisfying assignment. Describe a polynomial time algorithm that finds a satisfying assignment (if it exists) to a given 3-SAT instance.

<ol start="6">

 <li><strong> Shipping Goods</strong></li>

</ol>

Given n positive integers x1​ ,…,x<sub>​ </sub>n​ . The Partition Problem asks if there is a subset S <sub>​ </sub>⊆ [n] such that:

∑ <em>x<sub>i </sub></em>= ∑ <em>x<sub>i</sub></em>

<em>i</em>∈<em>S          i</em>∈/ <em>S</em>

It can be proven that the Partition Problem is NP-complete. You do not prove it, but rather use it in the following problem.

Assume that you are consulting for a shipping company that ships a large amount of packages overseas. The company wants to pack n products with integer weights p1​ , . . . , p<sub>​ </sub>n ​ into a few boxes as possible to save<sub>​         </sub> on shipping costs. However, they cannot put any number of products into a box due to the ship- ping capacity restriction. The total weight of products in each box should not exceed W ? You may assume that for each i-th product pi ​ ≤ W . Your task is to advise the company if it can be placed into at most k &lt; n<sub>​ </sub> boxes. Show that the problem is NP-Complete by reduction from the Partition Problem.

<ol start="7">

 <li><strong> Longest Path </strong></li>

</ol>

Given a graph G = (V,E) and a positive integer k, the longest-path problem is the problem of determining whether a simple path (no repeated vertices) of length k exists in a graph. Show that this problem is  NP-complete by reduction from the Hamiltonian path.

<ol start="8">

 <li><strong> Helping with the COVID-19 Crisis </strong></li>

</ol>

Given an integer k, a set C of n cities c1​ ,…,c<sub>​ </sub>n​ , and the distances between these cities d<sub>​         </sub>ij ​ =<sub>​</sub> d(ci​ ,c<sub>​ </sub>j​ )<sub>​ </sub>, for 1 ≤ i &lt; j ≤ n, where d is the standard Euclidean distance. We want to select a set H of k cities for building mobile hospitals in light of the coronavirus outbreak. The distance between a given city c and the set H is given by d(c,H) = min h​∈H d(c,h). The goal is to select a set H of k cities that minimizes r = max <sub>​        </sub>c​∈C d(c,H). Namely,<sub>​</sub> the maximum distance from a city to the nearest mobile hospital is minimized. Give a 2-approximation algorithm for this problem.