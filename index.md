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
		<p>¡Hola! I am an Assistant Professor &amp; Faculty Fellow at the <a href="https://cds.nyu.edu/">NYU Center for Data Science</a>. My research develops flexible and robust statistical tools that turn machine learning predictions of unknown quality into decisions with provable guarantees, together with the conditions a predictive model must satisfy for these guarantees to hold. This agenda combines methods from nonparametric statistics, causal inference, optimization, and machine learning, and is developed for humanitarian and policy applications in close partnership with organizations such as UNOPS and The HALO Trust. I'm broadly interested in:</p>
		<ul style="padding-left: 19px">
			<li style="margin-bottom: 10px;"><strong>Algorithmic decision-support systems for landmine clearance</strong>, motivated by operational and data challenges in <a href="https://dl.acm.org/doi/10.1145/3648437">humanitarian mine action</a>. These systems have been used in real-world operations in Colombia and Afghanistan, and have been recognized by INFORMS, GICHD, ITU, and Kluz PeaceTech.</li>
			<li style="margin-bottom: 10px;"><strong>Doubly robust estimators from ML predictors</strong> for causal inference and population size estimation with heterogeneous capture probabilities and recapture dependencies, with applications in conservation, public health, and human rights.</li>
			<li>Design and deployment of AI systems (e.g., tabular or language foundation models) for <strong>resource allocation under uncertainty</strong>, how to incorporate them into broader decision-making workflows with honest guarantees, and how to audit their behavior once deployed.</li>
		</ul>
		<p>I hold a PhD in Statistics and Public Policy from Carnegie Mellon University, where I Was advised by <a href="https://www.ehkennedy.com/">Edward H. Kennedy</a> and received the William W. Cooper Doctoral Dissertation Award for my thesis “Robust Nonparametric Methods for Peacebuilding.”</p>
		<p><strong><i>I am on the 2026–2027 academic job market.</i></strong></p>
		<p><i>* Dulce is my first (paternal) last name and Rubio is my second (maternal) last name.</i></p>
	</div>
	</div>
	<div class="intro-right">
		<div style="height: 1rem"></div>
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
</div>



<hr class="l-middle home-hr">
<h2 class="feature-title l-middle">
	Recent News
</h2>
<div style="height: 0.5rem"></div>
<div class="l-middle">
	<table style="background-color:white">
	<tr>
		<td style="width:17%" > <b>October 2026</b> </td>
		<td> Our paper <a href="https://arxiv.org/pdf/2605.22612"> "Healthcare LLM Benchmarks Are Only as Good as Their Explicit Assumptions" </a> was acepted at the NeruIPS 2026 Workshop on GenAI for Health. </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2026</b> </td>
		<td> Accepted paper at NeurIPS on <a href="https://arxiv.org/pdf/2605.07979"> The Limits of AI-Driven Allocation: Optimal Screening under Aleatoric Uncertainty! </a> </td> 
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2026</b> </td>
		<td> Received funding from Minesight as PI for the project <i>"Statistical Foundations of Residual Risk and All Reasonable Effort in AI-Assisted Mine Action,"</i> in partnership with The HALO Trust. </td> 
	</tr>
	<tr>
		<td style="width:17%" > <b>March 2026</b> </td>
		<td> I'll be attending the AAAI Symposium on <a href="https://www.hadr.ai/home"> Artificial Intelligence for Humanitarian Assistance and Disaster Relief </a> to present our work on "Continuous Learning for AI-Informed Landmine Risk Assessment" and "Deploying AI-powered Landmine Risk Assessment in Afghanistan and Colombia." </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>February 2026</b> </td>
		<td> New preprint: <a href="https://arxiv.org/pdf/2602.09911"> "Doubly Robust Machine Learning for Population Size Estimation with Missing Covariates: Application to Gaza Conflict Mortality."</a> </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Awarded a Minesight Seedling Program grant to lead research on dynamic AI risk assessment of EO contamination. </td> 
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Two papers accepted at NeurIPS 2025! <a href="https://arxiv.org/pdf/2506.03531"> "Conformal Mixed-Integer Constraint Learning with Feasibility Guarantees"</a> (<b>spotlight!</b>) and <a href  = "https://arxiv.org/pdf/2509.07055"> "Sequentially Auditing Differential Privacy."</a> </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Our paper <a href="https://arxiv.org/pdf/2509.03329"> "SESGO: Spanish Evaluation of Stereotypical Generative Outputs"</a> was accepted at AIES 2025 for an oral discussion panel. See you in Madrid! </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> Joined New York University as an Assistant Professor / Faculty Fellow at the Center for Data Science! </td>
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
