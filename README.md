
<!DOCTYPE html>
<!-- saved from url=(0055)https://courses.cs.duke.edu/fall24/compsci532/index.php -->
<html lang="en"><head><meta http-equiv="Content-Type" content="text/html; charset=UTF-8"><style>body {transition: opacity ease-in 0.2s; } 
body[unresolved] {opacity: 0; display: block; overflow: hidden; position: relative; } 
</style>

<title>COMPSCI 532 - Fall 2024</title>
<meta name="description" content="Duke COMPSCI 532 | Fall 2024 | Design &amp; Analysis of Algorithms">
<link href="./index.php_files/styles.css" rel="stylesheet" type="text/css">
</head>

<body>

<a name="top"></a>

<div id="Wrapper" class="BoxEffect">


<div id="Header">
<a href="https://courses.cs.duke.edu/fall24/compsci532/index.php">
	<table id="HeaderTable">
		<tbody><tr>
			<td id="CourseDeets">COMPSCI 532<br>
				Fall 2024
			</td>
			<td id="CourseTitle">Design &amp; Analysis of Algorithms
			</td>
		</tr>
	</tbody></table>
</a>
</div>


<div id="InnerWrapper">

<div id="NavHolder">
<ul id="NavLinks">
<li><a href="https://courses.cs.duke.edu/fall24/compsci532/index.php">Home</a></li>
<!--
<li><a href="index.php">Synopsis</a></li>
<li><a href="index.php#grading">Grading</a></li>
<li><a href="index.php#collaboration">Collaboration</a></li>
-->
<li><a href="https://courses.cs.duke.edu/fall24/compsci532/lectures.html">Lectures</a></li>
<li><a href="https://courses.cs.duke.edu/fall24/compsci532/reading.html">Reading</a></li>
<li><a href="https://courses.cs.duke.edu/fall24/compsci532/assignments.html">Assignments</a></li>
</ul>
</div>



<div id="Content"><a name="admin"></a>

<h1 id="PageTitle"></h1>

<div>


<div style="width:250px; float:right; border: 2px solid silver; margin-bottom: 20px; margin-left:30px; padding: 3px;">

<img src="./index.php_files/picture01.png" style="width:250px;">

<p style="text-align:center; font-size: 11px; margin-top:0px; margin-bottom: 0px;">Gregor Reisch: Madame Arithmatica, 1508</p>

</div>

<h2 class="SectionHead" style="border:none; margin-top:-25px;">Administration</h2>

<p class="Bold">
Design &amp; Analysis of Algorithms<br>COMPSCI 532 • Fall 2024</p>


<p style="margin-bottom:0px;"><span class="BoldColor">Instructor</span>: <a href="http://www.cs.duke.edu/~pankaj">Pankaj K. Agarwal</a></p>

<p style="margin-top:8px; margin-bottom:0px;"><span class="BoldColor">TA</span>: <a href="https://courses.cs.duke.edu/fall24/compsci532/index.php">Rahul Raychaudhury</a></p>

<p style="margin-top:8px; margin-bottom:0px;"><span class="BoldColor">Time</span>:&nbsp;Mon, Wed 3:05-4:20 pm</p>

<p style="margin-top:8px; margin-bottom:0px;"><span class="BoldColor">Location</span>:&nbsp;French 4233</p>

<p style="margin-top:8px;"><span class="BoldColor">Office Hours:</span>  <br>
Agarwal: Mon 1:45-2:45 <br>
Raychaudhury: Tue, Thu 15:00-16:00, LSRC D309 </p>


</div>

<a name="overview"></a>
<h2 class="SectionHead" style="width:360px;">Course Synopsis</h2>

<p class="MarginBottomZero">This course covers design and analysis of efficient algorithms at a graduate level. Topics include:</p>

<ul class="Left MarginTopZero">

<li><span class="BoldColor"> Linear Programming:</span> Polyhedral combinatorics, LP algorithms, duality</li>

<li><span class="BoldColor"> Network Optimization Problems:</span> Max flow, min cut, min cost flow, optimal transport</li>

<li><span class="BoldColor"> Approximation Algorithms:</span> Greedy algorithms, local-search, multiplicative weight updatemethod, primal-dual method</li>

<li><span class="BoldColor"> Randomized Algorithms:</span> Tail bounds, global min-cut, LP rounding, SDP rounding, probabilistic embeddings</li>

<li><span class="BoldColor"> Similarity Search:</span> Nearest neighbor searching in low dimensions, dimension reduction, locality sensitive hashing</li>

<li><span class="BoldColor"> Algebraic and Numerical Algorithms:</span> Polynomial identity testing, gradient descent,
graph Laplacian, Markov chains</li>

</ul>

<a name="prereq"></a>
<h2 class="SectionHead">Prerequisites</h2>
<p class="MarginTopZero">COMPSCI 230 and 330, or equivalent courses. This course requires undergraduate background in discrete mathematics and algorithms</p>

<a name="textbook"></a>

<div id="HomeBooks">

<h2 class="SectionHead">Textbook</h2>

<table class="HomeBooks">
<tbody><tr><td class="ColOne">[KT]</td><td>J. Kleinberg and E. Tardos, <span class="Italic">Algorithm Design</span>, Addison Wesley, 2005.</td></tr>

<tr><td class="ColOne">[WS]</td><td>D. Williamson and D. B. Shmoys, <span class="Italic">The Design of Approximation Algorithms</span>, Cambridge
University Press, 2011.</td></tr>
</tbody></table>

<a name="ref"></a>
<h2 class="SectionHead">Reference Books</h2>

<table class="HomeBooks">

<tbody><tr><td class="ColOne">[Er]</td><td>J. Erickson, <span class="Italic">Algorithms</span>, 2019.</td></tr>

<tr><td class="ColOne">[HP]</td><td>S. Har-Peled, <span class="Italic">Geometric Approximation Algorithms</span>, AMS, 2013.</td></tr>

<tr><td class="ColOne">[MG]</td><td>J. Matoušek and B. Gärtner, <span class="Italic">Understanding and Using Linear Programming</span>,
Springer, 2007.</td></tr>

<tr><td class="ColOne">[MR]</td><td>R. Motwani and P. Raghavan, <span class="Italic">Randomized Algorithms</span>, Cambridge University
Press.</td></tr>

</tbody></table>


</div>

<a name="grading"></a>
<h2 class="SectionHead">Grading</h2>

<ul class="Left MarginTopZero">
<li>Assignments (four out of five): 40%</li>
<li>Two midterm exams (in-class, closed book): 60%</li>
</ul>

<p class="LinkToTop"><a href="https://courses.cs.duke.edu/fall24/compsci532/index.php#top">page top</a></p>

</div> <!--Close Content -->

</div> <!--Close InnerWrapper -->

</div> <!--Close Wrapper -->

<br>



</body></html>
