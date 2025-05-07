---
permalink: /
title: "" # "About"
# excerpt: "About me"
layout: archive         # single        # most probably
# if you use 'archive' layout it spreads full page to right
# 'about' is custom created layout, just cleaned from single now
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

 <!-- # **KMA Solaiman**   -->
<!-- **Assistant Teaching Professor**  
[Department of Computer Science & Electrical Engineering](https://csee.umbc.edu)  
[University of Maryland, Baltimore County (UMBC)](https://umbc.edu) -->

<!-- **Director**, [H.A.R.M.O.N.I. Lab](https://ksolaiman.github.io/harmoni-lab/)   -->

<!-- --- -->

<!-- I work at the intersection of multimodal learning, open-world reasoning, and data-centric AI for real-world decision-making.  -->
At UMBC, I design and teach core AI and Machine Learning courses while leading research at the intersection of multimodal learning, open-world reasoning, and data-centric AI for real-world decision-making. 
My research focuses on enabling AI systems to reason under **uncertainty**, adapt to dynamic environments, and serve critical real-world missions.

At UMBC, I lead the [**H.A.R.M.O.N.I. Lab**](https://ksolaiman.github.io/harmoni-lab/) — 
**H**uman-**A**ligned, **R**esilient, **M**ultimodal, **O**pen-ended, **N**ovelty-Informed **I**ntelligence. We design AI systems that adapt, align, and **endure** — systems that operate safely in uncertain environments like smart energy, public health, and civic tech. 
<!-- Our research blends **machine learning**, **multimodal retrieval**, and **open-world learning**, always with an eye toward **real-world impact**. -->

I earned my Ph.D. and M.Sc. in Computer Science from [Purdue University](https://www.purdue.edu), working with [Prof. Bharat Bhargava](https://www.cs.purdue.edu/people/faculty/bbshail.html) and collaborating with [Prof. Michael Stonebraker](https://www.csail.mit.edu/person/michael-stonebraker) on DARPA and Northrop Grumman–funded projects.
My work has appeared in top venues like VLDB, SIGMOD, AAAI, and IEEE Journals, and I’ve collaborated with institutions including MIT, USC-ISI, and West Lafayette Police Department.

<small><em>Fun fact:</em> At UMBC, people know me as **Khaled**. I also go by **Salvi** — a name derived from *salve*, meaning healing — which reflects the mission behind our lab.</small>

---
<div class="news-title">NEWS</div>
<div class="news-slider">
  <ul class="news-list">
    {% assign sorted_news = site.data.news | sort: "date" | reverse %}
    {% for item in sorted_news %}
      <li class="{% if forloop.first %}highlight{% endif %}">
        <strong>{{ item.date }}</strong>&nbsp;&nbsp;&nbsp;—&nbsp;&nbsp;&nbsp;{{ item.text }}
      </li>
    {% endfor %}
  </ul>
</div>


---


<!-- ## Acedemic Service
 - Program committee member ECML-PKDD 2023, ECML-PKDD 2022
 - Volunteer in NeurIPS 2022
 - PC Member in IEEE PIMRC 2019 -->


<!-- * [Profile](https://scholar.google.com/citations?user={{ site.data.scholar.id }})
* Citations: {{ site.data.scholar.citations }}
* h-index: {{ site.data.scholar.h_index }}
* i10-index: {{ site.data.scholar.i10_index }} -->
