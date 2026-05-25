---
layout: neurips26
title: "Verifications in the Age of AI Scientists"
permalink: /neurips26


speakers:
    
  - name: Mario Krenn
    url: https://www.artificial-scientist-lab.ai/
    aff: University of Tübingen
    interest: AI, Physics 
    image: assets/images/mario.png

  - name: Teresa Head-Gordon
    url: https://thglab.berkeley.edu/
    aff: UC Berkeley
    interest: AI, Chemistry
    image: assets/images/teresa.jpeg

  - name: Anna Scaglione
    url: https://sinelab.tech.cornell.edu/
    aff: Cornell
    interest: AI, Power System
    image: assets/images/anna.jpeg

  - name: Adam Zsolt Wagner
    url: https://zawagner22.github.io/
    aff: Google DeepMind
    interest: AI, Mathematics
    image: assets/images/adam.jpeg

  - name: Charlotte Deane
    url: https://www.stats.ox.ac.uk/~deane/
    aff: Oxford
    interest: AI, Biology
    image: assets/images/charlotte_deane.jpg

  - name: Amanda Barnard
    url: https://comp.anu.edu.au/people/amanda-barnard/
    aff: Australian National University
    interest: AI, Healthcare
    image: assets/images/amanda.jpeg
  


Panelist:

  # - name: Max Welling (Moderator)
  #   url: https://staff.fnwi.uva.nl/m.welling
  #   aff: CuspAI
  #   interest: 
  #   image: assets/images/max.png 

  - name: Marinka Zitnik (Moderator)
    url: https://zitniklab.hms.harvard.edu
    aff: Harvard
    interest: 
    image: assets/images/marinka.png  

  - name: David Rolnick
    url: https://davidrolnick.com/
    aff: McGill and Mila
    interest: AI, Climate Science
    image: assets/images/david_rolnick.jpeg

  - name: Rianne van den Berg
    url: https://www.microsoft.com/en-us/research/people/rvandenberg/
    aff: Microsoft Research
    interest: AI, Chemistry
    image: assets/images/rianne.jpeg

  - name: Cheng Soon Ong
    url: https://www.ong-home.my/
    aff: CSIRO and Australian National University
    interest: AI, Science
    image: assets/images/cheng.jpeg

  # - name: Priya Donti
  #   url: https://priyadonti.com/
  #   aff: MIT
  #   interest: AI, Climate Science
  #   image: assets/images/priya.jpg


Organizers:

  # - name: Max Welling
  #   url: https://staff.fnwi.uva.nl/m.welling
  #   aff: CuspAI
  #   interest: 
  #   image: assets/images/max.png 

  - name: Marinka Zitnik
    url: https://zitniklab.hms.harvard.edu
    aff: Harvard
    interest: 
    image: assets/images/marinka.png  
    
  - name: Priya Donti
    url: https://priyadonti.com/
    aff: MIT
    interest: 
    image: assets/images/priya.jpg
    
  - name: Yuanqi Du
    url: https://yuanqidu.github.io/
    aff: Microsoft Research 
    interest: 
    image: assets/images/yuanqi.png 
  
  - name: Ada Fang
    url: https://scholar.google.com/citations?user=f40sqL8AAAAJ&hl=en 
    aff: Harvard
    interest: 
    image: ./assets/images/ada.jpg 

  - name: Anvita Bhagavathula
    url: https://a-bhagava.github.io/
    aff: MIT
    interest: 
    image: ./assets/images/anvita.jpeg 
  
  - name: Ana Rivera
    url: https://eesg.mit.edu/ana-rivera
    aff: MIT
    interest:
    image: ./assets/images/ana.png 
  
  - name: Emilien Dupont
    url: https://emiliendupont.github.io/
    aff: Google DeepMind
    interest: 
    image: ./assets/images/emilien.jpeg





---

# About

AI Scientists now operate at a scale that outpaces human capacity for manual review. Systems such as Sakana's AI Scientist write entire workshop papers end-to-end. Lila Sciences runs autonomous ``AI Science Factories'' that hypothesize, experiment, and iterate without human guidance. FutureHouse's Kosmos and Robin generate thousands of candidate hypotheses in a single run, and Google's Co-Scientist proposes testable experiments at a rate no laboratory can fully evaluate. 
Each of these systems emphasizes *verified* results, yet that standard ranges from near-perfect formal proof in mathematics to decade-long clinical trials in medicine, with no shared framework for judging sufficiency across domains. As outputs scale beyond what humans can manually inspect, the question of which results to trust becomes as hard as generating them. *The bottleneck for AI for Science is no longer hypothesis generation, it is verification*.

Our NeurIPS 2026 workshop, *Verification in the Age of AI Scientists*, asks how we should trust, judge, and act on AI-generated science when verifiers are imperfect, scarce, or absent. In most sciences the verifier itself is imperfect or prohibitively expensive, and as AI Scientists scale beyond what humans can manually inspect, the central problem becomes *which AI outputs deserve our scarce verification budget, and on what evidence we should be willing to act*. We organize our discussion around three challenges.

