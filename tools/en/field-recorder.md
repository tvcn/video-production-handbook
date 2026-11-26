---
id: tools.capability.field-recorder.en
site: tools
type: tool
lang: en
translation_key: tools.capability.field-recorder
translation_status: reviewed
title: 'Field Recorder: 32-Bit Is Not Magic'
summary: 32-bit float can rescue clipping, not dialogue eaten by wind; mic and placement
  still come first.
slug: field-recorder
aliases:
- field-recorder
canonical_site: tools
canonical_path: /en/article/field-recorder/
status: published
diagram: /images/diagrams/en/field-recorder.svg
diagram_alt: 'Structure diagram for Field Recorder: 32-Bit Is Not Magic.'
diagram_caption: Watch “Record quiet dialogue with peaks at -12 dB.” and “Deliberately
  clip once and see whether 32-bit recovers”; judge whether the spec maps to one concrete
  shooting problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-05-26'
related: [tools.workflow.first-shoot-day, tools.capability.fluid-head, shoot.camera.composition]
source_kind: experience
---
<p>If one camera input is enough and sound is controlled, a separate recorder adds a sync step; solve mic distance and camera preamp first. Do not hide missing monitoring behind more gear.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/field-recorder.svg" alt="Structure diagram for Field Recorder: 32-Bit Is Not Magic.">
  <figcaption>Watch “Record quiet dialogue with peaks at -12 dB.” and “Deliberately clip once and see whether 32-bit recovers”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Channels and preamps:</strong> how many independent inputs, phantom power and gain range; preamp noise matters more than a 32-bit claim.</li><li><strong>Limits of 32-bit:</strong> it rescues a clipped peak, not a missing lav, a stopped record or wind in the capsule; still watch levels and monitor.</li><li><strong>Media and power:</strong> card type, dual-card backup, battery runtime and external power; a card change must not stop recording.</li></ul></section><section><h2 id="section-3">On set</h2><p>Record a quiet line with peaks at -12 dB, then clip it on purpose and see whether 32-bit float recovers it.</p></section><section><h2 id="section-4">Do this</h2><p>32-bit float can rescue clipping but not dialogue eaten by wind; microphone and position still come first.</p><ol><li>Record quiet dialogue with peaks at -12 dB.</li><li>Deliberately clip once and see whether 32-bit recovers it.</li><li>Test wind and confirm float cannot rescue it; do not treat it as insurance.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not treat 32-bit as universal insurance; it cannot save wind noise or bad placement.</p></section>
<h2>Check</h2><ul><li>Quiet dialogue peaks near -12 dB with audible noise floor.</li><li>Deliberate clipping is recovered to intelligibility in 32-bit.</li><li>A wind test proves float cannot rescue wind-eaten dialogue.</li></ul>


> Intent split: this page covers the practical details of “Field Recorder: 32-Bit Is Not Magic”; start with <a href="https://tools.tvcn.org/article/lav-hidden/">Lav Hiding: Collar, Hair, Tape</a> for the cluster-level judgement, then return here.

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## Experience note

Experience note:This page draws on 4 gear trials and on-set playbacks under the listed model/firmware, once indoors and once outdoors; it covers the selection and use limits of “Field Recorder: 32-Bit Is Not Magic”, not an external laboratory test, unlisted models, unit-level QC, warranty/rental contracts or safety certification.
<!-- SOURCES_END -->

