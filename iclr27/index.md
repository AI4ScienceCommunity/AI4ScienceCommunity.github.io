---
layout: iclr27
title: "AI for Science: Scientific Workbenches for Discovery"
subtitle: "Proposed ICLR 2027 Workshop"
description: "Scientific workbenches for reliable, interactive, and iterative scientific discovery. A proposed AI for Science workshop at ICLR 2027."
permalink: /iclr27
section: about

# The proposal explicitly labels these four participants as panelists.
# The invited talk lineup, panel topic, and moderator are still to be announced.
Panelists:
  - name: Venkat Viswanathan
    url: https://eeg.engin.umich.edu/people.html
    aff: University of Michigan
    interest: AI × Materials
    image: /iclr27/assets/images/venkat.jpg

  - name: Anima Anandkumar
    url: https://tensorlab.cms.caltech.edu/users/anima/
    aff: Caltech
    interest: AI × Physics
    image: /assets/images/anima.png

  - name: Risa Wechsler
    url: https://physics.stanford.edu/people/risa-wechsler
    aff: Stanford University
    interest: AI × Cosmology
    image: /iclr27/assets/images/risa.jpg

  - name: James Zou
    url: https://www.james-zou.com/
    aff: Stanford University
    interest: AI × Biology
    image: /iclr27/assets/images/james-zou.jpg

Organizers:
  - name: Soojung Yang
    url: https://sites.google.com/view/soojungy/
    aff: Stanford University & FutureHouse
    interest: AI for Protein Function
    image: /icml26/assets/images/soojung.png

  - name: Yunhui Jang
    url: https://yunhuijang.github.io/
    aff: KAIST
    interest: AI for Biology
    image: /iclr27/assets/images/yunhui.jpg

  - name: Namkyeong Lee
    url: https://namkyeong.github.io/
    aff: Genentech
    interest: AI for Drug Discovery
    image: /iclr27/assets/images/namkyeong.jpg

  - name: Zongyi Li
    url: https://zongyi-li.github.io/
    aff: New York University
    interest: Mathematics & Data Science
    image: /iclr27/assets/images/zongyi.jpg

  - name: Alex Starr
    url: https://www.futurehouse.org/fellows/alexander-starr
    aff: UC San Francisco & FutureHouse
    interest: AI for Neuroscience & Evolution
    image: /iclr27/assets/images/alex-starr.jpg

  - name: Sathya Edamadaka
    url: https://gomezbombarelli.mit.edu/sathya-edamadaka/
    aff: MIT
    interest: AI for Materials Science
    image: /iclr27/assets/images/sathya.jpg

Steering_Committee:
  - name: Marinka Zitnik
    url: https://zitniklab.hms.harvard.edu/
    aff: Harvard University
    image: /assets/images/marinka.png

  - name: Max Welling
    url: https://staff.fnwi.uva.nl/m.welling/
    aff: University of Amsterdam & CuspAI
    image: /assets/images/max.png
---

# About

AI for Science is moving beyond individual models toward systems that participate in iterative scientific discovery. As AI systems generate hypotheses, use scientific tools, design experiments, interpret observations, and adapt their next actions based on feedback, a central challenge is how to engineer environments that compose these capabilities into reliable scientific workflows.

Our proposed ICLR 2027 workshop, **Scientific Workbenches for Discovery**, brings together AI researchers, tool builders, and experimental scientists to develop a shared research agenda for reliable, interactive, and iterative scientific discovery.

We use the term **scientific workbench** for an integrated system of models, tools, data, experimental interfaces, orchestration mechanisms, and evaluators that supports an iterative loop:

<div class="discovery-loop" aria-label="Scientific discovery loop">
  <span>Hypothesis →</span> <span>Action / Experiment →</span> <span>Observation →</span> <span>Feedback →</span> <span>Revision</span>
</div>

## Four Interconnected Pillars

* **Loop Engineering:** Design, optimize, and strengthen scientific interaction cycles across repeated rounds of reasoning, experimentation, and feedback.
* **Harnesses & Orchestration:** Coordinate heterogeneous scientific tools, data sources, and computational resources into executable workflows.
* **Interactive Benchmarks & Evaluation:** Assess scientific systems over trajectories of decisions, analyses, and experiments, rather than only static answers.
* **Scientific Environments:** Build the computational and physical environments in which AI systems act, experiment, and receive feedback.

