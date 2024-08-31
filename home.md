---
layout: home
title: Home
permalink: /
nav_order: 1
seo:
  type: Course
  name: COMS E6998 Cloud Computing 
---

# COMS E6998 Spcial Topics in Computer Science: Cloud Computing 

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
    <td><i>Time:</i> 10:10am-12:00pm</td>
    <td><i>Location:</i> TBD</td>
  </tr>
</table>

## Overview
One of the most significant transformations in the computer sector over the last decade has been the rise of cloud computing. 
Companies are progressively transferring their tasks to external cloud platforms and utilizing advanced global services that were previously unattainable within individual data centers.
Nonetheless, the construction and utilization of cloud systems entails tackling numerous intricate research challenges.
This research seminar will explore both industrial and academic contributions to cloud computing, focusing on systems for machine learning and machine learning for systems.
Participants will analyze and guide discussions on research papers, and collaborate in small groups to undertake a research project throughout the semester.

## Prerequisites
Appropriate for EE/CS grad students or advanced undergraduates that have taken _Operating Systems I_ (COMS W4118) or an equivalent course.

## Format

Reading, writing about, and discussing research papers.
Short presentations. Research projects in small groups. Participation will be required.
The grading rubric will be **50%** _project_, **25%** _participation_, and **25%** _paper_ presentations and summaries


