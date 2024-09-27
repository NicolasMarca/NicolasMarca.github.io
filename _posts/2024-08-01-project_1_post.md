---
title: Interactive Data Analysis Report @UN Migration
layout: post
category: project
sidebar-hide: true
---
Developed an interactive report to draw insights from various datasets and previous reports of remittances in Belgium, designed to be embedded and displayed on a website.

<section class="article-text">
  <p>
    As part of my consultancy work for the UN Migration Belgium and Luxembourg the report allows users to explore data interactively, displaying graphs and visualizations that make the insights clear and accessible. This analysis builds on <a href="https://belgium.iom.int/remittances-belgium-key-data">two earlier studies</a>, one being a market analysis and another a report where I applied advanced statistical methods—specifically, a two-step Generalized Method of Moments (GMM) with instrumental variables (IV)—to investigate cause-and-effect relationships within Belgium's remittance market. To ensure accuracy and efficiency, I constructed a comprehensive database and established an ETL process to manage and integrate the data effectively.
  </p>
  <p>
    The primary goal of the interactive report is to provide stakeholders with a clearer understanding of remittance market dynamics in Belgium. By allowing users to explore data interactively, the report is designed to enhance decision-making processes and facilitate more targeted interventions in the market:
  </p>
  <figure>
    <img src="{{ 'assets/images/oremit_interactive_gif_1.gif' | relative_url }}" alt="OREMIT 1" width="100%" />
    <figcaption><b>Gif 1. Report Intro</b></figcaption>    
  </figure>

  <p>
    In generating this interactive report, I leveraged a range of technical tools and frameworks, including Pandas, NumPy, Seaborn, Plotly (express, graph_objects, subplots), Bar Chart Race, GeoPandas, Pretty Jupyter, Jinja, HTML, and CSS. One of the main challenges was estimating missing data with regards to corridor level remittance flows, which I addressed employing the <a href="https://openknowledge.worldbank.org/entities/publication/9296043a-53d8-5423-a6df-d7361ef769ad">methodology of the World Bank for estimating bilateral remittance flows</a>. This approach allowed for a more complete and reliable analysis, despite data limitations in the remittance landscape in Belgium. 
  </p>
  <p>
    This interactive format offers several advantages compared to traditional reports: 
  </p>
  <table style="width:100%; border-collapse: collapse; font-size: 18px;">
    <tr>
      <th style="border-bottom: 2px solid #ccc; text-align: left; padding: 8px;">Feature</th>
      <th style="border-bottom: 2px solid #ccc; text-align: left; padding: 8px;">Traditional Report</th>
      <th style="border-bottom: 2px solid #ccc; text-align: left; padding: 8px;">Interactive Report</th>
    </tr>
    <tr>
      <td style="padding: 8px;">Data Exploration</td>
      <td style="padding: 8px;">Static, limited to pre-defined sections</td>
      <td style="padding: 8px;">Dynamic, allowing users to explore specific data points, filter information, and interact with the visualizations</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Visualizations</td>
      <td style="padding: 8px;">Static charts and tables</td>
      <td style="padding: 8px;">Interactive charts with real-time filtering, zooming, and animation options</td>
    </tr>
    <tr>
      <td style="padding: 8px;">User Engagement</td>
      <td style="padding: 8px;">Passive reading of content</td>
      <td style="padding: 8px;">Active engagement with data through hover features, clickable elements, and more</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Accessibility</td>
      <td style="padding: 8px;">Print or PDF formats</td>
      <td style="padding: 8px;">Accessible across multiple devices, with optimized web performance</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Depth of Analysis</td>
      <td style="padding: 8px;">Generalized for all audiences</td>
      <td style="padding: 8px;">Allows deeper, personalized analysis, specific to user needs</td>
    </tr>
    <tr>
      <td style="padding: 8px;">Didactic Experience</td>
      <td style="padding: 8px;">Limited to a static narrative</td>
      <td style="padding: 8px;">Interactive and self-paced learning through visual and data interaction</td>
    </tr>
  </table>

  <p>
    This interactive format provides a more layered view of the data, offering an engaging experience that enhances both comprehension and exploration. Below, you can find a short preview of how the report's interactive functionalities, making the information more intuitive and accessible for all stakeholders: 
  </p>

  <figure>
    <img src="{{ 'assets/images/oremit_interactive_gif_2.gif' | relative_url }}" alt="OREMIT 2" width="100%" />
    <figcaption><b>Gif 2. Features Display Snippet</b></figcaption>
  </figure>

</section>
<br>
Note: As this is an internal project the source code cannot be shared publicly, however, I am open to discussing about it.