* **Verification in open-ended hypothesis generation** When AI Scientists propose thousands of candidate hypotheses, only a small fraction can ever be tested, and not all plausible outputs are scientifically meaningful, novel, or worth pursuing. Subtle failure modes such as data leakage, benchmark gaming, and hallucinated citations can make an output look verified without being so, and human taste, intuition, and domain expertise remain essential filters that are not yet well understood as learnable verifiers. This workshop asks how to build verifiers that can separate genuinely novel scientific contributions from convincing artifacts.

* **Verification under imperfect simulators** Scientific domains differ dramatically in the reliability of their verifiers. In mathematics, formal systems such as Lean provide near-perfect verification, but in biology, force fields fail outside their training distribution and structure prediction has well-documented blind spots , while climate models depend on partial observations and expert judgment. This workshop asks when surrogate verifiers can substitute for ground truth, and on what evidence AI Scientists should be willing to act when the two disagree.

* **Verification under real-world constraints (uncertainty & safety)** In practice, verification is bounded by time, cost, experimental throughput, and safety. A single Phase III clinical trial costs hundreds of millions of dollars and takes a decade, and in extreme weather prediction, rare out-of-distribution events drive evacuation and infrastructure decisions before sufficient evidence can be gathered. This workshop asks how scarce verification resources should be allocated across competing AI-generated hypotheses when downstream decisions affect human lives.

<!-- ## New Dataset Proposal Competition

We use [the NeurIPS 2026 LaTeX template](https://media.neurips.cc/Conferences/NeurIPS2026/Styles.zip) (**Note** that you do not need to attach the NeurIPS checklist). Please change the footnote to Submitted to/Accepted at/Published in the AI for Science workshop (NeurIPS 2026). Check details on [this page](/neurips25/dataset.html). -->

## Follow Us

Please follow us on [X](https://x.com/AI_for_Science) and [LinkedIn](https://www.linkedin.com/company/ai-for-science/) for the latest news, or join us on the [Slack](https://join.slack.com/t/aiforscience/shared_invite/zt-3eferk1xy-vIDrgaBCdpXfCKmQs9WH0g) for active discussions.

## AI for Science Party

Detailed information to be posted. 
<!-- We are hosting a party for the community, check the registration link [here](https://partiful.com/e/IDy23TR5e14Dz4L3hatk?). -->

# Invited Talks 

{% include team.html id="speakers" %}

# Panel: The Verification Gap: Abundant Hypotheses, Scarce Verifiers

{% include team.html id="Panelist" %}


# Tentative Dates (Anywhere on Earth)

- Abstract Submission Deadline: Aug 22, 2026 
- Paper Submission Deadline: Aug 25, 2026
- Review Bidding Period: Aug 25-27, 2026
- Review Deadline: Sep 19, 2026
- Acceptance Notification Date: Sep 22, 2026
- Workshop Date: Dec 7, 2026



## Submissions 

Please submit your paper on [Openreview](https://openreview.net/group?id=NeurIPS.cc/2026/Workshop/AI4Science). Our workshop is **nonarchival**, the accepted papers will be posted on our website. We use [the template from NeurIPS 2026](https://media.neurips.cc/Conferences/NeurIPS2026/Styles.zip) (**Note** that you do not need to attach the NeurIPS checklist). Please change the footnote to Submitted to/Accepted at/Published in the AI for Science workshop (NeurIPS 2026). The submissions are expected to be 4-8 pages with unlimited references and appendices. For more detials, please check [the Call for Papers page](/neurips25/call.html).

## Call for Reviewers/Area Chairs

We are calling for active researchers in the field to help with our review process. Here are the [reviewer](https://docs.google.com/forms/d/e/1FAIpQLSff7J0JVJ_oXEARMagWYB6a6wSNifjY7rl50eODT4xwm8vPRw/viewform) and [area chair](https://docs.google.com/forms/d/e/1FAIpQLSfYbGfWTtMFRe5fKdC2HrIOgnKXsfupLjV0z-Zzf1g0HNzkhA/viewform) sign up forms.

## Frequent Q&A

- What is the abstract deadline and why do we have it?
- You only need to create a submission tab on OpenReview by the abstract deadline. (**This is not a separate submission track for short papers**). As we receive a large volume of diverse submissions, to entire good review quality and coverage of reviewer areas, we keep an abstract deadline for us to have a chance to invite new reviewers if needed.

- Can I attend the workshop even if I don't have any submissions?
- Yes, you are welcome to attend the workshop. Registration is through NeurIPS 2026 registration system with workshop selected. 

- Can I join the organizing team?
- We always welcome new members to join our organizing team, feel free to reach out to us if you are interested. Several questions are recommended to be answered to help us make decision: what do you like about the workshop? what do you think we should improve? what can you contribute to the organizing team?



# Organizers and Contact

For any question, please contact [ai4sciencecommunity@gmail.com](mailto:ai4sciencecommunity@gmail.com).


## Organizers 

{% include team.html id="Organizers" %}









