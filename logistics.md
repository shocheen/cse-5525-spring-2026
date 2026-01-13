---
layout: page
title: Logistics
layout: page
description: logistics
permalink: /logistics/
nav_order: 2
---

# Logistics
{:.no_toc}

## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}

---

## Introduction

This class is a graduate-level introduction to Natural Language Processing (NLP), the study of computing systems that can process, understand, or communicate in human language. The course covers fundamental approaches, particularly deep learning and language model pre-training, used across the field of NLP, as well as a comprehensive set of NLP tasks both historical and contemporary. Techniques studied include basic classification techniques, feedforward neural networks, attention mechanisms, pre-trained large language models (BERT-style encoders and GPT-style LMs), and structured models (sequences, trees, etc.). Problems range from syntax (part-of-speech tagging, parsing) to semantics (lexical semantics, question answering, grounding) and include various applications such as summarization, machine translation, information extraction, and dialogue systems. Programming assignments throughout the semester involve building scalable machine learning systems for various of these NLP tasks.

## Learning Resources

There is no required textbook for this course. 

### All readings are optional. Readings from book chapters and papers will be posted on the course website.

* [Y. Goldberg, Neural Network Methods in Natural Language Processing, 2017.](https://dl.acm.org/doi/book/10.5555/3110856)
* [Michael Collins, Notes on Statistical NLP.](https://www.cs.columbia.edu/~mcollins/notes-spring2013.html)
* [D. Jurafsky & James H. Martin, Speech and Language Processing: An Introduction to Natural Language Processing, Computational Linguistics and Speech Recognition, Prentice Hall, Third Edition, 2023 (in progress).](https://web.stanford.edu/~jurafsky/slp3/)
* [J. Eisenstein, Introduction to Natural Language Processing, MIT Press, 2019.](https://cseweb.ucsd.edu/~nnakashole/teaching/eisenstein-nov18.pdf)
* [C.D. Manning & H. Schuetze, Foundations of Statistical Natural Language Processing, MIT Press, 1999.](https://dl.acm.org/doi/book/10.5555/311445)
* [P. Koehn, Neural Machine Translation (book chapter drafts)](https://arxiv.org/pdf/1709.07809)

### Other Related Readings
* [Ian Goodfellow, Yoshua Bengio, and Aaron Courville, Deep Learning, 2016.](https://www.deeplearningbook.org/)
* [François Fleuret, the Little Book of Deep Learning](https://fleuret.org/francois/lbdl.html)
* [Hal Daumé III, A Course in Machine Learning.](http://ciml.info/)
* [Emily Bender, Linguistic Fundamentals for Natural Language Processing: 100 Essentials from Morphology and Syntax, Morgan & Claypool, 2013.](https://dl.acm.org/doi/book/10.5555/2534456)
* [Emily Bender, Linguistic Fundamentals for Natural Language Processing II: 100 Essentials from Semantics and Pragmatics, Morgan & Claypool, 2019.](https://dl.acm.org/doi/book/10.5555/3383733)
* [Noah Smith, Linguistic Structure Prediction, Mogran & Claypool, 2011.](https://link.springer.com/book/10.1007/978-3-031-02150-3)

### NLP Conferences and Journals
The main publication venues are ACL, NACCL, EMNLP, TACL, EACL, CoNLL, and CL. All papers from these publications can be found in the ACL Anthology. NLP publications often appear in ML and AI conferences, including ICML, NeurIPS, ICLR, AAAI, IJCAI. Work in the intersection of NLP and other fields often appears in the venues of these fields, such as Computer Vision (CVPR, ICCV, ECCV, etc.) and Robotics (CoRL, RSS, ICRA, HRI, etc.).


## Communication

This is an in-person lecture-based course. All resources (i.e. slides, reading materials, homeworks) can be found on the course website. We will use gradescope for submitting assignments, tophat for occassional attendance and quizes, and Teams for discussions and announcements. Please email me if you have not been added to either of these platforms. 

## Grading

There will be no written exams in this course. Instead, you will be graded based on class participation and in-class quizes, programming assigments, and a final project.

The timeline of assignments is on the course calendar. Assignment specifications, code, and data will be made available on the course website. Grading breakdowns are as follows:

* Assignment 1: 10%
* Assignment 2: 15%
* Assignment 3: 20%
* Final project: 45%
* Quizes: 10% 
* Class Participation: 4% (bonus)

Assignments will be submitted on Gradescope. Each assignment PDF will have more detailed instructions about what to submit; typically the submissions will consist of autograded code (e.g., measuring dev set accuracy of your model) and a brief written report.

Each student is given 5 slip days to use throughout the term. Any number of these days can be applied to Assignments 1 through 3 (**not the final project**) to extend the deadline for that assignment. E.g., you can turn the first project in 2 days late and the second project 3 days late. Slip days must be applied as entire days: submitting 25 hours late incurs 2 slip days. After your slip days are exhausted, each day of lateness will incur a 5% **absolute** penalty to that assignment's grade. If you would've received 90/100 on an assignment, you would then receive 75/100 if turned in 3 days late. Plan your slip day budget accordingly: you may want to save them up if you know you'll be traveling for a conference around a due date for a later project. Additional extensions may be granted in cases of medical or other emergencies, but must be agreed on with the course staff **before the project's original due date**.

Illness and Medical Extensions: Extensions may be granted in cases of illness, medical emergency, or other emergency circumstances. In all cases, the student should inform the course staff as soon as is practical, and the extension must be negotiated before the assignment's original due date.

### Assignments
Each assignment centers around an NLP task on a standard dataset, with part of the project being an open-ended extension where you'll have options for exactly what you want to implement or explore further.

Projects are graded 0-100. Typically the bulk of the grade is determined by completing the required coding task. The remainder of the grade is based on a writeup that describes what you did and how well it worked. Your report should be written in the tone and style of an ACL/NeurIPS conference paper. Any format with reasonably small (1" margins) is fine, including the [ACL style files](http://acl2017.org/calls/papers/) or any one- or two-column format with similar density.

### Final Project
Students have two options: the **Default Final Project**,  in which students tackle a predefined task, namely post-training (SFT + RL) a pretrained LM (more details TBA), or a **Custom Final Project**, in which students choose their own project involving human language and deep learning). This project should constitute novel work beyond directly implementing concepts from lecture and should result in a report that roughly reads like an NLP/ML conference submission in terms of presentation and scope. You may work on the final project in groups of two or three (individual final projects are not allowed); This is to encourage collaboration and to enable more substantial projects. You are allowed to integrate the project with ongoing research or projects from other classes (assuming the other instructor also approves).

**Proposal**: Partway through the semester, you will submit a brief proposal (around 1 page) explaining your idea, which the course staff will provide feedback on.

**Writeup**: Your final project report should be 4-8 pages. Use your discretion about the length. The scope should be similar to that of an ACL paper: you should present a novel idea, discuss related work, describe your implementation or what you did, give results, and provide discussion or error analysis.

Presentation: You will give lightning talks (around 3-5 minutes) about your project on the last two class days.

## Final Grades
Your final grade is computed based on the total points earned across all assignments. The final grade is mapped to a letter as follows, with grades on the boundary receiving the higher grade:

G | Range
--|--------------
A |	100 - 93.3
A-|	93.3 - 90.0
B+|	90.0 - 86.6
B |	86.6 - 83.3
B-|	83.3 - 80.0
C+|	80.0 - 76.6
C |	76.6 - 73.3
C-|	73.3 - 70.0
D |	70 - 65
F |	below 65

## Academic Honesty: Collaboration and ChatGPT

Please read the University's [academic honesty policies](https://oaa.osu.edu/academic-integrity-and-misconduct). For this course, students are encouraged to discuss lecture material, homework problems, and coding assignments with others! However, your final written solution or source code must be your own, excluding the final project, which may be completed in groups. Finally, note that you may consult external resources such as blog posts, YouTube videos, academic papers, GitHub repositories, AI assistants, and more. However, your use of such resources, particularly GitHub repositories, must be limited in the same way as discussions with other students: you can look at these to get an idea of how to solve a problem, but you should not take external code and submit it as part of your assignment, except for the final project when it is appropriately attributed.

Be sure you respect these policies when posting on the discussion board. Asking clarifying questions, addressing possible bugs in the provided code, etc. are fair game, but you should not discuss solutions in a substantive way that might spoil them for others. When in doubt, and when posting large amounts of source code, post privately to the instructors.

Students who violate these policies may receive a failing grade on the assignment in question or for the course overall, depending on the instructors' judgment and the severity of the infraction.

You are free to discuss the homework assignments with other students and work towards solutions together. However, all of the code you write must be your own! We will use anti-plagiarism software and any copied code will be treated as a violation of academic honesty and may result in a failing grade. In addition, your writeup must be entirely your own and your extension cannot duplicate those of your collaborators'.

**Policy on GitHub Copilot**: You are allowed to use GitHub Copilot for the assignments to seek assistance but *NOT* to solve entire homeworks. However, you must disclose this usage in two places. First, in your writeup, clearly state how you used GitHub Copilot. Second, in your code, indicate using a comment any blocks of code of more than 2 lines that were included from GitHub Copilot.

**Policy on ChatGPT**: Understanding the capabilities of these systems and their boundaries is a major focus of this class, and there's no better way to do that than by using them!

We encourage you to use ChatGPT to understand concepts in AI and machine learning. You should see it as a another tool like web search that can supplement understanding of the course material.

**You are allowed to use ChatGPT for preparing your writeups**. However, usage of ChatGPT must be limited in the same way as usage of other resources like websites or other students. You should write your report yourself and only use ChatGPT as a mild writing assistant. Furthermore, you must disclose your usage of ChatGPT in an Acknowledgments section, describing what it was used for and which sections of the report it was used to produce. Failing to adequately disclose ChatGPT usage will be considered academic dishonesty. Furthermore, including text that fails to follow standards of scientific writing (i.e., the vague and flowery text that ChatGPT produces) will be subject to point deductions on the writeup.

## Thanks

The content of this course has been adapted from courses taught by [Greg Durrett](https://www.cs.utexas.edu/~gdurrett/courses/sp2024/cs388.shtml), [Yoav Artzi](https://lm-class.org/), and [Ana Marasović](https://utah-intro-nlp.github.io/).