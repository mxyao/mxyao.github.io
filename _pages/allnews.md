---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% assign grouped_news = site.data.news | group_by: "year" | sort: "name" | reverse %}
{% for year in grouped_news %}
  <h4 style="color:#0cbdf4;">{{ year.name }}</h4>
  {% for article in year.items %}
  <p>
    <!-- <strong>{{ article.date }}</strong><br> -->
    <!-- <strong><span style="color:#87aac5;">{{ article.date }}</span></strong><br> -->
    <strong><span style="color:#0cbdf4;">{{ article.date }}</span></strong><br>
    {{ article.headline }}
    <!-- <span style="color:#888;">{{ article.headline }}</span><br> -->
  </p>
  <hr style="border-top: 1px solid #3283c2;">
  {% endfor %}
{% endfor %}
</div>

<!-- <div class="jumbotron">
{% for article in site.data.news %}
  <p>
    <strong>{{ article.date }}</strong><br>
    {{ article.headline }}
  </p>
  <hr style="border-top: 1px solid #ccc;">
{% endfor %}
</div> -->

<!-- ---
title: "News"
layout: textlay
sitemap: false
permalink: /allnews.html
---

## News

<div class="jumbotron">
{% for article in site.data.news %}
<b>{{ article.date }}</b>

{{ article.headline }}
{% endfor %}

</div> -->
