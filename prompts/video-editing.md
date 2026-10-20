# Bounded video edits

[Catalog](README.md) · [Official editing examples](../docs/official-examples.md#o07)

Use an authorized source clip whose content matches the input description. Each prompt names the edit and the parts to preserve; the result still needs comparison against the source.

<a id="k082"></a>
## K082 — Remove a foreground shopping bag

**Use:** clear a storefront view. **Mode:** video edit. **Brief:** preserve source duration and framing. **Inputs:** a short storefront clip with an unwanted bag in the lower foreground.

```text
Edit @Video1. Remove only the red shopping bag resting in the lower-left foreground. Reconstruct the paving and lower storefront area it covers, using the surrounding lines, texture, and changing perspective. Preserve the storefront, all people, their movements, reflections, camera path, lighting, audio, framing, and duration. The restored region should remain consistent as the camera moves. Keep every object outside the bag's outline unchanged. Retain the source sound exactly and add no subtitles or music.
```

**Adjust:** target description to match the source. **Review:** paving lines continue; no residual bag shadow; unaffected motion matches source.

<a id="k083"></a>
## K083 — A paper rabbit in a real room

**Use:** local character restyling. **Mode:** video edit. **Brief:** preserve source timing. **Inputs:** a clip of one toy rabbit moving across a tabletop.

```text
Edit @Video1. Change only the toy rabbit into an origami-style paper rabbit with visible folds, matte cream paper, and the same overall size. Preserve its path, pauses, head direction, and contact with the table. Keep the room, tabletop, camera motion, lighting, other objects, audio, and duration unchanged. Let the paper ears flex slightly while the folded body retains a coherent structure. Match the new rabbit's contact shadow to the original lighting. Add no titles, speech, or music.
```

**Adjust:** paper color and fold detail. **Review:** edit follows the rabbit only; path matches source; room retains its original material.

<a id="k084"></a>
## K084 — Change the wall color

**Use:** interior color exploration. **Mode:** video edit. **Brief:** preserve source framing and length. **Inputs:** a room clip with a clear rear wall.

```text
Edit @Video1. Change the rear wall from its current color to muted sage green, retaining the original plaster texture and the brightness differences created by window light. Preserve furniture, frames, skirting boards, ceiling, floor, people, camera movement, reflections, and audio. Keep the paint boundary aligned to the wall edges throughout the shot. Objects passing in front of the wall retain their original colors. The edit changes the wall surface only, with no new decor, subtitles, or music.
```

**Adjust:** paint color. **Review:** boundary accuracy during motion; preserved texture; foreground colors remain unchanged.

<a id="k085"></a>
## K085 — Replace the table centerpiece

**Use:** alternate hospitality styling. **Mode:** video edit. **Brief:** source duration. **Inputs:** dining-table clip and reference photo of a small ceramic vase.

```text
Edit @Video1. Replace the single centerpiece on the middle of the dining table with the vase shown in @Image1. Use @Image1 only for the vase's shape, glaze, and proportions. Match the original centerpiece's approximate height and table position. Preserve the plates, glasses, chairs, people, camera path, lighting, audio, and duration. Recreate the vase's reflection and contact shadow according to the source scene. Keep all movement outside the centerpiece region unchanged. No flowers, new tableware, captions, or added music.
```

**Adjust:** vase reference. **Review:** scale fits table; occlusions remain correct; reflections correspond to replacement.

<a id="k086"></a>
## K086 — Calm the curtain movement

**Use:** reduce a distracting local action. **Mode:** video edit. **Brief:** source duration. **Inputs:** room clip with a strongly moving curtain.

```text
Edit @Video1. Reduce only the curtain's movement to a slow, shallow sway beside the window. Preserve its color, length, folds, attachment points, and transparency. Keep the window, outdoor view, furniture, people, camera motion, light direction, audio, and duration unchanged. The curtain should still respond gently to air rather than becoming a rigid sheet. Preserve correct occlusion where it passes in front of the sill. Add no text, dialogue, or music.
```

**Adjust:** desired sway amplitude. **Review:** curtain stays attached; source actions outside it match; transparency remains consistent.

<a id="k087"></a>
## K087 — A different jacket color

**Use:** wardrobe color variation. **Mode:** video edit. **Brief:** source timing. **Inputs:** an authorized adult walking in a plain jacket.

```text
Edit @Video1. Change only the adult's jacket fabric to deep burgundy. Preserve the jacket cut, seams, buttons, wrinkles, and shading, along with the person's face, hair, skin, other clothing, body motion, and hand positions. Keep the background, camera movement, lighting, sound, framing, and duration unchanged. The color must remain attached to the jacket as arms cross the torso and the person turns. Preserve highlights and dark folds rather than applying a flat overlay. No new logos, captions, speech, or music.
```

**Adjust:** fabric color. **Review:** mask follows cuffs and collar; skin untouched; fold shading retained.

<a id="k088"></a>
## K088 — The unexpected scarf

**Use:** revise a short comic ending. **Mode:** video edit. **Brief:** preserve source length. **Inputs:** a clip of an adult opening a drawer at the end, plus a scarf reference.

```text
Edit @Video1. Preserve the opening and middle of the clip. When the adult opens the drawer in the final scene, show the folded striped scarf from @Image1 inside it in place of the original single object. Preserve the drawer's motion, the person's identity, hand movement, camera, lighting, and timing. Replace only the final spoken line with, "So that is where it went." Keep the same speaker and natural delivery, and retain the remaining source audio. The scarf stays inside the drawer. No added subtitles or music.
```

**Adjust:** reference object and final line together. **Review:** edit begins at reveal; lip sync matches replacement line; earlier frames remain consistent.

<a id="k089"></a>
## K089 — Recast a rehearsal room

**Use:** change scene ingredients while retaining performance. **Mode:** video edit. **Brief:** source duration. **Inputs:** authorized single-performer clip, new authorized performer image, empty studio image.

```text
Edit @Video1. Replace the adult performer with the adult in @Image1, using that image for face, hair, and clothing. Replace the room with the studio in @Image2, preserving a compatible floor plane and camera perspective. Keep the source performance, hand gestures, travel path, shot timing, camera motion, and audio. Match the replacement person's foot contact and shadow to the new studio lighting. Maintain one performer throughout. The replacement changes identity and setting while retaining the original movement. Add no text, extra props, or music.
```

**Adjust:** person and environment references. **Review:** performance survives replacement; floor contact holds; source background does not bleed through.

<a id="k090"></a>
## K090 — A knitted miniature world

**Use:** whole-clip material treatment. **Mode:** video edit. **Brief:** source timing. **Inputs:** a simple original scene clip and knitted-material reference.

```text
Edit @Video1. Transform the visible scene into a miniature knitted world using @Image1 only for yarn texture and stitch scale. Preserve every subject's identity cues, location, movement, camera path, shot order, duration, and audio. Convert surfaces coherently: clothing, furniture, and background all have knitted construction while their original shapes remain readable. Keep the source light direction and recreate shadows on the yarn surfaces. Do not render the reference image itself. Retain the original pacing and add no captions or music.
```

**Adjust:** yarn palette, stitch size. **Review:** treatment covers the whole scene; geometry and action match source; texture stays attached.
