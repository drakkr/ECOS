---
layout: page
title: Evaluating Cost of Open Source
tagline: Collaborative costs & benefits assesment
---
{% include JB/setup %}

### Recent news

<ul class="posts">
  {% for post in site.posts limit: 5 %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

<a href="https://github.com/drakkr/ECOS/"><img style="position: absolute; top: 0; right: 0; border: 0;" src="https://s3.amazonaws.com/github/ribbons/forkme_right_gray_6d6d6d.png" alt="Fork me on GitHub"></a>

### Introducing ECOS

ECOS is a free project aiming to provide a formal and collaborative approach for evaluating the costs and benefits of open source migration and adoption.

It is part of the [drakkr](http://www.drakkr.org) framework for open source governance.

The ECOS approach, composed of four interdependent steps, start at the first stage before making a decision, goes on during the installation or migration of a part of the information system and keeps going after the change-over, in operational conditions.

![General approach of ECOS](https://raw.github.com/drakkr/ECOS/master/Method/en/Images/processus_en.png)

The general approach of ECOS is composed of several interdependent steps that may be followed with different granularities in order to be more or less detailed:

* Define: Definition with the IT teams of the domains and sectors that will be studied and the time frame of the study. 

* Collect: Collection of the data regarding the information system, the governance, its use and its costs. IT teams involvement is required through interviews and access to financial figures.                                                              

* Evaluate: Evaluation of the opportunity of migration and relevant free and open sourc alternatives.

* Compare: Qualitative and quantitative comparison of relevant scenarios with advantages, disadvantages, costs, benefits and return on investments.

The ECOS method can be used before, during and after the installation of a free and open source solution.

![Continuous application of ECOS](https://raw.github.com/drakkr/ECOS/master/Method/en/Images/timeline_en.png)