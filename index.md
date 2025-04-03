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

Project Specifications: Develop a data cleaning process or stored procedure based on aircraft maintenance logs in Skywise to identify recurring defects and anomalies in aircraft performance. When a component or system keeps failing, it can lead to delays or cancellations. The goal is to analyze pilot and mechanic logbook entries (PIREP and MAREP Write-Ups) to spot patterns in these failures so maintenance teams can fix problems before they cause delays. Leveraging historical maintenance data, defect patterns, and operational context to improve maintenance scheduling and reduce unscheduled downtime.

The application will be built using Skywise, a data analytics platform by Airbus and Palantir, and specifically on Slate, a tool that allows for a mix of no-code, low-code, and full-code solutions using Python and SQL.

### Project Updates

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.date | date: "%d %B %Y" }} - {{ post.title }}</a>
    </li>
  {% endfor %}
</ul>

{% include links.html %}
