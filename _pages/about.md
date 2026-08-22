---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>

/* =========================================================
   HOME DESIGN SYSTEM
========================================================= */

:root {
  --accent: #52789d;
  --accent-dark: #456987;
  --accent-soft: #f6f9fc;

  --text-main: #4f555a;
  --text-secondary: #6f767c;
  --text-muted: #969da3;

  --border: #e2e7eb;
  --border-soft: #edf0f2;
}


/* =========================================================
   GENERAL
========================================================= */

.home-section {
  margin: 38px 0;
}

.home-section-heading {
  display: flex;
  align-items: center;
  gap: 12px;

  margin-bottom: 13px;
}

.home-section-label {
  flex-shrink: 0;

  font-size: 0.73em;
  font-weight: 650;
  letter-spacing: 0.09em;
  text-transform: uppercase;

  color: #7f878d;
}

.home-section-line {
  width: 100%;
  height: 1px;

  background: linear-gradient(
    90deg,
    #dfe5ea,
    transparent
  );
}


/* =========================================================
   INTRODUCTION
========================================================= */

.home-intro {
  color: var(--text-main);
}

.home-intro p {
  margin: 0 0 18px;

  line-height: 1.62;
}


/* =========================================================
   JOB MARKET
   TEXT EMPHASIS ONLY
========================================================= */

.job-market {
  margin: 25px 0 22px;
}

.job-market-label {
  margin-bottom: 4px;

  font-size: 0.66em;
  font-weight: 650;
  letter-spacing: 0.09em;
  text-transform: uppercase;

  color: #9aa0a5;
}

.job-market-text {
  font-size: 1.08em;
  font-weight: 600;
  line-height: 1.4;

  color: var(--accent-dark);
}


/* =========================================================
   COLLABORATION + CONTACT
========================================================= */

.home-collab {
  margin-top: 2px;

  line-height: 1.58;

  color: var(--text-main);
}

.home-contact {
  margin-top: 15px;

  font-size: 0.94em;

  color: var(--text-secondary);
}

.home-contact a {
  color: var(--text-secondary);
  text-decoration: none;
}

.home-contact a:hover {
  color: var(--accent);
}


/* =========================================================
   RESEARCH
   OPEN / NO OUTER BOX
========================================================= */

.research-layout {
  display: grid;
  grid-template-columns: 1fr 1fr;

  gap: 46px;

  padding: 4px 0 2px;
}


/* Research column */

.research-group {
  min-width: 0;
}

.research-group-heading {
  margin-bottom: 6px;

  font-size: 0.68em;
  font-weight: 650;
  letter-spacing: 0.08em;
  text-transform: uppercase;

  color: #8a9196;
}


/* Research items */

.research-list {
  margin: 0;
  padding: 0;

  list-style: none;
}

.research-item {
  position: relative;

  padding: 8px 0 8px 15px;

  font-size: 0.85em;
  font-weight: 400;
  line-height: 1.35;

  color: #60676d;
}

.research-item + .research-item {
  border-top: 1px solid #eef0f2;
}


/* Small accent mark */

.research-item::before {
  content: "";

  position: absolute;

  left: 0;
  top: 50%;

  width: 5px;
  height: 5px;

  border-radius: 50%;

  background: #8ca9c1;

  transform: translateY(-50%);
}


/* =========================================================
   UPCOMING TALKS
========================================================= */

.upcoming-list {
  display: flex;
  flex-direction: column;

  gap: 11px;
}


/* Talk card */

.upcoming-card {
  display: grid;
  grid-template-columns: 68px minmax(0, 1fr);

  gap: 17px;

  padding: 17px 19px;

  background: linear-gradient(
    115deg,
    #f6f9fc 0%,
    #fbfcfd 100%
  );

  border: 1px solid #e1e9ef;
  border-radius: 10px;

  box-shadow:
    0 4px 14px rgba(55, 75, 95, 0.025);

  transition:
    transform 0.17s ease,
    border-color 0.17s ease,
    box-shadow 0.17s ease;
}

.upcoming-card:hover {
  transform: translateY(-1px);

  border-color: #d3e0ea;

  box-shadow:
    0 6px 18px rgba(55, 75, 95, 0.045);
}


/* Date */

.upcoming-date {
  padding-top: 2px;

  text-align: center;
}

