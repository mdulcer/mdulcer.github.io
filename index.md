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
	<div class="intro-left">
		<div id="intro-title-wrapper" class="intro-left">
			<h1 id="intro-title">Mateo Dulce Rubio</h1>
		</div>	
		<div class="intro-left">
			¡Hola! I am an Assistant Professor & Faculty Fellow at the <a href="https://cds.nyu.edu/">NYU Center for Data Science</a>. I recently completed a PhD in Statistics and Public Policy at Carnegie Mellon University, advised by <a href="https://www.ehkennedy.com/">	Edward H. Kennedy</a>, where I received the William W. Cooper Doctoral Dissertation Award for my thesis “Robust Nonparametric Methods for Peacebuilding.” 
		</div>
		<div style="height: 1rem"></div>
		<div class="intro-left">
			My research develops flexible and robust statistical methods for humanitarian and policy applications, using tools from nonparametric statistics, causal inference, mathematical optimization, and responsible machine learning. My work includes creating an AI-informed tool for estimating <a href="https://news.un.org/en/story/2023/04/1135252"> landmine contamination</a> risk, used in Colombia and Afghanistan to identify priority areas for mine clearance in collaboration with the UN Mine Action Service and UNOPS. I also work on developing doubly robust estimators for causal inference and population size estimation under capture heterogeneity and recapture dependence, with applications in conservation, public health, and human rights. Finally, I investigate limitations of current algorithmic decision-making from observational data and devise new methods to address issues like selection biases, missing data, privacy, and algorithmic discrimination.
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
		<td> Our paper <a href="https://arxiv.org/pdf/2509.03329"> "SESGO: Spanish Evaluation of Stereotypical Generative Outputs"</a> was accepted at AIES 2025, for an oral discussion panel. </td>
	</tr>
	<tr>
		<td style="width:17%" > <b>September 2025</b> </td>
		<td> <b>Joined New York University as an Assistant Professor & Faculty Fellow at the Center for Data Science! </b> </td>
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
