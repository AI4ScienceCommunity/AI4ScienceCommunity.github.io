---
layout: default
title: "AI for Science: Theories and Foundations"
permalink: /icml22


speakers:

  - name: Anima Anandkumar
    url: http://tensorlab.cms.caltech.edu/users/anima/
    topic: 
    aff: Caltech
    interest: AI, Chemistry
    image: assets/images/anima.png

  - name: Anthony Gitter
    url: https://www.biostat.wisc.edu/~gitter/
    topic: 
    aff: UW-Madison
    interest: AI, Biology
    image: assets/images/tony.jpeg

  - name: Carla P. Gomes
    url: https://www.cs.cornell.edu/gomes/
    topic: 
    aff: Cornell
    interest: AI, Sustainability
    image: assets/images/carla.png

  - name: Rafael Gomez-Bombarelli
    url: http://gomezbombarelli.mit.edu/
    topic: 
    aff: MIT
    interest: AI, Material
    image: assets/images/rafael.jpeg

  - name: Jiequn Han
    url: https://users.flatironinstitute.org/~jhan/
    topic: 
    aff: Flatiron Institute
    interest: AI, Mathematics
    image: assets/images/jiequn.jpeg

  - name: Daphne Koller 
    url: https://www.linkedin.com/in/daphne-koller-4053a820/
    topic:
    aff: Insitro 
    interest: AI, Drug
    image: assets/images/daphne.jpeg

  - name: Frank Noe
    url: http://www.mi.fu-berlin.de/en/math/groups/ai4s
    topic: 
    aff: FU Berlin
    interest: AI, Physics
    image: assets/images/frank.jpeg

  - name: Max Tegmark
    url: https://space.mit.edu/home/tegmark/
    topic: 
    aff: MIT
    interest: AI, Physics
    image: assets/images/max.jpeg

StudentOrganizers:
  - name: Yuanqi Du (DP Technology)
    url: https://yuanqidu.github.io/

  - name: Tianfan Fu (Gatech)
    url: https://futianfan.github.io/

  - name: Wenhao Gao (MIT)
    url: https://scholar.google.com/citations?user=s4eywrUAAAAJ&hl=en

  - name: Kexin Huang (Stanford)
    url: https://www.kexinhuang.com/

  - name: Shengchao Liu (MILA)
    url: https://chao1224.github.io/

  - name: Ziming Liu (MIT)
    url: https://kindxiaoming.github.io/

  - name: Hanchen Wang (Cambridge)
    url: https://hansen7.github.io/


ProfessorOrganizers:

  - name: Connor Coley (MIT)
    url: https://cheme.mit.edu/profile/connor-w-coley/

  - name: Le Song (BioMap)
    url: https://scholar.google.com/citations?user=Xl4E0CsAAAAJ&hl=en

  - name: Linfeng Zhang (DP Technology)
    url: https://scholar.google.com/citations?user=jk7qwmcAAAAJ&hl=zh-CN

  - name: Marinka Zitnik (Harvard)
    url: https://zitniklab.hms.harvard.edu
---

## About

For centuries, the method of discovery—the fundamental practice of science that scientists use to explain the natural world systematically and logically—has remained largely the same. Artificial intelligence (AI) and machine learning (ML) hold tremendous promise in having an impact on the way scientific discovery is performed today at the fundamental level. However, to realize this promise, we need to identify priorities and outstanding open questions for the cutting edge of AI going forward. We are particularly interested in the following topics:

- ** Boosting Scientific Simulation/Calculation with AI & ML**

- ** Responsible use and development of AI for science**

- ** Learning Scientific Meaningful Representations**

- ** Theory and Foundations**

## Invited Talks (In alphabetical order)

{% include team.html id="speakers" %}


# Important Dates (Anywhere on Earth)

- Abstract Deadline: May 16, 2022
- Submission Deadline: May 23, 2022
- Author Notification: June 13, 2022

## Follow Us

Please follow us on [Twitter](https://twitter.com/AI_for_Science) & [LinkedIn](https://www.linkedin.com/company/ai-for-science/) for updates; also join [Slack](https://join.slack.com/t/ai4sciencecommunity/shared_invite/zt-15rtaehdi-we~H~LhzZqrQTy6RtLGtug) for active discussions.



## Organizers and Contact

Organizers are in the alphabetical order. For any question, please [send us an email](mailto:ai4sciencecommunity@gmail.com)!


<ul>
{% for p in page.StudentOrganizers %}
<li>
<a{% if p.url %} href="{{ p.url }}"{% endif %}>{{ p.name }}</a>
</li>
{% endfor %}
</ul>



<ul>
{% for p in page.ProfessorOrganizers %}
<li>
<a{% if p.url %} href="{{ p.url }}"{% endif %}>{{ p.name }}</a>
</li>
{% endfor %}
</ul>
