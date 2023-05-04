Download Link: https://assignmentchef.com/product/solved-cs596-homework-2
<br>
You are given the following matrix <em>A</em>

<em> .</em>

<ol>

 <li>a) Is <em>A </em>diagonalizable? <em>Give explanations on your YES/NO answer, otherwise it will be considered incorrect!</em>. b) Compute <em>A<sup>n</sup>,n &gt; </em> c) Compute <em>e<sup>A</sup></em>.</li>

</ol>

<strong>Problem 2: </strong>If V is the space of all random variables (including the deterministic variables that are regarded as random with 0 variance) then a) Show that this is a vector space. b) If <em>x,y </em>two random variables then show that the expectation of the product E[<em>xy</em>] defines an inner product in V. c) Consider the random variables 1<em>,z</em><sub>1</sub><em>,…,z<sub>k </sub></em>which define a linear subspace <em>Ω </em>in V. If <em>x </em>is any random variable, find the best approximation ˆ<em>x </em>of <em>x </em>that lies in <em>Ω</em>. d) What is the physical meaning of the problem you have solved in c)?

<strong>Problem 3: </strong>Form your own random matrix of size 20 × 5 which must be of <strong>rank equal to 3 </strong><em>(You must explain how you do it, to receive full grade)</em>. From the 100 elements of this matrix, start deleting at random positions first <em>N </em>= 2 elements, then <em>N </em>= 3<em>,</em>4<em>,</em>5 by replacing them with 0.

<ol start="3">

 <li>a) After you have deleted <em>N </em>elements, apply an SVD on the resulting matrix and examine its rank. Is it still 3? If not what is the maximum value the rank can attain?. b) Apply matrix filling using SVD and using the information that the original was of rank 3. c) Compare the reconstructed matrix with the original one (the one that has all the elements) for the different values of the number of deletions <em>N </em>and compute a measure of the error. When would you characterize the reconstruction method satisfactory?</li>

</ol>

<strong>Problem 4: </strong>a) Show that the smallest distance of a point (<em>x</em><sub>∗</sub><em>,y</em><sub>∗</sub>) on the plane from a linear√

manifold (line) with equation <em>Ax</em>+<em>By</em>+<em>C </em>= 0 is equal to |<em>Ax</em><sub>∗</sub>+<em>By</em><sub>∗</sub>+<em>C</em>|<em>/ A</em><sup>2 </sup>+ <em>B</em><sup>2</sup>. b) Suppose now that you are given a collection of points {(<em>x</em><sub>1</sub><em>,y</em><sub>1</sub>)<em>,…,</em>(<em>x<sub>n</sub>,y<sub>n</sub></em>)}. Define a cost function by considering the sum of the squares of the distances of each point from the manifold. By taking the derivative with respect to <em>C</em>, express <em>C </em>as a function of <em>A </em>and <em>B </em>and compute the new form of the cost. Put the resulting cost under a form which is suitable to apply the known result that computes the minimum value of the ratio min<em><sub>X </sub><u><sup>X</sup></u><sub>X</sub></em><sup>|</sup><sub>|</sub><em><u><sup>ΩX</sup></u><sub>X </sub></em>for a symmetric matrix <em>Ω</em>. c) Repeat questions a) and b) for a <em>circular </em>manifold with the circle defined by the coordinates of its center (<em>A,B</em>) and its radius <em>C &gt; </em>0. For question c) you need to compute first the shortest distance of a point from the circle as a function of <em>A,B,C</em>. Then define a cost by considering the sum of squares of the distances of the points from the circle. Next you must express <em>C </em>in terms of <em>A,B </em>by taking the derivative with respect to <em>C </em>and equating it to 0. Finally you must derive the new cost function that now depends only on <em>A,B</em>. d) Write the steepest descent algorithm for <em>A,B </em>that minimize this final cost function.<img decoding="async" data-recalc-dims="1" data-src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/217.png?w=980&amp;ssl=1" class="lazyload" src="data:image/gif;base64,R0lGODlhAQABAAAAACH5BAEKAAEALAAAAAABAAEAAAICTAEAOw==">

 <noscript>

  <img decoding="async" src="https://i0.wp.com/www.ankitcodinghub.com/wp-content/uploads/2022/04/217.png?w=980&amp;ssl=1" data-recalc-dims="1">

 </noscript>