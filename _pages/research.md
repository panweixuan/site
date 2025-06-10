---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true

---
<!-- 
# Welcome to My Research Website! 👋
-->


## Cosmological Simulation of Large-Scale Structure
### Advisor: [Qiao Wang](https://nao.cas.cn/jypy/ds/ssds/202204/t20220406_6419582.html)
### 01/2025 - Present

As the fundamental building blocks of the large-scale structure of the Universe, dark matter halos are typically located on filaments or at their junctions, though some reside in lower-density voids. The galaxies we observe often form within these halos. Consequently, studying dark halos can deepen our understanding of galaxy evolution, while the study of galaxies, in turn, can constrain halo properties and thus inform dark matter models. In this study, I focus on several commonly discussed properties of dark halos, such as density profile, mass function, among others.
![Density Profiles of the Largest 10 Halos](https://github.com/panweixuan/site/blob/master/files/Density%20Profilne.png?raw=true){: style="width: 35%; max-width: 450px; height: auto; float: left;"}


***

## Spectroscopy of one H II region in the external galaxy NGC 0925
### Advisor: [Yewei Mao](https://spee.gzhu.edu.cn/info/1681/18121.htm)
### 05/2024 - 11/2024

H II regions are where star formation takes place in the galaxy, characterized by a series of emission lines in their spectra. Spectral observation and analysis are the primary methods used to study the properties of H II regions. Using the 2.16-meter telescope at the [National Astronomical Observatories of China](https://english.nao.cas.cn/), we carried out spectral observations and analysis of an H II region in the galaxy NGC 0925. Based on the obtained emission line spectrum, the Balmer Decrement method was applied to determine the intrinsic extinction of the region (A（V） = 0.630 mag), followed by extinction corrections. Further analysis revealed that the H II region exhibits high star formation activity. The star formation rate surface density, derived from the Hα emission line luminosity, is ΣSFR = 0.084 M⊙ yr⁻¹ kpc⁻². Additionally, the strong emission line method indicated its high metallicity, with an oxygen abundance of 12+log(O/H) = 8.293 dex. These findings suggest that this region is a star-forming area with significant dust extinction, active star formation, and rich mental enrichment.





{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
