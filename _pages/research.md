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

## Effects of Dark-Matter Halo Properties on the Stability of Disk Galaxies
### Advisor: [Shi Shao](https://nao.cas.cn/jypy/ds/bsds/202301/t20230110_6598174.html)
### 07/2025 - Present

<div style="position: relative; padding-bottom: 56.25%; height: 0; overflow: hidden; max-width: 100%; text-align:center;">
  <iframe 
      src="https://www.youtube.com/embed/KEE4Pc2SDng"
      title="YouTube video player"
      frameborder="0"
      allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share"
      allowfullscreen
      style="position: absolute; top: 0; left: 0; width: 70%; height: 80%; margin-left: 10%;">
  </iframe>
</div>
***


## Dust Attenuation Fitting and Analysis
### Advisor: [Yewei Mao](https://spee.gzhu.edu.cn/info/1681/18121.htm)
### 05/2025 - Present

<p>    
<img src="https://github.com/panweixuan/site/blob/master/files/M81SED.png?raw=true" width=500 align="right"  />
</p>

Dust grains absorb ultraviolet and visible photons, creating a characteristic "UV bump" feature around 2175Å linked to organic particles like PAHs. Without correcting for dust effects, key galactic physical parameters such as stellar formation rates and masses can be significantly misestimated, making it crucial to understand galactic attenuation properties.

I investigated the attenuation properties of spiral galaxy M81. Initially, I constructed a 17-band SED from ultraviolet to mid-infrared and fitted it using a two-component power-law intrinsic model combined with 3 attenuation curves. The Milky Way type performed best with a reduced χ² ≈ 7.3, indicating that M81's attenuation characteristics are more consistent with Milky Way-type dust than with bump-deficient extragalactic environments.

I presented a flash talk in our department to report my research findings. [Click here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fpanweixuan%2Fsite%2Frefs%2Fheads%2Fmaster%2Ffiles%2FWeixuan_M81AttCurv.pptx&wdOrigin=BROWSELINK) to view my slide.

More recently, I conducted a Bayesian SED fitting analysis of M81 using the [BAGPIPES](https://github.com/ACCarnall/bagpipes) program. I employed the Salim dust attenuation model, performing separate fits with and without the UV bump feature. The Bayesian evidence favored the no-bump model with ΔlnZ = -1.539 ± 0.273. 

This analysis reveals the inherent limitations in current photometric constraints on M81's UV bump strength, with both statistical methods producing uncertain conclusions about the galaxy's dust attenuation properties.

[Click here](https://view.officeapps.live.com/op/view.aspx?src=https%3A%2F%2Fraw.githubusercontent.com%2Fpanweixuan%2Fsite%2Frefs%2Fheads%2Fmaster%2Ffiles%2FWeixuan_M81AttBp.pptx&wdOrigin=BROWSELINK) for a quick overview of this new result.

***


## Cosmological Simulation of Large-Scale Structure
### Advisor: [Qiao Wang](https://english.nao.cas.cn/sourcedb/people/202103/t20210325_339201.html)
### 09/2024 - 07/2025

[Report](https://panweixuan.github.io/site//files/LSS_Report.pdf) 
<p>    
<img src="https://github.com/panweixuan/site/blob/master/files/halo_profile.png?raw=true" width=500 align="right"  />
As the fundamental building blocks of the large-scale structure of the Universe, dark matter halos are typically located on filaments or at their junctions, though some reside in lower-density voids. The galaxies we observe often form within these halos. Consequently, studying dark halos can deepen our understanding of galaxy evolution, while the study of galaxies, in turn, can constrain halo properties and thus inform dark matter models. In this study, I focus on several commonly discussed properties of dark halos, such as density profile, mass function, among others.
</p>

<div align = "center"> 
<img  src="https://github.com/panweixuan/site/blob/master/files/halo_hmf.png?raw=true" width="60%" height=1300/>
<img  src="https://github.com/panweixuan/site/blob/master/files/halo_2pcf.png?raw=true" width="30%"  height=500/>
</div>

***

## Spectroscopy of one H II region in the external galaxy NGC 0925
### Advisor: [Yewei Mao](https://spee.gzhu.edu.cn/info/1681/18121.htm)
### 05/2024 - 11/2024

H II regions are where star formation takes place in the galaxy, characterized by a series of emission lines in their spectra. Spectral observation and analysis are the primary methods used to study the properties of H II regions. Using the 2.16-meter telescope at [the Xinglong Observatory of the National Astronomical Observatories](http://www.xinglong-naoc.cn/html/en/), we carried out spectral observations and analysis of an H II region in the galaxy NGC 0925. 

Based on the obtained emission line spectrum, the Balmer Decrement method was applied to determine the intrinsic extinction of the region (A（V） = 0.630 mag), followed by extinction corrections. Further analysis revealed that the H II region exhibits high star formation activity. The star formation rate surface density, derived from the Hα emission line luminosity, is ΣSFR = 0.084 M⊙ yr⁻¹ kpc⁻². Additionally, the strong emission line method indicated its high metallicity, with an oxygen abundance of 12+log(O/H) = 8.293 dex. These findings suggest that this region is a star-forming area with significant dust extinction, active star formation, and rich mental enrichment.

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
