---
layout: page
title: Logistics
layout: page
description: logistics
permalink: /logistics/
has_children: false
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

This graduate level special topics course examines emerging frontiers in language modeling research. Specifically, this offering will focus on the following topics (subject to minor changes): 
* Reasoning and Tool Use: Understanding model abilities and limitations in performing complex, multi-step inference.
* Long inputs and outputs: Analyzing model performance on long-context processing and long-form generation, including data requirements and efficiency considerations.
* New architectures and modeling paradigms, such as state space models (SSMs) and their variants, recurrent and linear-attention hybrids, and diffusion-based language models.
* Applications of language models for expert domains including law, medicine, journalism, and scientific discovery.

The format of the class will be a mix of lectures and research paper presentations. The course culminates in a semester long research or implementation project, presented as a final paper and in class presentation. Projects should emphasize novel failure modes, under explored behaviors, or emerging risks rather than incremental performance gains. 

**Prerequisites**: CSE 5525 or instructor consent. Undergraduate students require instructor permission to enroll. 

## Learning Resources

### Textbook
No required textbook, we will read research papers in this course. But if you are interested, the following textbooks might be useful to understand certain topics we will cover in the course.

* [A Primer on Neural Network Models for Natural Language Processing](https://arxiv.org/abs/1510.00726).
* [Natural Language Processing with Transformers](https://nlp-with-transformers.github.io/website/)
* [RLHF book](https://rlhfbook.com/)

We will be reading research papers from premier conferences in the field E.g., ACL, EMNLP, ICLR, NeurIPS, ICML, and NAACL, among others.

## Communication

We will primarily use Microsoft Teams for announcements and student discussions with any instrutor post cross-posted on Canvas. We will not regularly check Canvas, so please do not post anything there. For any questions / comments, please use teams. 

Canvas Link:  [CSE 5539 Canvas](https://osu.instructure.com/courses/219498).

If you are registered for the course and not yet in the course team, please click this [link](https://teams.microsoft.com/l/team/19%3Am1Yif0euIagov96GEgqKtUKFPLuIZEU9ymMIEIcxQ6U1%40thread.tacv2/conversations?groupId=cc18a6b3-a224-40b6-8e5d-7b85857a791c&tenantId=eb095636-1052-4895-952b-1ff9df1d1121) to join and and you will be added after instructor approval.

For occasional attendance and quizzes, we will use [TopHat](https://app.tophat.com/e/434791).

Please email the instructor if you face any issues in being added to these platform.

## Content
For much of the semester, each class will involve the presentation and discussion of recent important papers. The objective of the course is to learn about and discuss the latest developments in Language Modeling and broadly NLP, and help the participants understand their broad implications.

### Presenters
Each paper will be presented by a group of students each with an assigned "role". This role defines the lens through which they read the paper and determines what they prepare for the group in-class discussion. Here are the roles we will experiment with (more will be added soon):

Stakeholder ✍️: Act as if you're the authors of this paper. Describes their motivation, problem definition, method and experimental findings of this paper. (time budget: 15 minutes)

Scientific Reviewer 🔎: Act like you're a reviewer of this work. Be critical of the work, though not necessarily negative. You can follow the guidelines for NeurIPS reviewers (under "Review Content"), taking note of the example reviews included therein. (time budget: 10 minutes)

Archaeologist 🏺: Determine where this paper sits in the context of previous and subsequent work. Find and report on one prior paper that substantially influenced the current paper and one newer paper that cites this current paper. (time budget: 10 minutes)

Visionary 🔭: Propose an imaginary follow-up research project or a new application -- not just based on the current but only possible due to the existence and success of the current paper. (time budget: 10 minutes)

The presentation of each role will be done individually or in a group of two depending on the complexity of the paper. In case of a group presentation the presenters may decide how to divide the work among themselves but it should be roughly equal. 

Who presents what role and when? In a given class session, two papers centered around a theme will be discussed. The students will each be given a random role (determined at least 10 days before the presentation). Each role (irrespective of how many students are assigned to it) should aim for specified time budgets for each role. You're encouraged to have slides for your role, though it is not mandatory. If you do so, I would recommend less than 7-10 slides to make sure stay within our time budget.

What slides? To minimize time spent context switching or fighting with screen sharing/projector dongles, we will have a shared pool of slides. Each role group are encouraged to title their slides with "[role emoji]: [student name]" (as in "🏺: Jane, John") so that the slides are quickly identified during the session. If you choose to make slides, you're not expected to prepare a full-blown presentation -- they're encouraged for visual aid and facilitating the presentation.

### Non-Presenters
If you aren't in the presenting group during a given class period: Come up with one question / discussion point about the paper (either something you're confused about or something you'd like to hear discussed more). Submit this question to TopHat (a submission link will be provided before the class)

During the class: While only a subset of the class will participate in presenting a paper, the rest of the class is expected to come to class ready to participate in the discussions. The instructor might call upon you to answer a question raised during the discussion.

## Grading

This is a seminar level course and instead of exams, grades will be based on leading/participating in class discussions and a final project.

### Foundations Homework (5%)

### Paper presentation and discussions (40%)

* 20%: Paper presentation
    * Each student will lead the presentation of up to 4 sessions (depending on the size of the class). The students will be encouraged to think of themselves as the author of the paper presenting it at a conference venue. The purpose of this is to discuss the main insights and findings of the paper and connect the paper with other papers and lectures discussed in class. The presenter is also encouraged to prepare a few discussion points/questions after the presentation.

* 10% Active participation
    Each student, when not presenting, will engage in discussions about the paper. They will act as audience or reviewers of the paper. They will discuss strengths, weaknesses and possible extensions/solutions

* 10% Turn in questions and occasional quizzes.
    * Quizes will be based on small group discussions and will be distributed occasionally in some (not all) of the sessions and must be turned in by next day after the class.

### Class project (55%) 

Students must complete a final research project on a topic of their choice related to the class. The students can team up with other students but the team size is limited to 3 students. Larger group require instructor approval. 

* 10%: proposal (due September 20)
    * Students should submit a 1-2 page proposal for their project by week 3-4. The proposal should: state and motivate the problem, and position the proposed project within related work. The project should propose either a novel research, a novel investigation of existing methods, an extension of prior work for a specific purpose, or a new application. It should also include a brief description of the approach as well as the experimental plan (e.g., baselines, datasets, etc) to validate the effectiveness of the approach.

* 10%: project progress report
    * 2-3 page document due by week 10-11 (around the time of mid-term). It should describe the project goal and related work, initial results, and the plan continuing the project. 

* 10%: code 
    * Your project code should be clean, readable, with clear running instructions, and the results should be fully reproducible

* 10%: final project presentation
    * We will dedicate the final session of the class to presentations. Depending on the size of the class this can be either a poster presentation or oral presentation. We may need to extend the class time to fully accomodate all presentations.

* 20%: final project report
    * 6-8 page conference format report (e.g., ACL/EMNLP Links to an external site.) detailing the project motivation, related work, proposed approach, results, and discussion. You can think of this as a conference paper. Negative results will not be penalized, but should be accompanied with detailed analysis of why the proposed methods didn’t work and provide some additional insights into the problem. 


<!-- ### Relevant resources:

Here are compute resources available for free

#### Compute Resources

- Each student will get access to OSC Compute
- Google Colab provides free GPU usage for up to 12 hours/day for academic purposes. One can obtain more compute on Colab with relatively minimal pay.
- Google offers research TPU credits.
- Kaggle offers GPUs for its users.
- AWS and Azure both offer welcome credits to students (which includes access to several LLM APIs)

#### Demos:
- GPT-J demo
- OPT demo
- BLOOM demo
- A queryable interface to Dolma, pile
- AllenAI OLMo demo
- AllenNLP demo
- Social stereotypes in models
- Meta's BlenderBot demo
- Examples from AudioLM
- A repository of language tasks and their instructions

#### Tutorials:
- These tutorials do a good job of introducing PyTorch.
- A course on Huggingface's Transformers library.
- Dive into Deep Learning: Interactive deep learning book with code, math, and discussions.

Besides these resources, I will try my best to satisfy individual needs through discussion in class / office hours. -->