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
   HOME — DESIGN SYSTEM
========================================================= */

:root {
  --home-text: #4f5458;
  --home-text-soft: #666c71;
  --home-muted: #92989d;
  --home-light: #a5aaae;

  --home-blue: #52789d;
  --home-blue-soft: #f3f7fb;
  --home-blue-line: #d8e3ee;

  --home-bg-soft: #fafbfc;
  --home-border: #e8ebed;
  --home-border-light: #f0f1f2;
}


/* =========================================================
   INTRO / HERO
========================================================= */

.home-hero {
  margin: 4px 0 36px;
}

.home-intro {
  max-width: 820px;

  font-size: 1em;
  line-height: 1.62;

  color: var(--home-text);
}

.home-intro p {
  margin: 0 0 18px;
}

.home-intro a {
  text-underline-offset: 2px;
}


/* =========================================================
   JOB MARKET
========================================================= */

.job-market-strip {
  display: flex;
  align-items: center;

  margin: 25px 0 20px;
  padding: 12px 17px;

  background: linear-gradient(
    90deg,
    var(--home-blue-soft) 0%,
    #ffffff 100%
  );

  border: 1px solid var(--home-blue-line);
  border-left: 4px solid var(--home-blue);
  border-radius: 6px;

  color: var(--home-text);
}

.job-market-strip strong {
  font-size: 1.02em;
  font-weight: 600;
}


/* =========================================================
   COLLABORATION + CONTACT
========================================================= */

.home-collab {
  margin-top: 4px;

  font-size: 0.96em;
  line-height: 1.58;

  color: var(--home-text);
}

.home-contact {
  display: inline-flex;
  align-items: center;
  gap: 6px;

  margin-top: 12px;

  font-size: 0.92em;
  color: var(--home-text-soft);
}

.home-contact a {
  color: var(--home-text-soft);
  text-decoration: none;
}

.home-contact a:hover {
  color: var(--home-blue);
}


/* =========================================================
   SHARED SECTION HEADING
========================================================= */

.home-section {
  margin: 38px 0;
}

.home-section-heading {
  display: flex;
  align-items: center;
  gap: 12px;

  margin-bottom: 12px;
}

.home-section-label {
  flex-shrink: 0;

  font-size: 0.75em;
  font-weight: 600;

  letter-spacing: 0.09em;
  text-transform: uppercase;

  color: #81878c;
}

.home-section-line {
  width: 100%;
  height: 1px;

  background: #eef0f2;
}


/* =========================================================
   RESEARCH
========================================================= */

.research-box {
  display: grid;
  grid-template-columns: 1fr 1fr;

  padding: 18px 22px;

  background: var(--home-bg-soft);

  border: 1px solid var(--home-border);
  border-radius: 8px;
}

.research-column:first-child {
  padding-right: 28px;
}

.research-column:last-child {
  padding-left: 28px;

  border-left: 1px solid #e8ebed;
}

.research-subheading {
  margin-bottom: 7px;

  font-size: 0.69em;
  font-weight: 600;

  letter-spacing: 0.07em;
  text-transform: uppercase;

  color: var(--home-muted);
}

.research-list {
  margin: 0;
  padding: 0;

  list-style: none;
}

.research-item {
  position: relative;

  padding: 7px 0 7px 13px;

  font-size: 0.84em;
  line-height: 1.35;

  color: #62686d;
}

.research-item + .research-item {
  border-top: 1px solid #eef0f2;
}

/* tiny visual marker — not a pill */
.research-item::before {
  content: "";

  position: absolute;
  left: 0;
  top: 50%;

  width: 4px;
  height: 4px;

  background: #8ea9c1;
  border-radius: 50%;

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
  grid-template-columns: 72px minmax(0, 1fr);

  gap: 18px;

  padding: 16px 18px;

  background: #ffffff;

  border: 1px solid var(--home-border);
  border-radius: 8px;

  transition:
    border-color 0.18s ease,
    box-shadow 0.18s ease;
}

.upcoming-card:hover {
  border-color: #d5dfe7;

  box-shadow:
    0 4px 16px rgba(45, 60, 75, 0.04);
}


/* Date block */

.upcoming-date {
  padding-top: 3px;

  text-align: center;
}

.upcoming-date-month {
  font-size: 0.66em;
  font-weight: 600;

  letter-spacing: 0.08em;

  color: var(--home-blue);

  text-transform: uppercase;
}

.upcoming-date-day {
  margin-top: -1px;

  font-size: 1.45em;
  font-weight: 600;
  line-height: 1.15;

  color: #5b6670;
}


/* Talk content */

.upcoming-content {
  min-width: 0;
}

.upcoming-title {
  margin-bottom: 4px;

  font-size: 1em;
  font-weight: 600;
  line-height: 1.4;

  color: var(--home-text);
}

.upcoming-eventline {
  display: flex;
  justify-content: space-between;
  align-items: baseline;

  gap: 15px;

  font-size: 0.82em;
  line-height: 1.4;
}

.upcoming-conference {
  font-weight: 500;
  color: #73797e;
}

.upcoming-details {
  flex-shrink: 0;

  color: var(--home-muted);

  white-space: nowrap;
}