.upcoming-date-month {
  font-size: 0.63em;
  font-weight: 650;
  letter-spacing: 0.09em;
  text-transform: uppercase;

  color: var(--accent);
}

.upcoming-date-day {
  margin-top: 1px;

  font-size: 1.42em;
  font-weight: 600;
  line-height: 1.05;

  color: #5d6973;
}


/* Talk content */

.upcoming-content {
  min-width: 0;
}

.upcoming-title {
  margin-bottom: 5px;

  font-size: 1em;
  font-weight: 600;
  line-height: 1.38;

  color: var(--text-main);
}

.upcoming-eventline {
  display: flex;
  justify-content: space-between;
  align-items: baseline;

  gap: 14px;

  font-size: 0.80em;
  line-height: 1.4;
}

.upcoming-conference {
  font-weight: 500;

  color: var(--text-secondary);
}

.upcoming-details {
  flex-shrink: 0;

  color: var(--text-muted);

  white-space: nowrap;
}


/* Session information */

.upcoming-sessions {
  margin-top: 9px;
  padding-top: 7px;

  border-top: 1px solid rgba(82, 120, 157, 0.12);
}

.upcoming-session-row {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;

  gap: 14px;

  padding: 2px 0;

  font-size: 0.74em;
  line-height: 1.4;
}

.upcoming-session {
  color: #777e84;
}

.upcoming-session-meta {
  color: #969da2;

  white-space: nowrap;
}


/* =========================================================
   PAST TALKS
========================================================= */

.past-talks-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;

  margin: 27px 0 7px;
}

.past-talks-title {
  font-size: 0.86em;
  font-weight: 500;

  color: #696f74;
}

.scroll-note {
  font-size: 0.68em;
  font-weight: 400;

  color: #a1a6aa;
}


/* Scroll container */

.past-talks-list {
  max-height: 205px;
  overflow-y: auto;

  padding-right: 7px;

  border-top: 1px solid #eceeef;
  border-bottom: 1px solid #eceeef;

  scrollbar-width: thin;
  scrollbar-color: #c4c9cd transparent;
}


/* Each past talk */

.past-talk-row {
  display: grid;
  grid-template-columns: 76px minmax(0, 1fr);

  gap: 16px;

  padding: 10px 3px;

  border-bottom: 1px solid #f0f1f2;
}

.past-talk-row:last-child {
  border-bottom: none;
}

.past-talk-date {
  padding-top: 1px;

  font-size: 0.77em;

  color: #999ea2;

  white-space: nowrap;
}

.past-talk-info {
  min-width: 0;

  font-size: 0.81em;
  line-height: 1.4;

  color: #656b70;
}

.past-talk-name {
  color: #5c6267;
}

.past-talk-location {
  margin-top: 1px;

  font-size: 0.91em;

  color: #a0a4a8;
}


/* Scrollbar */

.past-talks-list::-webkit-scrollbar {
  width: 5px;
}

.past-talks-list::-webkit-scrollbar-track {
  background: transparent;
}

.past-talks-list::-webkit-scrollbar-thumb {
  background: #c4c9cd;
  border-radius: 10px;
}


/* =========================================================
   LAST UPDATED
========================================================= */

.home-updated {
  margin-top: 30px;

  font-size: 0.70em;

  color: #a6aaae;
}


/* =========================================================
   MOBILE
========================================================= */

