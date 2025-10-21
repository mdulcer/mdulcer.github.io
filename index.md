---
layout: home
title: Home
---

<style>
table, th, td {
  border-style: none;
  vertical-align: top;
}
</style>

<div id ="intro-wrapper" class="l-middle">
	<div id="intro-title-wrapper" class="intro-left">
			<h1 id="intro-title">Mateo Dulce Rubio</h1>
	</div>	
	<div class="intro-left">
		<div class="intro-left">
			¡Hola! I am an Assistant Professor & Faculty Fellow at the <a href="https://cds.nyu.edu/">NYU Center for Data Science</a>. I recently completed a PhD in Statistics and Public Policy at Carnegie Mellon University, advised by <a href="https://www.ehkennedy.com/">	Edward H. Kennedy</a>, where I received the William W. Cooper Doctoral Dissertation Award for my thesis “Robust Nonparametric Methods for Peacebuilding.” 
		</div>
		<div style="height: 1rem"></div>
		<div class="intro-left">
			My research develops flexible and robust statistical tools for humanitarian and policy applications, advancing methods from nonparametric statistics, causal inference, mathematical optimization, and responsible machine learning. Specifically, I focus on:
			<ul style="padding-left: 19px">
  				<li style="margin-bottom: 10px;">Localized decision-making and <strong>geographic resource allocation</strong> under low-quality data. I actively work on ML/OR-powered tools to support planning and prioritization in <a href="https://dl.acm.org/doi/10.1145/3648437">humanitarian mine action</a>, in partnership with <a href="https://www.unops.org/news-and-stories/news/ai-innovation-transforms-mine-action">UNOPS</a> and local demining organizations. My work has been deployed in real-world operations in Colombia and Afghanistan and recognized by INFORMS, GICHD, ITU, and Kluz PeaceTech.</li>
  				<li style="margin-bottom: 10px;"><strong>Doubly-robust ML estimators</strong> for <a href="https://projecteuclid.org/journals/annals-of-applied-statistics/volume-19/issue-2/Effects-of-adolescent-victimization-on-offending--Flexible-methods-for/10.1214/24-AOAS2005.short">causal inference</a> under missing data, and for <a href="https://arxiv.org/abs/2407.03539">population size estimation</a> with heterogeneous capture probabilities and recapture dependencies, with applications in conservation, public health, and human rights.</li>
  				<li><strong>Principled statistical methods for responsible AI systems</strong>. I develop general frameworks to address key challenges in algorithmic decision-support systems with theoretical guarantees, including <a href="https://dl.acm.org/doi/abs/10.5555/3692070.3692442">selection bias</a>, <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0294020">counterfactual allocation</a>, <a href="https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0287776">underreported events</a>, <a href="https://arxiv.org/abs/2509.07055">anytime-valid differential privacy auditing</a>, <a href="https://ojs.aaai.org/index.php/AIES/article/view/36707">culturally-aware bias assessment in LLMs</a>, and <a href="https://arxiv.org/abs/2506.03531">conformalized optimization with feasibility guarantees</a>.</li>
			</ul>
			Feel free to reach out if you want to discuss research or applications in these areas!
		</div>
	</div>
	<div class="intro-right">
		<div style="height: 2rem"></div>
		<img id="intro-image" class="intro-right" src="/images/MDR.jpg">
		<div style="height: 0.5rem"></div>
		<div id="intro-image-links" class="intro-right">
			{% for link in site.data.social-links %}
				{% if link.on-homepage == true %}
					{% include social-link.html link=link %}
				{% endif %}
			{% endfor %}
		</div>
	</div>
</div>
<div class="l-middle">	
	<i>* Dulce is my first (paternal) last name and Rubio is my second (maternal) last name.</i> 
</div>



<hr class="l-middle home-hr">
<h2 class="feature-title l-middle">
	Recent News
</h2>
<div style="height: 0.5rem"></div>
<div class="l-middle">
	<table style="background-color:white">
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Two papers accepted at NeurIPS 2025! <a href="https://arxiv.org/pdf/2506.03531"> "Conformal Mixed-Integer Constraint Learning with Feasibility Guarantees"</a> (<b>spotlight!</b>) and <a href  = "https://arxiv.org/pdf/2509.07055"> "Sequentially Auditing Differential Privacy"</a>. </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Our paper <a href="https://arxiv.org/pdf/2509.03329"> "SESGO: Spanish Evaluation of Stereotypical Generative Outputs"</a> was accepted at AIES 2025 for an oral discussion panel. See you in Madrid! </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> <b>Joined New York University as an Assistant Professor / Faculty Fellow at the Center for Data Science! </b> </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>May 2025</b> </td>
		<td> Honored to receive the  <b>William W. Cooper Doctoral Dissertation Award</b> for my thesis "Robust Statistical Methods for Peacebuilding". </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>April 2025</b> </td>
		<td> I was selected as <b>Student of the Year</b> by the American Statistical Association, Pittsburgh chapter. </td>
	</tr>
	</table>
</div>


<hr class="l-middle home-hr">
<h2 class="feature-title l-middle">
	Selected Research Projects
</h2>
<div style="height: 0.5rem"></div>
<div class="cover-wrapper l-screen">
	{% assign sortedPublications = site.data.pubs | sort: 'feature-order' %}
	{% for feature in sortedPublications %}
		{% if feature.featured%}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
</div>


<hr class="l-middle home-hr">
<h4 class="feature-title l-middle">
	Miscellaneous
</h4>
<div class="l-middle">
	During my PhD, I was a <a href="https://www.cmu.edu/fso/prestigious-%20scholarships/kl-gates-presidential-fellowship/index.html"> K&L Gates Presidential Fellow</a> in Ethics and Computational Technologies, and worked at RAND Corporation and Apple on natural language processing and foundation models. Before that, I co-founded the <a href="https://centroanaliticapp.org/"> Centro de Analítica para Políticas Públicas</a> and worked at <a href="https://quantil.co/en//"> Quantil</a> mostly on crime modeling research in Bogotá. My background is in Mathematics (BSc) and Economics (BSc, MSc <i>cum laude</i>) from Universidad de los Andes in Colombia.
</div>
