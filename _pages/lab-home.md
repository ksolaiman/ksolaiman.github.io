---
layout: single
title: "H.A.R.M.O.N.I. Lab"
permalink: /harmoni-lab/
redirect_from:
  - /lab/
  - /harmoni.lab/
---

<!-- # H.A.R.M.O.N.I. Lab -->

<!-- ### **Human-Aligned, Resilient, Multimodal, Open-ended, Novelty-Informed Intelligence**   -->
<HUGE><strong>H</strong>uman-<strong>A</strong>ligned, <strong>R</strong>esilient, <strong>M</strong>ultimodal, <strong>O</strong>pen-ended, <strong>N</strong>ovelty-informed <strong>I</strong>ntelligence</HUGE>  
*Director:* KMA Solaiman

---

## Designing AI That Endures

At the H.A.R.M.O.N.I. Lab, we design AI systems that think beyond narrow objectives — systems that **adapt, align, and reason** in complex, real-world environments. From smart grids to policy documents, from missing persons to triage prediction, our research spans multiple modalities and domains, bridging real-world applications with foundational AI challenges.

Our work is organized into **three core clusters**, each linked to active 📌 [projects](#lab-projects) and real-world [applications](#applications-we-explore):

- **Robust AI & Adaption to Novelty**  
  Detecting and reasoning about unseen or shifting inputs to ensure safe operation in dynamic settings.  
  📌 [Structure-Aware Novelty in Open-World AI](#structure-aware-novelty) • [Novelty-Aware Smart Electric Grids](#smart-electric-grid)  
  • [Unsupervised Clustering and Structure Discovery](#clustering-algos)

- **Multimodal Information Retrieval and Reasoning**  
  Aligning content across text, image, and graph modalities to enable open-world understanding.  
  📌 [Multimodal Information Retrieval and Alignment](#multimodal-information-retrieval) • [Motherboard Defect Detection](#motherboard-defect-detection)  
  • [Adaptive Prediction in Triage & Finance](#triage-and-stock-market)

- **Human-Centered Decision Systems**  
  Supporting real-world users with interpretable, context-aware AI for safety, health, and preferences.  
  📌 [Adaptive Prediction in Triage & Finance](#triage-and-stock-market) • [Human-Centered Reasoning](#human-centered-reasoning)


---

### Applications We Explore

- Electricity theft, anomaly detection, and triage in smart energy systems  
- Legal and policy document understanding  
- Intelligent triage and decision support in healthcare  
- Missing person retrieval and civic response systems  
<!-- - Mental health content support (exploratory)   -->
- Stock forecasting using news, sentiment, and historical signals  
- Fault and defect detection in hardware (e.g., motherboards)

---

## Lab Projects

{% assign sorted_projects = site.projects | sort: 'rank' %}

{% for project in sorted_projects %}
    {% include archive-project-card.html post=project %}
{% endfor %}

<!-- COMMENT: to filter (e.g., by category or tag) -->
<!-- {% for project in site.projects %}
  {% if project.website-separation-category == "c1" %}
    {% include archive-single.html post=project %}
  {% endif %}
{% endfor %} -->


## Join the Lab

We welcome students who are curious, motivated, and eager to build practical AI systems that tackle real-world complexity. Your time is valuable, and we strive to ensure that your contributions are recognized — through course credit, funding, or formal research roles.

### Who We're Looking For
- **UMBC undergraduates**, especially those interested in AI/ML, data systems, HCI, or applied computing.
- **Graduate students** pursuing thesis or project work.
- **Independent contributors** working on domain-driven or experimental projects.
- Students enrolled in or planning to take **CMSC 471, 478, or 678** with Prof. Solaiman.

---
### For UMBC Master's and Undergraduate Students

> While I currently do **not have dedicated funding** for master's or undergraduate students, I am open to supervising **independent projects** and collaborative research for credit.

I strongly prefer to **get to know students through coursework** before working together. If you're interested in joining the lab, please consider enrolling in one of my classes.  

<!-- ### Ways to Join -->

While I would like to work with many exceptional students, I may not always be able to accommodate everyone. However there are several useful resources and programs at UMBC: 

- **Research for Credit**  
  - `CMSC 499/699`: Independent Study  
  - `CMSC 698`: Project in Computer Science  
  - `CMSC 799`: Master's Thesis

- **Funded Undergraduate Opportunities** *(UMBC-specific)*  
  - [URA – Undergraduate Research Awards](https://ur.umbc.edu/ura/)  
  - [URCAD – Research Day Presentations](https://ur.umbc.edu/urcad/)  
  - [SURF – Summer Undergraduate Research](https://ur.umbc.edu/summer-research-opportunities/)  
  - [Goldwater Scholarship](https://goldwater.scholarsapply.org/)  

- **Funded Graduate Fellowships** *(external)*  
  - [NSF CSGrad4US Fellowship](https://www.nsf.gov/careers/graduate/csgrad4us.jsp)  
  - [NSF Graduate Research Fellowship Program (GRFP)](https://www.nsfgrfp.org/)

- **Cross-Faculty Collaboration**  
  If you're funded through another PI, we welcome joint mentorship and interdisciplinary project involvement.

<small>*Courtesy: List based off of [Dr. Tejas Gokhale’s](https://www.tejasgokhale.com/faq.html) FAQ.*</small>

---

### Collaborations
We collaborate across campus and beyond:
- **UMBC Center for AI**
- **University of Maryland Medical Center (UMMC)**
- **UMB School of Pharmacy (SOP)**
- **Purdue University**
- Past partnerships: **MIT, NGC, DARPA, USC-ISI**

---

### Contact

**KMA Solaiman**  
Assistant Teaching Professor, CSEE, UMBC  
Director, H.A.R.M.O.N.I. Lab  
📧 [ksolaima@umbc.edu](mailto:ksolaima@umbc.edu)  
🌐 [Lab Website](https://ksolaiman.github.io/harmoni-lab/)

> If you're driven by curiosity and care about the real-world impact of AI, we’d love to hear from you.
