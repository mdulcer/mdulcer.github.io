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
			¡Hola! I am a Ph.D. candidate in <a href="https://www.cmu.edu/dietrich/statistics-datascience/academics/phd/statistics-public-policy/index.html"> Statistics and Public Policy </a> at Carnegie Mellon University, advised by <a href="https://www.ehkennedy.com/"> Edward H. Kennedy</a>. My research develops flexible and robust statistical methods for humanitarian and policy applications, using tools from nonparametric statistics, causal inference, mathematical optimization, and responsible machine learning. 
		</div>
		<div style="height: 1rem"></div>
		<div class="intro-left">
			My work includes creating an AI-informed tool for estimating <a href="https://news.un.org/en/story/2023/04/1135252"> landmine contamination</a> risk, used in Colombia and Afghanistan to identify priority areas for mine clearance in collaboration with the UN Mine Action Service and UNOPS. I also work on developing doubly robust estimators for causal inference and population size estimation under capture heterogeneity and recapture dependence, with applications in conservation, public health, and human rights. Finally, I investigate limitations of current algorithmic decision-making from observational data and devise new methods to address issues like selection biases, missing data, privacy, and algorithmic discrimination.
		</div>
		<div style="height: 1rem"></div>
		<div class="intro-left">	
			I am a <a href="https://www.cmu.edu/fso/prestigious-%20scholarships/kl-gates-presidential-fellowship/index.html"> K&L Gates Presidential Fellow</a> in Ethics and Computational Technologies. I have worked at RAND Corporation and Apple on natural language processing and foundation models. Before that, I co-founded the <a href="https://centroanaliticapp.org/"> Centro de Analítica para Políticas Públicas</a> and worked at <a href="https://quantil.co/en//"> Quantil</a> mostly on crime modeling research in Bogotá. My background is in Mathematics (BSc) and Economics (BSc, MSc <i>cum laude</i>) from Universidad de los Andes in Colombia.
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

<div style="height: 1rem"></div>
<div class="l-middle">	
	<i>* Dulce is my first (paternal) last name and Rubio is my second (maternal) last name.</i> 
</div>
<div style="height: 1rem"></div>
<div class="l-middle">	
	<h3> ★ I am on the academic job market for tenure track postitions and postdocs! </h3>
</div>



<hr class="l-middle home-hr">
<h2 class="feature-title l-middle">
	Recent News
</h2>
<div style="height: 0.5rem"></div>
<div class="l-middle">
	<table style="background-color:white">
	<tr>
		<td style="width:17%" > <b>October 2024</b> </td>
		<td> My co-author <a href="https://secg5.github.io/"> Santiago Cortes-Gómez </a> will be presenting our work <a href="https://proceedings.mlr.press/v235/cortes-gomez24a.html"> "Statistical Inference Under Constrained Selection Bias"</a> at EAAMO'24! </td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>October 2024</b> </td>
		<td> Invited to give a talk at the INFORMS Doing Good with Good OR competition on "Identification of Hazard Clusters for Priority Landmine Clearance as a Quadratic Knapsack Problem".</td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>August 2024</b> </td>
		<td> I'm organizing a topic-contributed session at JSM on "Recent Advances in Capture-Recapture Methods for Population Size Estimation" (8/5, 10:30 am).</td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>July 2024</b> </td>
		<td> New preprint out on <a href="https://arxiv.org/pdf/2407.03539"> "Population Size Estimation with Many Lists and Heterogeneity: A Conditional Log-Linear Model Among the Unobserved"</a>. Feedback is welcome!</td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>June 2024</b> </td>
		<td> I was named a finalist for the INFORMS 2024 <a href="https://msom.informs.org/Recognizing-Excellence/INFORMS-Prizes/Doing-Good-with-Good-OR-Student-Paper-Competition"> Doing Good with Good OR competition </a> for my work on "Identification of Hazard Clusters for Priority Landmine Clearance as a Quadratic Knapsack Problem".</td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>May 2024</b> </td>
		<td> Our work on <a href="https://proceedings.mlr.press/v235/cortes-gomez24a.html"> "Statistical Inference Under Constrained Selection Bias"</a>  was accepted at ICML'24!</td>   
	</tr>
	<tr>
		<td style="width:17%" > <b>April 2024</b> </td>
		<td> I will spend next summer as a machine learning intern at Apple (Seattle), working on evaluation of large language models.</td>  
	</tr>
	<tr>
		<td style="width:17%" > <b>January 2024</b> </td>
		<td> Won the ASA <a href="https://magazine.amstat.org/blog/2024/03/01/sections2024winners/"> Student Paper Competition Award</a> in the Social Statistics Section for my work on nonparametric capture-recapture methods and will be presenting at <a href="https://ww2.amstat.org/meetings/jsm/2024/"> JSM 2024</a> .</td>  
	</tr>
	<tr>
		<td><b>January 2024</b></td>
		<td>Our paper <a href="https://arxiv.org/pdf/2311.03115.pdf"> "RELand: Risk Estimation of Landmines via Interpretable Invariant Risk Minimization"</a>  was accepted for publication at the ACM Journal on Computing and Sustainable Societies and will be presented at <a href="https://compass.acm.org/"> COMPASS</a> in July!</td>  
	</tr>
	<tr>
		<td><b>October 2023</b></td>
		<td> Awarded the <a href="https://www.cmu.edu/ethics-ai/about/fellows/fellows-2425.html"> K&L Gates Presidential Fellowship </a> in Ethics and Computational Technologies.</td>  
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
