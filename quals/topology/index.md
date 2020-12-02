---
layout: default
title: Topology Qual Stuff
---

<!-- Allows for LaTeX writing -->
<script type="text/javascript" async 
	src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?
	config=TeX-AMS-MML_HTMLorMML">
</script>

<br>
<h1 align=center style="color: darkblue">Topology</h1>
<br>










<div style="border-top: 1px solid #d5d5d5"></div>
<br>
<br>
<p style="margin-left:50px; margin-right:50px; page-break-after: always;">One of the ways my roommates and I studied for our quals was by presenting an entire year of material to each other in under an hour. Now we had the added benefit (or drawback depending on how you look at it) of somehow all taking different core classes, leaving room for lots of questions throughout our presentations. Below are the detailed notes I made for my topology presentation. If you're studying for a qual I highly encourage you to make your own set of notes and give someone in your cohort a presentation on everything you've learned.</p>
<br>

<br>
<div class=TLDRpdf style="background-color: #f3f3f3; border-top: 1px solid #d5d5d5; border-bottom: 1px solid #d5d5d5">
	<embed src="/quals/topology/TLDR_Topology.pdf" width="1150px" height="855px" style="background-color: #f3f3f3; margin-top:30px; margin-bottom:30px;"/>
	<p style="font-size:70%;">Note: I left out a lot of point-set topology in my notes as it's mostly undergrad level and everyone I presented this to had seen it before.</p>
	<br>
</div>
<br>










<br>
<p style="margin-left:50px; margin-right:50px; page-break-after: always;">Below is a list of certain path connected topological spaces and their corresponding fundamental groups and homologies. Being able to have these in your back pocket will greatly enhance your toolset when going into the quals. However, you should also be able to prove that these fundamental groups and homology groups are what I claim they are.</p>
<br>

<br>
<div class=topExamples style="background-color: #f3f3f3; border-top: 1px solid #d5d5d5; border-bottom: 1px solid #d5d5d5">
	<br/>
	<style>
		table, th, td { border: 1px solid black; border-collapse: collapse; background: #ffffff; margin-top: 50px; margin-bottom:50px; }
		th, td { padding: 10px; }
	</style>
	<div align=center>
		<table style="width:50%">
			<tr>
				<th>Name</th>
				<th>Notation</th>
				<th>Fundamental Group</th>
				<th>Homology</th>
			</tr>
			<!-- top image -->
			<!-- name -->
			<!-- top fundamental group -->
			<!-- top homology (write as piecewise function) -->
			<tr>
				<td align=center>n-Sphere</td>
				<td align=center>\( S^{n} \)</td>
				<td align=center>\(\pi_1(S^{n}) = \begin{cases} \mathbb{Z} & \text{if } n = 1 \\ 0 & \text{if } n > 1 \end{cases} \)</td>
				<td align=center>\(H_k(S^n) = \begin{cases} \mathbb{Z} & \text{if } k = 0, n \\ 0 & \text{else } \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Möbius Band</td>
				<td align=center>\(M\)</td>
				<td align=center>\(\pi_1(M) = \mathbb{Z} \)</td>
				<td align=center>\(H_k(M) = \begin{cases} \mathbb{Z} & \text{if } k = 0 \\ \mathbb{Z} & \text{if } k = 1 \\ 0 & \text{if } k \geq 2 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>n-Rose</td>
				<td align=center>\(\vee_{i=1}^{n} S^1\)</td>
				<td align=center>\(\pi_1(\vee_{i=1}^{n}S^1) = F_{n} \)</td>
				<td align=center>\(H_k(\vee_{i=1}^{n}S^1) = \begin{cases} \mathbb{Z} & \text{if } k = 0 \\ \mathbb{Z}^n & \text{if } k = 1 \\ 0 & \text{if } k \geq 2 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Real Projective Space</td>
				<td align=center>\(\mathbb{R}P^{n}\)</td>
				<td align=center>\(\pi_1(\mathbb{R}P^{n}) = \begin{cases} \mathbb{Z} & \text{if } n = 1 \\ \mathbb{Z}/2\mathbb{Z} & \text{if } n > 1 \end{cases} \)</td>
				<td align=center>\(H_k(\mathbb{R}P^{n}) = \begin{cases} \mathbb{Z} & \text{if } k = 0, n \text{ odd} \\ \mathbb{Z}/2\mathbb{Z} & \text{if } 0 < k < n \text{ odd} \\ 0 & \text{else } \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Klein Bottle</td>
				<td align=center>\(K_4\)</td>
				<td align=center>\(\pi_1(K_4)= < a,b \mid aba^{-1}b >\)</td>
				<td align=center>\(H_k(K_4) = \begin{cases} \mathbb{Z} & \text{if } n = 0 \\ \mathbb{Z} \oplus \mathbb{Z}/2\mathbb{Z} & \text{if } n = 1 \\ 0 & \text{if } n \geq 2 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Torus</td>
				<td align=center>\(T^2\)</td>
				<td align=center>\(\pi_1(T^2) = \mathbb{Z}^2 \)</td>
				<td align=center>\(H_k(T^2) = \begin{cases} \mathbb{Z} & \text{if } n = 0 \\ \mathbb{Z}^{2} & \text{if } n = 1 \\ \mathbb{Z} & \text{if } n = 2 \\ 0 & \text{if } n \geq 3 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Genus 2 Surface</td>
				<td align=center>\(S_2\)</td>
				<td align=center>\(\pi_1(S_2)= < a,b,c,d \mid aba^{-1}b^{-1}cdc^{-1}d^{-1} >\)</td>
				<td align=center>\(H_k(S_2) = \begin{cases} \mathbb{Z} & \text{if } n = 0 \\ \mathbb{Z}^{4} & \text{if } n = 1 \\ \mathbb{Z} & \text{if } n = 2 \\ 0 & \text{if } n \geq 3 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Genus g Surface</td>
				<td align=center>\(S_g\)</td>
				<td align=center>\(\pi_1(S_g)= < a_1, b_1, \cdots, a_g, b_g \mid [a_1, b_1] \cdots [a_g, b_g] >\)</td>
				<td align=center>\(H_k(S_g) = \begin{cases} \mathbb{Z} & \text{if } n = 0 \\ \mathbb{Z}^{2g} & \text{if } n = 1 \\ \mathbb{Z} & \text{if } n = 2 \\ 0 & \text{if } n \geq 3 \end{cases} \)</td>
			</tr>
			<tr>
				<td align=center>Wedged Spaces</td>
				<td align=center>\(X \vee Y\)</td>
				<td align=center>\(\pi_1(X \vee Y) = \pi_1(X) \star \pi_1(Y) \)</td>
				<td align=center>\(H_k(X \vee Y) = H_k(X) \oplus H_k(Y) \)</td>
			</tr>
			<tr>
				<td align=center>Product Spaces</td>
				<td align=center>\(X \times Y\)</td>
				<td align=center>\(\pi_1(X \times Y) = \pi_1(X) \times \pi_1(Y) \)</td>
				<td align=center>Uhhh... it's complicated</td>
			</tr>
		</table>
	</div>
	<br>
</div>

<!-- 
<div class=topExamples>
	<span class="math inline">\(S^{n}\)</span> for <span class="math inline">\(n > 1\)</span>
	
</div>
<br clear="all" />
 -->