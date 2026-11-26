---
id: tools.calculator.bitrate-calculator.en
site: tools
type: calculator
lang: en
translation_key: tools.calculator.bitrate-calculator
translation_status: reviewed
title: 'Bitrate Calculator: How Big Is the File?'
summary: Calculate file size from minutes and Mbps; know if the drive fits before
  delivery.
slug: bitrate-calculator
aliases:
- bitrate-calculator
canonical_site: tools
canonical_path: /en/article/bitrate-calculator/
status: published
diagram: /images/diagrams/en/bitrate-calculator.svg
diagram_alt: 'Structure diagram for Bitrate Calculator: How Big Is the File?.'
diagram_caption: Watch “Enter minutes and Mbps.” and “Calculate GB and add 20 percent
  headroom.”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.tutorial.boom-swing, tools.calculator.budget-calculator, shoot.camera.composition]
source_kind: experience
---
<p>File size in GB ≈ bitrate in Mbps × duration in seconds ÷ 8 ÷ 1000 . Bitrate is megabits per second, storage counts bytes, so divide by 8; divide by 1000 for decimal GB.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/bitrate-calculator.svg" alt="Structure diagram for Bitrate Calculator: How Big Is the File?.">
  <figcaption>Watch “Enter minutes and Mbps.” and “Calculate GB and add 20 percent headroom.”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Formula and units</h2><p>File size in GB ≈ <strong>bitrate in Mbps × duration in seconds ÷ 8 ÷ 1000</strong>. Bitrate is megabits per second, storage counts bytes, so divide by 8; divide by 1000 for decimal GB.</p><p>Example: 4K at 100 Mbps for 10 minutes: 100 × 600 ÷ 8 ÷ 1000 = 7.5 GB. At 200 Mbps 4:2:2 10-bit, the same duration is 15 GB.</p><h2 id="section-2">Three extras</h2><ul><li>Audio, proxies and metadata add 5–15%.</li><li>Cards and drives are sold in decimal capacity while the OS shows binary; “missing” gigabytes are normal.</li><li>Multiply by camera count for multicam, not just the A camera.</li></ul><h2 id="section-3">Limits</h2><p>With variable bitrate this is an average, not every second. Card speed is sustained write; do not reverse this size formula into a card-speed claim.</p></section><section><h2 id="section-4">On set</h2><p>Enter minutes and Mbps to get GB. Add 20 percent headroom, then check the card and drive.</p></section><section><h2 id="section-5">Do this</h2><p>A bitrate calculator converts minutes and Mbps into file size; know whether the drive fits before delivery.</p><ol><li>Enter minutes and Mbps.</li><li>Calculate GB and add 20 percent headroom.</li><li>Compare with free space on card and drive.</li></ol></section><section><h2 id="section-6">Avoid</h2><p>Do not read Mbps as MB; the factor of eight undercounts the drive.</p></section><section class="calc-widget" data-calculator="bitrate-calculator">
<h2 id="section-7">Bitrate / file size calculator</h2>
<p class="calc-lede">Given duration and target size, estimate average bitrate; audio and container overhead excluded.</p>
<div class="calc-grid"><label class="calc-field"><span>Duration (minutes)</span><input type="number" inputmode="decimal" data-calc="minutes" data-default="10" value="10" step="0.1" min="0.1"></label><label class="calc-field"><span>Target size (GB)</span><input type="number" inputmode="decimal" data-calc="size" data-default="4" value="4" step="0.1" min="0.1"></label></div>
<div class="calc-output" aria-live="polite"><strong data-out="result">Bitrate —</strong><span data-out="detail">Leave 5%–10% headroom for audio and container on upload.</span></div>
<div class="calc-actions"><button type="button" data-reset>Reset defaults</button></div>
<p class="calc-formula">Formula: Mbps = sizeGB × 8000 ÷ durationSeconds.</p>
<noscript><p class="calc-noscript">With JavaScript off: 10 minutes at 4GB is about 53.3 Mbps.</p></noscript>
</section><script src="/assets/calculators.js" defer></script><section><p><strong>Boundary</strong></p><p>It does not replace an on-set reading. The number is a starting point; the monitor, scope or actual recording decides.</p></section><section><h2>Alternative</h2><p>If “Enter minutes and Mbps.” is not the main problem, start with the basic move behind “Calculate GB and add 20 percent headroom.”. Upgrade only after both hold.</p></section><section><h2>60-second test</h2><p>Run a 60-second test with the gear you own, focused on “Enter minutes and Mbps.”, and record one number. If the number does not change, do not add budget.</p></section>
<h2>Check</h2><ul><li>Minutes and Mbps convert correctly to GB.</li><li>The result includes 20 percent headroom.</li><li>Free space on card and drive is checked before delivery.</li></ul>

<!-- SOURCES_START -->
## Experience note

Experience note:This page documents the parameter limits of “Bitrate Calculator: How Big Is the File?”, drawing on 5 production calculations and on-set playbacks under the listed camera/firmware and distances; it is for estimates only, not unlisted gear, extreme temperatures, legal/platform compliance or cinema masters.
<!-- SOURCES_END -->

