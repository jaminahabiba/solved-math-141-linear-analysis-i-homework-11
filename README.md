Download Link: https://assignmentchef.com/product/solved-math-141-linear-analysis-i-homework-11
<br>
<ol>

 <li>(<em>if not done last week</em>) Calculate the following determinant using Gaussian elimination. To make calculation by hand easier, you may use any row operations that we may or may not use in our <em>standard </em>forward Gaussian elimination process.</li>

</ol>

<table width="661">

 <tbody>

  <tr>

   <td width="661">Here are typed-up definitions of minors and cofactors and how they lead to formulas for det<em>A </em>and <em>A</em><sup>−1</sup>.<em>A<sub>n</sub></em><sub>×<em>n </em></sub>is a square matrix. • <em>a<sub>ij </sub></em>are the <strong><em>entries </em></strong>of <em>A</em>:<em>a<sub>ij </sub></em>= entry of the matrix <em>A </em>at the intersection of row-<em>i </em>and column-<em>j.</em>•    <em>M<sub>ij </sub></em>are <strong><em>submatrices </em></strong>of <em>A</em>, each of which is (<em>n </em>− 1)-by-(<em>n </em>− 1):<em>M<sub>ij </sub></em>= those remain in <em>A </em>after deleting entire row-<em>i </em>and column-<em>j </em>from <em>A.</em>•    The <strong><em>minors </em></strong>(which do not have their own notations) of <em>A </em>are determinant of the submatrices:<em>minors </em>= det<em>M<sub>ij</sub>.</em>•    <em>C<sub>ij </sub></em>are the <strong><em>cofactors </em></strong>of <em>A</em>, which are the minors det<em>M<sub>ij </sub></em>multiplied by a (±)-sign determined by the indices <em>ij</em>:<em>C</em><em>ij </em>= (−1)<em>i</em>+<em>j </em>det<em>M</em><em>ij</em><em>.</em><em>C </em>= [<em>C<sub>ij</sub></em>] is called the <strong>cofactor matrix </strong>of <em>A</em>Warning: The matrix <em>C </em>has <em>C<sub>ij </sub></em>as its entries at the intersection of row-<em>i </em>and column-<em>j</em>. Pay careful attention to the order of <em>i </em>and <em>j</em>.<strong>The formula for </strong>det<em>A </em><strong>using expansion along any row-</strong><em>i </em><strong>is</strong>det<em>A </em>= <em>a<sub>i</sub></em><sub>1</sub><em>C<sub>i</sub></em><sub>1 </sub>+ <em>a<sub>i</sub></em><sub>2</sub><em>C<sub>i</sub></em><sub>2 </sub>+ ··· + <em>a<sub>in</sub>C<sub>in</sub>,               </em><strong>for any one fixed </strong><em>i,</em><strong>and the formula for </strong>det<em>A </em><strong>using expansion along any column-</strong><em>j </em><strong>is</strong>det<em>A </em>= <em>a</em><sub>1<em>j</em></sub><em>C</em><sub>1<em>j </em></sub>+ <em>a</em><sub>2<em>j</em></sub><em>C</em><sub>2<em>j </em></sub>+ ··· + <em>a<sub>nj</sub>C<sub>nj</sub>,                 </em><strong>for any one fixed </strong><em>j.</em><strong>One formula for </strong><em>A</em><sup>−1 </sup><strong>is</strong><em>.</em></td>

  </tr>

 </tbody>

</table>

