---
title: "Publications"
layout: gridlay
sitemap: false
permalink: /publications/
years: [2016, 2017, 2018, 2019, 2020, 2021]
---

<style>
.jumbotron{
    padding:3%;
    padding-bottom:10px;
    padding-top:10px;
    margin-top:10px;
    margin-bottom:30px;
}
</style>

<!-- <div class="jumbotron">
### Preprints
{% bibliography --query @unpublished %}
</div> -->

### Journal Publications
<div class="jumbotron">
#### 2025
{% bibliography --query @article[year = 2025] %}
</div>

<div class="jumbotron">
#### 2024
{% bibliography --query @article[year = 2024] %}
</div>

<div class="jumbotron">
#### 2023
{% bibliography --query @article[year = 2023] %}
</div>

<div class="jumbotron">
#### 2020
{% bibliography --query @article[year = 2020] %}
</div>

<div class="jumbotron">
#### 2019
{% bibliography --query @article[year = 2019] %}
</div>

<div class="jumbotron">
#### 2018
{% bibliography --query @article[year = 2018] %}
</div>

<div class="jumbotron">
#### 2017
{% bibliography --query @article[year = 2017] %}
</div>

### Refereed Conference Proceedings
<div class="jumbotron">
{% bibliography --query @inproceedings %}
</div>

### Theses
<div class="jumbotron">
{% bibliography --query @phdthesis %}
{% bibliography --query @mastersthesis %}
</div>