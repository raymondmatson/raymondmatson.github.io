---
layout: default
title: Teaching
---

<!-- Allows for LaTeX writing -->
<script type="text/javascript" async
	src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?
	config=TeX-AMS-MML_HTMLorMML">
</script>
<script>
	function showDiv(myVar) {
		var x = document.getElementById(myVar);
		if (x.style.display === "none") {
			x.style.display = "block";
		} else {
			x.style.display = "none";
		}
	}
</script>





<br>
<h1 align=center style="color:darkblue">Fundamental Exercises in Algebra</h1>
<br>
<br>


<br>
<div style="background-color: #f3f3f3; ">
	<br/>
	<style>
		table, th, td { border: 1px solid black; border-collapse: collapse; background: #ffffff; margin-top: 50px; margin-bottom:50px; }
		th, td { padding: 10px; }
	</style>
	<div align=center style="margin-left:10px; margin-right:50px;">
		<p><u>Fundamental Exercises in Algebra</u>:</p><br>
		<div align=left>
			<p>In studying for the Algebra Qualifying Exam, these are some exercises you should really really know. Most of these are either common questions on past qualifying exams or popular homework problems chosen from Hungerford's <i>Algebra</i>.</p>
			<br>
			<p>Since these exercises are so fundamental, solutions to many of them can be found either in <a href="">John Dusel’s notes</a>, or in <a href="">Kayla Murray’s notes</a>, or somewhere online like <a href="">Math Stack Exchange</a> (MathSE). If you find a solution online, you should send me a link so I can post it here. Otherwise, if you think it’ll help you study, you can type up a solution and send me a PDF to post here. Or better, you can type up your solution on MathSE so that other algebra students can easily find it, add to it, comment on it, etc. The MathSE community is going through a bit of a phase right now, though, so it would be a good idea to read over this <a href="">brief guide to posting on MathSE</a> before writing up your solution there.</p>
			<br>
		</div>
		<br>
		<br>
		<input type="button" name="answer" value="Groups" onclick="showDiv('AlgGroups')" />
		<div id="AlgGroups" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Group Theory</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>Suppose that \(G\) has a subgroup \(H\) of finite index. Prove that the number of left cosets of \(H\) in \(G\) is the same as the number of right cosets.</li><br>
				<li>Consider a finite group \(G\) and \(N \triangleleft G\).
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>For \(g∈G\), prove that the order of \(gN\) in \(G/N\) divides the order of \(g\) in \(G\).</li>
						<li>For a subgroup \(H\) of \(G\), prove that if \(|H|\) and \([G:N]\) are relatively prime, then \(H\) is a subgroup of \(N\).</li>
						<li>Prove that if \(|N|\) and \([G:N]\) are relatively prime, then \(N\) is the only subgroup of \(G\) with order \(|N|\).</li>
					</ol>
				</li><br>
				<li>Prove that a subgroup of index two must be normal.</li><br>
				<li>Can you find examples of a groups \(K\), \(H\), and \(G\) such that \(H \triangleleft G\) and \(K \triangleleft H\), but \(K\) is not normal in \(G\)?</li><br>
				<li>What's a finite group G with normal subgroups A and B such that
				<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(A \cong B\) but \(G/A \ncong G/B\)?</li>
						<li>\(A \ncong B\) but \(G/A \cong G/B\)?</li>
					</ol>
				</li><br>
				<li>Prove that every (nontrivial) subgroup of \(\mathbb{Z}\) is cyclic.</li><br>
				<li>Let \(G\) be an abelian group, and let \(H\) be a subgroup of \(G\). Prove that if there is a homomorphism \( \varphi : G \to H\) such that \(\varphi\) restricted to \(H\) is the identity, then \(G \cong H \times \ker\varphi\).</li><br>
				<li>Suppose that \(\sigma \in S_n\) is given in cyclic notation as \((i_1 i_2 \cdots i_m)\). For \(\tau \in S_n\) prove that \(\tau\sigma\tau^{-1} = (\tau(i_1)\tau(i_2) \cdots \tau(i_m))\).</li><br>
				<li>An element of \(S_n\) may be written as a product of transpositions. Among all such ways of writing an element as a product of transpositions, there is a minimal number of transpositions necessary to write that element. For any \(n\), what is the maximum number over all elements of \(S_n\) of this minimal number of transpositions that you need to write that element?</li><br>
				<li>For a finitely generated abelian group \(G\), recall the definition of the <i>invariant factors</i> of \(G\) and of the <i>elementary divisors</i> of \(G\). For an abelian group of the following orders, write down every possibility for its list of invariant factors and elementary divisors.\[165 \quad 180 \quad 128\]</li><br>
				<li>Prove that if \(G\) is a finite noncyclic abelian group, then \(Aut(G)\) is not abelian.</li><br>
				<li>For a group \(G\) acting on a set \(X\), for an element \(x \in X\) recall the definition of the <i>orbit</i> of \(x\), denoted \(G.x\), and of the <i>stabilizer</i> of \(x\), denoted \(G_x\). Prove that \(|G.x| = [G:G_x]\).</li><br>
				<li>What is the definition of an inner automorphism of a group? Prove that the group of inner automorphisms of a group \(G\) form a normal subgroup of \(Aut(G)\). Furthermore prove that the group of inner automorphisms is isomorphic to \(G/Z(G)\), where \(Z(G)\) denotes the center of \(G\).</li><br>
				<li>Prove that if a group contains an element of order greater than two, then it must have a nontrivial automorphism.</li><br>
				<li>Prove that \(G/Z(G)\) is cyclic if and only if \(G\) is abelian.</li><br>
				<li>Related to the previous question, prove that \(Aut(G)\) being cyclic means \(G\) is abelian. What's an example of an abelian group with non-cyclic automorphism group? (<a href="https://math.stackexchange.com/questions/33254/showing-that-a-cyclic-automorphism-group-makes-a-finite-group-abelian">MathSE</a>)</li><br>
				<li>For a group \(G\) and a subgroup \(H\) of \(G\) of finite index, prove that there must exist a normal subgroup \(N\) of \(G\) contained in \(H\) that also has finite index. (<a href="https://math.stackexchange.com/questions/88719/a-group-g-with-a-subgroup-h-of-index-n-has-a-normal-subgroup-k-subset-h">MathSE</a>)</li><br>
				<li>A variation on the previous exercise: If \(G\) is a finite simple group with a subgroup \(H\) of index \(n\), show that \(G\) is isomorphic to a subgroup of \(S_n\).</li><br>
				<li>For a finite group \(G\) with subgroup \(H\) of index \(p\), if \(p\) is the smallest prime divisor of \(|G|\), then \(H\) must be normal in \(G\). (<a href="https://math.stackexchange.com/questions/164244/normal-subgroup-of-prime-index">MathSE</a>)</li><br>
				<li>Prove that a finite \(p\)-group has nontrivial center.</li><br>
				<li>Prove that if \(|G|=p^n\) for some prime integer \(p\), then \(Z(G)\) is nontrivial.</li><br>
				<li>Prove that for a normal Sylow \(p\)-subgroup \(P\) of a finite group \(G\), and an endomorphism \(\phi\) of \(G\), that \(\phi(P)\) is a subgroup of \(P\). Is this true if \(G\) is infinite?</li><br>
				<li>Prove that if \(|G| = p^2\) for some prime integer \(p\), then \(G\) is abelian.</li><br>
				<li>Suppose that \(p\) and \(q\) are prime integers such that \(p > q\). Prove that if \(|G|=p^n q\), then \(G\) cannot be simple.</li><br>
				<li>Show that a group of any of the following orders cannot be simple. (<a href="https://math.stackexchange.com/questions/280657/non-abelian-simple-group-of-order-120">MathSE</a>)\[105 \quad 120 \quad 200 \quad 250\]</li><br>
				<li>For a group \(G\), what is the definition of its commutator subgroup? Denote the commutator subgroup as \(G'\). Prove that \(G'\) is normal in \(G\), and show that for any abelian group \(A\), a homomorphism \(G \to A\) must factor through the quotient \(G/G'\).</li><br>
				<li>Recall what it means for a group to be <i>nilpotent</i> and what it means for a group to be <i>solvable</i>. Prove that a nilpotent group is solvable. (See Hungerford Chapter II, Section 7, Exercises 3 and 4 for an different characterizations of solvability and nilpotency that make this proof easier.)</li><br>
				<li>Prove that every subgroup and every homomorphic image of a solvable group is solvable.</li><br>
				<li>If \(N\) is normal in \(G\) and both \(N\) and \(G/N\) are solvable, prove that \(G\) is solvable too.</li><br>
			</ol>
			<br>
			<br>
		</div>
	</div>
	<br>
</div>

