---
permalink: /
title: "Ad Astra"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .research-timeline {
    margin: 1.75rem 0 2.5rem;
    position: relative;
  }

  .research-timeline::before {
    background: #cbd9e6;
    bottom: 0.75rem;
    content: "";
    left: 4.75rem;
    position: absolute;
    top: 0.45rem;
    width: 2px;
  }

  .research-item {
    display: grid;
    gap: 1.5rem;
    grid-template-columns: 4rem minmax(0, 1fr);
    margin: 0 0 2rem;
    position: relative;
  }

  .research-year {
    color: #005bbb;
    font-size: 0.9rem;
    font-weight: 700;
    line-height: 1.4;
    padding-top: 0.05rem;
    text-align: right;
  }

  .research-content {
    border-bottom: 1px solid #e6e8eb;
    min-width: 0;
    padding: 0 0 1.75rem 1rem;
    position: relative;
  }

  .research-content::before {
    background: #fff;
    border: 3px solid #005bbb;
    border-radius: 50%;
    content: "";
    height: 12px;
    left: -0.81rem;
    position: absolute;
    top: 0.25rem;
    width: 12px;
  }

  .apa-citation {
    font-size: 1rem;
    line-height: 1.55;
    margin: 0 0 0.85rem;
  }

  .corresponding-author-note {
    color: #5b6470;
    font-size: 0.86rem;
    margin: 0.8rem 0 0;
  }

  .research-item .research-abstract {
    border-left: 2px solid #dbe4ec;
    color: #46515c;
    font-size: 0.95rem;
    line-height: 1.65;
    margin: 0 0 0 1rem;
    padding-left: 1rem;
  }

  .abstract-label {
    color: #25313c;
    font-weight: 600;
  }

  .workflow-figure {
    margin: 1rem 0 0.35rem;
  }

  .workflow-figure img {
    border: 1px solid #e6e8eb;
    display: block;
    height: auto;
    margin-left: auto;
    margin-right: auto;
    max-height: 520px;
    max-width: 100%;
    object-fit: contain;
    width: auto;
  }

  .workflow-figure figcaption {
    color: #6b7280;
    font-size: 0.85rem;
    line-height: 1.45;
    margin-top: 0.55rem;
  }

  @media (max-width: 600px) {
    .research-timeline::before {
      left: 0.35rem;
    }

    .research-item {
      display: block;
      padding-left: 1.75rem;
    }

    .research-year {
      margin-bottom: 0.45rem;
      text-align: left;
    }

    .research-content {
      padding-left: 0;
    }

    .research-content::before {
      left: -1.76rem;
    }

    .research-item .research-abstract {
      margin-left: 0.25rem;
    }
  }
</style>

Hello there, this is <strong>Jing</strong>, a Ph.D. student in <a href="https://www.buffalo.edu/cas/geography.html">Geography</a> at <a href="https://www.buffalo.edu/">University at Buffalo</a>, advised by <a href="https://www.buffalo.edu/cas/geography/faculty/faculty_directory/le-wang.html">Prof. Le Wang</a>. Before this, I received my M.S. in <a href="https://geospatial.szu.edu.cn/index.htm">Geo-information and Smart City</a> from <a href="https://en.szu.edu.cn/">Shenzhen University</a> and my B.E. in Surveying and Mapping Engineering from <a href="https://english.sdau.edu.cn/main.htm">Shandong Agricultural University</a>.

Research Interests
------------------

My research focuses on <strong>mangrove forest dynamics</strong> and <strong>coastal resilience</strong> through remote sensing and spatial analysis. Specifically, I am interested in using multi-source satellite imagery and geospatial modeling to characterize mangrove species composition, canopy condition, disturbance, and recovery, with the broader goal of supporting coastal ecosystem monitoring and risk assessment.

Recent Research
---------------

