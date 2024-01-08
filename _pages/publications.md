---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

Conferences
==============
- **To Err is Human: A Field Experiment in Nudging Doctors to Safety** <br/>
  Xiaodan Shao, Vivek Choudhary
  - 13th POMS-HK International Conference, Hong Kong Polytechnic University, Hong Kong, Jan 2023 
  - Singapore Rising Scholars Conference, Singapore Management University, Singapore, May 2023
  - INFORMS Manufacturing and Service Operations Management Conference, McGill University, Canada, Jun 2023

- **Why Do We Need More Female Doctors? Patient-Doctor Gender Concordance During Lockdown** <br/>
  Xiaodan Shao, Vivek Choudhary, Anandasivam Gopal
  - 13th POMS-HK International Conference, Hong Kong Polytechnic University, Hong Kong, Jan 2023
  - 14th POMS-HK International Conference, Hong Kong University of Science and Technology, Hong Kong, Jan 2024 
<br/>
<br/>

Grant
==============
Ministry of Education Academic Research Funding (MOE-AcRF) Tier 1 Grant, student PI

{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
