---
layout: page
title: CITRUS
description: In the CITRUS project, we use modern techniques from statistics and machine learning to identify treatment effect heterogeneity in cancer research.
img: /assets/img/citrus-wallpaper.jpeg
importance: 1
category: Ongoing
---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/citrus-wallpaper.jpeg' | relative_url }}" alt="" title="Stock image of lemons, obatined from unsplash.com, photographer: Jeremy Zero"/>
    </div>
</div>

<br>

### General Information
CITRUS is an acronym for <em>Convergence for Individualizing TReatment Using Statistical approaches</em>. The CITRUS project is a collaboration between the [Econometric Institute](https://www.eur.nl/en/ese/department-econometrics){:target="_blank"} and the [Department of Public Health](https://www.publichealthrotterdam.com/){:target="_blank"} at Erasmus Medical Center (MC) and will be carried out by me, [Andreas Alfons](https://personal.eur.nl/alfons/){:target="_blank"} (Econometric Institute), and Kevin ten Haaf (Erasmus MC). This project is funded by a ~€20,000 grant of the Dutch [Convergence Alliance](https://convergencealliance.nl/){:target="_blank"} and will be active between August 1, 2021, and December 31, 2021.

### Description
It is well known that individual patients who receive the same treatment may have very different health outcomes. The concept that treatment effects vary across patients is known as heterogeneous treatment effects (HTE). Consequently, identifying the HTE for different interventions can help in tailoring medical interventions for each individual. Thus, personalized medicine has the potential to improve the balance of benefits and harms of individual treatment pathways. The presence of HTE in medicine is commonly assessed through evaluating treatment effects across specific subgroups ("one-variable-at-a-time" analyses). However, such methods are insufficient for this purpose, due to fundamental limitations such as low statistical power and multiplicity, which makes them prone to both false-negative and false-positive results.

Recent guidelines such as <em>The Predictive Approaches to Treatment effect Heterogeneity (PATH) Statement </em> [(Kent et al., Annals of Internal Medicine, 2020)](https://www.acpjournals.org/doi/full/10.7326/M18-3667){:target="_blank"} for identifying HTE across subgroups have recommended the application of predictive statistical modeling approaches and machine learning techniques to overcome these limitations. In particular, novel machine learning methods from the statistical literature have been suggested to allow for the accurate identification of HTE. However, limited comparative evaluations for identifying the HTE of medical interventions have been performed between machine learning-based methods and predictive statistical modeling approaches.

CITRUS aims to perform a comparative evaluation of different machine learning methods and predictive statistical modeling approaches through simulation studies. We will design extensive simulation studies to answer the following research questions:

1. <em>"Which methods are most eligible for identifying HTE in which scenario?"</em>;
2. <em>"To what extent do common characteristics of medical data (e.g., low representation of risk factors, missing values, high dimensionality) affect the performance of these methods?".</em>


### Projected Outcome
1. A publication in a peer-reviewed journal in medicine or statistics in which we publish our findings. Working paper versions will be continuously published on the [arXiv](https://arxiv.org/){:target="_blank"}.
2. An open-source <span style="font-family:sans-serif;">R</span> package (published on the [CRAN](https://cran.r-project.org/){:target="_blank"}) that incorporates the methods that we use in a user-friendly manner to promote their use in medical research.

### Context
I strongly believe that techniques from modern statistics and machine learning can aid in solving statistical problems in medical research. Corresponding research collaborations are strongly encouraged by the Dutch [Convergence Alliance](https://convergencealliance.nl/){:target="_blank"}, in which the three institutions [TU Delft](https://www.tudelft.nl/en/){:target="_blank"}, [Erasmus MC](https://www.erasmusmc.nl/en){:target="_blank"}, and [Erasmus University Rotterdam](https://www.eur.nl/en){:target="_blank"} join forces to work on projects in medical research. This process is referred to as <em>convergence</em>. For that purpose, the Convergence Alliance has set up the [Open Mind Call](https://www.tudelft.nl/evenementen/2021/tbm/open-mind-call-2021-health-and-technology){:target="_blank"} in which teams from these three institutions could apply for grants of up to €20,000 to fund interdisciplinary projects. I am humbled that the CITRUS project is one of the 22  projects (out of 124 applications) that were selected for funding.