<div class="research-timeline">
  <article class="research-item">
    <div class="research-year">2026</div>
    <div class="research-content">
      <p class="apa-citation"><strong>Miao, J.</strong>, &amp; Wang, L.<sup>*</sup> (Manuscript under revision). A cross-scale foundation model framework for annual regional mapping of post-hurricane mangrove degradation and recovery.</p>
      <p class="research-abstract"><span class="abstract-label">Abstract:</span> This study develops a cross-scale framework for annual mapping of post-hurricane mangrove degradation and recovery across South Florida and the northern Caribbean from 2016 to 2025. High-resolution NAIP-derived degradation labels are used to train a SkySense++ remote-sensing foundation model with a U-Net decoder. The resulting annual maps are then used to examine how species composition, canopy structure, topography, wind exposure, and inundation shape mangrove degradation and recovery trajectories.</p>
      <figure class="workflow-figure">
        <a href="/images/workflow-mangrove-degradation.png">
          <img src="/images/workflow-mangrove-degradation.png" alt="Workflow for post-hurricane mangrove degradation mapping and recovery analysis">
        </a>
        <figcaption>Workflow for annual post-hurricane mangrove degradation mapping, model training, prediction, segmentation, and recovery analysis.</figcaption>
      </figure>
    </div>
  </article>

  <article class="research-item">
    <div class="research-year">2026</div>
    <div class="research-content">
      <p class="apa-citation"><strong>Miao, J.</strong>, &amp; Wang, L.<sup>*</sup> (2026). Innovative phenological feature extraction for enhanced mangrove species mapping using high-temporal-resolution Harmonized Landsat and Sentinel-2 imagery. <strong><em>Remote Sensing Applications: Society and Environment</em></strong>, <em>43</em>, 102254. <a href="https://doi.org/10.1016/j.rsase.2026.102254">https://doi.org/10.1016/j.rsase.2026.102254</a></p>
      <p class="research-abstract"><span class="abstract-label">Abstract:</span> This study develops a phenology-based framework for mapping three dominant mangrove species, <em>Rhizophora mangle</em>, <em>Avicennia germinans</em>, and <em>Laguncularia racemosa</em>, together with dieback areas using high-temporal-resolution HLS imagery. Second-order harmonic regression is applied to vegetation-index time series to derive phenological parameters, which are integrated into a Gaussian mixture model for probabilistic classification and uncertainty assessment.</p>
      <figure class="workflow-figure">
        <a href="/images/workflow-mangrove-species-classification.png">
          <img src="/images/workflow-mangrove-species-classification.png" alt="Workflow for mangrove species classification and uncertainty assessment">
        </a>
        <figcaption>Workflow for mangrove species classification using high-temporal remote sensing imagery, vegetation-index time series, Gaussian mixture models, and uncertainty assessment.</figcaption>
      </figure>
    </div>
  </article>

  <article class="research-item">
    <div class="research-year">2026</div>
    <div class="research-content">
      <p class="apa-citation"><strong>Miao, J.</strong>, Wang, L.<sup>*</sup>, &amp; Sousa, W. P. (2026). Tracking lightning-induced mangrove canopy gaps in Panama using multi-temporal remote sensing. <strong><em>Geo-spatial Information Science</em></strong>, 1–17. <a href="https://doi.org/10.1080/10095020.2026.2751778">https://doi.org/10.1080/10095020.2026.2751778</a></p>
      <p class="research-abstract"><span class="abstract-label">Abstract:</span> Lightning-induced canopy gaps play an important role in mangrove regeneration and forest structural dynamics, but their long-term recovery is difficult to observe consistently. This study combines multi-sensor high-resolution satellite imagery, radiometric normalization, U-Net segmentation, and object-based temporal tracking to map mangrove canopy gaps in Panama from 2000 to 2020 and reconstruct gap formation, persistence, re-observation, and recovery.</p>
      <figure class="workflow-figure">
        <a href="/images/workflow-mangrove-gap-detection.png">
          <img src="/images/workflow-mangrove-gap-detection.png" alt="Workflow for multi-year mangrove canopy gap detection">
        </a>
        <figcaption>Workflow for detecting and characterizing mangrove canopy gaps using multi-year high-resolution satellite imagery.</figcaption>
      </figure>
    </div>
  </article>

  <article class="research-item">
    <div class="research-year">2024</div>
    <div class="research-content">
      <p class="apa-citation"><strong>Miao, J.</strong>, Wang, J.<sup>*</sup>, Zhao, D., Shen, Z., Xiang, H., Gao, C., Li, W., Cui, L., &amp; Wu, G. (2024). Modeling strategies and influencing factors in retrieving canopy equivalent water thickness of mangrove forest with Sentinel-2 image. <strong><em>Ecological Indicators</em></strong>, <em>158</em>, 111497. <a href="https://doi.org/10.1016/j.ecolind.2023.111497">https://doi.org/10.1016/j.ecolind.2023.111497</a></p>
      <p class="research-abstract"><span class="abstract-label">Abstract:</span> This paper maps mangrove canopy equivalent water thickness using Sentinel-2 imagery at the reserve scale and compares machine learning, radiative transfer, and hybrid modeling strategies. It further evaluates how species distribution, slope, elevation, and distance to dam influence the spatial distribution of canopy water status.</p>
    </div>
  </article>

  <article class="research-item">
    <div class="research-year">2022</div>
    <div class="research-content">
      <p class="apa-citation"><strong>Miao, J.</strong>, Zhen, J., Wang, J.<sup>*</sup>, Zhao, D., Jiang, X., Shen, Z., Gao, C., &amp; Wu, G. (2022). Mapping seasonal leaf nutrients of mangrove with Sentinel-2 images and XGBoost method. <strong><em>Remote Sensing</em></strong>, <em>14</em>(15), 3679. <a href="https://doi.org/10.3390/rs14153679">https://doi.org/10.3390/rs14153679</a></p>
      <p class="research-abstract"><span class="abstract-label">Abstract:</span> This study compares machine learning models for estimating mangrove leaf carbon, nitrogen, and phosphorus from Sentinel-2 imagery acquired in spring, summer, and winter. The best-performing model is then used to map seasonal leaf nutrient dynamics from 2017 to 2021.</p>
    </div>
  </article>
</div>

<p class="corresponding-author-note"><sup>*</sup> Corresponding author.</p>

Beyond Research
---------------

Outside of research, I enjoy tennis, basketball, reading novels, and exploring new ideas. Some of my favorite writers are Elena Ferrante and Albert Camus. I am drawn to evening glories, forests, the ocean, and the curiosity that keeps learning alive.
