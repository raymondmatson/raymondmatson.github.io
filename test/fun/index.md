---
layout: default
title: Teaching
---

<!-- Allows for LaTeX writing -->
<script type="text/javascript" async
	src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.1/MathJax.js?
	config=TeX-AMS-MML_HTMLorMML">
</script>
<!-- <script type="text/javascript" async
	src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=default">
</script> -->
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
<h1 align=center style="color: darkblue">Algebra</h1>
<br>






<div style="border-top: 1px solid #d5d5d5"></div>
<br>
<br>
<div style="background-color: #f3f3f3; ">
	<br/>
	<style>
		table, th, td { border: 1px solid black; border-collapse: collapse; background: #ffffff; margin-top: 50px; margin-bottom:50px; }
		th, td { padding: 10px; }
	</style>
	<div align=center style="margin-left:10px; margin-right:50px;">
		<p><u>Standard Exercises in Algebra</u>:</p><br>
		<div align=left>
			<p>In studying for the Algebra Qualifying Exam, these are some exercises you should really really know. The majority of these are either common questions on past qualifying exams or popular homework problems chosen from Hungerford's <i>Algebra</i>.</p>
			<br>
			<p>Since these exercises are fairly common, solutions to many of them can be found either in <a href="">John Dusel’s notes</a>, or in <a href="">Kayla Murray’s notes</a>, or somewhere online like <a href="">Math Stack Exchange</a> (MathSE). If you find a solution online, you should send me a link so I can post it here. Otherwise, if you think it’ll help you study, you can type up a solution and send me a PDF to post on Alec Martin's website. Or better, you can type up your solution on MathSE so that other algebra students can easily find it, add to it, comment on it, etc.</p>
			<br>
			<p>Click on any of the following buttons for a list of questions in that subject:</p>
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
		<input type="button" name="answer" value="Rings" onclick="showDiv('AlgRings')" />
		<div id="AlgRings" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Ring Theory</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>Prove that a finite integral domain is in fact a field.</li><br>
				<li>Recall what it means for an element of a ring to be <i>nilpotent</i>. For a commutative unital ring \(R\), prove that the set of nilpotent elements forms an ideal.</li><br>
				<li>Prove that if \(R\) is commutative and both \(a\) and \(b\) in \(R\) are nilpotent, the their sum \(a + b\) is nilpotent. Why do we need \(R\) to be commutative?</li><br>
				<li>Let \(R\) be a field of characteristic \(p \neq 0\). Show that the Frobenius map (\(r \mapsto r^p\)) is an isomorphism</li><br>
				<li>What is an example of an integral domain \(R\) and ideals \(I\) and \(J\) such that \(IJ \neq I \cap J\)?</li><br>
				<li>In a commutative unital ring, prove that maximal ideas are prime. Prove that the converse is true if your ring is a PID.</li><br>
				<li>In the category of commutative unital rings, give an example of a
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>Ring that is not an Integral Domain.</li>
						<li>Integral Domain that is not a GCD Domain.</li>
						<li>Integral Domain that is not a UFD. (Bonus points if your example is a GCD Domain.)</li>
						<li>UFD that is not a PID.</li>
						<li>PID that is not a Euclidian Domain.</li>
						<li>Euclidean Domain that is not a Field.</li>
					</ol>
				</li><br>
				<li>For a commutative unital ring \(R\), an ideal \(M\) is maximal if and only if for each \(r \in R\setminus M\) there is some \(s \in R\) such that \(1 − rs \in M\).</li><br>
				<li>Recall the definition of an <i>idempotent</i> element of a ring and of a <i>central element</i> of a ring. Two elements \(a\) and \(b\) of a ring are <i>orthogonal</i> if \(ab = 0\). If \(R\) is a unital ring with idempotent element \(e\),
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>then the element \(1-e\) is also idempotent,</li>
						<li>and if \(e\) is a central element of \(R\), then \(eR\) and \((1−e)R\) are ideals such that \(R = eR \times (1-e)R\).</li>
						<li>More generally, there are ideals \(\{J_i\}_{i \in 1, \cdots, n}\) of \(R\) such that \(R\) can be written as an <i>internal</i> direct sum of the \(J_i\), i.e. \(R = J_1 \oplus \cdots \oplus J_n\), if and only if \(R\) contains orthogonal central idempotents \(\{e_i\}_{i \in 1, \cdots, n}\) such that \(e_1 + \cdots + e_n = 1\) and \(J_i = e_i R\) for \(i \in \{1,…,n\}\).
						This is called the Peirce decomposition of a ring.</li>
					</ol>
				</li><br>
				<li>Recall the definition of a <i>local ring</i>. Prove that a commutative unital ring \(R\) is local if and only if for all \(a,b \in R\) we have that \(a + b = 1\) implies that either \(a\) or \(b\) is a unit.</li><br>
				<li>Prove that \(R\) is local if every non-unit of \(R\) is nilpotent.</li><br>
				<li>For a unital ring \(R\) of characteristic \(p\), let \(a\) be a nilpotent element of \(R\). Prove that \(a + 1\) is unipotent (that some power of \(a + 1\) equals \(1\)).</li><br>
				<li>What’s an example of an integral domain \(R\) with non-maximal ideal \(I\) such that \(char R = 0\) but \(char R/I \neq 0\)?</li><br>
				<li>For a commutative unital ring \(R\), suppose that \(f = a_nx^n + a_{n−1}x^{n−1} + \cdots + a_0\) is a zero divisor in \(R[x]\). Prove that there exists some \(b \in R\) such that \(b a_n = b a_{n-1}  = \cdots = b a_0 = 0\).</li><br>
				<li>For a commutative unital ring \(R\) and polynomial \(f = a_nx^n + a_{n−1}x^{n−1} + \cdots + a_0 \in R[x]\), \(f\) is a unit in \(R[x]\) if and only if \(a_0\) is a unit in \(R\) and \(a_1, \cdots, a_n\) are nilpotent.</li><br>
				<li>Suppose \(R\) is a ring such that \(r^2 = r\) for all \(r \in R\). Prove
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>every element is its own additive inverse.</li>
						<li>\(R\) is commutative.</li>
						<li>every finitely generated ideal is principal. (<a href="https://math.stackexchange.com/questions/110329/finitely-generated-ideals-in-a-boolean-ring-are-principal-why">MathSE</a>)</li>
						<li>every prime ideal is maximal.</li>
					</ol>
				</li><br>
				<li>For indeterminates \(x\) and \(y\) and a field \(k\), prove that \((x,y)\) is not a principal ideal of \(k[x,y]\).</li><br>
			</ol>
			<br>
			<br>
		</div>
		<input type="button" name="answer" value="Commutative Algebra" onclick="showDiv('AlgComm')" />
		<div id="AlgComm" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Commutative Algebra</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>Prove that these three characterizations of \(\text{Rad}(I)\), the <i>radical</i> of an ideal \(I\) of a commutative unital ring \(R\), are equivalent. The first one is the usual definition.
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(\text{Rad}(I) = \{r \in R : r^n \in I, n \in \mathbb{N}\}\)</li>
						<li>\(\text{Rad}(I)\) is the intersection of all prime ideals of \(R\) that contain \(I\).</li>
						<li>\(\text{Rad}(I)\) is the pre-image of the ideal of nilpotent elements in \(R/I\).</li>
					</ol>
				It would be a good idea to prove that \(\text{Rad}(I)\) is an honest ideal of \(R\) directly from the first of these characterizations.
				</li><br>
				<li>For a multiplicative subset \(S\) of a commutative unital ring \(R\), and an ideal \(I\) of \(R\), prove that \(S^{-1} \text{Rad}(I) = \text{Rad}(S^{-1}I)\).</li><br>
				<li>What’s an example of a Noetherian integral domain that is not a PID?</li><br>
				<li>For a commutative unital ring \(R\), let \(I\) be a <i>primary</i> ideal of \(R\), which means that for \(a,b \in R\) such that \(ab \in I\), either \(a \in I\) or \(b^n \in I\) for some \(n \in N\). Let \(S\) be a multiplicative subset of \(R\) such that \(S \cap I = \emptyset\). Prove that \(S^{-1}I\) is a primary ideal of \(S^{−1}R\).</li><br>
				<li>For a commutative unital ring \(R\) and proper ideal \(I\) of \(R\), prove that \(I\) is a primary ideal if and only if the zero divisors in \(R/I\) are all nilpotent.</li><br>
				<li>For a commutative unital ring \(R\), let \(S\) be a saturated multiplicative subset \(R\), so for \(x,y \in R\) we have that if \(xy \in S\) then \(x,y \in S\). Prove that \(R \setminus S\) is a union of prime ideals of \(R\)</li><br>
				<li>For a commutative unital ring \(R\), prove that the set of zero divisors of \(R\) is a union of prime ideals.</li><br>
			</ol>
			<br>
			<br>
		</div>
		<input type="button" name="answer" value="Modules" onclick="showDiv('AlgMods')" />
		<div id="AlgMods" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Modules</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>Recall what it means for arbitrary extension of rings, \(A \subset B\), to be <i>finite</i> and <i>free</i>.
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>Let \(\{b_1, \cdots, b_n\}\) be a free basis for \(A \subset B\). If \(b = a_1b_1 + \cdots + a_nb_n\) for each \(a_i \in A\) and some \(a_s\) is a unit, show one may replace \(b_s\) with \(b\) to obtain another free basis.</li>
						<li>Show that the natural inclusion \(\mathbb{Q}[x] \hookrightarrow \mathbb{Q}[x,y]/\langle y^3 - x^2 y^2 + 7xy - 11x^{100} \rangle\) is finite and free.</li>
						<li>Show that \(\mathbb{F}_p[x^p] \subset \mathbb{F}_p[x]\) is finite and free. What's the canonical free basis for this extension?</li>
						<li>Let \(R = \mathbb{F}_p[x_1, \cdots, x_n]\). Then each extension in \(\cdots \subset R^{p^k} \subset \cdots \subset R^{p^2} \subset R^p \subset R \subset R^{1/p} \subset \cdots\) is finite and free.</li>
					</ol>
				</li><br>
				<li>For unital ring \(R\), recall what it means for a unitary \(R\)-module to be <i>simple</i>. Prove that a simple \(R\)-module \(M\) must be cyclic, and that the ring \(\text{End}_R(M)\) is a division ring. What about the converse? Is it true that if \(\text{End}_R(M)\) is a division ring then \(M\) must be simple?</li><br>
				<li>For a commutative unital ring \(R\) and left \(R\)-modules \(M\) and \(N\), does \(\text{Hom}_R(M,N)\) have any sort of \(R\)-module structure? Is it necessary to assume that \(R\) is commutative? What if \(M\) is a right \(R\)-module instead? (<a href="https://math.stackexchange.com/questions/637807/why-is-operatornamehomm-n-not-necessarily-an-r-module">MathSE</a>)</li><br>
				<li>For a ring \(R\), consider the commutative diagram
				$$\require{AMScd} \begin{CD}
				0 @>>> A @>{f_1}>> B @>{f_2}>> C @>>> 0\\
				@. @. @V{\phi_2}VV @. @.\\
				0 @>>> X @>{g_1}>> Y @>{g_2}>> Z @>>> 0\\
				\end{CD}$$
				in the category of \(R\)-modules such that the top and bottom rows are exact. Suppose that there is a some map \(\phi_1 \in \text{Hom}_R(A,X)\) such that \(\phi_2 \circ f_1 = g_1 \circ \phi_1\). Prove that there exists some map \(\phi_3 \in \text{Hom}_R(C,Z)\) such that \(\phi_3 \circ f_2 = g_2 \circ \phi_2\).</li><br>
				<li>Suppose that \(P\) is a projective \(R\)-module, and is the homomorphic image of some \(R\)-module \(M\). Prove that \(P\) is isomorphic to a direct summand of \(M\). What is the analogous fact to this one concerning injective \(R\)-modules?</li><br>
				<li>For a unital ring \(R\), in the category \(R-\text{Mod}\), a free module is projective.</li><br>
				<li>More generally than the previous problem, consider the three following adjectives that could describe an \(R\)-module: \(\text{free} \quad \text{projective} \quad \text{torsion-free}\)<br>
				Which of these properties of an \(R\)-module imply another, and which don't? Provide proofs and counterexamples.</li><br>
				<li>Prove that a direct sum of \(R\)-modules \(\oplus_{i \in I} P_i\) is projective if and only if each \(P_i\) is projective.</li><br>
				<li>Prove that \(\mathbb{Q}\) is not a projective \(\mathbb{Z}\)-module. What is an example of a projective \(\mathbb{Z}\)-module?</li><br>
				<li>Recall the definition of a \(\mathbb{Z}\)-module (abelian group) being <i>divisible</i>. Prove that a unitary \(\mathbb{Z}\)-module is injective if an only if it is divisible.</li><br>
				<li>Suppose that in the category \(R\)-mod, for any object \(D\) the functor \(\text{Hom}_R(D,−)\) preserves the exactness of the sequence \[0 \to A \to B \to C \to 0.\] Prove that this sequence must split. Prove the converse of this statement too.</li><br>
				<li>For a unital ring \(R\) and a unitary left \(R\)-module \(M\), write out the details of the left \(R\)-module isomorphism \(M \cong \text{Hom}_R(R,M)\).</li><br>
				<li>For a left \(R\)-module \(M\), write down the details of the natural homomorphism of \(R\)-modules \(\theta_M : A \to A^{**}\). Prove that \(\theta_M\) is an isomorphism if \(R\) is unital and \(M\) is free with finite basis over \(R\).</li><br>
				<li>For a homomorphism of left \(R\)-modules \(f: M \to N\), write down the details of the natural map \(f^∗: M^{∗∗} \to N^{∗∗}\) such that the following diagram commutes:
					$$ \require{AMScd} \begin{CD}
					M @>{\theta_M}>> M^{\ast\ast}\\
					@V{f}VV @VV{f^\ast}V\\
					N @>{\theta_N}>> N^{\ast\ast}\\
					\end{CD} $$</li><br>
				<li>For a unital ring \(R\) and a unitary left \(R\)-module \(M\), write out the details of the left \(R\)-module isomorphism \(R \otimes_R M \cong M\).</li><br>
				<li>Let \(R\) be a PID and suppose \(V\) and \(W\) are (not fully torsion) finite dimensional modules over \(R\). Show the following:
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(\text{dim}(V \oplus W) = \text{dim}(V) + \text{dim}(W)\)</li>
						<li>\(\text{dim}(V \otimes W) = \text{dim}(V) \text{dim}(W)\)</li>
					</ol></li><br>
				<li>For integers \(m\) and \(n\), write out the details of the \(\mathbb{Z}\)-bimodule isomorphism \(\mathbb{Z}/(m) \otimes_\mathbb{Z} \mathbb{Z}/(n) \cong \mathbb{Z}/(m,n)\). (<a href="https://math.stackexchange.com/questions/72284/proof-of-mathbbz-m-mathbbz-otimes-mathbbz-mathbbz-n-mathbbz">MathSE</a>)</li><br>
				<li>Let \(S\) be a two-sided ideal of a ring \(R\) and let \(SM\) denote the abelian subgroup of an \(R\)-module \(M\) generated by elements of the form \(sm\) for \(s \in S\) and \(m \in M\). Show that \(SM\) is an honest submodule of \(M\), describe the natural left \(R\)-module structure on \((R/S) \otimes_R M\), and show that \((R/S)\otimes_R M \cong M/SM\) as left \(R\)-modules.</li><br>
				<li>Suppose that \(A\) and \(A'\) are left \(R\)-modules and \(B\) and \(B'\) are right \(R\)-modules. Take \(f \in Hom(A,A')\) and \(g \in \text{Hom}(B,B')\). Is it necessarily true that \[\ker(f \otimes g) \cong (\ker f \otimes B) + (A \otimes \ker g)?\]</li><br>
				<li>Give examples of a commutative ring \(R\), of \(R\)-modules \(M\), \(M'\), and \(N\), and of a map \(f \in \text{Hom}(M,M')\) such that
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(f\) is injective, but \(1 \otimes f : N \otimes M \to N \otimes M'\) is not injective.</li>
						<li>\(f\) is surjective, but \(f^∗ :\text{Hom}(N,M) \to \text{Hom}(N,M')\), where \(f^∗(h) = f \circ h\), is not surjective.</li>
					</ol></li><br>
				<li>For a ring \(R\) and left \(R\)-modules \(M\) and \(N\), write down the details of the homomorphism of abelian groups \(M^∗ \otimes_R N \to \text{Hom}_R(M,N)\). Prove that this homomorphism is an isomorphism if \(R\) is a field and \(M\) and \(N\) are finite-dimensional vector spaces over \(R\).</li><br>
				<li>Let \(R\) be an integral domain. For an \(R\)-module \(M\), define \(\tau(M) = \{m \in M : \mathcal{O}_m \neq \emptyset\}\), where \(\mathcal{O}_m\) is the annihilator of \(m\) in \(R\). Prove that \(\tau\) induces a left-exact functor from \(R\)-mod to the category of torsion \(R\)-modules, where \(M \mapsto \tau(M)\) and \(f \mapsto f\mid_{\tau(M)}\). Why do we need the assumption that \(R\) is an integral domain?</li><br>
				<li>Let \(R\) be a PID, and let \(M\) be a unitary left \(R\)-module. For \(s \in R\) recall the definition of a couple of our favorite submodules of \(M\): \(sM = \{sm : m \in M\}\) and \(M[s] = \{ m \in M : sm = 0 \}\). Let \(p\) be a prime element of \(R\). Additionally, recall the definition of a <i>cyclic</i> \(R\)-module, and let \(N\) be a cyclic \(R\)-module of order \(r \in R\).
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>What is the natural way to define \(M/pM\) as a vector space over \(R/(p)\)?</li>
						<li>What is the natural way to define \(M[p]\) as a vector space over \(R/(p)\)?</li>
						<li>Supposing \(s\) is relatively prime to \(r\), prove that \(sN = N\) and \(N[s] = 0\).</li>
						<li>Suppose \(s\) divides \(r\), so there is some \(k\) such that \(sk = r\). Prove that \(sN \cong R/(k)\) and \(N[s] \cong R/(s)\).</li>
					</ol>
				</li><br>
			</ol>
			<br>
			<br>
		</div>
		<input type="button" name="answer" value="Linear Algebra" onclick="showDiv('AlgLinAlg')" />
		<div id="AlgLinAlg" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Linear Algebra</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>For a division ring \(D\), let \(V_i\) be a finite dimensional vector space over \(D\) for \(i \in \{ 1, \cdots, k\}\). Suppose the sequence \[0 \to V_1 \to V_2 \to \cdots \to V_k \to 0\] is exact. Prove that \(\sum_{i=1}^{k} (-1)^{-i}\text{dim}_D (V_i) = 0\)</li><br>
				<li>Prove that if \(A\) and \(B\) are invertible matrices over a field \(k\), then \(A + \lambda B\) is invertible for all but finitely many \(\lambda \in k\).</li><br>
				<li>For the ring of \(n \times n\) matrices over a commutative unital ring \(R\), which we'll denote \(\text{Mat}_n(R)\), recall the definition of the <i>determinant</i> map \(\text{det}: \text{Mat}_n(R) \to R\). For \(A \in \text{Mat}_n(R)\) also recall the definition of the <i>classical adjoint</i> \(A^\alpha\) of \(A\)
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(\text{det}(A^\alpha) = \text{det}(A)^{n-1}\)</li>
						<li>\((A^\alpha)^\alpha = \text{det}(A)^{n-2}A\)</li>
					</ol>
				</li><br>
				<li>If \(R\) is an integral domain and \(A\) is an \(n \times n\) matrix over \(R\), prove that if a system of linear equations \(Ax = 0\) has a nonzero solution then \(\text{det}A = 0\). Is the converse true? What if we drop the assumption that \(R\) is an integral domain?</li><br>
				<li>What is the companion matrix \(M\) of the polynomial \(f = x^2 - x + 2\) over \(\mathbb{C}\)? Prove that \(f\) is the minimal polynomial of \(M\).</li><br>
				<li>Suppose that \(\phi\) and \(\psi\) are commuting endomorphisms of a finite dimensional vector space \(E\) over a field \(k\), so \(\phi\psi = \psi\phi\).
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>Prove that if \(k\) is algebraically closed, then \(\phi\) and \(\psi\) have a common eigenvector.</li>
						<li>Prove that if \(E\) has a basis consisting of eigenvectors of \(\phi\) and \(E\) has a basis consisting of eigenvectors of \(\psi\), then \(E\) has a basis consisting of vectors that are eigenvectors for both \(\phi\) and \(\psi\) simultaneously.</li>
					</ol>
				</li><br>
			</ol>
			<br>
			<br>
		</div>
		<input type="button" name="answer" value="Galois Theory" onclick="showDiv('AlgGal')" />
		<div id="AlgGal" align=left style="display:none; margin-left:40px;" class="answer_list" >
			<h3>Galois Theory</h3>
			<br>
			<ol style="list-style-position: inside; margin-left:30px;">
				<li>Suppose that for an extension field \(F\) over \(K\) and for \(a \in F\), we have that \(b \in F\) is algebraic over \(K(a)\) but transcendental over \(K\). Prove that \(a\) is algebraic over \(K(b)\).</li><br>
				<li>Suppose that for a field \(F/K\) that \(a \in F\) is algebraic and has odd degree over \(K\). Prove that \(a^2\) is also algebraic and has odd degree over \(K\), and furthermore that \(K(a) = K(a^2)\).</li><br>
				<li>For a polynomial \(f \in K[x]\), prove that if \(r \in F\) is a root of \(f\) then for any \(\sigma \in \text{Aut}_K(F)\), \(\sigma(r)\) is also a root of \(f\).</li><br>
				<li>Prove that as extensions of \(\mathbb{Q}\), \(\mathbb{Q}(x)\) is Galois over \(\mathbb{Q}(x^2)\) but not over \(\mathbb{Q}(x^3)\).</li><br>
				<li>If \(F\) is _______ over \(E\), and \(E\) is _______ over \(K\), is \(F\) necessarily _______ over \(K\)? Answer this question for each of the words "algebraic," "normal," and "separable" in the blanks.</li><br>
				<li>If \(F\) is _______ over \(K\), and \(E\) is an intermediate extension of \(F\) over \(K\), is \(F\) necessarily _______ over \(E\)? Answer this question for each of the words "algebraic", "normal", and "separable" in the blanks.</li><br>
				<li>If \(F\) is some (not necessarily Galois) field extension over \(K\) such that \([F:K] = 6\) and \(\text{Aut}_K(F) \cong S_3\), then \(F\) is the splitting field of an irreducible cubic over \(K[x]\).</li><br>
				<li>Recall the definition of the <i>join</i> of two subgroups \(H \vee G\) (or \(H + G\)). For \(F\) a finite dimensional Galois extension over \(K\) and let \(A\) and \(B\) be intermediate extensions. Prove that
					<ol type="a" style="list-style-position: inside; margin-left:30px;">
						<li>\(\text{Aut}_{AB}(F) = \text{Aut}_A(F) \cap \text{Aut}_B(F)\)</li>
						<li>\(\text{Aut}_{A \cap B}(F) = \text{Aut}_A(F) \vee \text{Aut}_B(F)\)</li>
					</ol></li><br>
				<li>For a field \(K\) take \(f \in K[x]\) and let \(n = \text{deg}(f)\). Prove that for a splitting field \(F\) of \(f\) over \(K\) that \([F:K] \leq n!\). Furthermore prove that \([F:K]\) divides \(n!\).</li><br>
				<li>Let \(F\) be the splitting field of \(f \in K[x]\) over \(K\). Prove that if \(g \in K[x]\) is irreducible and has a root in \(F\), then \(g\) splits into linear factors over \(F\).</li><br>
				<li>Prove that a finite field cannot be algebraically closed.</li><br>
				<li>For \(u = \sqrt{2 + \sqrt{2}}\), what is the Galois group of \(\mathbb{Q}(u)\) over \(\mathbb{Q}\)? What are the intermediate fields of the extension \(\mathbb{Q}(u)\) over \(\mathbb{Q}\)?</li><br>
				<li>Characterize the splitting field and all intermediate fields of the polynomial \((x^2 - 2)(x^2 - 3)(x^2 - 5)\) over \(\mathbb{Q}\). Using this characterization, find a primitive element of the splitting field.</li><br>
				<li>Characterize the splitting field and all intermediate fields of the polynomial \(x^4 - 3\) over \(\mathbb{Q}\)</li><br>
				<li>Consider the polynomial \(f = x^3 − x + 1\) in \(\mathbb{F}_3[x]\). Prove that \(f\) is irreducible. Calculate the degree of the splitting field of \(f\) over \(\mathbb{F}_3\) and the cardinality of the splitting field of \(f\).</li><br>
				<li>Given an example of a finite extension of fields that has infinitely many intermediate fields.</li><br>
				<li>Let \(u = \sqrt{3 + \sqrt{2}}\). Is \(\mathbb{Q}(u)\) a splitting field of \(u\) over \(\mathbb{Q}\)? (<a href="https://math.stackexchange.com/questions/1817583/is-sqrt7-in-mathbbq-left-sqrt3-sqrt2-right">MathSE</a>)</li><br>
				<li>Prove that the multiplicative group of units of a finite field must be cyclic, and so is generated by a single element.</li><br>
				<li>Prove that \(\mathbb{F}_{p^n}\) is the splitting field of \(x^{p^n} - x\) over \(\mathbb{F}_p\).</li><br>
				<li>Prove that for any positive integer \(n\) there is an irreducible polynomial of degree \(n\) over \(\mathbb{F}_p\).</li><br>
				<li>Recall the definition of a <i>perfect</i> field. Give an example of an imperfect field, and the prove that every finite field is perfect.</li><br>
				<li>For \(n > 2\) let \(\zeta_n\) denote a primitive \(n\)th root of unity over \(\mathbb{Q}\). Prove that \[[\mathbb{Q}(\zeta_n + \zeta_n^{-1} : \mathbb{Q})] = \frac{1}{2}\varphi(n)\] where \(\varphi\) is Euler's totient function.</li><br>
				<li>Suppose that a field \(K\) with characteristic not equal to \(2\) contains an primitive \(n\)th root of unity for some odd integer \(n\). Prove that \(K\) must also contain a primitive \(2n\)th root of unity.</li><br>
				<li>Prove that the Galois group of the polynomial \(x^n - 1\) over \(\mathbb{Q}\) is abelian. (<a href="https://math.stackexchange.com/questions/721864/prove-that-the-galois-group-of-xn-1-is-abelian-over-the-rationals">MathSE</a>)</li><br>
			</ol>
			<br>
			<br>
		</div>
	</div>
	<br>
	<br>
</div>





<div style="border-top: 1px solid #d5d5d5"></div>
<br>
<br>
<div align="center">
	<p>Here is the hierarchy of algebraic objects ranging from semigroups to fields. Each ellipse contains an example of its corresponding object strictly in its respective classification.</p>
	<p>If you know good examples that you think are worthy and would like to see on this picture please let me know and I'd be happy to include it.</p>
</div>
<br>

<div>
	<img src="/pictures/AlgebraicHierarchy.png" align="center" width="50%" height="50%" style="border:3px solid darkblue; margin-left:8px; margin-right:30px;">
	<br>
</div>

<div align="center">
	<br>
	<p>*Unfortunately, this picture can <em>technically</em> be misleading around the "Ring" and "Abelian Group" portion as it turns out every abelian group can have a ring structure attached to it if the law of composition is defined properly, it just might not be unital. For example, you can define multiplication to send everything to the additive identity. There are clearly no units, however, this will still meet all of the requirements to be a ring (depending on your definition of a ring). You can read more about it <a href="https://math.stackexchange.com/questions/93409/does-every-abelian-group-admit-a-ring-structure">here</a> and <a href="https://math.stackexchange.com/questions/432812/when-is-there-a-ring-structure-on-an-abelian-group-a">here</a>. Some people like to use the term <a href="https://en.wikipedia.org/wiki/Rng_(algebra)">rng</a>, pronounced "rung", to distinguish between rings without unit and rings with. Personally, I believe that nonunital rings should be categorized as rings and the almighty Hungerford, scripture for algebraists, doesn't require rings to be unital so therefore it must be true. That being said, I still decided to have separate classifications to distinguish the differences that we typically care about between the two algebraic objects.</p>
</div>
<br clear="all" />