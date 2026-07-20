---
layout: page
title: Research
permalink: /research/
nav: true
nav_order: 2
---

<div class="research-intro">
  <p class="lead">
    My research seeks to understand how and why the global methane cycle is
    changing by integrating atmospheric observations, stable isotopes,
    inverse modeling, process-based models, satellite remote sensing,
    and artificial intelligence.
  </p>

  <p>
    I develop observation-driven and scientifically interpretable approaches
    that connect methane processes across scales—from microbial activity in
    soils and wetlands to regional emissions and global atmospheric change.
  </p>
</div>

<div class="research-grid">

  <section class="research-item">
    <div class="research-image">
      <img
        src="/assets/img/carbontracker_ch4.png"
        alt="CarbonTracker-CH4 global methane inversion"
      >
    </div>

    <div class="research-text">
      <h2>CarbonTracker-CH₄ and the Global Methane Budget</h2>

      <p>
        I lead the continued development and application of
        <a href="https://gml.noaa.gov/ccgg/carbontracker-ch4/" target="_blank">
          CarbonTracker-CH₄
        </a>,
        NOAA’s global atmospheric methane inversion system. CarbonTracker-CH₄
        combines atmospheric observations, prior emission estimates, and
        atmospheric transport modeling to quantify methane sources and sinks
        across the globe.
      </p>

      <p>
        My work focuses on identifying the processes responsible for recent
        methane growth, improving microbial and fossil-fuel source attribution,
        and evaluating how uncertainties in atmospheric chemistry and soil
        uptake influence inferred emissions.
      </p>

      <p class="research-links">
        <a href="https://gml.noaa.gov/ccgg/carbontracker-ch4/" target="_blank">
          CarbonTracker-CH₄
        </a>
        <span>·</span>
        <a href="https://www.nature.com/articles/s41467-026-74777-4" target="_blank">
          Nature Communications
        </a>
      </p>
    </div>
  </section>

  <section class="research-item reverse">
    <div class="research-image">
      <img
        src="/assets/img/stable_isotopes.png"
        alt="Methane stable isotope observations and source attribution"
      >
    </div>

    <div class="research-text">
      <h2>Stable Isotopes and Methane Source Attribution</h2>

      <p>
        Stable isotopes provide critical information for distinguishing methane
        sources that cannot be separated using methane concentrations alone.
        I incorporate atmospheric δ¹³C-CH₄ observations—and increasingly
        δD-CH₄—into global inverse modeling frameworks.
      </p>

      <p>
        This multi-tracer approach helps distinguish microbial, fossil-fuel,
        biomass-burning, and sink-related contributions to atmospheric methane
        change while reducing ambiguity in global source attribution.
      </p>

      <p class="research-links">
        <a href="https://www.nature.com/articles/s41467-026-74777-4" target="_blank">
          Recent isotope-enabled inversion study
        </a>
      </p>
    </div>
  </section>

  <section class="research-item">
    <div class="research-image">
      <img
        src="/assets/img/natural_methane.png"
        alt="Wetland and soil methane processes"
      >
    </div>

    <div class="research-text">
      <h2>Natural Methane Sources and Sinks</h2>

      <p>
        Natural methane processes remain among the largest uncertainties in the
        global methane budget. My research examines wetland emissions, soil
        methane uptake, lake emissions, microbial oxidation, and high-latitude
        methane feedbacks.
      </p>

      <p>
        I combine process-based models, field observations, machine learning,
        remote sensing, and atmospheric inversions to evaluate both bottom-up
        and top-down estimates and identify the environmental controls governing
        methane exchange.
      </p>

      <p class="research-links">
        <a href="https://doi.org/10.1029/2025JG009668" target="_blank">
          Global soil methane sink
        </a>
        <span>·</span>
        <a href="https://doi.org/10.1038/s41558-020-0734-z" target="_blank">
          Arctic methane feedbacks
        </a>
      </p>
    </div>
  </section>

  <section class="research-item reverse">
    <div class="research-image">
      <img
        src="/assets/img/ai4methane.png"
        alt="AI4Methane knowledge-guided machine learning"
      >
    </div>

    <div class="research-text">
      <h2>AI4Methane and Knowledge-Guided Machine Learning</h2>

      <p>
        I lead
        <a href="https://ai4ch4.com/" target="_blank">AI4Methane</a>,
        an interdisciplinary working group connecting Earth scientists,
        atmospheric researchers, ecologists, and computer scientists.
      </p>

      <p>
        My AI research focuses on combining scientific knowledge with machine
        learning through hybrid modeling, physical constraints, uncertainty-aware
        prediction, interpretable model design, and benchmark datasets for
        methane science.
      </p>

      <p>
        Rather than replacing process-based models, I use machine learning to
        improve spatial representation, identify missing processes, evaluate
        model uncertainty, and support prediction under sparse observational
        coverage.
      </p>

      <p class="research-links">
        <a href="https://ai4ch4.com/" target="_blank">AI4Methane</a>
        <span>·</span>
        <a href="https://arxiv.org/abs/2606.00338" target="_blank">
          CHAM-net
        </a>
      </p>
    </div>
  </section>

  <section class="research-item">
    <div class="research-image">
      <img
        src="/assets/img/satellite_integration.png"
        alt="Satellite and surface methane observations"
      >
    </div>

    <div class="research-text">
      <h2>Satellite Observations and Multi-Scale Integration</h2>

      <p>
        Satellite methane observations provide broad spatial coverage, while
        surface networks, aircraft measurements, and atmospheric profiles offer
        high-accuracy constraints. My work integrates these complementary
        observing systems within atmospheric inversion frameworks.
      </p>

      <p>
        A central goal is to bridge the scale mismatch among field measurements,
        satellite retrievals, ecosystem models, and global inversions while
        accounting for sampling, transport, retrieval, and representation
        uncertainties.
      </p>

      <p>
        This research supports improved regional methane estimates, independent
        model evaluation, and the development of higher-resolution,
        decision-relevant CarbonTracker-CH₄ products.
      </p>
    </div>
  </section>