<ol start="2">

 <li>(<em>Strang 4th ed. </em><em>4.3 #5</em>) Let <em>F<sub>n </sub></em>be the determinant of the 1<em>,</em>1<em>,</em>−1 tridiagonal matrix (<em>n</em>-by-<em>n</em>):</li>

</ol>

<table width="424">

 <tbody>

  <tr>

   <td width="243">11 0<em>F<sub>n </sub></em>= … <sub></sub>0 0(a) Compute <em>F</em><sub>1 </sub>and <em>F</em><sub>2</sub>.</td>

   <td width="30">−11100</td>

   <td width="30">0−11…00</td>

   <td width="30">00−100</td>

   <td width="28">·········…······</td>

   <td width="23">00011</td>

   <td width="30">0 00…−11</td>

   <td width="9"></td>

  </tr>

 </tbody>

</table>

(b) By expanding in cofactors along row 1, show that <em>F<sub>n </sub></em>= <em>F<sub>n</sub></em><sub>−1 </sub>+ <em>F<sub>n</sub></em><sub>−2</sub>.

This yields the <em>Fibonacci sequence </em>1<em>,</em>2<em>,</em>3<em>,</em>5<em>,</em>8<em>,</em>13<em>,… </em>for the determinants.

<ol start="3">

 <li>(<em>Strang 4th ed. </em><em>4.3 #6</em>) Suppose <em>A<sub>n </sub></em>is the <em>n</em>-by-<em>n </em>tridiagonal matrix with 1s on the three diagonals:</li>

</ol>

Let <em>D<sub>n </sub></em>be the determinant of <em>A<sub>n</sub></em>; we want to find it.

<ul>

 <li>Expand in cofactors along the first row to show that <em>D<sub>n </sub></em>= <em>D<sub>n</sub></em><sub>−1 </sub>− <em>D<sub>n</sub></em><sub>−2</sub>.</li>

 <li>Starting from <em>D</em><sub>1 </sub>= 1 and <em>D</em><sub>2 </sub>= 0, find <em>D</em><sub>3</sub><em>,D</em><sub>4</sub><em>,…,D</em><sub>8</sub>. By noticing how these numbers cycle around (with what period?) find <em>D</em><sub>1000</sub>.</li>

</ul>

<ol start="4">

 <li>Earlier in the semester, we discussed how we could think of the modes of transportation in Finding Gauss problem as a basis for R<sup>2</sup>. The travel of the hover board was given by and that of the magic carpet by  . We found, for instance, that Gauss’s cabin, located 107 miles East and 64 miles North of your home, could be reached by riding the hover board forward for 30 hours and the magic carpet forward for 17 hours. Thus, Gauss’s location <em>~x </em>could be described in two ways: using the standard basis, call it <em>α</em>, Gauss lives at. Using the modes of transportation as a basis, call it, Gauss lives</li>

</ol>

at.

<ul>

 <li>Suppose Uncle Cramer’s house <em>w~ </em>is located at. Describe this location as a vector in the ’travel” coordinate system <em>β</em>. Explain your work.</li>

 <li>Suppose you visit a museum <em>~v </em>located at. Describe the location of the museum as a vector</li>

</ul>

in the standard coordinate system <em>α</em>. Explain your work.

<ul>

 <li>Express each of the following in terms of the travel basis and.</li>

 <li>Express each of the following in terms of the standard basisand.</li>

</ul>

<ol start="5">

 <li>Consider the following plane with both the red and black coordinate systems. The red axes correspond to what are normally thought of as the linesand <em>y </em>= 4<em>x</em>. Let the two red vectors highlighted along the red axis be the basis vectors for a new ”red basis”, called.

  <ul>

   <li>Write the coordinates of each of the points (a)-(f) relative to both the red basis <em>red </em>and the standard black basis <em>black</em>.</li>

   <li>Determine a matrix that will

    <ol>

     <li>Rename points from the red basis as points in the black one (call it <em>P</em>).</li>

     <li>Rename points from the black basis as points in the red one (call it <em>Q</em>).</li>

    </ol></li>

  </ul></li>

</ol>

How are <em>P </em>and <em>Q </em>related?

<ul>

 <li>Consider now the linear transformation <em>S </em>: R<sup>2 </sup>→ R<sup>2 </sup>that has a stretch factor of 2 corresponding to the lineand a stretch factor of −1 corresponding to the line <em>y </em>= 4<em>x</em>.

  <ol>

   <li>Determine what happens to the vector under this transformation. Represent the answer using coordinates in the black basis. Explain all steps in your solution approach. ii. Determine what happens to the vector under this transformation. Represent the answer using coordinates in the red basis. Explain all steps in your solution approach.</li>

  </ol></li>

 <li>Consider the following diagram, where <em>~y </em>is the image of <em>~x </em>under the transformation <em>S</em>, the matrices <em>B </em>and <em>D </em>are the stretch matrices for <em>S </em>in black and red respectively, and the matrix <em>P </em>renames vectors from red coordinates to black coordinates:

  <ol>

   <li>Find the matrices <em>B</em>, <em>D</em>, and <em>P </em>that correspond to this diagram for this particular problem. For each of these, give at least one sentence explaining how you found them. How are the matrices <em>B</em>, <em>D</em>, and <em>P </em>related to each other?</li>

   <li>Pick one of the questions in part (c) above, either (c)i or (c)ii, and explain, using the above diagram, how there are two different methods in which you could have found the answer to that question.</li>

  </ol></li>

</ul>

<ol start="6">

 <li>We use the same red and black coordinate systems as in the previous problem, and <em>S </em>: R<sup>2 </sup>→ R<sup>2 </sup>denotes the same linear transformation that has a stretch factor of 2 corresponding to the lineand a stretch factor of −1 corresponding to the line <em>y </em>= 4<em>x</em>.

  <ul>

   <li>Without trying to find any matrices, describe in words, the stretch factors and stretch directions for the linear transformation <em>S</em><sup>2</sup>. Recall that <em>S</em><sup>2 </sup>= <em>S </em>◦ <em>S</em>, or equivalently, <em>S</em><sup>2</sup>(<em>~x</em>) = <em>S</em>(<em>S</em>(<em>~x</em>)) for any <em>~x </em>in the domain of <em>S</em>.</li>

   <li>Consider a diagram similar to that in problem 5(d) but for <em>S</em><sup>2</sup>, where <em>~z </em>is the image of <em>~x </em>under the transformation <em>S</em><sup>2</sup>, the matrices <em>B<sub>S</sub></em>2 and <em>D<sub>S</sub></em>2 are the stretch matrices for <em>S</em><sup>2 </sup>in black and red respectively.</li>

  </ul></li>

</ol>

Find the matrices <em>B<sub>S</sub></em>2 and <em>D<sub>S</sub></em>2, using the same method with which you found matrices <em>B </em>and <em>D </em>for

<em>S</em>.

<ul>

 <li>How is the matrix <em>B<sub>S</sub></em>2 related to <em>B </em>in problem 1? What about <em>D<sub>S</sub></em>2 to <em>D</em>? How are <em>B<sub>S</sub></em>2, <em>D<sub>S</sub></em>2, and <em>P </em>related?</li>

 <li>If we ask the same questions as those in parts (a), (b), and (c) about <em>S<sup>k </sup></em>for some integer <em>k &gt; </em>2, what do you think the answers are?</li>

</ul>

<ol start="7">

 <li>(<em>optional</em>) We consider three linear transformations R<sup>2 </sup>→ R<sup>2 </sup>and their matrices in this problem.

  <ul>

   <li>(from lecture) <em>T </em>: R<sup>2 </sup>→ R<sup>2 </sup>has a stretch factor of 2 corresponding to the line <em>y </em>= −3<em>x </em>and a stretch factor of 1 corresponding to the line <em>y </em>= <em>x</em>.</li>

   <li>(from problem 5) <em>S </em>: R<sup>2 </sup>→ R<sup>2 </sup>has a stretch factor of 2 corresponding to the lineand a stretch factor of −1 corresponding to the line <em>y </em>= 4<em>x</em>.</li>

   <li>(a new one) <em>R </em>: R<sup>2 </sup>→ R<sup>2 </sup>has a stretch factor of 1/4 corresponding to the line <em>y </em>= −3<em>x </em>and a stretch factor of −2 corresponding to the line <em>y </em>= <em>x</em>.</li>

  </ul></li>

</ol>

The following diagrams show the naming convention for various matrices associated to <em>T</em>, <em>S</em>, and <em>R</em>.

for

for

<ul>

 <li>(We have found all matrices in the first two diagrams in lecture or in problem 1.) Find matrices <em>C</em>, <em>D<sub>R</sub></em>, and <em>P<sub>R </sub></em>in the last diagrm for the linear transform <em>R</em>.</li>

 <li>Calculate two matrix products <em>AB </em>and <em>BA </em>to verify that <em>AB </em>6= <em>BA</em>. (We say that <em>A </em>and <em>B <strong>do not commute</strong></em>.)</li>

 <li>Calculate two other matrix products <em>AC </em>and <em>CA </em>to verify that <em>AC </em>= <em>CA</em>. (We say that <em>A </em>and <em>C <strong>commute</strong></em>.)</li>

 <li>Study the above descriptions of <em>T</em>, <em>S</em>, <em>R </em>and the associated diagrams, to construct an explanation on why <em>A </em>and <em>B </em>do not commute while <em>A </em>and <em>C </em></li>

</ul>