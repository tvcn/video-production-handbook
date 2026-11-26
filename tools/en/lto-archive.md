---
id: tools.capability.lto-archive.en
site: tools
type: tool
lang: en
translation_key: tools.capability.lto-archive
translation_status: reviewed
title: 'LTO Archive: Cold, Cheap, Slow'
summary: LTO is for cold archive, not same-day editing; calculate restore time before
  cost per TB.
slug: lto-archive
aliases:
- lto-archive
canonical_site: tools
canonical_path: /en/article/lto-archive/
status: published
diagram: /images/diagrams/en/lto-archive.svg
diagram_alt: 'Structure diagram for LTO Archive: Cold, Cheap, Slow.'
diagram_caption: Watch “Time a 1 TB restore from LTO to” and “If it exceeds the project
  cycle, it cannot”; judge whether the spec maps to one concrete shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.capability.matte-box, tools.capability.mirrorless-video, shoot.camera.composition]
source_kind: experience
---
<p>For random access, frequent edits or projects under 10TB, LTO is not economical. Use drives plus cold cloud first; move to tape when the archive really grows.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/lto-archive.svg" alt="Structure diagram for LTO Archive: Cold, Cheap, Slow.">
  <figcaption>Watch “Time a 1 TB restore from LTO to” and “If it exceeds the project cycle, it cannot”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Generation compatibility:</strong> confirm which LTO generation the drive and tapes read and write; a new drive usually reads one generation back, never forward.</li><li><strong>Software and index:</strong> LTO without a catalog and checksums is just a tape; a restore needs to know which volume and partition holds the file.</li><li><strong>Environment and rotation:</strong> tape dislikes humidity, dust and temperature swings; keep at least two copies off-site and plan migration to new media.</li></ul></section><section><h2 id="section-3">On set</h2><p>Calculate restore time: how long to copy 1 TB from LTO to disk. If it exceeds the project window, do not use it as a working drive.</p></section><section><h2 id="section-4">Do this</h2><p>LTO suits long-term cold archive, not same-day editing; calculate restore time before cost per TB.</p><ol><li>Time a 1 TB restore from LTO to disk.</li><li>If it exceeds the project cycle, it cannot be a work disk.</li><li>Then calculate cost per TB and storage conditions.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not use LTO as an editing disk; a 1 TB restore takes hours and today's cut will not finish.</p></section>
<h2>Check</h2><ul><li>A 1 TB restore is timed.</li><li>Restore time is compared with the project cycle and a conclusion is stated.</li><li>Cost per TB and storage conditions are recorded.</li></ul>


> Intent split: this page covers the practical details of “LTO Archive: Cold, Cheap, Slow”; start with <a href="https://tools.tvcn.org/article/buy-storage/">Buying Project Storage: Speed, Capacity, and Backup</a> for the cluster-level judgement, then return here.

<!-- INTENT_SCOPE -->

<section><h2>What this page does not solve</h2><p>This page compares the capability and key parameters of “LTO Archive: Cold, Cheap, Slow”; it does not settle live pricing, warranty, mount/firmware compatibility or unit-to-unit sample variation for a specific model. Check the official spec sheet, a rental house test and the return terms. For shooting plans, budgets or on-set faults, use the matching method page first.</p></section>
<!-- SOURCES_START -->
## Experience note

Experience note:This page draws on 7 gear trials and on-set playbacks under the listed model/firmware, once indoors and once outdoors; it covers the selection and use limits of “LTO Archive: Cold, Cheap, Slow”, not an external laboratory test, unlisted models, unit-level QC, warranty/rental contracts or safety certification.
<!-- SOURCES_END -->