</div>

<style>
.research-intro {
  max-width: 920px;
  margin-bottom: 3rem;
}

.research-intro .lead {
  font-size: 1.25rem;
  line-height: 1.7;
  margin-bottom: 1rem;
}

.research-grid {
  display: flex;
  flex-direction: column;
  gap: 4rem;
}

.research-item {
  display: grid;
  grid-template-columns: minmax(280px, 42%) 1fr;
  gap: 2.5rem;
  align-items: center;
}

.research-item.reverse .research-image {
  order: 2;
}

.research-item.reverse .research-text {
  order: 1;
}

.research-image img {
  width: 100%;
  min-height: 280px;
  max-height: 360px;
  object-fit: cover;
  border-radius: 10px;
  box-shadow: 0 8px 24px rgba(0, 0, 0, 0.12);
  transition:
    transform 0.25s ease,
    box-shadow 0.25s ease;
}

.research-image img:hover {
  transform: translateY(-4px);
  box-shadow: 0 12px 30px rgba(0, 0, 0, 0.17);
}

.research-text h2 {
  margin-top: 0;
  margin-bottom: 1rem;
  font-size: 1.55rem;
  line-height: 1.3;
}

.research-text p {
  line-height: 1.7;
}

.research-links {
  margin-top: 1rem;
  font-weight: 600;
}

.research-links span {
  margin: 0 0.45rem;
  color: var(--global-text-color-light);
}

@media (max-width: 768px) {
  .research-item,
  .research-item.reverse {
    grid-template-columns: 1fr;
    gap: 1.4rem;
  }

  .research-item.reverse .research-image,
  .research-item.reverse .research-text {
    order: initial;
  }

  .research-image img {
    min-height: auto;
    max-height: none;
  }

  .research-grid {
    gap: 3rem;
  }
}
</style>
