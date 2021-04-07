---
layout: talks
title: Math Interests
---

<script type="text/javascript" async 
	src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?config=TeX-AMS-MML_HTMLorMML">
</script>







<br>
<div style="background-color: #0084bd;">
	<br>
	<h1 align=center style="color:white">Past Talks</h1>
	<br>
</div>
<br>



<!-- The Game of Cops and Robbers -->
<div class="talkBox-labelcontainer">
	<div class="talkBox-labellefthalf">
		<button type='button' onclick="toggleAbstract('abstract1')" style="color: green; margin-top: 3%;">Abstract</button><!-- Make sure that the function takes in the id from the abstract -->
		<p id='abstract1' style="font-size: 20px; display: none; overflow: auto; width: auto; height: 95px; margin-top: 3%; border: 1px solid darkblue; box-shadow: 0 0 3px 3px black; background: white">
			The game of cops and robbers is a type of graph searching problem where a team of cops try to capture a robber by moving onto the same vertex as the robber. The canonical question that arises is: what is the smallest number of cops needed to ensure that the cops will win for any graph of order <span class="math inline">\(n\)</span>? Henri Meyniel conjectured that for any connected graph of order <span class="math inline">\(n\)</span>, the number of cops needed is <span class="math inline">\(O(\sqrt{n})\)</span>. We will explore the upper bound of some specific graphs as well as attempts to prove Meyniel's conjecture.
		</p>
	</div>
	<div class="talkBox-labelrighthalf">
		<h4>The Game of Cops and Robbers on Graphs</h4>
		<p style="margin-top: 3%;">Graduate Student Seminar - January 17, 2020</p>
	</div>
</div>
<!-- Content -->
<div class="talkBox-contentcontainer">
	<div class="talkBox-lefthalf">
		<img src="/pictures/CopsAndRobbers.jpg" style="width:100%; height:100%; display: inline-block;">
	</div>
	<div class="talkBox-righthalf">
		<iframe src="/math-interests/Cops_and_Robbers_Notes.pdf" style="width:100%; height:100%;"></iframe>
	</div>
</div>
<br>



<!-- Supercharacter Theory -->
<div class="talkBox-labelcontainer">
	<div class="talkBox-labellefthalf">
		<h4>Supercharacter Theories of Pattern Groups</h4>
		<p style="margin-top: 3%;">Lie Theory Seminar - March 3, 2020</p>
	</div>
	<div class="talkBox-labelrighthalf">
		<button type='button' onclick="toggleAbstract('abstract2')" style="color: green; margin-top: 3%;">Abstract</button><!-- Make sure that the function takes in the id from the abstract -->
		<p id='abstract2' style="font-size: 20px; display: none; overflow: auto; width: auto; height: 95px; margin-top: 3%; border: 1px solid darkblue; box-shadow: 0 0 3px 3px black; background: white">
			Classical character theory is a way to condense important information of representations in order to classify groups up to isomorphism. Out of trying to characterize some particularly difficult cases, an even more condensed type of theory was discovered named supercharacter theories. We'll introduce supercharacter theory by talking about a particular motivating example called a pattern group. If there's time we will compare classical character tables to supercharacter tables.
		</p>
	</div>
</div>
<!-- Content -->
<div class="talkBox-contentcontainer">
	<div class="talkBox-lefthalf">
		<iframe src="/math-interests/An_Introduction_to_Supercharacter_Theory.pdf" style="width:100%; height:100%;"></iframe>
	</div>
	<div class="talkBox-righthalf">
		<img src="/pictures/supercharacter.png" style="width:100%; height:100%; display: inline-block;">
	</div>
</div>
<br>



<!-- An Introduction to Machine Learning and Neural Networks -->
<div class="talkBox-labelcontainer">
	<div class="talkBox-labellefthalf">
		<button type='button' onclick="toggleAbstract('abstract3')" style="color: green; margin-top: 3%;">Abstract</button><!-- Make sure that the function takes in the id from the abstract -->
		<p id='abstract3' style="font-size: 20px; display: none; overflow: auto; width: auto; height: 95px; margin-top: 3%; border: 1px solid darkblue; box-shadow: 0 0 3px 3px black; background: white">
			Artificial intelligence, machine learning, neural networks, deep learning -- so many buzzwords! But what do they all mean?! When I search online for answers (and not just on math stack exchange) I often find that the majority of explanations either give you a bunch of deep theory without any realistic applications or it's all about the code and fails to provide any understanding. In this talk I'll attempt to give a fairly basic introduction to ML and neural nets that lies somewhere in between, and probably somehow manage to give you neither application nor theory.
		</p>
	</div>
	<div class="talkBox-labelrighthalf">
		<h4>Intro to Machine Learning and Neural Networks</h4>
		<p style="margin-top: 3%;">Graduate Student Seminar - April 2, 2021</p>
	</div>
</div>
<!-- Content -->
<div class="talkBox-contentcontainer">
	<div class="talkBox-lefthalf">
		<img src="/pictures/ML.jpg" style="width:100%; height:100%; display: inline-block;">
	</div>
	<div class="talkBox-righthalf">
		<iframe src="/math-interests/Intro_To_ML_And_NN.pdf" style="width:100%; height:100%;"></iframe>
	</div>
</div>
<br>









<script>
	function toggleAbstract(abstNum) {
		var abstText = document.getElementById(abstNum);
		if (abstText.style.display === "none") {
			abstText.style.display = "block";
		} else {
			abstText.style.display = "none";
		}
	}
</script>
