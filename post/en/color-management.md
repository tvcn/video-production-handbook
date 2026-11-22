---
id: post.color.color-management.en
site: post
type: article
lang: en
translation_key: post.color.color-management
translation_status: reviewed
title: "Color Management: Put the LUT in the Right Place"
summary: "Color management is not applying a cinematic LUT. It answers what the source space is, what the monitor is, and what delivery needs, then puts the transform on the right node."
slug: color-management
aliases: [color-management]
canonical_site: post
canonical_path: /en/color/color-management/
status: published
diagram: /images/diagrams/en/color-management.svg
diagram_alt: "Color-management node diagram"
diagram_caption: "Diagram: every arrow is a transform. Putting a look LUT before the input transform crushes every source together."
difficulty: intermediate
stage: handbook
format: workflow
authors: ["TVCN Post Desk"]
last_verified: 2026-11-22
review_due: 2027-11-22
sources: [S24, S25, S30]
test_context: "Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci Resolve 20 and Premiere Pro 2025; results vary by machine."
known_failures: "Known failures: older-version timelines break; camera Logs need remapping; lost proxies require relinking."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/color-management.svg" alt="Color-management node diagram">
  <figcaption>Diagram: every arrow is a transform. Putting a look LUT before the input transform crushes every source together.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>Separate the four spaces</h2><p>A film has at least four spaces: capture (S-Log3, LogC, RAW), working (ACES or DaVinci Wide Gamut), display (Rec.709, P3, HDR PQ), and delivery (platform Rec.709, HLG, PQ). Mix them and the LUT becomes a guess.</p><p>Match each source to the correct input transform: camera, gamut, gamma, matrix. If it is missing, shoot a grey card or color chart and build it manually; do not use a “close enough” LUT.</p><h2>Where the LUT goes: three nodes, no stacking</h2><p>The input transform creates the working space; the creative LUT sits inside it; the display transform sits before the monitor; the delivery transform sits before output. A common error is putting a Rec.709 look LUT on Log footage, then another display LUT, crushing highlights twice.</p><p>Each LUT answers one question: transform, look, or calibration. If it cannot answer, do not stack it. Name nodes input/look/display/delivery so the next artist can read the tree.</p><h2>Monitor and calibration: trust the screen before the eye</h2><p>Calibrate the monitor before grading: white point, gamma, gamut, luminance. Without calibration, every decision is true on this screen and false elsewhere. Check black, white, and skin with a grey ramp and color chart.</p><p>Do not judge on an office monitor; its contrast and gamut flatten shadows. Client review must use the same display transform, or “the client sees it differently” is usually a different screen, not a bad grade.</p><h2>Handoff: deliver LUT, node tree, and references together</h2><p>The handoff includes project file, LUTs, input-transform notes, display-transform notes, reference frames, and a limit list. Sending one LUT without its position is sending nothing.</p><p>Mark each reference “light” or “color”: light means direction, softness, ratio; color means white point, skin, saturation. Mixed references make the colorist guess.</p><h2>Failure case: one LUT on every camera</h2><p>A three-camera interview used three camera models and one “film LUT” on all sources. A went green in skin, B went grey in highlights, C went red in shadows. The colorist blamed the lighting until realizing the input transforms were never separated.</p><p>The fix is per-camera input transforms into one working space, then one creative LUT. Multicam starts with correct transforms, not “looks the same.”</p><h2>Cost and acceptance</h2><p>Low: input-transform cleanup and one display calibration, ¥2,000–6,000. Mid: full color management, node tree, handoff pack, ¥6,000–20,000. High: ACES pipeline, dual HDR versions, on-set DIT, ¥20,000–60,000+.</p><h2>Check</h2><ul><li>Every source has a named input transform.</li><li>Working, display, and delivery spaces are written separately.</li><li>One creative LUT sits on the correct node.</li><li>Monitor is calibrated; grey ramp and color chart pass.</li><li>References are marked light or color.</li><li>Handoff includes LUTs, node tree, and limits.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S24]</span> ACES Color Management</li><li><span class="mono">[S25]</span> ITU-R BT.709</li><li><span class="mono">[S30]</span> DaVinci Resolve</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
