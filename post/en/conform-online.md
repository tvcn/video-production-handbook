---
id: post.delivery.conform-online.en
site: post
type: article
lang: en
translation_key: post.delivery.conform-online
translation_status: reviewed
title: "Conform and Online: Relink, Round-Trip, and Master"
summary: "Conform is not opening the edit in another app. It verifies every cut returns to the original media, every clip has enough handles, and every version traces to one master."
slug: conform-online
aliases: [conform-online]
canonical_site: post
canonical_path: /en/article/conform-online/
status: published
diagram: /images/diagrams/en/conform-online.svg
diagram_alt: "Conform and online round-trip diagram"
diagram_caption: "Diagram: a round-trip is not “it opened.” Every cut returns to source with handles."
difficulty: intermediate
stage: handbook
format: workflow
authors: ["TVCN Post Desk"]
last_verified: 2026-11-22
review_due: 2027-11-22
sources: [S23, S30, S34]
test_context: "Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci Resolve 20 and Premiere Pro 2025; results vary by machine."
known_failures: "Known failures: older-version timelines break; camera Logs need remapping; lost proxies require relinking."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/conform-online.svg" alt="Conform and online round-trip diagram">
  <figcaption>Diagram: a round-trip is not “it opened.” Every cut returns to source with handles.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>First decision: when Online is needed</h2><p>Online is needed when the film gets a grade, VFX, or multiple platform versions. A straight cut with no grade can finish in the NLE. The test is not runtime; it is whether the timeline returns to original media.</p><p>If the edit used proxies, transcodes, speed changes, or nests, Online must rebuild from source. Grading a proxy timeline is judging at low resolution.</p><h2>Round-trip: EDL/XML is an address, not media</h2><p>When exporting EDL/XML/AAF, confirm reel name, timecode, frame rate, and clip name. Filenames can change; timecode cannot. Leave at least 12–24 frames of handles at every cut for transitions, stabilization, denoise, and grading.</p><p>Check shot by shot after relink: source file, in point, out point, speed, transform, audio sync. Total duration matching does not mean every cut matches.</p><h2>Order of grade and VFX</h2><p>Do VFX before the final grade unless the VFX needs a graded background as reference. VFX before grade gives the compositor neutral footage; after grade means chasing a locked look and repeating notes.</p><p>Build separate versions for VFX shots instead of editing the master timeline. Label each version with VFX on/off, captions on/off, titles on/off. One master, many versions.</p><h2>Master and versions: naming beats software</h2><p>Keep one master: highest quality, no captions, no titles, no platform compression. Platform versions derive from it and never modify it. Filenames carry project, date, version, status; no final/final2.</p><p>Watch the master end to end before delivery: no black frames, offline media, wrong captions, or drift. Archive LUTs, fonts, music licenses, and output presets with the project.</p><h2>Failure case: the round-trip opened, every cut was wrong</h2><p>An ad edit used 120% speed changes and heavy nesting. The XML opened in the grade with the right duration, but every speed change pulled the wrong frames and transitions stretched. Two days of grading were wasted when the client saw the action was wrong.</p><p>The problem was not the software; speed and nests were not flattened and handles were missing. Conform starts with whether the timeline can be reconstructed, not whether it opens.</p><h2>Cost and acceptance</h2><p>Low: single-seat relink and basic check, ¥2,000–5,000. Mid: full conform, grade, VFX round-trip, version outputs, ¥5,000–20,000. High: multicam, multiple versions, HDR, separate captions/titles, ¥20,000–60,000+.</p><h2>Check</h2><ul><li>EDL/XML timecode, frame rate, and reel match.</li><li>Every cut has at least 12 frames of handles.</li><li>Shot check covers source, in/out, speed, and transform.</li><li>VFX versions are separate from the master.</li><li>One master; platform versions trace back.</li><li>Watch the master end to end before delivery.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S23]</span> SMPTE Standards</li><li><span class="mono">[S30]</span> DaVinci Resolve</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
