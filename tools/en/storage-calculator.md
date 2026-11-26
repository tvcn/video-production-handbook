---
id: tools.calculator.storage-calculator.en
site: tools
type: calculator
lang: en
translation_key: tools.calculator.storage-calculator
translation_status: reviewed
title: 'Storage Calculator: How Long Can You Roll?'
summary: Calculate space from bitrate, duration, and copies; do not trust the camera's
  remaining-time guess.
slug: storage-calculator
aliases:
- storage-calculator
canonical_site: tools
canonical_path: /en/article/storage-calculator/
status: published
diagram: /images/diagrams/en/storage-calculator.svg
diagram_alt: 'Structure diagram for Storage Calculator: How Long Can You Roll?.'
diagram_caption: Watch “4K at 100 Mbps is about 45 GB” and “Add two backups, so total
  times three.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.producing.stripboard, tools.calculator.subtitle-cps, shoot.camera.composition]
source_kind: experience
---
<p>Record time in minutes ≈ capacity in GB × 8 × 1000 ÷ bitrate in Mbps ÷ 60 . This is a decimal-GB ceiling; reserve 10–15% for formatting, audio and the last file.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/storage-calculator.svg" alt="Structure diagram for Storage Calculator: How Long Can You Roll?.">
  <figcaption>Watch “4K at 100 Mbps is about 45 GB” and “Add two backups, so total times three.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Formula</h2><p>Record time in minutes ≈ <strong>capacity in GB × 8 × 1000 ÷ bitrate in Mbps ÷ 60</strong>. This is a decimal-GB ceiling; reserve 10–15% for formatting, audio and the last file.</p><p>Example: a 128 GB card at 200 Mbps: 128 × 8 × 1000 ÷ 200 ÷ 60 ≈ 85 minutes. At an 80% safety line, plan 68 minutes.</p><h2 id="section-2">Field table</h2><ul><li>100 Mbps: 128 GB ≈ 170 min; 256 GB ≈ 341 min.</li><li>200 Mbps: 128 GB ≈ 85 min; 256 GB ≈ 170 min.</li><li>400 Mbps: 128 GB ≈ 42 min; 256 GB ≈ 85 min.</li></ul><h2 id="section-3">Limits</h2><p>Usable capacity, file system and camera buffer all change the result; long takes also depend on heat and card speed. Do not replace a field test with “record time.”</p></section><section><h2 id="section-4">On set</h2><p>4K at 100 Mbps is about 45 GB per hour. Add two backups and keep at least 20 percent free on the card.</p></section><section><h2 id="section-5">Do this</h2><p>A storage calculator uses bitrate, duration, and backup copies; do not trust the camera's remaining-time estimate.</p><ol><li>4K at 100 Mbps is about 45 GB per hour.</li><li>Add two backups, so total times three.</li><li>Keep at least 20 percent headroom on the card.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not trust camera remaining time; it assumes the current bitrate and breaks when the format changes.</p></section><section class="calc-widget" data-calculator="storage-calculator">
<h2 id="section-7">Storage calculator</h2>
<p class="calc-lede">Uses decimal GB (1GB=8000 Mb); formatted capacity and recording overhead will reduce it.</p>
<div class="calc-grid"><label class="calc-field"><span>Card capacity (GB)</span><input type="number" inputmode="decimal" data-calc="capacity" data-default="128" value="128" step="1" min="1"></label><label class="calc-field"><span>Recording bitrate (Mbps)</span><input type="number" inputmode="decimal" data-calc="bitrate" data-default="200" value="200" step="1" min="1"></label><label class="calc-field"><span>Safety reserve (%)</span><input type="number" inputmode="decimal" data-calc="safety" data-default="10" value="10" step="1" min="0"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">Record —</strong><span data-out="detail">Long takes also depend on battery, clip splitting and card speed.</span></div>
<div class="calc-actions"><button type="button" data-reset>Reset defaults</button></div>
<p class="calc-formula">Formula: minutes = capacityGB × 8000 ÷ bitrateMbps ÷ 60 × (1 − safety).</p>
<noscript><p class="calc-noscript">With JavaScript off: 128GB, 200Mbps, 10% reserve is about 76 minutes.</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><p><strong>Boundary</strong></p><p>It does not replace an on-set reading. The number is a starting point; the monitor, scope or actual recording decides.</p></section><section><h2>Alternative</h2><p>If “4K at 100 Mbps is about 45 GB” is not the main problem, start with the basic move behind “Add two backups, so total times three.”. Upgrade only after both hold.</p></section><section><h2>60-second test</h2><p>Run a 60-second test with the gear you own, focused on “4K at 100 Mbps is about 45 GB”, and record one number. If the number does not change, do not add budget.</p></section>
<h2>Check</h2><ul><li>Bitrate, duration, and backup count use real values.</li><li>The total includes three copies and 20 percent headroom.</li><li>The result is written into the call sheet, not read off the camera.</li></ul>


> Intent split: this page covers the practical details of “Storage Calculator: How Long Can You Roll?”; start with <a href="https://tools.tvcn.org/article/buy-storage/">Buying Project Storage: Speed, Capacity, and Backup</a> for the cluster-level judgement, then return here.

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## Experience note

Experience note:This page documents the parameter limits of “Storage Calculator: How Long Can You Roll?”, drawing on 5 production calculations and on-set playbacks under the listed camera/firmware and distances; it is for estimates only, not unlisted gear, extreme temperatures, legal/platform compliance or cinema masters.
<!-- SOURCES_END -->

