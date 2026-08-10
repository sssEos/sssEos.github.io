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
   GENERAL
========================================================= */

.home-section {
  margin: 34px 0;
}

.home-section-label {
  margin-bottom: 12px;

  font-size: 0.76em;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;

  color: #777d82;
}


/* =========================================================
   JOB MARKET
   MAIN HIGHLIGHT #1
========================================================= */

.job-market-box {
  margin: 18px 0;
  padding: 13px 18px;

  border: 1px solid #d8e3ee;
  border-left: 5px solid #52789d;
  border-radius: 6px;

  background: linear-gradient(
    90deg,
    #f3f7fb 0%,
    #ffffff 100%
  );

  font-size: 1.08em;
  line-height: 1.5;
}


/* =========================================================
   RESEARCH
   SEPARATE SECTION
========================================================= */

.research-box {
  padding: 18px 20px;

  background: #fafbfc;
  border: 1px solid #edf0f2;
  border-radius: 7px;
}


/* Topics | Methodologies */

.research-columns {
  display: grid;
  grid-template-columns: 1.45fr 1fr;
  gap: 36px;
}

.research-subheading {
  margin-bottom: 9px;

  font-size: 0.70em;
  font-weight: 600;
  letter-spacing: 0.06em;
  text-transform: uppercase;

  color: #999ea3;
}

.research-labels {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
}

.research-label {
  display: inline-block;

  padding: 6px 12px;

  font-size: 0.82em;
  font-weight: 400;
  line-height: 1.25;

  color: #5d6267;
  background: #ffffff;

  border: 1px solid #e0e4e7;
  border-radius: 16px;
}


/* =========================================================
   EDUCATION
   SEPARATE SECTION
========================================================= */

.education-box {
  padding: 18px 20px;

  background: #fafbfc;
  border: 1px solid #edf0f2;
  border-radius: 7px;
}

.education-list {
  width: 100%;
}

.education-row {
  display: grid;
  grid-template-columns: 1fr auto;
  gap: 22px;

  padding: 6px 0;

  font-size: 0.86em;
  line-height: 1.5;

  color: #60656a;
}

.education-main {
  font-weight: 400;
}

.education-year {
  font-weight: 400;
  color: #999ea2;

  white-space: nowrap;
}


/* Exchange = secondary information */

.education-extra {
  margin-top: 8px;
  padding-top: 8px;

  border-top: 1px solid #eceff1;

  font-size: 0.77em;
  line-height: 1.5;

  color: #969b9f;
}


/* =========================================================
   UPCOMING TALK
   MAIN HIGHLIGHT #2
========================================================= */

.upcoming-section {
  margin: 40px 0 0 0;
}

.upcoming-talk-card {
  padding: 20px 22px;

  border: 1px solid #d8e3ee;
  border-left: 5px solid #52789d;
  border-radius: 6px;

  background: linear-gradient(
    90deg,
    #f4f7fa 0%,
    #ffffff 100%
  );
}

.upcoming-label {
  margin-bottom: 8px;

  font-size: 0.72em;
  font-weight: 700;
  letter-spacing: 0.10em;
  text-transform: uppercase;

  color: #52789d;
}

.upcoming-title {
  max-width: 760px;

  margin-bottom: 11px;

  font-size: 1.02em;
  font-weight: 600;
  line-height: 1.5;

  color: #474c51;
}

.upcoming-conference {
  margin-bottom: 4px;

  font-size: 0.88em;
  font-weight: 500;

  color: #60656a;
}

.upcoming-meta {
  font-size: 0.82em;
  line-height: 1.6;

  color: #858a8f;
}


/* =========================================================
   PAST TALKS
========================================================= */

.past-talks-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;

  margin: 22px 0 7px 0;
}

.past-talks-title {
  font-size: 0.87em;
  font-weight: 500;

  color: #666b70;
}

.scroll-note {
  font-size: 0.69em;
  font-weight: 400;

  color: #a1a5a9;
}


/* Scroll box */

.past-talks-list {
  max-height: 205px;
  overflow-y: auto;

  padding-right: 8px;

  border-top: 1px solid #eceeef;
  border-bottom: 1px solid #eceeef;

  scrollbar-width: thin;
  scrollbar-color: #c4c9cd transparent;
}


/* Each talk */

.past-talk-row {
  display: grid;
  grid-template-columns: 76px 1fr;
  gap: 15px;

  padding: 11px 3px;

  border-bottom: 1px solid #f0f1f2;
}

.past-talk-row:last-child {
  border-bottom: none;
}

.past-talk-date {
  font-size: 0.79em;
  font-weight: 400;

  color: #969b9f;
  white-space: nowrap;
}

