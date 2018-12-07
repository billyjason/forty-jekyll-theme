---
layout: page
title: My Projects
nav-menu: true
---

<!-- Main -->
<div id="main" class="alt">

<!-- One -->
<section id="one">
	<div class="inner">
		<header class="major">
			<h1>My projects</h1>
		</header>

<!-- Content -->
<h2 id="content">Main ones</h2>
<p></p>
<div class="row">
	<div class="6u 12u$(small)">
		<h3>Programme recommendation System</h3>
		<p>I developed a prototype of programme recommendation System for YouView TV ltd</p>
		<img class="mySlides" src="assets/img/2.png">
		<img class="mySlides" src="assets/img/3.png">
		<img class="mySlides" src="assets/img/4.png">
		<img class="mySlides" src="assets/img/5.png">
		<img class="mySlides" src="assets/img/6.png">
		<img class="mySlides" src="assets/img/7.png">
		<img class="mySlides" src="assets/img/8.png">
		<img class="mySlides" src="assets/img/9.png">
		<img class="mySlides" src="assets/img/9.png">
		<img class="mySlides" src="assets/img/10.png">
		<img class="mySlides" src="assets/img/11.png">
		<img class="mySlides" src="assets/img/12.png">
		<button class="w3-button w3-display-left" onclick="plusDivs(-1)">&#10094;</button>
		<button class="w3-button w3-display-right" onclick="plusDivs(+1)">&#10095;</button>
	</div>
	<div class="6u$ 12u$(small)">
		<h3>Auction House system</h3>
		<p>
		 <a href="https://github.com/billyjason/Auction-House-System">
		https://github.com/billyjason/Auction-House-System</a>
		</p>
	</div>
	<!-- Break -->
	<div class="4u 12u$(medium)">
		<h3>Cache Similator</h3>
		<p>
		 <a href="https://github.com/billyjason/Cache-Similator-LRU-FIFO-and-Random-">
		https://github.com/billyjason/Cache-Similator-LRU-FIFO-and-Random-</a>
		</p>
	</div>
	<div class="4u 12u$(medium)">
		<h3>Natural language processing pipeline</h3>
		<p>
		 <a href="https://github.com/billyjason/Natural-Language-Processing-Pipeline">
		https://github.com/billyjason/Natural-Language-Processing-Pipeline</a>
		</p>
	</div>
	<div class="4u 12u$(medium)">
		<h3>Micro Hasketll Formal Language Processing Pipeline</h3>
		<p>
		 <a href="https://github.com/billyjason/Micro-Hasketll-FL-Pipeline">
		https://github.com/billyjason/Micro-Hasketll-FL-Pipeline</a>
		</p>
	</div>
	<div class="4u$ 12u$(medium)">
		<h3>Library Managment System</h3>
		<p>
		 <a href="https://github.com/billyjason/Library-Managment-System">
		https://github.com/billyjason/Library-Managment-System</a>
		</p>
	</div>
	<div class="4u$ 12u$(medium)">
		<h3>Voting Site</h3>
		<p>
		 <a href="https://github.com/billyjason/votingsite2">
		https://github.com/billyjason/votingsite2</a>
		</p>
	</div>
</div>

<hr class="major" />
<div class="12u$ 12u$(medium)">
		<h3>This video hightlights the projects I worked on when I was in highschool (2013-2016)</h3>
		<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/v8cuZL6tEbk?start=1" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
	</div>
<script>
	var slideIndex = 1;
	showDivs(slideIndex);

	function plusDivs(n) {
	showDivs(slideIndex += n);
	}

	function showDivs(n) {
	var i;
	var x = document.getElementsByClassName("mySlides");
	if (n > x.length) {slideIndex = 1}    
	if (n < 1) {slideIndex = x.length}
	for (i = 0; i < x.length; i++) {
		x[i].style.display = "none";  
	}
	x[slideIndex-1].style.display = "block";  
	}
</script>
