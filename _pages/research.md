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

<table>
<tr>
<td width="50%">

H II regions are where star formation takes place in the galaxy, characterized by a series of emission lines in their spectra. Spectral observation and analysis are the primary methods used to study the properties of H II regions. Using the 2.16-meter telescope at the National Astronomical Observatories of China, we carried out spectral observations and analysis of an H II region in the galaxy NGC 0925. Based on the obtained emission line spectrum, the Balmer Decrement method was applied to determine the intrinsic extinction of the region (A（V） = 0.630 mag), followed by extinction corrections. Further analysis revealed that the H II region exhibits high star formation activity. The star formation rate surface density, derived from the Hα emission line luminosity, is ΣSFR = 0.084 M⊙ yr⁻¹ kpc⁻². Additionally, the strong emission line method indicated its high metallicity, with an oxygen abundance of 12+log(O/H) = 8.293 dex. These findings suggest that this region is a star-forming area with significant dust extinction, active star formation, and rich mental enrichment.

</td>
<td width="50%">

![The spectrum for the target HIll region](https://panweixuan.github.io/site//files/The%20spectrum%20for%20the%20target%20H%20ll%20region.png)
<br>
<div align="center">
<small>The black lines in the figure represent spectra in which the main spectral emission lines have been labelled.</small>
</div>

</td>
</tr>
</table>
<hr style="height:5px">

## Spectroscopy of one H II region in the external galaxy NGC 0925
### Advisor: [Yewei Mao](https://spee.gzhu.edu.cn/info/1681/18121.htm)
### 05/2024 - 11/2024

H II regions are where star formation takes place in the galaxy, characterized by a series of emission lines in their spectra. Spectral observation and analysis are the primary methods used to study the properties of H II regions. Using the 2.16-meter telescope at the [National Astronomical Observatories of China](https://english.nao.cas.cn/), we carried out spectral observations and analysis of an H II region in the galaxy NGC 0925. Based on the obtained emission line spectrum, the Balmer Decrement method was applied to determine the intrinsic extinction of the region (A（V） = 0.630 mag), followed by extinction corrections. Further analysis revealed that the H II region exhibits high star formation activity. The star formation rate surface density, derived from the Hα emission line luminosity, is ΣSFR = 0.084 M⊙ yr⁻¹ kpc⁻². Additionally, the strong emission line method indicated its high metallicity, with an oxygen abundance of 12+log(O/H) = 8.293 dex. These findings suggest that this region is a star-forming area with significant dust extinction, active star formation, and rich mental enrichment.



<!-- 
## Alternative evolutionary pathway for stellar population by orbit modeling ⭐
### Advisor: [Robert Mathieu](https://www.astro.wisc.edu/?uw_staff=mathieu-robert)
### Started 05/2023 - 06/2024
### [Astrobites](https://astrobites.org/2024/07/03/ur-blue-stars-that-should-not-exist/)
![BSS_HR](https://yanbopanpi.github.io/yanbo_pan.github.io//images/BSS_HR.png){: style="width: 50%; max-width: 450px; height: auto; float: right;"}
Blue Straggler Stars (BSS) are believed to have originated from binary star interactions. Therefore, modeling binary orbits is crucial for understanding their formation and evolution. In this study, we applied The Joker (a Monte Carlo rejection sampler) to model binary orbits in the WIYN Open Cluster Survey (WOCS). Our objective was to evaluate The Joker’s efficacy on binaries with ample radial-velocity data (RVD). Exploring the potential usage of The Joker, designed for sparsely measured radial velocities, we applied it to known single-lined binary orbits in M67 and NGC 188. With 70+ binary systems, we compared our Joker orbital parameters among binaries having a diverse array of period-eccentricity combinations (Geller et al. 2021). We found that 5-7 RVD start to meaningfully constrain orbital parameters, and 8-10 RVD are required for unimodal period solutions with eccentricities converging to previous studies’ solutions. Additionally, we explored the possibility of devising observing plans having limited prior measurements with The Joker predicting possible periastron approach times to constrain eccentricity. This work enables us to estimate binary orbital solutions with fewer RVD and to enhance our understanding of the alternative evolutionary tracks of binary systems.

For our future work, we will fit more binary solutions for WD-MS binaries, while improving the pipeline to better suit observation plans and reduce bias our priors might introduce. This study is also used to design future observation plans to break the degeneracies between possible orbits. 
-->
<!---
Through this research experience, I learned about rejection and MCMC sampling. Exposed to time-series radial-velocity data for the first time, I designed a custom pipeline that allows statistical comparison between our results and previous scientific results done by [Aaron M. Geller](https://arxiv.org/abs/2101.07883). I also become more familiar with using cloud computing and virtual machines. 
![binary_demo](https://yanbopanpi.github.io/yanbo_pan.github.io//images/binary_demo.jpg){: style="width: 50%; max-width: 450px; height: auto; float: left;"}
*image credit: Aaron Geller* 
!--->

<!---
## Mining Ultra-Faint Galaxies in the Local Group 🌌
### Advisor: [Eric Bell](https://sites.lsa.umich.edu/ericbell/)
### 01/2023 - 05/2024
![star_galaxy](https://yanbopanpi.github.io/yanbo_pan.github.io//images/star_galaxy_classification.png){: style="width: 50%; max-width: 450px; height: auto; float: right;"}

By analyzing the stellar spatial distribution, we try to search for potential ultra-faint dwarf (UFD) galaxies of M31 by examining stellar overdensities within the DELVE survey. We attempt to search for overdensities for horizontal branch (HB) and red giant branch stars (RGB) using Density-Based Spatial Clustering of Applications with Noise (DBSCAN). We first focused on Pegasus IV dwarf galaxy and its stellar population as a guide for designing our overdensity search pipeline. With the detected overdensities on the color-magnitude diagram, we also explore the stellar overdensities regarding their spatial distribution. 

Ultra-faint dwarf (UFD) satellite galaxies are believed to have the oldest, most dark-matter-dominated, and least chemically evolved stellar populations. Therefore, UFDs serve as effective cosmological probes for the early stage of the Universe. In this study, we applied unsupervised machine learning (DBSCAN & OPTICS) to search for potential UFDs by analyzing spatial overdensities of the tip of red giant branch (TRGB) stars in the DELVE survey. 

![AndXXIX](https://yanbopanpi.github.io/yanbo_pan.github.io//images/AndXXIX.png){: style="width: 35%; max-width: 450px; height: auto; float: left;"}

After devising the pipeline with DBSCAN, we also tried using HDBSCAN and OPTICS to test which unsupervised machine learning method yielded the best result for the UFD search. Finally, OPTICS is chosen since it recovers several UFDs of M31 with the least number of false positives. During this project, we also explore the star-galaxy separation criteria in the DELVE survey. The tip of the red giant branch selection criteria is modified based on the star-galaxy separation magnitude limit. 

Our objective is to complement the current catalog of UFDs in the local volume while exploring the potential of using modern statistical density searching tools in UFD studies. We have focused on searching for M31 UFDs and recovered all 10 M31 satellite galaxies in the DELVE DR2 coverage. This work provides tools to identify UFDs in large sky surveys, which helps to test the cosmological constraints of the Lambda Cold Dark Matter (ΛCDM) model.
!--->

<!---
Through this experience, I learned about unsupervised machine learning algorithms by dealing with large survey data. I also have a taste of astrostatistics and designed my own SQL query throughout this project. 
!--->

<!---
To further this project, I hope to introduce other types of stars (MS, BSS) into the selection criteria. Also, data from larger areas of the sky will be explored for those “missing satellites”. 

![delve](https://yanbopanpi.github.io/yanbo_pan.github.io//images/delve_dr2_footprint.png)
*image credit: DELVE Collaboration*
!--->



  




{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


