---
layout: archive
title: "Research"
permalink: /publications/
author_profile: true

---
<!-- 
# Welcome to My Research Website! 👋
-->
I actively seek any potential research opportunities and also look forward to exploring diverse areas. I will share details of my past projects here. 👩‍💻


## Cosmological Simulation of Large-Scale Structure
### Advisor: [Qiao Wang](https://nao.cas.cn/jypy/ds/ssds/202204/t20220406_6419582.html)
### 01/2025 - Present

<p>    

As the fundamental building blocks of the large-scale structure of the Universe, dark matter halos are typically located on filaments or at their junctions, though some reside in lower-density voids. The galaxies we observe often form within these halos. Consequently, studying dark halos can deepen our understanding of galaxy evolution, while the study of galaxies, in turn, can constrain halo properties and thus inform dark matter models. In this study, I focus on several commonly discussed properties of dark halos, such as density profile, mass function, among others.
</p>

***

## Spectroscopy of one H II region in the external galaxy NGC 0925
### Advisor: [Yewei Mao](https://spee.gzhu.edu.cn/info/1681/18121.htm)
### 05/2024 - 11/2024

H II regions are where star formation takes place in the galaxy, characterized by a series of emission lines in their spectra. Spectral observation and analysis are the primary methods used to study the properties of H II regions. Using the 2.16-meter telescope at the [National Astronomical Observatories of China](https://english.nao.cas.cn/), we carried out spectral observations and analysis of an H II region in the galaxy NGC 0925. Based on the obtained emission line spectrum, the Balmer Decrement method was applied to determine the intrinsic extinction of the region (A（V） = 0.630 mag), followed by extinction corrections. Further analysis revealed that the H II region exhibits high star formation activity. The star formation rate surface density, derived from the Hα emission line luminosity, is ΣSFR = 0.084 M⊙ yr⁻¹ kpc⁻². Additionally, the strong emission line method indicated its high metallicity, with an oxygen abundance of 12+log(O/H) = 8.293 dex. These findings suggest that this region is a star-forming area with significant dust extinction, active star formation, and rich mental enrichment.

<div align = "center">    
<img  src="https://github.com/panweixuan/site/blob/master/files/The%20spectrum%20for%20the%20target%20H%20ll%20region.png?raw=true" width="40%" />
<img  src="https://github.com/panweixuan/site/blob/master/files/Physical%20Parameter%20Measurement%20Results.png?raw=true" width="40%" />
</div>


<!-- 
<img align = "center" src="https://github.com/panweixuan/site/blob/master/files/The%20spectrum%20for%20the%20target%20H%20ll%20region.png?raw=true" width=500 height=300 />
<img align = "center" src="https://github.com/panweixuan/site/blob/master/files/Physical%20Parameter%20Measurement%20Results.png?raw=true"  width=500 />
-->




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
