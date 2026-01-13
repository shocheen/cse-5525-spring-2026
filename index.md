---
layout: home
title: Home
nav_exclude: false
nav_order: 1
permalink: /
seo:
  type: Course
  name: Foundations of Speech and Language Processing
---

<!-- # {{ site.tagline }} -->
<!-- {: .mb-2 } -->
# {{ site.description }}
#### {{ site.title }} &middot; {{ site.semester }} &middot; {{ site.university }}

{% if site.announcements %}
{{ site.announcements.last }}
[Announcements](announcements.md){: .btn .btn-outline .fs-3 }
{% endif %}

<!-- <img src="assets/images/crafting_software_header_noBG.png" > 

## Welcome to 17-950 Crafting Software-->

This course constitutes an introduction to natural language processing (NLP), the goal of which is to enable computers to use human languages as input, output, or both. 
NLP is at the heart of many of today’s most exciting technological achievements, including machine translation, automatic conversational assistants and Internet search. 
The course will introduce core problems and methodologies in NLP, including machine learning, problem design, and evaluation methods.

---

**Lectures**: WF 2:20-3:40 pm ET 

**Lecture Location**: Mendenhall Lab 191

## Prerequisite Knowledge

### Formal

CSE 3521 or CSE 5521; CSE 5522; Stat 3460 or 3470.

### Informal (please check with instructor if in any doubt)

We expect that you:

…are experienced with programming in Python – we won't be reviewing your code directly and we expect you to figure out the implementation side on your own; we are here to help you with understanding concepts and translating ideas into pseudocode,

…are comfortable with basic calculus, probability, and linear algebra,

…can quickly pick up machine learning and deep learning,

…can quickly pick up coding in pytorch,

…are interested in language and don't aim to just deepen your machine learning knowledge.

**Revisiting/polishing your knowledge**:

There are a ton of Python resources for people with some programming experience. Check them out [here](https://wiki.python.org/moin/BeginnersGuide/Programmers). I highly recommend these [slides](https://web.stanford.edu/class/cs224n/readings/cs224n-python-review-2023.pdf)/[colab](https://colab.research.google.com/drive/1hxWtr98jXqRDs_rZLZcEmX_hUcpDLq6e?usp=sharing) (caution: there are some typos).

Math and machine learning basics are nicely covered in the first part of the [Deep Learning book](https://www.deeplearningbook.org/). Obviously, you can use the same book to familiarize yourself with deep learning. If you learn by coding then you will find this resource helpful [Practical Deep Learning for Coders by Fast.ai](https://course.fast.ai/) (3: Neural net foundations; 5: From-scratch model, 13: Backpropagation & MLP, 14: Backpropagation)


---

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% assign teaching_assistants = site.staffers | where: 'role', 'Teaching Assistant' %}
{% assign num_teaching_assistants = teaching_assistants | size %}
{% if num_teaching_assistants != 0 %}
### Teaching Assistants

{% for staffer in teaching_assistants %}
{{ staffer }}
{% endfor %}
{% endif %}

## Code of Conduct

The strength of the university depends on academic and personal integrity. In this course, you must be honest and truthful, abiding by the University Academic Integrity Policy: [https://oaa.osu.edu/academic-integrity-and-misconduct](https://oaa.osu.edu/academic-integrity-and-misconduct)


