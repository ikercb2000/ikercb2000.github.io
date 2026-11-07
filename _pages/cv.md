---
layout: single
title: CV
permalink: /cv/
author_profile: true
redirect_from:
- /resume
page_class: page--cv
education:
- title: Ph.D. in Data-Driven Engineering & Sciences
  organisation: University of Bristol
  period: 2026 - Present
  details:
  - 'Scholarships: Full DTE Scholarship of the School of Engineering Mathematics and Technology'
  - 'Specialisation: Uncertainty Quantification in Multi-Agent Systems'
- title: MSc in Mathematical Finance
  organisation: University of Warwick
  period: 2025 - 2026
  details:
  - 'Scholarships: Warwick Business School merit-based scholarship'
  - 'Specialisation: C++, Advanced Probability, Stochastic Calculus, Statistical Learning Theory'
  - 'Dissertation: *Machine Learning with Choquet Integrals for Risk Management and Decision Making*'
- title: MSc in Mathematical Engineering
  organisation: Universitat Oberta de Catalunya
  period: 2023 - 2025
  details:
  - 'Specialisation: Simulation, Differential Equations, Numerical Methods, Machine Learning'
  - 'Dissertation: *Artificial Neural Networks for Financial Time Series: Forecasts and Loss Functions*'
- title: MSc in Statistics and Operations Research
  organisation: Universitat Politècnica de Catalunya
  period: 2022 - 2024
  details:
  - 'Scholarships: Santander Master + UB Scholarship and Bosch-Gimpera Foundation Scholarship'
  - 'Specialisation: Advanced Probability, Time Series, Statistical Learning, Optimization'
  - 'Dissertation: *Probabilistic and Statistical Methods for Power Laws in Complex Systems: Applications to Finance*'
- title: BSc in Economics with Mathematics Minor
  organisation: Universitat Pompeu Fabra
  period: 2018 - 2022
  details:
  - Top 10 student in a cohort of more than 100 students
  - 'Scholarships: Highest honours in 13 modules'
  - Advanced Undergraduate Programme at the Barcelona School of Economics to take MSc modules
  - 'Dissertation: *The SABR Model in Financial Practice*'
experience:
- title: Quantitative Researcher
  organisation: Metron Trading, Spain
  period: July 2024 - November 2025
  details:
  - Developed arbitrage strategies in Python and Rust for cryptocurrency market-making.
  - Built advanced machine learning analysis pipelines to improve trading volume and profitability.
  - Engineered optimal execution algorithms to reduce slippage for institutional clients.
  - Designed risk management dashboards and models for several trading strategies.
- title: Quantitative Risk Analyst, AI & ML Team
  organisation: Deloitte S.L., Spain
  period: September 2023 - July 2024
  details:
  - Calibrated probability of default and early warning mortgage risk models for major Spanish banks.
  - Developed reinforcement learning algorithms in Python for debt monitoring and collection.
  - Delivered training in quantitative risk modelling and risk analytics for Uruguay's Central Bank.
- title: Research Intern
  organisation: Mathematics Research Centre (CRM), Spain
  period: July 2023 - September 2023
  details:
  - Worked within the Complex Systems Group on statistical modelling for financial markets.
  - Applied Extreme Value Theory and power-law modelling to high-frequency market index data.
  - Studied connections between complex systems, econophysics and financial market models.
skills:
- name: Programming
  description: Python, Rust, C++, Lean, SAS, SQL
- name: Python libraries
  description: Polars, NumPy, CUDA and related scientific computing tools
- name: C++ tools
  description: QuantLib, Boost, CMake
- name: Quantitative methods
  description: Stochastic modelling, statistical learning, time series, optimization, financial forecasting, risk
    management
- name: Languages
  description: Spanish and Catalan native; English proficient; Chinese intermediate and German basic
research_interests:
- Uncertainty Quantification
- Sequential Decision-Making
- Statistical Learning Theory
- Stochastic Modelling
- Financial Engineering
service:
- title: Member
  organisation: Nova Talent
  period: 2023 - Present
  details:
  - Selected as part of a top 3% talent network based on academic performance and professional achievements.
  - Participated in workshops with leaders from finance, technology and academia.
- title: President and Founder
  organisation: Pompeu Research Club
  period: 2021 - 2022
  details:
  - Led a team of 10 students in advanced mathematical economics research projects.
  - Organised high-impact academic and industry events with speakers from leading firms.
---

<section class="cv-block" id="education" aria-labelledby="education-title">
  <h2 id="education-title">Education</h2>
  {% include cv-timeline.html items=page.education icon="graduation-cap" %}
</section>

<section class="cv-block" id="experience" aria-labelledby="experience-title">
  <h2 id="experience-title">Work experience</h2>
  {% include cv-timeline.html items=page.experience icon="briefcase" bullets=true %}
</section>

<section class="cv-block" id="skills" aria-labelledby="skills-title">
  <h2 id="skills-title">Skills</h2>
  <dl class="cv-skills">
    {% for skill in page.skills %}
    <div class="cv-skills__group">
      <dt>{{ skill.name | escape }}</dt>
      <dd>{{ skill.description | escape }}</dd>
    </div>
    {% endfor %}
  </dl>
</section>

<section class="cv-block" id="research-interests" aria-labelledby="interests-title">
  <h2 id="interests-title">Research interests</h2>
  <ul class="cv-interests" role="list">
    {% for interest in page.research_interests %}<li>{{ interest | escape }}</li>{% endfor %}
  </ul>
</section>

<section class="cv-block" id="service" aria-labelledby="service-title">
  <h2 id="service-title">Service and leadership</h2>
  {% include cv-timeline.html items=page.service icon="handshake" bullets=true %}
</section>
