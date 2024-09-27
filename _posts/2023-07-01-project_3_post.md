---
title: Automated Report Generation System @UN Migration
layout: post
category: project
sidebar-hide: true
---
Developed an automated report generation system to establish a consistent and efficient framework for generating analytical reports based on selected indicators and IDs.

<section class="article-text">
  <p>The Automated Report Generation System was designed to streamline the process of creating in-depth reports for IOM's country offices. By utilizing standardized templates and pulling data directly from IOM’s SQL servers and the Migration Data Portal, the system goal was to allow for the rapid generation of reports, complete with key performance indicators, trend analyses, and key statistics. This system emerged out of a need to create reports faster, providing country offices with actionable insights in their engagements with national stakeholders.</p>
  
  <p>The key feature of the system was its ability to automate the insertion of modular indicators into a pre-built Word document template, ensuring that relevant statistics and data visualizations are populated accurately:</p>

  <figure>
    <img src="{{ 'assets/images/hmcs_1.png' | relative_url }}" alt="hmcs 1" width="50%" />
    <figcaption><b>Fig 1. Report Template v1</b></figcaption>    
  </figure>

  <p>After choosing from a list of indicators and selecting an ID in this case countries a report is generated:</p>

  <figure>
    <img src="{{ 'assets/images/hmcs_2.png' | relative_url }}" alt="hmcs 2" width="50%" />
    <figcaption><b>Fig 2. Report Example India</b></figcaption>    
  </figure>

  <p>The reports generated were meant for external engagement, which is why Microsoft Word was chosen as the output format for its familiarity and ease of sharing across different levels of expertise. There were also considerations of piloting features like generative AI to assist in interpreting and summarizing data. I implemented this feature and after testing it thoroughly it proved useful in descriptive tasks, however, the AI was prone to errors with deeper analysis that involved extra research not currently being showcased in the data.</p>
  
  <p>I developed the proof of concept during my time at IOM’s Global Migration Data Analysis Centre (GMDAC), however I left before it reached completion. My intentions for future advancements would have involved building a user-friendly interface, potentially employing tools such as Streamlit, Dash or Shiny to allow IOM's 160+ country offices to generate reports on demand, refining the system through a pilot phase before global implementation. The impact of this system lies in its ability to automate what was previously a time-consuming process, enabling faster delivery of insights and freeing up resources for deeper analysis and decision-making.</p>  

</section>
<br>
Note: As this is an internal project the source code cannot be shared publicly, however, I am open to discussing about it.
