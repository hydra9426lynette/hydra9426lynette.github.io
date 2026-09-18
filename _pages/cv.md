---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<div class="cv-layout">

  <nav class="cv-sidenav">
    <a href="#education">Education</a>
    <a href="#experience">Experience</a>
    <a href="#skills">Skills</a>
    <a href="#awards">Awards</a>
  </nav>

  <div class="cv-content">

    <section id="education" class="cv-card">
      <h2>Education</h2>
      <ul class="cv-plain-list">
        <li>M.S. in Statistics, Columbia University, Sep 2024 – Dec 2025</li>
        <li>B.S. in Statistics, Pennsylvania State University — University Park, Aug 2019 – Dec 2021 (Dean's List, 2019)</li>
      </ul>
    </section>

    <section id="experience" class="cv-card">
      <h2>Experience</h2>

      <div class="timeline">

        <div class="timeline-item">
          <div class="timeline-date">Jun 2023 – Feb 2024</div>
          <h4 class="timeline-role">SAS Programmer <span class="timeline-focus">Clinical / CRO</span></h4>
          <div class="timeline-meta">Clinpharma Clinical Research LLC <span class="dot">&middot;</span> Princeton, NJ</div>
          <div class="timeline-skills"><span>SAS</span><span>R</span><span>Experimental Design</span><span>QA / Compliance Reporting</span></div>
          <ul class="timeline-bullets">
            <li>Applied advanced statistical methods in R and SAS to rigorously test pharmaceutical research hypotheses.</li>
            <li>Conducted experimental design and advanced statistical analyses; R for simulation/modeling/visualization, SAS for regulatory-compliant reporting and validation.</li>
            <li>Implemented a risk-based, flexible QA approach — R for statistical modeling/visualization, SAS for compliance reporting.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">Feb 2024 – Aug 2024</div>
          <h4 class="timeline-role">Statistical Programmer <span class="timeline-focus">Clinical / CRO</span></h4>
          <div class="timeline-meta">JN Data Resolution LLC <span class="dot">&middot;</span> Florham Park, NJ</div>
          <div class="timeline-skills"><span>SAS</span><span>SAS Macros</span><span>CDISC/SDTM</span><span>R / R Shiny</span><span>SQL</span></div>
          <ul class="timeline-bullets">
            <li>Produced and peer-reviewed statistical analyses and visualizations with SAS, R, and SQL — regression, categorical, time-to-event, and mixed-model methods on safety and efficacy data.</li>
            <li>Validated safety and efficacy datasets using SAS macros in CDISC structure; decided on analysis methods based on data structure and objectives.</li>
            <li>Produced data visualizations using SAS and R/R Shiny; peer-reviewed programs coded by other programmers for data consistency.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">Jan 2025 – May 2025</div>
          <h4 class="timeline-role">Research Intern</h4>
          <div class="timeline-meta">Columbia University <span class="dot">&middot;</span> New York, NY</div>
          <div class="timeline-skills"><span>R</span><span>Approximate Bayesian Computation</span><span>Random Forests</span><span>Bayesian Statistics</span></div>
          <ul class="timeline-bullets">
            <li>Analyzed high-dimensional DNA-sequencing data in R — QC assessment, sequencing reads, genetic variation, structural changes.</li>
            <li>Developed R-based simulations to evaluate statistical methods for interpreting genetic mechanisms and disease pathways.</li>
            <li>Applied Approximate Bayesian Computation with random forests and sequential Monte Carlo methods to infer parameters and quantify uncertainty in high-dimensional genetic datasets.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">Sep 2025 – Present</div>
          <h4 class="timeline-role">Machine Learning Engineer</h4>
          <div class="timeline-meta">Around Technologies Inc. <span class="dot">&middot;</span> New York, NY</div>
          <div class="timeline-skills"><span>PyTorch</span><span>SQL</span><span>sf / r5r (R)</span><span>Bayesian Spatial Models (INLA/SPDE)</span><span>GTFS</span></div>
          <ul class="timeline-bullets">
            <li>Scraped and standardized U.S. GIS, GTFS, and administrative-boundary data (states, counties, tracts, blocks) in R, applying geographic crosswalks to build analysis-ready spatial datasets.</li>
            <li>Built routable multimodal networks and travel-time matrices from GTFS feeds using sf and r5r; calculated route-speed, service-coverage, and accessibility metrics.</li>
            <li>Applied Bayesian hierarchical spatial models (INLA/SPDE) and deep-learning approaches to areal and geostatistical delivery data, engineering spatial features for ETA prediction.</li>
            <li>Built SQL pipelines joining order, route, GPS, and behavioral data for ETA error, A/B testing, and launch-performance metrics; built executive dashboards linking forecasts to profit impact.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">Sep 2025 – Present</div>
          <h4 class="timeline-role">Data Science Research Scholar <span class="timeline-focus">Dept. of Pediatrics</span></h4>
          <div class="timeline-meta">Columbia University <span class="dot">&middot;</span> New York, NY</div>
          <div class="timeline-skills"><span>R</span><span>PCA</span><span>Logistic Regression</span><span>Gradient Boosting</span><span>XGBoost</span></div>
          <ul class="timeline-bullets">
            <li>Built an R-based pipeline to clean, transform, impute, and analyze high-frequency pediatric EHR data (blood pressure, labs, ICD codes, nursing flowsheets).</li>
            <li>Derived and validated age- and weight-specific lower blood-pressure bounds beyond fixed AHA/PALS thresholds; engineered hypotension-burden measures (episode frequency, duration, severity) and evaluated sensitivity/PPV against nurse-documented adverse events.</li>
            <li>Evaluated missingness, selection bias, and cohort coverage; applied stratified sampling, downsampling, PCA, regression, gradient boosting, and XGBoost, presenting findings to a multidisciplinary pediatric research team.</li>
          </ul>
        </div>

        <div class="timeline-item">
          <div class="timeline-date">Jan 2026 – Jul 2026</div>
          <h4 class="timeline-role">Data Research Intern</h4>
          <div class="timeline-meta">United Nations <span class="dot">&middot;</span> New York, NY</div>
          <div class="timeline-skills"><span>Python</span><span>SQL Server</span><span>Power BI</span><span>Data Governance</span></div>
          <ul class="timeline-bullets">
            <li>Consolidated five years of fragmented flight operational records into a centralized, SQL Server-backed metadata repository.</li>
            <li>Migrated and reconciled two years of historical records via Python-based schema mapping, entity resolution, deduplication, and source-to-target validation.</li>
            <li>Designed data dictionaries, naming standards, validation rules, and governance controls; built automated workflows to enforce them across intake and reporting.</li>
            <li>Developed real-time Power BI dashboards for fleet availability, GPS tracking, utilization, and operational risk.</li>
          </ul>
        </div>

      </div>
    </section>

    <section id="skills" class="cv-card">
      <h2>Skills</h2>
      <div class="skill-pills">
        <span>SAS</span><span>CDISC (SDTM/ADaM)</span><span>SAS Macros</span><span>R / R Shiny</span><span>SQL / MySQL</span>
        <span>Clinical Trial Reporting (TLFs)</span><span>Regulatory-Compliant Validation</span><span>Survival / Time-to-Event Analysis</span>
        <span>Mixed-Model Methods</span><span>Python</span><span>PyTorch</span><span>Tableau</span><span>Power BI</span>
        <span>AWS</span><span>Machine Learning</span><span>EDA</span><span>ETL</span><span>Excel</span>
        <span>Geospatial (sf, r5r, GTFS)</span><span>Bayesian Spatial Models (INLA/SPDE)</span><span>Scanpy / AnnData</span>
      </div>
    </section>

    <section id="awards" class="cv-card">
      <h2>Awards</h2>
      <ul class="cv-plain-list">
        <li>Top Finalist, <a href="https://www.enar.org/">ENAR</a> (a top biostatistics conference) —
          <a href="https://www.enar.org/meetings/spring2025/program/datafest_submission.cfm">2025 DataFest</a>:
          <em>"The Interaction Effect Between Antihypertensive Medication and Depressive Symptoms on Uncontrolled
          Hypertension Using Regression Survey Analysis and Random Forest Tree Approach,"</em> with Sarvar
          Khamidov and Linqing Zheng, presented March 24, 2025 in New Orleans, mentored by
          <a href="https://case.edu/medicine/pqhs/about/people/primary-faculty/liangliang-lyons-zhang">Dr. Liangliang (Lyons) Zhang</a>.
          See the <a href="https://ma.stat.columbia.edu/2024/08/22/2024-joint-statistical-meetings-ma-student-experience/">Columbia Statistics Department announcement</a>.</li>
        <li>3rd Place, sponsored by NVIDIA &amp; Amazon — 2025 NSF LEAP "Harnessing Machine Learning to Improve
          Subseasonal-to-Seasonal Climate Predictions" Hackathon</li>
      </ul>
    </section>

  </div>
</div>

<script>
(function () {
  var links = document.querySelectorAll('.cv-sidenav a');
  var sections = Array.prototype.map.call(links, function (a) {
    return document.getElementById(a.getAttribute('href').slice(1));
  });
  function setActive() {
    var pos = window.scrollY + 120;
    var current = sections[0];
    sections.forEach(function (sec) {
      if (sec && sec.offsetTop <= pos) current = sec;
    });
    links.forEach(function (a) {
      a.classList.toggle('active', current && a.getAttribute('href') === '#' + current.id);
    });
  }
  document.addEventListener('scroll', setActive, { passive: true });
  setActive();
})();
</script>
