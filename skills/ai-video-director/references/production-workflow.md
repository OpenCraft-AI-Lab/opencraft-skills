# Production workflow

Use the requested step only. Keep a small decision record so a later editor can explain why each shot and cut exists. Examples in this skill come from a Muse account in October 2026; verify the active generator's capabilities and terms at the time of use.

## 1. Brief and acceptance test

Agree on film form, viewer, platform and aspect ratio, intended duration, product or story premise, ending, brand or character constraints, voice and music treatment, available references, and the limit on generation rounds. Make the acceptance test observable: for example, “the fill line remains visible in the dark opener” or “the viewer sees the cat place the tip before the courier reacts.” If a decision belongs to the creator, present a small set of concrete alternatives and record the selection. Do not infer permission to generate from a request to plan.

## 2. Shot map and reference lock

Make a shot table with these fields; add only fields the project needs:

| Field | Question |
| --- | --- |
| ID and story job | What new information or feeling does this shot carry? |
| Start frame and anchors | Which approved subject, location, prop, lighting and aspect references control it? |
| On-screen action | What single observable event must happen, and when? |
| Ending state | What frame, motion, light, prop or sound will hand off to the next shot? |
| Dialogue and sound | Which words belong here, and what must be heard? |
| Acceptance and risks | What would reject this candidate? What can be fixed in the edit? |

Save the accepted subject stills and their identifiers. Inspect at the final viewing size. A still is accepted only if the defining trait reads, not merely if the image is attractive. Keep a separate list of rejected frames and the reason; never silently treat the generator's self-review as inspection.

## 3. Risk-first test, then generation rounds

Choose one or two shots that test the central uncertainty before generating the full slate. In a product film this may be the hero product under the planned light. In a drama it may be the scale, interaction, or hardest character move. Use the approved still as the video start frame where the tool supports it. Ask for one primary action per clip and an early action window, then inspect when it actually occurs. A requested three-second action may take most of a generated ten-second file.

Batch only after the test teaches something useful. For each generation, record the exact input, reference IDs, output filename, model/settings if known, date, observed duration and format, visible result, failure or rejection, and whether the creator selected it. Record actual charges or usage only from the account evidence; leave unknowns unknown. Keep original files unchanged. A practical layout is `inputs/`, `outputs/`, `qc/`, and `selected/`; the editor imports selected source or an explicitly documented derivative.

When drafting a shot request, make its constraints inspectable. A compact pattern is: **approved reference IDs → subject/world traits to preserve → start-frame composition → one action and its intended timing → camera/light movement → end state needed by the next cut → dialogue/sound → rejection criteria**. Use the fields the generator supports; do not pretend unsupported controls or an exact timing guarantee. Preserve the final request text so a retry can change one cause at a time.

When a result fails, identify the smallest cause before retrying. A composition pulled wide by a second reference may call for a start-frame-only test; a slow light move may be solved by trimming or speed; an invented prop or broken action may require a new clip. Treat those as diagnoses to verify, not universal model rules. Stop retrying when a structural change, a local edit, or a different concept will address the problem more reliably.

## 4. Select and edit the real action

Create an edit decision list with source file, in/out time, speed, timeline position, sound source, and transition. Keep the useful action, not the entire generated duration. Check the last and first frames of adjacent shots for position, scale, light direction and brightness, motion direction, character or product state, and props. A match cut should connect the same subject or story world, not just two similar silhouettes. Confirm the timeline frame rate after duplicating or moving a cut; frame numbers copied between different rates can change duration and source out points.

For sound, compare source clips before simply turning them up: generated air tone, sudden silence, stray speech, and doubled dialogue can become prominent. Use a continuous ambience bed or short J/L cuts where they help, then listen across every join. If the creator says “echo,” identify whether it is reverberation, duplicated speech, or a different voice before choosing a repair. Plan music cuts against the chosen track's actual beats and audition them; a text prompt cannot guarantee the requested beat timing. Preserve a continuous music phrase when a picture repair can be made around it.

## 5. Review and verification

Inspect contact sheets or sparse frame strips to screen candidates, then look more densely at action peaks and every cut point. Play the composed film from start to finish at normal speed and at the intended viewing size. Listen on the actual mixed timeline. Check dialogue against the visible speakers; speech recognition can flag a duplicate but does not prove natural sound. Ask the creator to judge the current version at the agreed checkpoint and record the exact verdict and affected version. Repair the rejected part while preserving approved material.

Before reporting completion, distinguish these states: **source inspected**, **timeline frames inspected**, **full playback watched**, **mix heard**, **export inspected**. Describe any unchecked state plainly. Export and inspect only when that action was requested. A rendered file should be checked for the intended duration, picture and audio streams, cut boundaries, dialogue and sound, and any difference from the editable timeline. Do not claim an exported master from an approved timeline alone.
