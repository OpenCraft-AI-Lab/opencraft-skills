# Example: Tiny Courier, a miniature AI short drama

**Form:** visual gag with a causal ending. **Production:** EP11, October 17–19, 2026. Muse generated the stills and clips; Claude assembled local previews; ChatCut held a later music and voice version. The creator chose a landscape, 16:9 miniature courier story after an earlier Medusa concept.

## Story and risky test

Sam, about 14 cm tall, carries a soup dumpling across a kitchen to a house cat. The cat gives him one kibble as a tip. The tip is the ending, so the shot map works backward: departure, chopstick bridge, cat approach, worried reaction, phone insert, delivery and gulp, paw placing kibble, Sam's stare. The character's yellow jacket and orange bag, the cat, morning kitchen light and known objects such as a coin, chopsticks and fork were specified as anchors. Those objects had to *appear* beside Sam for the scale to read.

The creator asked to see one or two moving shots first. Sam's departure and the cat's approach were tested before completing the slate. The scale largely held, but a requested early walk took roughly 7–8 seconds in the generated clip. The edit could use only the action-bearing portion. One still made the kibble too small for the joke; it was revised before the final reaction. This shows why the ending's readable object size belongs in the acceptance test.

## Edit revision

The first local preview used seven source shots and ran about 26.5 seconds. The creator accepted the footage but wanted a tighter edit. A shorter version still felt rough: sound jumped at cuts, a silent phone insert broke ambience, Sam appeared to jump from the cat to a kibble that seemed to arrive from nowhere, one face smeared late in its source clip, and the bridge shot cut before the intended wobble. These were identified from the source windows and cut points, not fixed by generating the whole story again.

The later cut kept the action peaks, opened the final shot on the cat's paw *placing* the kibble, and used an ambience bed with short audio overlaps. The approved **v4** was **12.4 seconds**. It was a case-specific edit result, not a target duration for all short dramas. A ChatCut version later added approved generated music and Alex voice lines; those additions were post work, not Muse output.

## Reusable decisions and limits

- Write the punchline first and ensure every earlier shot makes it legible.
- Put concrete scale markers in the image and test the hardest physical interaction before expanding the shot list.
- Ask for one action per generated clip, but trim to the actual action even if the source is much longer.
- At a cut, preserve the cause of the next reaction. Inspect both the source picture and the sound seam.

**Verification boundary:** The creator approved the local v4 cut. The run record says its sound had not been listened to, and the subsequent ChatCut music/voice mix had not been listened to or exported. The approved picture and a fully verified finished audio mix are different claims.

**Production evidence in `OpenCraft-Production`:** `ep11_muse_free_ai_video/3-media/gen/muse-tiny-courier/RUN.md`, `inputs/shot-plan-tiny-courier-v1.md`, `inputs/preview-cut-v4-edl.txt`, and `3-media/graphics/muse-stories-v1/README.md`.
