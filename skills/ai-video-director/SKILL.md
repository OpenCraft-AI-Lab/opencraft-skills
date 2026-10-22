---
name: ai-video-director
description: "Plan, make, edit, or review a multi-shot AI-generated product ad or short drama. Use when shot roles, visual continuity, character or product references, clip selection, sound, and the final cut must work together. Skip for a single isolated video prompt or ordinary talking-head editing."
---

# AI video director

Turn a brief and generated clips into a coherent short film. This skill distills three EP11 productions made with Meta Muse and edited with Claude, FFmpeg, and ChatCut. Apply the production reasoning to other generators only after checking their current inputs, output formats, costs, and usage terms.

## Choose the film form

- **Product ad:** the viewer must recognize the same product across shots, follow one visual reveal, and see a readable final product and brand. Read [product ads](references/product-ads.md). The [perfume example](references/examples/perfume-ad.md) shows a rejected first structure, a locked bottle, and a rebuilt cut.
- **AI short drama:** the viewer must understand a causal sequence, stable characters and world, and the intended ending. Read [AI short dramas](references/ai-short-dramas.md). The [tiny courier example](references/examples/tiny-courier.md) shows a silent miniature gag and scale; [Cloud Nine](references/examples/cloud-nine.md) shows an ensemble story with dialogue and sound repair.

Use the shared [production workflow](references/production-workflow.md) for briefs, shot records, generation rounds, edit decisions, and verification. Read only the chosen form guide and the example useful to the current problem. For a small revision, start from the existing approved cut and its recorded defect; do not restart the entire film.

## Decisions that matter

1. Define what the viewer must see or understand at the end. Build shots backward from that result. Give each shot a distinct job and a testable on-screen event.
2. Lock the subject and world in still references before expanding video rounds. For an ad, check physical product truth even in silhouette. For a drama, check identity, geography, and scale with visible anchors.
3. Test the highest-risk one or two shots before filling the plan. Treat a generated clip as raw footage: inspect the actual frames, select the useful action window, then decide whether a retry, a cut, or a local repair is warranted.
4. Judge transitions on both sides of every cut. Match relevant position, scale, light state, motion, prop state, and sound. A shared shape alone may still feel like a different world.
5. Separate what the generator produced from what the editor, voice tool, or music tool added. Preserve originals and record selections, rejected candidates, edits, creator decisions, and unverified checks.

## Authorization and evidence

Advance only through the step the user requested. In OpenCraft production, present each creative gate for the creator's decision. A plan or request to revise footage does not authorize spending generation credits, uploading assets, exporting, or publishing; do those actions only when specifically requested. Do not add subtitles or captions in OpenCraft work unless requested. Existing approvals apply to their recorded versions; keep approved parts when repairing a local defect.

Check the current tool and account before making claims about free access, quotas, model specifications, or feature availability. EP11 file measurements and account observations are historical case evidence, not current product promises. Report whether picture was inspected as stills, played through, heard, and checked after export; these are different levels of verification. Automated transcription, a waveform, and a frame strip do not replace listening and full playback.
