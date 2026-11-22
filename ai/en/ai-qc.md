---
id: ai.post.ai-qc.en
site: ai
type: article
lang: en
translation_key: ai.post.ai-qc
translation_status: reviewed
title: "AI Post QC: Catch Generation Errors Before Delivery"
summary: "AI QC is not “does it look real.” Check in order: identity, motion, lip sync, text, physics, continuity, rights and disclosure. One failure stops the gate."
slug: ai-qc
aliases: [ai-qc]
canonical_site: ai
canonical_path: /en/article/ai-qc/
status: published
diagram: /images/diagrams/en/ai-qc.svg
diagram_alt: "Six-gate AI post QC diagram"
diagram_caption: "Diagram: pass six gates in order. If the first two fail, grading and music are wasted."
difficulty: intermediate
stage: handbook
format: workflow
authors: ["TVCN AI Desk"]
last_verified: 2026-11-22
review_due: 2027-11-22
sources: [S04, S05, S19, S20]
test_context: "Review setup: Windows 11 + Chrome 131; public web/API versions as of 2026-11; model versions change."
known_failures: "Known failures: model/API versions change; repeated runs differ; watermark and labelling rules update."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/ai-qc.svg" alt="Six-gate AI post QC diagram">
  <figcaption>Diagram: pass six gates in order. If the first two fail, grading and music are wasted.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>Set the acceptance floor first</h2><p>Write a floor: which errors are automatic fails (extra fingers, severed limbs, face change, completely wrong lip sync, garbled brand text), which are fixable (minor noise, edge flicker, small background objects). Without a floor, review becomes “generate one more” forever.</p><p>Watch every shot three times: normal speed for story, frame-by-frame for hands/eyes/edges, muted for lip and motion sync.</p><h2>Six gates: in order, no skipping</h2><p>Gate one, identity: face, hairline, wardrobe, build. Gate two, motion: continuity, time direction, intersections. Gate three, lip and voice: mismatch or a different voice fails. Gate four, text: on-screen words, logos, captions readable, no gibberish. Gate five, physics: shadows, reflections, gravity, liquids. Gate six, rights: footage, likeness, music, AI disclosure.</p><p>Do not pass a failed gate. Fix identity before grading, lip before music; wrong order doubles rework.</p><h2>Fix, not “roll again”</h2><p>Fix locally where possible: face replace, hand patch, lip fix, background text replace; use local repaint/comp rather than regenerating the whole shot. A full regeneration changes approved performance and light and sends you back to gate one.</p><p>Log every failure in one line: shot, error type, model/version, prompt version, fix, time. After ten, you know whether the model, prompt, or source is the problem.</p><h2>Delivery and disclosure: do not make the audience guess</h2><p>Disclose per platform: fully generated, live action with generated elements, live action with AI post are three different labels. Use title, description, or corner mark; do not hide it in small print. Real people, brands, and news need more specific labels.</p><p>Keep a generation log: model, date, prompt, seed, output. It is not for the audience; it is for traceability. Without it, you cannot prove which version is final.</p><h2>Failure case: face passed, hands failed</h2><p>An AI character short passed review on faces; identity looked strong. After delivery, the third shot had six fingers around a cup and the fifth had fingers through the cup wall. A full regeneration changed the face, forcing a return to the first version for local comp.</p><p>The fix is not “AI does that”; it is the six gates. Check face and hands separately, fix locally first, regenerate the whole shot last.</p><h2>Cost and acceptance</h2><p>Low: manual frame-by-frame QC plus local fixes, ¥2,000–6,000. Mid: QC sheet, local repaint, lip/text repair, ¥6,000–20,000. High: multi-model comparison, compositor, legal/rights review, ¥20,000–60,000+.</p><h2>Check</h2><ul><li>Floor lists automatic fails and fixable errors.</li><li>Every shot checked normal, frame-by-frame, muted.</li><li>Six gates pass in order, no skipping.</li><li>Local fixes first; full regeneration last.</li><li>Failure log has model, prompt, fix, time.</li><li>AI label matches platform and content type.</li></ul>
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S04]</span> China's Interim Measures for Generative AI Services</li><li><span class="mono">[S05]</span> EU AI Act policy page</li><li><span class="mono">[S19]</span> Generative Adversarial Nets (2014)</li><li><span class="mono">[S20]</span> Denoising Diffusion Probabilistic Models (2020)</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
