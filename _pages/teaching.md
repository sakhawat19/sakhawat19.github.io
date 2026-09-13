---
title: "Teaching"
permalink: /teaching/
---

## CSC 250-02 — Foundations of Computer Science I

**Course Instructor · Spring 2026 · UNC Greensboro**

I independently designed the instructional materials and taught the entire semester-long, in-person course, with responsibility for course planning, instruction, assessment, and grading. I organized the content into **13 modules**, delivered three 50-minute meetings each week, and developed five assignments, two exams, and a cumulative final examination.

The course develops logical reasoning, proof-writing, and algorithmic thinking through proof techniques and induction; sets, functions, and relations; graphs and trees; recursion; algorithm complexity; counting; and recurrence relations. I supported students through office hours, individual appointments, and Canvas course resources.

## Lecture slides

Browse the available Spring 2026 materials below. PDF previews can be expanded on this page, or opened in a separate browser tab.

{% for lecture in site.data.csc250 %}
<div class="lecture-card">
  <h3>{{ lecture.title | escape }}</h3>
  <a class="btn btn--primary" href="{{ lecture.file | relative_url }}">{% if lecture.format == 'PDF' %}Open PDF{% else %}Download PowerPoint{% endif %}</a>
  <a class="btn" href="{{ lecture.file | relative_url }}" download>Download {{ lecture.format }}</a>
  {% if lecture.powerpoint %}
  <a class="btn" href="{{ lecture.powerpoint | relative_url }}" download>Download PowerPoint</a>
  {% endif %}
  {% if lecture.format == 'PDF' %}
  <details>
    <summary>Preview slides</summary>
    <iframe loading="lazy" title="{{ lecture.title | escape }} slides" src="{{ lecture.file | relative_url }}" width="100%" height="540"></iframe>
    <p><a href="{{ lecture.file | relative_url }}">Open the PDF if the preview is unavailable.</a></p>
  </details>
  {% endif %}
</div>
{% endfor %}

## Teaching approach

I emphasize clear explanations, structured practice, and independent reasoning. I aim to create an accessible environment where students with different levels of preparation can ask questions, participate, and build confidence. My software development experience helps connect foundational concepts with practical computing problems.

## Teaching interests

Foundations of computer science and discrete mathematics; introductory programming and Python; artificial intelligence and machine learning; natural language processing; software engineering and web development; database systems.
