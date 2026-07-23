---
permalink: /
title: "Ad Astra"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  .about-intro {
    font-size: 1.05rem;
    line-height: 1.75;
    margin-bottom: 2rem;
  }

  .research-item {
    border-left: 3px solid #52adc8;
    margin: 1.35rem 0;
    padding-left: 1rem;
  }

  .research-item h3 {
    font-size: 1.05rem;
    line-height: 1.35;
    margin-bottom: 0.35rem;
  }

  .research-item p {
    margin-bottom: 0;
  }

  .workflow-figure {
    margin: 1rem 0 0.35rem;
  }

  .workflow-figure img {
    border: 1px solid #e6e8eb;
    display: block;
    height: auto;
    max-height: 520px;
    max-width: 100%;
    object-fit: contain;
    width: 100%;
  }

  .workflow-figure figcaption {
    color: #6b7280;
    font-size: 0.85rem;
    line-height: 1.45;
    margin-top: 0.55rem;
  }
</style>

<div class="about-intro">
  Hello, I am <strong>Jing Miao</strong>, a Ph.D. student in <a href="https://www.buffalo.edu/cas/geography.html">Geography</a> at the <a href="https://www.buffalo.edu/">University at Buffalo</a>, advised by <a href="https://www.buffalo.edu/cas/geography/faculty/faculty_directory/le-wang.html">Professor Le Wang</a>. My work examines mangrove forest dynamics, coastal resilience, and hurricane-related flooding through remote sensing, machine learning, and spatial analysis.
</div>

Recent Research
---------------

<div class="research-item">
  <h3>A cross-scale foundation model framework for annual regional mapping of post-hurricane mangrove degradation and recovery <em>(under revision)</em></h3>
  <p>This study develops a cross-scale framework for annual mapping of post-hurricane mangrove degradation and recovery across South Florida and the northern Caribbean from 2016 to 2025. High-resolution NAIP-derived degradation labels are used to train a SkySense++ remote-sensing foundation model with a U-Net decoder. The resulting annual maps are then used to examine how species composition, canopy structure, topography, wind exposure, and inundation shape mangrove degradation and recovery trajectories.</p>
  <figure class="workflow-figure">
    <a href="/images/workflow-mangrove-degradation.png">
      <img src="/images/workflow-mangrove-degradation.png" alt="Workflow for post-hurricane mangrove degradation mapping and recovery analysis">
    </a>
    <figcaption>Workflow for annual post-hurricane mangrove degradation mapping, model training, prediction, segmentation, and recovery analysis.</figcaption>
  </figure>
</div>

<div class="research-item">
  <h3>Innovative phenological feature extraction for enhanced mangrove species mapping using high-temporal Harmonized Landsat and Sentinel-2 imagery <em>(under revision)</em></h3>
  <p>This study develops a phenology-based framework for mapping three dominant mangrove species, <em>Rhizophora mangle</em>, <em>Avicennia germinans</em>, and <em>Laguncularia racemosa</em>, together with dieback areas using high-temporal-resolution HLS imagery. Second-order harmonic regression is applied to vegetation-index time series to derive phenological parameters, which are integrated into a Gaussian mixture model for probabilistic classification and uncertainty assessment.</p>
  <figure class="workflow-figure">
    <a href="/images/workflow-mangrove-species-classification.png">
      <img src="/images/workflow-mangrove-species-classification.png" alt="Workflow for mangrove species classification and uncertainty assessment">
    </a>
    <figcaption>Workflow for mangrove species classification using high-temporal remote sensing imagery, vegetation-index time series, Gaussian mixture models, and uncertainty assessment.</figcaption>
  </figure>
</div>

<div class="research-item">
  <h3>Tracking lightning-induced mangrove canopy gaps in Panama using multi-temporal remote sensing <em>(under revision)</em></h3>
  <p>Lightning-induced canopy gaps play an important role in mangrove regeneration and forest structural dynamics, but their long-term recovery is difficult to observe consistently. This study combines multi-sensor high-resolution satellite imagery, radiometric normalization, U-Net segmentation, and object-based temporal tracking to map mangrove canopy gaps in Panama from 2000 to 2020 and reconstruct gap formation, persistence, re-observation, and recovery.</p>
  <figure class="workflow-figure">
    <a href="/images/workflow-mangrove-gap-detection.png">
      <img src="/images/workflow-mangrove-gap-detection.png" alt="Workflow for multi-year mangrove canopy gap detection">
    </a>
    <figcaption>Workflow for detecting and characterizing mangrove canopy gaps using multi-year high-resolution satellite imagery.</figcaption>
  </figure>
</div>

<div class="research-item">
  <h3><a href="https://doi.org/10.1016/j.ecolind.2023.111497">Modeling strategies and influencing factors in retrieving canopy equivalent water thickness of mangrove forest with Sentinel-2 imagery</a></h3>
  <p>This paper maps mangrove canopy equivalent water thickness using Sentinel-2 imagery at the reserve scale and compares machine learning, radiative transfer, and hybrid modeling strategies. It further evaluates how species distribution, slope, elevation, and distance to dam influence the spatial distribution of canopy water status.</p>
</div>

<div class="research-item">
  <h3><a href="https://doi.org/10.3390/rs14153679">Mapping seasonal leaf nutrients of mangroves with Sentinel-2 imagery and XGBoost</a></h3>
  <p>This study compares machine learning models for estimating mangrove leaf carbon, nitrogen, and phosphorus from Sentinel-2 imagery acquired in spring, summer, and winter. The best-performing model is then used to map seasonal leaf nutrient dynamics from 2017 to 2021.</p>
</div>

Beyond Research
---------------

Outside of research, I enjoy tennis, basketball, reading novels, and exploring new ideas. Some of my favorite writers are Elena Ferrante and Albert Camus. I am drawn to evening glories, forests, the ocean, and the curiosity that keeps learning alive.
