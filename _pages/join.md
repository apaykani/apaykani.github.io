---
layout: page
permalink: /join/
title: Join Us
nav: true
nav_order: 7
---

<style>
#join-opportunities {
  --join-title: #17324d;
  --join-accent: #087f78;
  --join-muted: #596776;
  --join-border: #dce4e9;
  --join-status-bg: #e9f5f2;
  --join-pending-bg: #eef2f6;
  --join-hover: #edf7f5;
  color: var(--global-text-color, #263442);
  margin: 1.5rem 0 2.5rem;
}
html[data-theme="dark"] #join-opportunities {
  --join-title: #e6eef8;
  --join-accent: #6bd5ca;
  --join-muted: #bac5cf;
  --join-border: #3d4955;
  --join-status-bg: #173b35;
  --join-pending-bg: #293542;
  --join-hover: #173b35;
}
#join-opportunities .join-section-title {
  color: var(--join-muted);
  font-size: 0.95rem;
  font-weight: 600;
  letter-spacing: 0.08em;
  text-transform: uppercase;
  margin: 0 0 1.1rem;
}
#join-opportunities .join-card {
  border: 1px solid var(--join-border);
  border-left: 4px solid var(--join-accent);
  border-radius: 8px;
  padding: 1.5rem;
  margin: 0 0 1.25rem;
  background: var(--global-bg-color, #ffffff);
  overflow-wrap: anywhere;
}
#join-opportunities .join-card--upcoming {
  border-left-color: var(--join-border);
}
#join-opportunities .join-card-header {
  display: flex;
  align-items: center;
  justify-content: space-between;
  flex-wrap: wrap;
  gap: 0.6rem 1rem;
  margin-bottom: 0.8rem;
}
#join-opportunities .join-status {
  display: inline-block;
  background: var(--join-status-bg);
  color: var(--join-accent);
  border-radius: 4px;
  padding: 0.3rem 0.6rem;
  font-size: 0.78rem;
  line-height: 1.4;
  font-weight: 600;
}
#join-opportunities .join-status--upcoming {
  background: var(--join-pending-bg);
  color: var(--join-title);
}
#join-opportunities .join-scheme {
  color: var(--join-muted);
  font-size: 0.82rem;
  font-weight: 500;
}
#join-opportunities .join-card h3 {
  color: var(--join-title);
  font-size: 1.3rem;
  font-weight: 600;
  line-height: 1.35;
  margin: 0 0 0.75rem;
}
#join-opportunities .join-card p {
  line-height: 1.65;
  margin: 0 0 0.9rem;
}
#join-opportunities .join-meta {
  display: grid;
  grid-template-columns: repeat(2, minmax(0, 1fr));
  gap: 0.8rem 1.5rem;
  margin: 1rem 0;
}
#join-opportunities .join-meta dt {
  color: var(--join-muted);
  font-size: 0.8rem;
  font-weight: 500;
  margin-bottom: 0.15rem;
}
#join-opportunities .join-meta dd {
  color: var(--join-title);
  font-weight: 500;
  margin: 0;
}
#join-opportunities .join-note {
  color: var(--join-muted);
  font-size: 0.9rem;
}
#join-opportunities .join-action {
  display: inline-flex;
  align-items: center;
  min-height: 44px;
  color: var(--join-accent);
  border: 1px solid var(--join-accent);
  border-radius: 4px;
  padding: 0.5rem 0.9rem;
  font-size: 0.9rem;
  font-weight: 500;
  text-decoration: none;
  line-height: 1.4;
}
#join-opportunities .join-action:hover {
  color: var(--join-accent);
  background: var(--join-hover);
  text-decoration: none;
}
#join-opportunities .join-action:focus-visible {
  outline: 2px solid var(--join-accent);
  outline-offset: 3px;
}
#join-opportunities .join-card > :last-child { margin-bottom: 0; }
@media (max-width: 600px) {
  #join-opportunities .join-card { padding: 1.1rem; }
  #join-opportunities .join-meta { grid-template-columns: 1fr; }
  #join-opportunities .join-card h3 { font-size: 1.18rem; }
}
</style>