@media (max-width: 700px) {

  /* General */

  .home-section {
    margin: 31px 0;
  }


  /* Introduction */

  .home-intro {
    font-size: 0.94em;
  }

  .home-intro p {
    line-height: 1.56;
  }


  /* Job market */

  .job-market {
    margin: 21px 0 19px;
  }

  .job-market-label {
    font-size: 0.60em;
  }

  .job-market-text {
    font-size: 0.96em;
  }


  /* Research */

  .research-layout {
    grid-template-columns:
      minmax(0, 1fr)
      minmax(0, 1fr);

    gap: 18px;
  }

  .research-group-heading {
    font-size: 0.61em;
  }

  .research-item {
    padding: 7px 0 7px 11px;

    font-size: 0.72em;
    line-height: 1.3;
  }

  .research-item::before {
    width: 4px;
    height: 4px;
  }


  /* Upcoming talks */

  .upcoming-card {
    grid-template-columns: 50px minmax(0, 1fr);

    gap: 11px;

    padding: 14px 12px;

    border-radius: 9px;
  }

  .upcoming-date-month {
    font-size: 0.58em;
  }

  .upcoming-date-day {
    font-size: 1.20em;
  }

  .upcoming-title {
    font-size: 0.90em;
  }


  /* Conference */

  .upcoming-eventline {
    display: block;

    font-size: 0.73em;
  }

  .upcoming-details {
    display: block;

    margin-top: 2px;

    white-space: nowrap;
  }


  /* Sessions */

  .upcoming-session-row {
    display: block;

    padding: 3px 0;

    font-size: 0.68em;
  }

  .upcoming-session {
    display: block;
  }

  /* Keep time + full location together */
  .upcoming-session-meta {
    display: block;

    margin-top: 1px;

    white-space: nowrap;
  }


  /* Past talks */

  .past-talk-row {
    grid-template-columns: 64px minmax(0, 1fr);

    gap: 9px;
  }

  .past-talks-list {
    overflow-y: scroll;

    padding-right: 6px;

    scrollbar-width: auto;
    scrollbar-color: #aeb4b9 #f1f3f4;
  }

  .past-talks-list::-webkit-scrollbar {
    width: 7px;
  }

  .past-talks-list::-webkit-scrollbar-track {
    background: #f1f3f4;
    border-radius: 10px;
  }

  .past-talks-list::-webkit-scrollbar-thumb {
    background: #aeb4b9;
    border-radius: 10px;
  }


  /* Mobile scroll cue */

  .scroll-note {
    display: none;
  }

  .past-talks-heading::after {
    content: "↓";

    margin-left: auto;

    font-size: 0.85em;

    color: #9ba0a4;
  }

}

</style>


<!-- =========================================================
     INTRODUCTION
========================================================= -->

<div class="home-intro">

  <p>
    I am Xiaodan Shao, a Ph.D. candidate in Operations Management at
    Nanyang Business School, Nanyang Technological University, where I am
    fortunate to be advised by Prof.
    <a href="https://sites.google.com/view/vkchoudhary">
      Vivek Choudhary
    </a>
    and Prof.
    <a href="https://dr.ntu.edu.sg/cris/rp/rp01345">
      Anandasivam Gopal
    </a>.
  </p>

  <p>
    My empirical research is driven by a desire to improve how healthcare
    is delivered and operated. I study how people and organizations across
    the healthcare system respond to information and technology, and how
    data-driven interventions can make care safer, more accessible, and
    more effective.
  </p>

</div>


<!-- =========================================================
     JOB MARKET
========================================================= -->

<div class="job-market">

  <div class="job-market-label">
    Job Market
  </div>

  <div class="job-market-text">
    I am on the 2026–2027 academic job market.
  </div>

</div>


<!-- =========================================================
     COLLABORATION
========================================================= -->

<div class="home-collab">

  Some of the most rewarding research comes from working with practitioners
  and policymakers to turn real-world challenges into useful insights.
  If you’re facing a hard problem or exploring a new idea, feel free to
  reach out.

</div>

<div class="home-contact">
  📧 Email:
  <a href="mailto:xiaodan001@e.ntu.edu.sg">
    xiaodan001@e.ntu.edu.sg
  </a>
</div>


<!-- =========================================================
     RESEARCH
========================================================= -->

<div class="home-section">

  <div class="home-section-heading">

    <div class="home-section-label">
      Research
    </div>

    <div class="home-section-line"></div>

  </div>


  <div class="research-layout">


    <!-- Topics -->

    <div class="research-group">

      <div class="research-group-heading">
        Topics
      </div>

      <ul class="research-list">

        <li class="research-item">
          Healthcare Operations
        </li>

        <li class="research-item">
          Behavioral Operations
        </li>

        <li class="research-item">
          AI &amp; Digital Health
        </li>

      </ul>

    </div>


    <!-- Methodologies -->

    <div class="research-group">

      <div class="research-group-heading">
        Methodologies
      </div>

      <ul class="research-list">

        <li class="research-item">
          Econometrics
        </li>

        <li class="research-item">
          Field Experiments
        </li>

        <li class="research-item">
          Data Analytics
        </li>

      </ul>

    </div>

  </div>

