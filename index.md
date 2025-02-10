---
title: "Project Homepage"
keywords: sample homepage
tags: [getting_started]
sidebar: mydoc_sidebar
permalink: index.html
summary: Main page for project details.
---

## Project Details

Project Sponsor: Hawaiian Airlines

Project Specifications: Develop a data cleaning process or stored procedure based on aircraft maintenance logs in Skywise to identify recurring defects and anomalies in aircraft performance. Leveraging historical maintenance data, defect patterns, and operational context to improve maintenance scheduling and reduce unscheduled downtime.

### Project Updates

1. [27 Janurary 2025 Update](/update01.html)

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%d %B %Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% include links.html %}