/* Sessions */

.upcoming-sessions {
  margin-top: 9px;
  padding-top: 7px;

  border-top: 1px solid #eef0f2;
}

.upcoming-session-row {
  display: grid;
  grid-template-columns: minmax(0, 1fr) auto;

  gap: 14px;

  padding: 2px 0;

  font-size: 0.76em;
  line-height: 1.4;
}

.upcoming-session {
  color: #777d82;
}

.upcoming-session-meta {
  color: #969ca1;

  white-space: nowrap;
}


/* =========================================================
   PAST TALKS
========================================================= */

.past-talks-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;

  margin: 28px 0 7px;
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
  max-height: 210px;
  overflow-y: auto;

  padding-right: 7px;

  border-top: 1px solid #eceeef;
  border-bottom: 1px solid #eceeef;

  scrollbar-width: thin;
  scrollbar-color: #c4c9cd transparent;
}


/* Individual past talk */

.past-talk-row {
  display: grid;
  grid-template-columns: 76px minmax(0, 1fr);

  gap: 16px;

  padding: 10px 3px;

  border-bottom: 1px solid var(--home-border-light);
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


/* Scrollbar — Chrome / Safari */

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

  font-size: 0.7em;

  color: #a6aaae;
}


/* =========================================================
   MOBILE
========================================================= */

@media (max-width: 700px) {

  /* Intro */

  .home-hero {
    margin-bottom: 30px;
  }

  .home-intro {
    font-size: 0.94em;
    line-height: 1.55;
  }

  .home-intro p {
    margin-bottom: 15px;
  }


  /* Job market */

  .job-market-strip {
    margin: 21px 0 17px;
    padding: 11px 13px;
  }

  .job-market-strip strong {
    font-size: 0.96em;
  }


  /* Sections */

  .home-section {
    margin: 31px 0;
  }


  /* Research */

  .research-box {
    grid-template-columns:
      minmax(0, 1fr)
      minmax(0, 1fr);

    padding: 14px 12px;
  }

  .research-column:first-child {
    padding-right: 10px;
  }

  .research-column:last-child {
    padding-left: 10px;
  }

  .research-subheading {
    font-size: 0.64em;
  }

  .research-item {
    padding: 6px 0 6px 10px;

    font-size: 0.73em;
    line-height: 1.3;
  }

  .research-item::before {
    width: 3px;
    height: 3px;
  }


  /* Upcoming talks */

  .upcoming-card {
    grid-template-columns: 52px minmax(0, 1fr);

    gap: 11px;

    padding: 13px 12px;
  }

  .upcoming-date-month {
    font-size: 0.61em;
  }

  .upcoming-date-day {
    font-size: 1.25em;
  }

  .upcoming-title {
    font-size: 0.91em;
    line-height: 1.35;
  }


  /* Conference then date/location */

  .upcoming-eventline {
    display: block;

    font-size: 0.75em;
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

    font-size: 0.70em;
  }

  .upcoming-session {
    display: block;
  }

  /* Keep meeting time + venue together */
  .upcoming-session-meta {
    display: block;

    margin-top: 1px;

    font-size: 0.96em;

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


  /* Mobile: tiny scroll cue */

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
     INTRO
========================================================= -->

<div class="home-hero">

  <div class="home-intro">

    <p>
      I am Xiaodan Shao, a Ph.D. candidate in Operations Management at
      Nanyang Business School, Nanyang Technological University, where I am
      fortunate to be advised by Prof.
      <a href="https://sites.google.com/view/vkchoudhary">Vivek Choudhary</a>
      and Prof.
      <a href="https://dr.ntu.edu.sg/cris/rp/rp01345">Anandasivam Gopal</a>.
    </p>

    <p>
      My empirical research is driven by a desire to improve how healthcare
      is delivered and operated. I study how people and organizations across
      the healthcare system respond to information and technology, and how
      data-driven interventions can make care safer, more accessible, and
      more effective.
    </p>

  </div>


  <!-- Job Market -->

  <div class="job-market-strip">
    <strong>
      I am on the 2026–2027 academic job market.
    </strong>
  </div>


  <!-- Collaboration -->

  <div class="home-collab">
    Some of the most rewarding research comes from working with practitioners
    and policymakers to turn real-world challenges into useful insights.
    If you’re facing a hard problem or exploring a new idea, feel free to
    reach out.
  </div>

  <div class="home-contact">
    <span>📧</span>
    <span>Email:</span>
    <a href="mailto:xiaodan001@e.ntu.edu.sg">
      xiaodan001@e.ntu.edu.sg
    </a>
  </div>

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


  <div class="research-box">

    <div class="research-column">

      <div class="research-subheading">
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


    <div class="research-column">

      <div class="research-subheading">
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


    <!-- Oct 31 -->

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
            5th Symposium on Environmental and Social Sustainability
          </span>

          <span class="upcoming-details">
            UC Berkeley · TBA
          </span>

        </div>

      </div>

    </div>


    <!-- Nov 2 -->

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
              Service Science Best Student Paper Award
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

This is the front page of a website that is powered by the academicpages
template and hosted on GitHub Pages.

{% endcomment %}