.past-talk-info {
  font-size: 0.83em;
  line-height: 1.45;

  color: #666b70;
}

.past-talk-name {
  font-weight: 400;
  color: #575c61;
}

.past-talk-location {
  margin-top: 2px;

  font-size: 0.93em;
  color: #999da1;
}


/* Scrollbar: Chrome / Safari */

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
  margin-top: 32px;

  font-size: 0.72em;
  color: #a3a7ab;
}


/* =========================================================
   MOBILE
========================================================= */

@media (max-width: 700px) {

  .home-section {
    margin: 28px 0;
  }

  .research-columns {
    grid-template-columns: 1fr;
    gap: 18px;
  }

  .research-box,
  .education-box {
    padding: 16px;
  }

  .education-row {
    grid-template-columns: 1fr;
    gap: 0;
  }

  .education-year {
    margin-top: 1px;
    font-size: 0.92em;
  }

  .upcoming-talk-card {
    padding: 18px;
  }

  .past-talk-row {
    grid-template-columns: 67px 1fr;
    gap: 10px;
  }

  .scroll-note {
    display: none;
  }

}

</style>


I am Xiaodan Shao, a Ph.D. candidate in Operations Management at Nanyang Business School, Nanyang Technological University, where I am fortunate to be advised by Prof. [Vivek Choudhary](https://sites.google.com/view/vkchoudhary) and Prof. [Anandasivam Gopal](https://dr.ntu.edu.sg/cris/rp/rp01345).


<!-- =========================================================
     JOB MARKET
========================================================= -->

<div class="job-market-box">
  <strong>I am on the 2026–2027 academic job market.</strong>
</div>


📧 Email: xiaodan001@e.ntu.edu.sg



<!-- =========================================================
     RESEARCH
     SEPARATE SECTION
========================================================= -->

<div class="home-section">

  <div class="home-section-label">
    Research
  </div>

  <div class="research-box">

    <div class="research-columns">


      <!-- TOPICS -->

      <div>

        <div class="research-subheading">
          Topics
        </div>

        <div class="research-labels">

          <span class="research-label">
            Healthcare Operations
          </span>

          <span class="research-label">
            Behavioral Operations
          </span>

          <span class="research-label">
            AI &amp; Digital Health
          </span>

        </div>

      </div>


      <!-- METHODOLOGIES -->

      <div>

        <div class="research-subheading">
          Methodologies
        </div>

        <div class="research-labels">

          <span class="research-label">
            Econometrics
          </span>

          <span class="research-label">
            Field Experiments
          </span>
          
          <span class="research-label">
            Data Analytics
          </span>



        </div>

      </div>


    </div>

  </div>

</div>



<!-- =========================================================
     EDUCATION
     COMPLETELY SEPARATE SECTION
========================================================= -->

<div class="home-section">

  <div class="home-section-label">
    Education
  </div>

  <div class="education-box">


    <div class="education-list">


      <div class="education-row">

        <div class="education-main">
          Ph.D., Operations Management · NTU
        </div>

        <div class="education-year">
          Present
        </div>

      </div>


      <div class="education-row">

        <div class="education-main">
          M.Sc., Business Analytics (Dean's Honours List) · NTU
        </div>

        <div class="education-year">
          2022
        </div>

      </div>


      <div class="education-row">

        <div class="education-main">
          B.Econ. (Honours) · Nanjing Audit University
        </div>

        <div class="education-year">
          2017
        </div>

      </div>


    </div>


    <div class="education-extra">
      Exchange · National University of Singapore (2023–2024)
      &nbsp;&nbsp;·&nbsp;&nbsp;
      University of Melbourne (2016)
    </div>


  </div>

</div>



<!-- =========================================================
     UPCOMING TALK
     COMPLETELY SEPARATE SECTION
========================================================= -->

<div class="upcoming-section">

  <div class="upcoming-talk-card">


    <div class="upcoming-label">
      Upcoming Talk
    </div>


    <div class="upcoming-title">
      Reducing Prescription Errors Through Information Intervention:
      A Field Experiment in Healthcare Operations
    </div>


    <div class="upcoming-conference">
      INFORMS Annual Meeting 2026
    </div>


    <div class="upcoming-meta">

      Session: TBA

      &nbsp;&nbsp;·&nbsp;&nbsp;

      Date &amp; Time: TBA

      &nbsp;&nbsp;·&nbsp;&nbsp;

      Location: TBA

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
          Workshop on Empirical Operations Management (WEOM)
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
          National University of Singapore, Singapore
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
          Hong Kong
        </div>

      </div>

    </div>


  </div>

</div>



<div class="home-updated">
  Last updated: Aug 2026
</div>


{% comment %} 
This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

{% endcomment %}
