---
title: Home
---

# EANBiT Residential Training 2019 

{% include figure.html img="uidaho-workshop.jpg" alt="intro image here" caption="Library workshop" width="75%" %}


The Eastern Africa Network for Bioinformatics Training (EANBiT) will conduct an intensive 6-
week bioinformatics residential course to be hosted by the International Centre of Insect
Physiology and Ecology, icipe in Nairobi, Kenya and Pwani University, Kilifi, Kenya from **01st
July – 09th August 2019.**

This training aims at strengthening bioinformatics technical capacity and skills among the
participants; preparing them to work as bioinformaticians and to become project ready so that
they have the necessary skills to offer bioinformatics support in projects they are attached to.

The topics covered include:
Key topics to be covered include:

- Version control and collaborative development (Git & Github & Slack etc.)
- Advanced Scripting
- Biological databases and API
- Gene models and annotation
- Reproducibility and package management: workflow languages (CWL, Snakemake,
Conda)
- Specialized databases (VectorBase, EupathDB) and APIs
- Phylogenomics (Visualization and Annotation)

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}} (get [source code]({{ site.repo }})).
> Last build date: {{ site.time | date: "%Y-%m-%d" }}.
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
