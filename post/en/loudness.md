---
id: post.sound.loudness.en
site: post
type: article
lang: en
translation_key: post.sound.loudness
translation_status: reviewed
title: 'Loudness: Platform Target and True Peak'
summary: Deliver to the platform's loudness target and leave true-peak headroom. Loud
  is not good.
slug: loudness
aliases:
- loudness
canonical_site: post
canonical_path: /en/article/loudness/
status: published
diagram: /images/diagrams/en/loudness.svg
diagram_alt: 'Structure diagram for Loudness: Platform Target and True Peak.'
diagram_caption: Watch “Mix to the platform target, commonly -14 LUFS.” and “Set true
  peak at -1 dB and leave”; judge whether removing one shot makes the scene faster
  rather than muddier.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Post Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [post.color.lut, post.delivery.mastering, shoot.camera.composition]
depth: deep
deep_minutes: 5
sources:
- S24
- S27
- S28
- S30
- S34
test_context: 'Review setup: Windows 11 (RTX 3060) + macOS 14 (M1); re-run in DaVinci
  Resolve 20 and Premiere Pro 2025; results vary by machine.'
known_failures: 'Known failures: older-version timelines break; camera Logs need remapping;
  lost proxies require relinking.'
verified: 2026-11-22
source_kind: sourced
---
<p>Make dialogue clear at normal monitoring, then match overall loudness to the platform target. Do not raise the master gain to rescue dialogue. Check true peak before export and leave 1–2 dB for encoding so platform compression does not clip.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/loudness.svg" alt="Structure diagram for Loudness: Platform Target and True Peak.">
  <figcaption>Watch “Mix to the platform target, commonly -14 LUFS.” and “Set true peak at -1 dB and leave”; judge whether removing one shot makes the scene faster rather than muddier.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">Dialogue first, platform target, true-peak headroom</h2><p>Targets differ by platform; check the current spec before delivery. If one master goes to several platforms, export separate versions rather than one universal file.</p><h2 id="section-2">Limits</h2><p>Louder is not better. Maxing music and relying on captions for dialogue may grab attention, but nobody finishes the film. If dialogue is unclear, go back to the mix, not the master fader.</p></section><section><h2 id="section-3">On set</h2><p>Platforms often target -14 LUFS with a -1 dB true peak. Mix to the target, leave 0.5 to 1 dB headroom, and do not slam the limiter.</p></section><section><h2 id="section-4">Do this</h2><p>Deliver to the platform loudness target and leave true-peak headroom. Loud is not better.</p><ol><li>Mix to the platform target, commonly -14 LUFS.</li><li>Set true peak at -1 dB and leave another 0.5 to 1 dB of margin.</li><li>Do not slam the limiter; go back to dialogue and dynamics.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not treat loudness as competition; a flattened limiter makes dialogue tiring.</p></section><section><h2>Judge</h2><p>This page passes on three observable checks, not slogans:</p><ul><li><strong>1.</strong> Integrated loudness sits near the platform target, not guessed by ear.</li><li><strong>2.</strong> True peak stays at or below -1 dB with no continuous red.</li><li><strong>3.</strong> Dialogue stays clear and music or ambience does not flatten the dynamics.</li></ul></section><section><h2>Failures</h2><p>Any one of these means stop and fix it before post:</p><ul><li><strong>1.</strong> Check 1 is only staged (“Integrated loudness sits near the platform tar…”); another camera position or location exposes it.</li><li><strong>2.</strong> Check 2 is left to post or a verbal explanation (“True peak stays at or below -1 dB with no cont…”); nothing on set can be rechecked.</li><li><strong>3.</strong> Do not treat loudness as competition; a flattened limiter makes dialogue tiring.</li></ul></section><section><h2>Extend</h2><p><strong>10-minute exercise:</strong> Take 30 seconds of footage and make an A/B, changing only “Mix to the platform target, commonly -14 LUFS.”. Note one timecode and one difference before keeping it.</p></section>
<h2>Check</h2><ul><li>Integrated loudness sits near the platform target, not guessed by ear.</li><li>True peak stays at or below -1 dB with no continuous red.</li><li>Dialogue stays clear and music or ambience does not flatten the dynamics.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 5 minutes.</strong> Loudness is not turning the volume up. It is making dialogue survive the platform, headphones, and a phone speaker.</p>
### LUFS is not a volume knob
<p>LUFS is the average loudness of the whole film, not a single second. Platforms often target -14 to -16 LUFS with true peak near -1 dB; check the platform’s current spec.</p><p>Make dialogue hold first, then add music and ambience. If music makes you push dialogue up, the final mix will be loud and unintelligible.</p>
### Check in this order
<p>Listen to dialogue alone, then with music, then with ambience. Play it on a phone speaker, headphones, and a laptop. A meter gives numbers; a line you cannot understand still needs a re-cut.</p><p>Mark the quietest line and the loudest line, and jump straight to both before delivery. If the extremes hold, the middle usually holds too.</p>
### A phone speaker is the final exam
<p>Play the film on a phone at half volume and stand two meters away. A line you cannot hear is a mix problem, not a listener problem.</p><p>A phone speaker removes low end; the more bass in the music, the muddier the dialogue. Protect the midrange before mood.</p>
### The balance of music and ambience
<p>In dialogue scenes, music stays under and ambience fills the room; only in wordless passages can music lead. Do not run music from first frame to last or the audience tires.</p><p>Every time you add a layer, solo the dialogue and confirm it still holds. If it does not, lower the new layer, do not push the dialogue.</p>
### Ten listening checks before delivery
<ul><li>Solo dialogue and confirm every line is intelligible</li><li>Add music and listen again</li><li>Add ambience and listen again</li><li>Play on a phone at half volume from two meters</li><li>Listen on headphones for sibilance and clipping</li><li>Listen once on a laptop speaker</li><li>Mark the timecode of the quietest line</li><li>Mark the timecode of the loudest line</li><li>Jump to both before delivery</li><li>Confirm true peak does not exceed minus one</li></ul><p>A loudness meter proves the number, not that the audience understood. The last pass belongs to your ears, not your eyes. Play it for someone who has not seen it and ask which line they missed; that is usually the fix.</p>
<!-- DEEP_DIVE_END -->

<!-- SOURCES_START -->
## References and further reading

- [S24] [ACESCentral: ACES](https://acescentral.com/) — Accessed 2026-11-27. Used to check the terminology and public context in the opening paragraph (“Deliver to the platform's loudness target and leave true-pea”) against ACES color encoding, ACEScg and delivery/archive workflows; not a substitute for an on-set test.
- [S27] [ITU-R: BS.1770 音频响度与真峰值测量](https://www.itu.int/rec/R-REC-BS.1770/en) — Accessed 2026-11-27. Used to check the terminology and public context in the opening paragraph (“Deliver to the platform's loudness target and leave true-pea”) against ITU algorithms for loudness measurement and true peak, the basis referenced by EBU R128; not a substitute for an on-set test.
- [S28] [Netflix Partner Help](https://partnerhelp.netflixstudios.com/) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Deliver to the platform's loudness target and leave true-pea”) against Public entry for delivery specs, HDR/SDR and QC; not a substitute for an on-set test.
- [S30] [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Deliver to the platform's loudness target and leave true-pea”) against Official entry for editing, grading, Fusion and delivery; not a substitute for an on-set test.
- [S34] [Adobe Premiere Pro Guide](https://helpx.adobe.com/premiere-pro/user-guide.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Deliver to the platform's loudness target and leave true-pea”) against Official docs for editing, proxies, color and export; not a substitute for an on-set test.
<!-- SOURCES_END -->

