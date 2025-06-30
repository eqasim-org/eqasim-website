---
layout: about
title: about
permalink: /
subtitle: #<a href='#'>Affiliations</a>. Address. Contacts. Motto. Etc.

profile:
  align: right
  image: # prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info:

selected_papers: false # includes a list of papers marked as "selected={true}"
social: false # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

The *eqasim* framework helps you set up agent-based transport simulations based on [MATSim](https://matsim.org/) in a standardized way.

<img style="width: 220px; float: right; clear: right; display: block; margin-left: 10px;" src="{{ site.baseurl }}/assets/img/synpop.png" alt="Synthetic population" />

**Synthetic populations** are an important input to agent-based transport simulations, and *eqasim* provides processes based on open data and software to generate *households*, *persons*, and *daily activity chains* for a variety of regions:

- Any region or department in **[France](https://github.com/eqasim-org/ile-de-france)**
- The **[Sao Paulo](https://github.com/eqasim-org/sao_paulo)** Metropolitan region
- Any place in **[California](https://github.com/eqasim-org/california)**
- All **[Bavaria](https://github.com/eqasim-org/bavaria)** or smaller parts such as Munich

Read more about **[eqasim-synpop]({{ site.baseurl }}/synpop)**!

<video width="220" style="float: right; clear: right; display: block; margin-left: 10px;" autoplay muted>
  <source src="{{ site.baseurl }}/assets/video/simulation.mp4" type="video/mp4">
  Video of an agent-based simulation
</video> 

**Agent-based simulations** allow to explore new technologies, modes of transport, public policies, social trends and more including their economic, ecological and social impacts. We provide a streamlined distribution of the [MATSim](https://matsim.org/) framework with a couple of individual improvements and simplifications to quickly bootstrap such an agent-based simulation for the cases cited above.

Read more about **[eqasim-java]({{ site.baseurl }}/java)**!

<h2>News</h2>
<div style="width: 70%">
  {% include news.liquid %}
</div>
