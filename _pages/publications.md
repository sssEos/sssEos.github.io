---
layout: archive
title: ""
permalink: /publications/
author_profile: true
---

<h1 style="margin-bottom: 28px;">Working Papers</h1>

<div style="border: 1px solid #ddd; border-radius: 16px; padding: 32px; margin-top: 20px; margin-bottom: 32px; background-color: #fff;">

  <h2 style="margin-top: 0; margin-bottom: 8px; font-size: 22px;">
    Reducing Prescription Errors Through Information Intervention: A Field Experiment in Healthcare Operations
  </h2>

  <p style="margin-bottom: 6px;">
    Xiaodan Shao, Vivek Choudhary, Arnab Majumdar
  </p>

  <p style="margin-bottom: 18px; color: #555;">
    <i>Major Revision at M&amp;SOM (2nd Round)</i>
  </p>

  <ul style="margin-top: 12px; margin-bottom: 0;">
    <li>Best Student Paper, Operational Research Society of Singapore (ORSS), Analytics for X 2025</li>
    <li>Finalist, Junior Scholar Paper Competition at College of Behavior in Operations Management (CBOM), POMS 2024</li>
    <li>Best Poster Presentation, CBS-NBS Research Day on Emerging Technology, Risks, and Markets 2024</li>
  </ul>

</div>

<div style="border: 1px solid #ddd; border-radius: 16px; padding: 32px; margin-top: 20px; margin-bottom: 32px; background-color: #fff;">

  <h2 style="margin-top: 0; margin-bottom: 8px; font-size: 22px;">
    Interrupted Continuity: An Empirical Analysis of Interruptions in Continuous Pharma Manufacturing
  </h2>

  <p style="margin-bottom: 6px;">
    Xiaodan Shao, Vivek Choudhary, Jiatao Ding
  </p>

  <p style="margin-bottom: 18px; color: #555;">
    <i>Major Revision at M&amp;SOM</i>
  </p>

  <ul style="margin-top: 12px; margin-bottom: 0;">
    <li>Winner (First Prize), 2025 The M&amp;SOM Data-Driven Research Challenge</li>
  </ul>

</div>

<div style="border: 1px solid #ddd; border-radius: 16px; padding: 32px; margin-top: 20px; margin-bottom: 32px; background-color: #fff;">

  <h2 style="margin-top: 0; margin-bottom: 8px; font-size: 22px;">
    Last-Mile Healthcare as an Access-Production Problem: A CARE Agenda for SDG 3
  </h2>

  <p style="margin-bottom: 6px;">
    Vivek Choudhary, Jiatao Ding, Anandasivam Gopal, Xiaodan Shao<sup>*</sup>
  </p>
  
  <p style="margin-top: 0; margin-bottom: 12px; font-size: 13px; color: #666;">
  <sup>*</sup> Authors listed alphabetically.

  <p style="margin-bottom: 0; color: #555;">
    <i>Proposal accepted for M&SOM Special Issue</i>
  </p>

</div>

<div style="border: 1px solid #ddd; border-radius: 16px; padding: 32px; margin-top: 20px; margin-bottom: 32px; background-color: #fff;">

  <h2 style="margin-top: 0; margin-bottom: 8px; font-size: 22px;">
    Should I Change My Physician’s Gender? On the Role of Ambiguity in Patient-Physician Gender Concordance
  </h2>

  <p style="margin-bottom: 6px;">
    Xiaodan Shao, Vivek Choudhary, Anandasivam Gopal
  </p>

  <p style="margin-bottom: 0; color: #555;">
    <i>Finalizing for Submission</i>
  </p>

</div>


{% comment %}
{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
{% endcomment %}
