---
layout: home
title: Home
permalink: /
nav_order: 1
seo:
  type: Course
  name: COMS E6998 Cloud Computing 
---

# COMS E6998 Special Topics in Computer Science: Cloud Computing 

#### Columbia University, Fall 2024

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}
{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}

<!-- ## Time and Place -->
<table>
  <tr>
    <td><i>Time:</i> Fridays, 10:10am-12:00pm</td>
    <td><i>Location:</i> Kent Hall 411</td>
  </tr>
</table>

## Overview

<p style="text-align: justify; padding-left: 0; padding-right: 0;">
One of the most significant transformations in the computer sector over the last decade has been the rise of cloud computing. 
Companies are progressively transferring their tasks to external cloud platforms and utilizing advanced global services that were previously unattainable within individual data centers.
Nonetheless, the construction and utilization of cloud systems entails tackling numerous intricate research challenges.
This research seminar will explore both industrial and academic contributions to cloud computing, focusing on systems for machine learning and machine learning for systems.
Participants will analyze and guide discussions on research papers, and collaborate in small groups to undertake a research project throughout the semester.
</p>

## Prerequisites
<p style="text-align: justify; padding-left: 0; padding-right: 0;">
Appropriate for EE/CS graduate or advanced undergraduates that have taken <i>Operating Systems I</i> (COMS W4118) or an equivalent course.
</p>

## Format
<p style="text-align: justify; padding-left: 0;">
Reading, writing about, and discussing research papers.
Short presentations. Research projects in small groups. Participation will be required.
The grading rubric will be <b>50%</b> <i>project</i>, <b>25%</b> <i>participation</i>, and <b>25%</b> <i>paper</i> presentations and summaries.
</p>

## Project Instructions

### Final Presentations
<p style="text-align: justify; padding-left: 0;">
Your presentation slot is 12min but we strongly suggest you prepare for a 10min presentation and leave time for questions. We will strictly enforce time, so please practice!
We suggest the following outline for your talk:
1. The problem
1. The idea
1. Design and implementation (1-2 slides)
1. What works/status
1. A key measurement/experiment

Feel free to deviate from this outline, but make sure you stick to the main points (and do not try to cover all your results). You can choose to have a single team member give the talk or have multiple members alternate. Please email your slides to Kostis and Vahab. *Note:* the presentation is not the final deliverable of your project. It is a way to get feedback on important issues you should address in your report.
</p>