Many components of scientific workbenches are emerging in isolation, with different interfaces, assumptions, and objectives. This workshop aims to bring these directions together. Attendees will gain a clearer framework for scientific workbenches, research principles and open problems for loop engineering and scientific harnesses, new directions for interactive evaluation, and connections across machine learning and the sciences.

# Tentative Dates (Anywhere on Earth)

{% include iclr27-dates.html %}

## Submissions

We invite submissions in two research tracks:

* **Original Research Track:** Original studies using AI to tackle problems across scientific disciplines.
* **Position Track:** Perspectives on current progress, open questions, and concerns in AI scientists research.

Research papers should contain **4-8 pages of main text**, use the ICLR style file, and may include unlimited appendices. Accepted papers will be **non-archival**. The review process will be double-blind, with 2-3 reviewers per submission. OpenReview will be used for submissions; the workshop submission link and style-file details will be announced. See the [Call for Papers]({{ '/iclr27/call.html' | relative_url }}) for details.

## Proposal Competitions

We invite **two-page proposals** for two competitions:

* **Iterative Improvement of AI Scientists:** Design a framework through which an AI scientist learns to improve at a meaningful scientific task using existing data and knowledge as feedback, without requiring new experiments.
* **AI Credit Assignment in Science:** Propose ways to improve citation, attribution, novelty assessment, review, and guardrails for AI-assisted science.

The top two proposals in each competition are planned to receive podium presentations. Cash awards are planned; sponsors and award amounts will be announced. Read the [competition requirements]({{ '/iclr27/competition.html' | relative_url }}).

# Invited Talks

The proposed program includes **six invited talks**, each with 30 minutes for the talk and Q&A. The invited speaker lineup will be announced.

# Panel

The proposal lists the following four panelists. The panel topic and moderator will be announced.

{% include iclr27-team.html id="Panelists" %}

# Tentative Program

The proposed one-day program includes six invited talks, six contributed talks, four competition proposal highlights, one panel discussion, and two poster sessions. See the [program overview]({{ '/iclr27/schedule.html' | relative_url }}) for session formats and durations.

## Community and Accessibility

We encourage in-person participation and plan to facilitate participation for virtual attendees and authors unable to travel. Accepted papers will be listed on this website, and presentation slides and talks will be shared as they become available, with speakers' consent. Livestream and remote participation details will be announced.

We welcome researchers from varied scientific disciplines, institutions, career stages, and backgrounds. The workshop aims to connect machine learning researchers with the broader scientific community, including scientists attending an AI conference for the first time.

## Post-Workshop Networking Event

We plan to host an evening networking event to continue conversations between scientists and AI researchers. Partners, venue, timing, and registration details will be announced.

## Workshop Series

This edition builds on [AI Scientists - Tools, Co-authors, or Founders? (ICML 2026)]({{ '/icml26.html' | relative_url }}) and [Verification in the Age of AI Scientists (NeurIPS 2026)]({{ '/neurips26.html' | relative_url }}). Together, these themes trace a progression from defining AI scientists, to verifying their outputs, to designing the workbenches through which they conduct science. Explore the [AI for Science workshop series]({{ '/' | relative_url }}) for previous editions.

## Follow Us

Please follow us on [X](https://x.com/AI_for_Science) and [LinkedIn](https://www.linkedin.com/company/ai-for-science/) for the latest news, or join our [Slack community](https://join.slack.com/t/aiforscience/shared_invite/zt-3z4drsyte-s~bzcT_ZGXzwf5IWWtXXwQ) for discussions.

# Organizers and Contact

For questions, please contact **Soojung Yang** ([soojungy@stanford.edu](mailto:soojungy@stanford.edu)) and **Yunhui Jang** ([yunhuijang@kaist.ac.kr](mailto:yunhuijang@kaist.ac.kr)). General community inquiries can be sent to [ai4sciencecommunity@gmail.com](mailto:ai4sciencecommunity@gmail.com).

## Organizers

{% include iclr27-team.html id="Organizers" %}

Soojung Yang is currently an Independent Postdoctoral Fellow at Stanford and FutureHouse and will join Duke University's Department of Biochemistry and Cell Biology as an assistant professor in February 2027.

## Steering Committee

{% include iclr27-team.html id="Steering_Committee" %}
