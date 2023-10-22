---
layout: home
title: Home
---

<div id ="intro-wrapper" class="l-middle">
	<div class="intro-left">
	<div id="intro-title-wrapper" class="intro-left">
		<h1 id="intro-title">Mateo Dulce Rubio</h1>
	</div>
		<div class="intro-left">
			Hola! I am a Ph.D. candidate in the <a href="https://www.cmu.edu/dietrich/statistics-datascience/academics/phd/statistics-public-policy/index.html"> Statistics and Public Policy </a> joint program at Carnegie Mellon University, advised by <a href="https://www.ehkennedy.com/"> Edward 
			H. Kennedy </a>. My research focuses on non-parametric statistics, causal inference, and responsible machine learning, with a strong emphasis on their applications for good. My dissertation encompasses the development of flexible and robust methods inspired by challenges arising in post-conflict scenarios and peacebuilding efforts.
	
		</div>
		<div style="height: 1rem"></div>
		<div class="intro-left">	
			Before starting my PhD I worked at Quantil. 
		</div>
	</div>
	<div class="intro-right">
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

<hr class="l-middle home-hr">

<h2 class="feature-title l-middle">
	Selected Research Projects
</h2>
<div class="cover-wrapper l-screen">
	{% assign sortedPublications = site.data.pubs | sort: 'feature-order' %}
	{% for feature in sortedPublications %}
		{% if feature.featured%}
			{% include feature.html feature=feature %}
		{% endif %}
	{% endfor %}
</div>
