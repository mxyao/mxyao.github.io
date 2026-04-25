---
title: "Home"
layout: homelay
sitemap: false
permalink: /
side_content: | 
  <h3>Welcome!</h3>
  Our research is focused on the numerical modelling and simulation of turbulent reacting and nonreacting flows. In addition to studying fundamental physics of turbulence and combustion, we are also interested in developing computationally efficient models which can be used to accelerate the predictive design of net-zero energy systems. Of particular interest is the use of alternative fuels such as carbon-free and sustainable aviation fuels for energy generation and propulsion applications. 

  <div class="jumbotron">
  We are currently looking for highly motivated MScE and PhD students to join our lab! 
  <div style="height: 16px;"></div>
  </div>

---

<div class="jumbotron">
  <h4>News</h4>

  {% for article in site.data.news limit:3 %}
  <strong><span style="color:#0cbdf4;">{{ article.date }}</span></strong>
  <!-- <b>{{ article.date }}</b> -->
    <br>{{ article.headline }}
  {% endfor %}
  
  <h5><a href="{{ site.url }}{{ site.baseurl }}/allnews.html">... see all News</a></h5>

</div>


<!-- <div class="container">
<div class="row">
<center>
<img src="{{ site.url }}{{ site.baseurl }}/images/banner.jpg" width="100%"/><br/>
Examples of Feynman diagrams. <br/>
Feynman R., The theory of positrons. <i>Phys. Rev.</i> (1949)
</center>
</div>
</div>
<br/> -->

<!-- ### About me

I am a Postdoctoral Research Associate at Princeton University where I work with <a href="https://ctrfl.princeton.edu/">Prof. Michael E Mueller</a> developing efficient computational models to predict soot and emissions production. Prior to this, I completed my PhD at Caltech under the supervision of <a href="https://theforce.caltech.edu/">Prof. Guillaume Blanquart</a> where I studied fundamental physics of turbulent combustion and reduced order combustion modelling, and my MASc at uWaterloo under the supervision of <a href="https://www.mpilab.ca/home">Prof. Jean-Pierre Hickey</a> where I studied fundamental combustion dynamics and turbulent wall-bounded flows.  -->
