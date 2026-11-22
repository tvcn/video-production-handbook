---
id: ai.generation.ai-shot-list.en
site: ai
type: article
lang: en
translation_key: ai.generation.ai-shot-list
translation_status: reviewed
title: "AI Shot List: One Prompt, One Shot"
summary: "One prompt, one shot. Three events in one prompt become a random montage."
slug: ai-shot-list
aliases: [ai-shot-list]
canonical_site: ai
canonical_path: /en/generation/ai-shot-list/
status: published
diagram: /images/diagrams/en/ai-shot-list.svg
diagram_alt: "AI Shot List: One Prompt, One Shot three-step diagram"
diagram_caption: "Do the three steps in order, then look again at the image or file."
difficulty: beginner
stage: field-note
format: handbook
authors: [editor]
last_verified: 2026-11-20
review_due: 2027-05-20
related: [main.paths.first-film]
depth: deep
deep_minutes: 6
---

<p>One prompt, one shot. Three events in one prompt become a random montage.</p>
<!-- DIAGRAM_START -->
<h2>Diagram</h2>
<figure>
  <img src="/images/diagrams/en/ai-shot-list.svg" alt="AI Shot List: One Prompt, One Shot three-step diagram">
  <figcaption>Do the three steps in order, then look again at the image or file.</figcaption>
</figure>
<!-- DIAGRAM_END -->
<h2>On set</h2>
<p>One prompt per shot, three to five seconds. The shot list records number, prompt, reference, and start and end frames; name outputs by shot number.</p>
<h2>Do this</h2>
<p>One prompt, one shot. A prompt with three events becomes a random cut.</p><ol><li>Each prompt covers one shot of three to five seconds.</li><li>The sheet lists shot number, prompt, reference, first and last frame.</li><li>Name outputs by shot number so the edit can find them.</li></ol>
<h2>Avoid</h2>
<p>Do not put three events in one prompt; the model cuts them into chaos.</p>
<h2>Check</h2>
<ul><li>Each prompt maps to one shot and a three-to-five-second duration.</li><li>The sheet has shot number, prompt, reference, and first/last frame columns.</li><li>Output files are named by shot number and match the edit directly.</li></ul>

<!-- DEEP_DIVE_START -->
## Deep dive
<p><strong>About 6 minutes.</strong> An AI shot list is not for generating the whole film in one go. It makes every shot answer one question.</p>
### One prompt, one shot problem
<p>Write subject, action, environment, and camera in four parts, but change one variable at a time. Test the face today and blocking tomorrow; change five phrases at once and you will not know what worked.</p><p>One action per shot. If the character opens a door, turns, and speaks, make three prompts. The generator will not board the scene for you.</p>
### How to accept an AI shot
<p>Check four things: is it the same person, does the motion break, does the light match the previous shot, and are there extra fingers or text. Generate three takes and choose the one whose worst take is still usable, not the beautiful exception.</p><p>Log each failure in one line: face, hand, wardrobe, light. After ten tries you will know whether to change the tool or the prompt.</p>
### Writing the four parts
<p>Subject is appearance and identity; action is one verb; environment is light and space; camera is size and movement. One sentence per part, not three adjectives in one.</p><p>Writing in one language and translating often loses concrete nouns. Use words that describe visible things or the model has to guess.</p>
### The failure log
<p>Log four columns per generation: take number, what broke, what changed, whether it improved. Without the log you will fall into the same hole twenty times.</p><p>Review weekly and separate “change tool” from “change prompt.” Most failures are not a stupid model; they are too many changes in one prompt.</p>
### Ten things to lock before generating
<ul><li>Change one variable per prompt</li><li>Subject is appearance and identity, not personality</li><li>Action is one verb</li><li>Environment is light and space</li><li>Camera is size and movement</li><li>Generate three takes per shot</li><li>Choose the take whose worst version still works</li><li>Log failures by face, hand, wardrobe, light</li><li>Fix reference and seed for the same character</li><li>Compare consistency every five shots</li></ul><p>An AI shot list does not make the model direct for you; it turns your judgment into a reproducible page. Save the successful prompt as text in the project file, not a screenshot; next week you will need that exact line again.</p>
<!-- DEEP_DIVE_END -->
