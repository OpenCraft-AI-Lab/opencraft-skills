# Example: Cloud Nine, a dialogue AI short drama

**Form:** ensemble romance with four planned dialogue lines. **Production:** EP11, October 2026. The creator supplied an existing nine-shot, 90-second Muse script and the Muse film. Claude subsequently diagnosed and edited it; ChatCut was used for the approved cut and music. The available records do **not** establish that Claude directed the original Muse generation or that every original shot used end-frame chaining.

## Story jobs before duration

The script fixed Liam, Ava, a wordless pilot, a balloon, a golden-hour valley and a ring box. Its nine ten-second shots had jobs: ascent, ring-box clue, shared view, ground-sign reveal, question, answer, celebration, ring detail and final wide view. Dialogue belonged only at four turning points. This is a useful plan because a finished edit can preserve the necessary beats while dropping long holds. The source's 90 seconds did not oblige a 90-second final film.

## Diagnose the actual defect

The creator first described “echo.” Audio inspection found that the proposal line occurred twice, while the other three planned lines occurred once. The second version therefore removed the repeated words instead of treating every voice as reverberation. Later experiments separated voice from music/wind, generated replacement speech, and tried a generated crying sound. The final ChatCut **v5** used selected original generated speech rather than the replacement TTS, with separate music and ambience. Each change was recorded as post work and checked for where the words landed, but transcription alone did not prove the mix sounded natural.

The edit compressed the film to roughly **35 seconds** by retaining the reveal, question, answer, ring and closing view. A brief broken shot around 26–27 seconds showed the couple without their balloon. The creator asked to remove it while keeping the music continuous. A first repair cut the music with the picture; the creator rejected its audible seam. The accepted repair shortened the broken picture and extended the continuous ring shot to fill the time, returning the music to its previous phrase. A stray “whoosh” at the join came from residual source audio that extended beyond a source-clip boundary; the audio in that section was replaced with a later clean portion and fades.

## Reusable decisions and limits

- Give every generated clip one narrative job. Keep only the beats the audience needs in the final edit.
- A user's sound description is a symptom. Confirm whether it is duplicate speech, reverb, an audio boundary, or voice mismatch before processing it.
- When picture and music conflict, try a picture-only repair that leaves an approved musical phrase intact.
- Verify dialogue line count, character voice and mouth timing separately; a transcript can assist but cannot replace listening.

**Verification boundary:** The creator approved ChatCut v5 and specifically requested its export. The exported file was inspected for duration, streams, expected visual cut points and one occurrence of each planned line in transcription. The record explicitly says the exported sound had **not** been checked by human listening. It is an approved and exported cut, with that audio verification still open.

**Production evidence in `OpenCraft-Production`:** `ep11_muse_free_ai_video/3-media/gen/muse-demo/RUN.md`, `inputs/cloud-nine-original-nine-clip-script.md`, `inputs/cloud-nine-cut-v4-edl.txt`, and `3-media/graphics/muse-stories-v1/README.md`.
