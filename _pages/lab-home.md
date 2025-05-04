---
layout: single
title: "H.A.R.M.O.N.I. Lab"
permalink: /lab/
---

<!-- # H.A.R.M.O.N.I. Lab -->

<!-- ### **Human-Aligned, Resilient, Multimodal, Open-ended, Novelty-Informed Intelligence**   -->
<Huge><strong>H</strong>uman-<strong>A</strong>ligned, <strong>R</strong>esilient, <strong>M</strong>ultimodal, <strong>O</strong>pen-ended, <strong>N</strong>ovelty-Informed <strong>I</strong>ntelligence</Huge>  

*Director:* KMA Solaiman

---

## Designing AI That Endures

At the H.A.R.M.O.N.I. Lab, we design AI systems that think beyond narrow objectives — systems that **adapt, align, and reason** in complex, real-world environments. From smart grids to policy documents, from missing persons to triage prediction, our research spans multiple modalities and domains, bridging real-world applications with foundational AI challenges.

Our work is organized into **three core clusters**, each with its ongoing 📌 [Projects](#projects) and real-world [Applications](#applications-we-explore):

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

## Projects

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


<!-- **Human-AI Interaction and Intent Modeling**   -->
<!-- Plant Matching
T&C modeling -->


## For Students

We welcome contributions from **UMBC undergraduates**, **independent study students**, and graduate students interested in AI research.

You may join the lab through:
- CMSC 499 / 699 / 799 research credits  
- Independent project work  
- Senior/honors thesis  
- Poster research under course mentoring (CMSC 471/478)

Recommended: background in Python and prior exposure to ML, AI, or data systems.  
Passion for experimental thinking and system design is more important than prior publications.

To inquire, email: [ksolaima@umbc.edu](mailto:ksolaima@umbc.edu)

---

## Collaborations

We collaborate with researchers and teams across:
- UMBC Center for AI  
- University of Maryland Medical Center (UMMC)  
- School of Pharmacy (SOP), public health, and AI/ML researchers  
- NSA/UMBC professional education initiatives  
- Former collaborators: MIT, NGC, DARPA SAIL-ON, USC-ISI

---

## Contact

KMA Solaiman  
Assistant Teaching Professor, CSEE, UMBC  
Director, H.A.R.M.O.N.I. Lab  
📧 [ksolaima@umbc.edu](mailto:ksolaima@umbc.edu)  
🔗 [Main Website](/) · [Teaching](/teaching/) · [Publications](/publications/)


### Collaborate With Us

We welcome students, faculty, and collaborators who are curious, mission-driven, and excited about AI that makes sense of a messy world.

[Contact us](mailto:ksolaima@umbc.edu) | [Visit our site](https://ksolaiman.github.io)
