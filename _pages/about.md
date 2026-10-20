---
layout: about
title: about
permalink: /
subtitle: <span class="text-nowrap">PhD Candidate&nbsp;·</span> <span class="text-nowrap">University of Michigan,</span> <span class="text-nowrap">Rackham Graduate School&nbsp;·</span> <span class="text-nowrap">Expected Graduation Fall 2026</span>

profile:
  align: left
  image: shadouaj_pic.jpg
  image_alt: Sami Hadouaj # describes the photo for search engines and screen readers
  image_circular: false # crops the image to make it circular
  more_info: >
    <p><a href="mailto:shadouaj@umich.edu">shadouaj@umich.edu</a></p>

person: # describes you to search engines (Schema.org Person)
  job_title: PhD Candidate
  affiliation: University of Michigan

selected_papers: true # includes a list of papers marked as "selected={true}"
industry_experience: true # includes industry experience section
teaching_experience: true # includes teaching experience section
service: true # includes service section
talks: true # includes talks & presentations section
fun_stuff: true # includes fun stuff section
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

<br>

## About Me

I am a PhD candidate at the Department of [Computer and Information Science](https://umdearborn.edu/cecs) at the University of Michigan-Dearborn, advised by Dr. [Niccolò Meneghetti](https://www-personal.umd.umich.edu/~niccolom/research/). My research lies at the intersection of Machine Learning and Systems, with a core focus on Bayesian inference and probabilistic modeling. In summer 2026, I was an Applied Research Intern at eBay, where I built a hybrid vector and graph retrieval engine to ground LLMs.

<div class="cv-download-section">
  <a href="{{ '/assets/pdf/resume.pdf' | relative_url }}" class="cv-download-btn" target="_blank">
    <i class="fa-solid fa-download"></i>
    <span>My Resume</span>
  </a>
</div>

<br><br>
<br><br>
<br>

**Research focus:** Real-world data is inherently uncertain, yet the systems we use to manage and query it were not designed to handle that uncertainty. My research addresses this gap by embedding Bayesian inference directly into database query engines, making probabilistic reasoning a native operation in the execution pipeline rather than an external add-on. I work at the intersection of data management, statistical inference, and probabilistic programming, building high-performance systems in C++ that reason under uncertainty as naturally as they filter and join. More broadly, I am interested in how principled statistical reasoning can be embedded into the AI systems that increasingly operate over real-world data.

<br><br>

## News

<div class="news-section">
  <div class="news-item">
    <div class="news-badge">
      <span class="news-badge-venue news-badge-company">eBay</span>
    </div>
    <div class="news-content">
      <p class="news-text">Spent summer 2026 as an <strong>Applied Research Intern at eBay</strong> in San Jose, building retrieval systems that ground LLMs in eBay’s knowledge graph.</p>
      <span class="news-date">May 2026 – August 2026</span>
    </div>
  </div>
  <div class="news-item">
    <div class="news-badge">
      <span class="news-badge-venue">SIGMOD 2026</span>
    </div>
    <div class="news-content">
      <p class="news-text">Paper accepted at <strong>ACM SIGMOD 2026</strong>. <em>Variational Inference for De Finetti Logic</em> brings variational inference natively into the database query engine, enabling fast, relational probabilistic programming.</p>
      <span class="news-date">March 2026</span>
    </div>
  </div>
</div>
