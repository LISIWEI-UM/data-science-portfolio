---
layout: default
---
<div class="portfolio-content">
<p class="eyebrow">LI SIWEI · STUDENT DATA SCIENCE PORTFOLIO</p>

<h1>Making the question<br>as clear as the chart.</h1>
<p class="intro">I am LI SIWEI, a CISC7204 student at the University of Macau. I am learning to turn data into reproducible analyses and visual explanations, with careful attention to what each metric can—and cannot—tell us.</p>

<div class="skills"><span>Python</span><span>Data cleaning</span><span>Exploratory analysis</span><span>Data visualization</span><span>Git & GitHub</span><span>Reproducible workflows</span></div>

<h2 id="project">Selected project</h2>

<div class="project">
<p><span class="status">ONGOING · independent source validation</span></p>
<h3>Messi vs Ronaldo: how the metric changes the story</h3>
<p class="lead">Who appears ahead when “performance” means goals, assists, or both?</p>
<p>This project extends my Practice 07 visualization into a reproducible portfolio case study. It compares annual values and accumulated contributions in one source table for 2002–2025. The incomplete 2026 year is excluded.</p>
<div class="metrics"><div class="metric"><strong>+79</strong><span>Ronaldo's lead in goals</span></div>
<div class="metric"><strong>+71</strong><span>Messi's lead in goals + assists</span>
</div>
<div class="metric"><strong>24 years</strong><span>Source-table observation window</span></div>
</div>
<p><img alt="Comparison of Messi and Ronaldo: goals 856 vs 935; assists 455 vs 305; combined 1311 vs 1240." src="assets/metric_comparison.png" /></p>
<p class="caption">Figure 1. The apparent leader changes with the metric. These are calculated values from the attributed source snapshot, not independently audited career totals.</p>

<p>Ronaldo leads in goals, while Messi leads when assists receive equal weight. This reversal shows why choosing a metric is part of the argument. It does not establish one objective “greatest player.”</p>
<p><img alt="Annual goals: Messi peaks at 91 in 2012; Ronaldo peaks at 69 in 2013." src="assets/annual_goals.png" /></p>
<p class="caption">Figure 2. Annual output separates a single-year peak from sustained scoring. The source records 14 Ronaldo years and 11 Messi years with at least 40 goals.</p>

<p><strong>Workflow:</strong> parse the source table → validate years and missing values → verify the snapshot hash → calculate totals and rates → generate two charts. The repository includes Python code, dependency instructions, and machine-readable results.</p>
<div class="note">
<p><strong>Read the limitation with the finding.</strong> This is a descriptive analysis of a fan-maintained table. Its annual figures still require independent auditing. The source uses a broad assist definition, the players have different career windows, and per-appearance rates do not adjust for minutes or competition strength. <strong>Dribbling is not measured, and penalty goals are not separated from non-penalty goals.</strong> The selected metrics cannot cover every aspect of performance.</p>
</div>
<p><strong>Data and permissions:</strong> <a href="https://messixronaldo.com/calendar-year-stats">source table</a> · <a href="https://messixronaldo.com/methodology">source methodology</a>. No explicit open-data license was found on the inspected pages. Raw source data and website assets are not redistributed; the repository documents this restriction and retrieves the public table when run.</p>
<p><a class="button" href="https://github.com/LISIWEI-UM/data-science-project">Explore the code &amp; reproduction steps ↗</a></p>
</div>
<h2>What I will improve next</h2>
<p>Audit annual observations against independent match records, establish data reuse permissions, and compare a common career window. Following peer feedback about limited dimensions, I will also consider dribbling and penalty/non-penalty breakdowns when reliable, consistently defined data are available.</p>
<h2>About this work</h2>
<p>This portfolio demonstrates developing skills in transparent measurement, visual communication, and reproducibility. It presents one focused coursework project. AI assistance through GPT-6 in the Codex desktop app helped with code, charts, writing, and site preparation; the project repository documents its role.</p>
</div>
