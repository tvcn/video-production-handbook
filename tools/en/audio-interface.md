---
id: tools.capability.audio-interface.en
site: tools
type: tool
lang: en
translation_key: tools.capability.audio-interface
translation_status: reviewed
title: 'Audio Interface: Inputs and Gain'
summary: Check input count, gain range, and noise floor; a expensive interface with
  low gain cannot record a whisper.
slug: audio-interface
aliases:
- audio-interface
canonical_site: tools
canonical_path: /en/article/audio-interface/
status: published
diagram: /images/diagrams/en/audio-interface.svg
diagram_alt: 'Structure diagram for Audio Interface: Inputs and Gain.'
diagram_caption: Watch “Connect a dynamic mic and set gain to” and “Record thirty
  seconds of silence and listen to”; judge whether the spec maps to one concrete shooting
  problem.
difficulty: beginner
stage: field-note
format: handbook
authors:
- TVCN Tools Desk
last_verified: '2026-11-26'
review_due: '2027-02-26'
related: [tools.guide.audio-noise-fix, tools.audio.audio-position, shoot.camera.axis-line]
sources:
- S23
- S31
- S29
- S30
- S70
source_kind: sourced
---
<p>If you only need one lav into a camera, an interface is an extra link; solve mic distance and gain first. Do not replace recording basics with more boxes.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/audio-interface.svg" alt="Structure diagram for Audio Interface: Inputs and Gain.">
  <figcaption>Watch “Connect a dynamic mic and set gain to” and “Record thirty seconds of silence and listen to”; judge whether the spec maps to one concrete shooting problem.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<section><h2 id="section-1">What to compare first</h2><ul><li><strong>Inputs and gain:</strong> confirm the preamp has enough gain for your mic and the noise floor at maximum is acceptable.</li><li><strong>Channels and monitoring:</strong> how many independent inputs, direct monitoring and headphone output; live work also needs a return.</li><li><strong>Connection and power:</strong> is USB bus power stable, or does it need a supply? Will a long cable add noise?</li></ul><h2 id="section-2">When not to use it</h2></section><section><h2 id="section-3">On set</h2><p>Connect a dynamic mic at 70 percent gain and record thirty seconds of silence. Listen to the noise floor and check the maximum gain.</p></section><section><h2 id="section-4">Do this</h2><p>An audio interface is judged by input count, gain range, and noise floor; a pricey box with too little gain cannot record quiet speech.</p><ol><li>Connect a dynamic mic and set gain to 70 percent.</li><li>Record thirty seconds of silence and listen to the noise floor.</li><li>Check whether maximum gain is enough for quiet dialogue.</li></ol></section><section><h2 id="section-5">Avoid</h2><p>Do not count inputs only; without gain, quiet dialogue is all noise floor.</p></section>
<h2>Check</h2><ul><li>A dynamic mic records thirty seconds of silence at 70 percent gain.</li><li>The noise floor is described, not just “fine.”</li><li>Maximum gain captures quiet dialogue with acceptable noise.</li></ul>


> Intent split: this page covers the practical details of “Audio Interface: Inputs and Gain”; start with <a href="https://tools.tvcn.org/article/lav-hidden/">Lav Hiding: Collar, Hair, Tape</a> for the cluster-level judgement, then return here.

<!-- INTENT_SCOPE -->

<!-- SOURCES_START -->
## References and further reading

- [S23] [SMPTE Standards](https://www.smpte.org/standards) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Check input count, gain range, and noise floor; a expensive ”) against Entry point for timecode, color, cinema and signal-chain standards; not a substitute for an on-set test.
- [S31] [ARRI Cine Systems](https://www.arri.com/en/cine-systems) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Check input count, gain range, and noise floor; a expensive ”) against Technical documentation for cameras, lenses and lighting; not a substitute for an on-set test.
- [S29] [YouTube Upload Specs](https://support.google.com/youtube/answer/1722171) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Check input count, gain range, and noise floor; a expensive ”) against Recommended resolution, bitrate, frame rate and audio codec; not a substitute for an on-set test.
- [S30] [DaVinci Resolve](https://www.blackmagicdesign.com/products/davinciresolve) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Check input count, gain range, and noise floor; a expensive ”) against Official entry for editing, grading, Fusion and delivery; not a substitute for an on-set test.
- [S70] [FFmpeg: Documentation](https://ffmpeg.org/documentation.html) — Accessed 2026-11-26. Used to check the terminology and public context in the opening paragraph (“Check input count, gain range, and noise floor; a expensive ”) against Codec, muxing and filter documentation; not a substitute for an on-set test.
<!-- SOURCES_END -->

