# Write a shot that can be reviewed

[Home](../README.md) · [Catalog](../prompts/README.md) · [Official examples](official-examples.md)

Start with the change a viewer should notice. A successful brief gives that change enough space to happen, then leaves a useful final image.

## Build from a visible event

Compare “a beautiful stationery commercial” with “a hand closes one magnetic bookmark around a page, releases it, and leaves the closed bookmark in view.” The second description gives you something to judge: a hinge, a page, a contact event, and a finished state.

Use this order when adapting a recipe:

1. Choose the subject and starting state.
2. Name the one change that matters most.
3. Describe the camera's starting position and destination.
4. Keep identity, geometry, and lighting details that must survive the action.
5. Add sound that belongs to the visible event.
6. Leave time for the movement to settle.

The [official Kling 4.0 guide](https://kling.ai/quickstart/kling-4-model-user-guide) recommends concrete visual descriptions and explicit roles for uploaded assets. Its examples are collected in the [official gallery](official-examples.md).

## Match the brief to your inputs

| Starting point | What to write first | Example |
|---|---|---|
| No assets | The scene and one observable event | [Returned umbrella](../prompts/cinematic-stories.md#k001) |
| First image | The movement compatible with that composition | [Magnetic bookmark](../prompts/product-films.md#k010) |
| Several references | Which details each asset controls | [Product in a new room](../prompts/omni-reference.md#k074) |
| Existing footage | The exact change and the source details to preserve | [Wall color](../prompts/video-editing.md#k084) |
| Prepared key images | The action connecting those visual moments | [Wrapped gift](../prompts/keyframe-transitions.md#k091) |

## Give each reference a limited job

A portrait can define a person's face and clothing. A room image can define a floor plan and light direction. A movement clip can define timing without supplying a new identity.

Before generating, compare the reference numbers in the prompt with the actual upload order. A good instruction assigned to the wrong image can produce a plausible but unwanted result.

## Separate three kinds of movement

**Subject:** the person rotates the umbrella.  
**Environment:** rain continues outside.  
**Camera:** the view moves slightly closer.

Write these independently. “Rotate around the umbrella” could describe either the camera or the object. Say which one moves and which one stays still.

## Use timing where it earns its place

A simple action may need only a beginning, middle, and ending. Several speakers or a staged reveal benefit from timed beats. Leave enough room for words to be spoken naturally and for objects to reach their destinations.

Durations and aspect ratios in this library are creative intentions. Set the actual output controls in the interface you use; writing “ten seconds” inside a prompt does not configure an API request.

## Direct dialogue like a performance

Name the speaker, exact words, language, delivery, and the listener's behavior. For a two-person exchange, place a pause between turns. For silent acting, describe visible changes in gaze, breath, posture, and expression.

Review generated speech with a fluent speaker before using it in a campaign. A translated README is a reading aid, not a claim about speech quality in that language.

## Revise one failure at a time

| What went wrong | A focused revision |
|---|---|
| A product changes shape | Use a clearer product reference and reduce competing actions |
| The camera hides the important contact | Choose an angle that keeps both surfaces visible |
| A gesture feels rushed | Reduce the number of beats or allow more time |
| Speakers swap lines | Reassert positions, clothing, and line ownership |
| An edit changes the whole scene | Narrow the target and explicitly preserve source motion |
| A final image arrives through a dissolve | Describe a physical route into the endpoint |

Keep the original brief when making a variation so that you can compare what changed. A beautiful frame and a useful video are different review questions: inspect the whole clip, especially transitions, occlusions, hands, reflections, and the last second.