</div>


<!-- =========================================================
     UPCOMING TALKS
========================================================= -->

<div class="home-section">

  <div class="home-section-heading">

    <div class="home-section-label">
      Upcoming Talks
    </div>

    <div class="home-section-line"></div>

  </div>


  <div class="upcoming-list">


    <!-- OCTOBER 31 -->

    <div class="upcoming-card">

      <div class="upcoming-date">

        <div class="upcoming-date-month">
          Oct
        </div>

        <div class="upcoming-date-day">
          31
        </div>

      </div>


      <div class="upcoming-content">

        <div class="upcoming-title">
          Last-Mile Healthcare: A CARE Agenda for SDG 3
        </div>


        <div class="upcoming-eventline">

          <span class="upcoming-conference">
            5th Symposium on Environmental and Social Sustainability in Supply Chains
          </span>

          <span class="upcoming-details">
            UC Berkeley Campus · Time &amp; Room TBA
          </span>

        </div>

      </div>

    </div>


    <!-- NOVEMBER 2 -->

    <div class="upcoming-card">

      <div class="upcoming-date">

        <div class="upcoming-date-month">
          Nov
        </div>

        <div class="upcoming-date-day">
          2
        </div>

      </div>


      <div class="upcoming-content">

        <div class="upcoming-title">
          Reducing Prescription Errors Through Information Intervention:
          A Field Experiment in Healthcare Operations
        </div>


        <div class="upcoming-eventline">

          <span class="upcoming-conference">
            INFORMS Annual Meeting 2026
          </span>

          <span class="upcoming-details">
            San Francisco
          </span>

        </div>


        <div class="upcoming-sessions">


          <div class="upcoming-session-row">

            <span class="upcoming-session">
              Service Science Best Student Paper Award II
            </span>

            <span class="upcoming-session-meta">
              2:45–4:00 PM · Moscone South-20 (Hall E/Exhibit Level)
            </span>

          </div>


          <div class="upcoming-session-row">

            <span class="upcoming-session">
              Causal Evidence and Precision Healthcare
            </span>

            <span class="upcoming-session-meta">
              4:15–5:30 PM · Moscone South-204 (Level 2)
            </span>

          </div>


        </div>

      </div>

    </div>

  </div>


  <!-- =======================================================
       PAST TALKS
  ======================================================== -->

  <div class="past-talks-heading">

    <span class="past-talks-title">
      Past Talks
    </span>

    <span class="scroll-note">
      Scroll for more ↓
    </span>

  </div>


  <div class="past-talks-list">


    <div class="past-talk-row">

      <div class="past-talk-date">
        Jan 2026
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          3rd Workshop on Empirical Operations Management (WEOM)
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Oct 2025
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          INFORMS Annual Meeting
        </div>

        <div class="past-talk-location">
          Atlanta, USA
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Sep 2025
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Analytics for X Conference
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Jul 2025
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          INFORMS International Meeting
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Oct 2024
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          CBS-NBS Research Day on Emerging Technology, Risks, and Markets
        </div>

        <div class="past-talk-location">
          Bangkok, Thailand
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        May 2024
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Singapore Rising Scholars Conference
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        May 2024
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Conference on Health IT and Analytics (CHITA)
        </div>

        <div class="past-talk-location">
          Washington, D.C., USA
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Apr 2024
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Production and Operations Management Society (POMS) Annual Conference
        </div>

        <div class="past-talk-location">
          Minneapolis, USA
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Apr 2024
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Asian Management Research Consortium
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        May 2023
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          Singapore Rising Scholars Conference
        </div>

        <div class="past-talk-location">
          Singapore
        </div>

      </div>

    </div>


    <div class="past-talk-row">

      <div class="past-talk-date">
        Jan 2023
      </div>

      <div class="past-talk-info">

        <div class="past-talk-name">
          POMS-HK International Conference
        </div>

        <div class="past-talk-location">
          Hong Kong, China
        </div>

      </div>

    </div>


  </div>

</div>


<!-- =========================================================
     LAST UPDATED
========================================================= -->

<div class="home-updated">
  Last updated: Aug 2026
</div>


{% comment %}

This is the front page of a website powered by the academicpages template
and hosted on GitHub Pages.

{% endcomment %}