<section id="join-opportunities" aria-labelledby="phd-heading">
  <h2 id="phd-heading" class="join-section-title">PhD opportunities</h2>

  <article class="join-card" aria-labelledby="quantum-phd-title">
    <div class="join-card-header">
      <span class="join-status">Applications open</span>
      <span class="join-scheme">QMUL–CSC scholarship route</span>
    </div>
    <h3 id="quantum-phd-title">Quantum Computing and AI for Nonlinear Dynamics</h3>
    <p>Physics-informed AI and hybrid quantum-classical methods for nonlinear systems, with applications to hydrogen and ammonia chemical kinetics.</p>
    <dl class="join-meta">
      <div><dt>Expected start</dt><dd>September 2027</dd></div>
      <div><dt>Application deadline</dt><dd>27 January 2027, 16:00 GMT</dd></div>
    </dl>
    <p class="join-note"><strong>Funding and eligibility:</strong> Queen Mary tuition-fee support and CSC living-expense support for eligible Chinese applicants, subject to securing a CSC scholarship. Application reference: SEMS-PHD-738.</p>
    <a class="join-action" href="https://www.sems.qmul.ac.uk/research/studentships/738/quantum-computing-and-ai-for-nonlinear-dynamics">Project details and how to apply</a>
  </article>

  <article class="join-card join-card--upcoming" aria-labelledby="dyson-phd-title">
    <div class="join-card-header">
      <span class="join-status join-status--upcoming">Expressions of interest</span>
      <span class="join-scheme">EPSRC IDLA · Dyson Institute</span>
    </div>
    <h3 id="dyson-phd-title">Machine Learning-Driven Thermal Optimisation for High-Power-Density Electric Motors</h3>
    <p>Machine learning and computational thermal modelling to improve cooling and thermal design for compact electric motors, in collaboration with the Dyson Institute.</p>
    <dl class="join-meta">
      <div><dt>Expected start</dt><dd>October 2027</dd></div>
      <div><dt>Recruitment status</dt><dd>Formal advertisement to follow</dd></div>
    </dl>
    <p class="join-note">Final funding details will accompany the formal advertisement. To express interest, please email your CV and a short description of your relevant experience.</p>
    <a class="join-action" href="mailto:a.paykani@qmul.ac.uk?subject=EPSRC%20IDLA%20PhD%20enquiry">Enquire about this PhD</a>
  </article>

  <article class="join-card join-card--upcoming" aria-labelledby="ascend-phd-title">
    <div class="join-card-header">
      <span class="join-status join-status--upcoming">Forthcoming opportunities</span>
      <span class="join-scheme">Horizon Europe MSCA Doctoral Network</span>
    </div>
    <h3 id="ascend-phd-title">ASCEND doctoral opportunities</h3>
    <p>PhD opportunities across our European network in scientific machine learning and chemically reactive-flow modelling.</p>
    <p class="join-note">Project descriptions, eligibility requirements and application dates will be announced when recruitment opens.</p>
  </article>
</section>

---

## Postdoctoral researchers

Funded PDRA positions are advertised above and on the QMUL jobs portal.

I also welcome approaches from researchers seeking to develop a fellowship application with the group. Relevant schemes include:

- Royal Society Newton International Fellowship
- Marie Skłodowska-Curie Postdoctoral Fellowship

Fellowship applications are substantial undertakings. Please get in touch well ahead of the deadline so there is time to shape the proposal properly.

---

## Visiting researchers

We host visiting PhD students and academics for periods of three to twelve months. Visitors are expected to arrive with their own funding and to have a clear research question that connects to one of our themes.

---

## How to get in touch

Email me at [a.paykani@qmul.ac.uk](mailto:a.paykani@qmul.ac.uk), including:

1. A short statement of your research interests
2. Your CV
3. **Which of our [research themes]({{ '/research/' | relative_url }}) you would like to work in, and why**

The third point is the one that matters. Enquiries that could have been sent to any group are unlikely to receive a reply.
