---
id: post.sound.sound.en
site: post
type: article
lang: en
translation_key: post.sound.sound
translation_status: reviewed
translation_reviewed: 2026-11-21
title: "Sound: Dialogue First, Music Later"
summary: "An audience can forgive a rough image, but not dialogue they cannot hear. Clean the voice first, then add music and atmosphere."
slug: sound
aliases: [sound]
canonical_site: post
canonical_path: /en/sound/sound/
status: published
difficulty: beginner
stage: edit
format: short-film
tools: []
authors: ["TVCN Post Desk"]
reviewers: [technical-reviewer]
cover: /images/post/sound.webp
diagram: /images/diagrams/en/sound.png
diagram_alt: "Sound order: dialogue first, music last"
diagram_caption: "Audiences forgive rough images, not muddy dialogue. Clean every word first, then add music. Music over dialogue kills the film."
last_verified: 2026-11-20
review_due: 2027-05-20
source_kind: experience
related: []
sources: [S24, S27, S28, S30, S34, S35]
test_context: "Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci Resolve 20 and Premiere Pro 2025; results vary by machine."
known_failures: "Known failures: older-version timelines break; camera Logs need remapping; lost proxies require relinking."
verified: 2026-11-22
---

<!-- DIAGRAM_START -->
## Diagram

<figure>
  <img src="/images/diagrams/en/sound.png" alt="Sound order: dialogue first, music last">
  <figcaption>Audiences forgive rough images, not muddy dialogue. Clean every word first, then add music. Music over dialogue kills the film.</figcaption>
</figure>
<!-- DIAGRAM_END -->

An audience can forgive a rough image, but not dialogue they cannot hear. Clean the voice first, then add music and atmosphere.

## Dialogue is the spine

Fix the voice first: denoise, remove mouth clicks, match levels, and make every line intelligible. Do not lay music over noisy dialogue; that only covers the problem.

If the location audio is unusable, consider ADR instead of replacing the voice with subtitles. Subtitles are support, not a substitute for sound.

## Ambience is space

Record 30 seconds of clean room tone or ambience at every location. Lay it under the cut so shot changes do not feel like jumps in a vacuum.

Ambience is not noise. It tells the audience “this is a kitchen, a street, a valley.” Without it, the image feels thin.

## Do not fill every second with music

Music is punctuation, not wallpaper. Save it for turns, decisions, and endings; let silence carry pressure. Build a version without music first, confirm the structure, then add it.

If the film falls apart when you remove the music, the problem is the cut, not the score.

## Three checks

- Every line is intelligible without guessing from subtitles.
- Every location has ambience.
- At least one moment deliberately uses silence.
<!-- SOURCES_START -->
<h2>Sources</h2>
<p class="source-types">Experience: TVCN field notes and project reviews; tested: the review setup and reproducible exercises noted on the page; references: public links below.</p>
<ul><li><span class="mono">[S24]</span> ACES Color Management</li><li><span class="mono">[S27]</span> EBU R128 Loudness</li><li><span class="mono">[S28]</span> Netflix Partner Help</li><li><span class="mono">[S30]</span> DaVinci Resolve</li><li><span class="mono">[S34]</span> Adobe Premiere Pro Guide</li><li><span class="mono">[S35]</span> Avid Resource Center</li></ul>
<p><a href="../../SOURCES.md">Full links and notes in SOURCES.md</a></p>
<!-- SOURCES_END -->
