# Procedural imperial rooftop parkour in Unreal Engine

Create a playable third-person rooftop traversal game with a procedural imperial environment, animated character, laptop performance targets, and a separate art critic review loop.

- **Tags:** game-generation, unreal-engine, procedural, third-person, parkour, blender, mixamo, sketchfab, character-animation, critic-agent
- **Tool / model:** AI development assistant with Unreal Engine, Blender MCP at localhost:9876, asset access, and separate critic-agent support
- **Status:** draft
- **Source:** Prompt supplied by the repository owner in conversation
- **Author:** Not specified
- **Added:** 2026-09-07

## When to use

Use when requesting a playable Unreal Engine game combining fast traversal, character animation, procedural environment creation, and iterative visual review.

## Inputs

No placeholders. Supply the referenced inspiration photo and confirm the character asset link before running. Optionally specify Unreal Engine version, project location, laptop specifications, and performance target.

| Input | Saved value |
| --- | --- |
| Character | Butterfly Academy on Sketchfab; split link preserved below |
| Animations | Relevant Mixamo animations retargeted to the character |
| Environment reference | Attached photo mentioned in the prompt; not supplied with this saved entry |
| Blender MCP address | localhost:9876 |
| Runtime | Playable within Unreal Engine |
| Review target | At least 8.5/10 with zero errors, up to four rounds |

## Prompt

```text
You are a world-class game developer. Make a procedural 3D game in unreal engine:
The user controls this character in 3rd person POV: [https://sketchfab.com/3d-models/butterfly-academy-](https://sketchfab.com/3d-models/butterfly-academy-)
d9544ecd63c84cbf88a155debf74a5e7
She's able to sprint really quickly and jump very high, leaping across rooftops like a ninja. You'll need to add appropriate animations for the character. You can look for relevant animations in Mixamo and map them onto the character.
If you're not able to download the assets because it requires a login, you can use the Playwright Chrome extension to open my current Chrome session where I'm already logged in to Sketchfab and Mixamo and map them onto the character. If you're not able to download the assets because it requires a login, you can use the Playwright Chrome extension to open my current Chrome session where I'm already logged in to Sketchfab and Mixamo. The environment should be a procedural Ancient Chingse imperial setting. See attached photo for inspiration. Generate all assets in Blender (via MCP at localhost:9876) and render them procedurally in Unreal Engine. Make it look as detailed, realistic, and grandiose as possible. Make it look like a AAA video game with impressive graphics and effects.

The game should be playable within Unreal Engine. It should be optimized to run efficiently on a regular laptop. After each completed attempt at animating the character and creating the assets and environment, a separate critic agent (a brutal AAA art director who writes no code) takes its own screenshots from several viewpoints and zoom levels, and scores the game design and aesthetics from 0-10: >8.5 = AAA qualitv. 7 = good indie. 5 = programmer art. Pass is >= 8.5 with zero errors. Below that, the builder gets the ranked issue list and tries again,

up to 4 rounds.
```

## Usage notes

- The Sketchfab link is split between a Markdown link and an identifier on the next line. Replace it with a complete, verified asset URL before reuse.
- Attach the inspiration photo when running the prompt; no reference image is included in this entry.
- The login fallback assumes an available Playwright Chrome extension and an authenticated browser session. Confirm the actual tools and asset access available when using the prompt.
- Clarify whether "Generate all assets in Blender" applies to environment assets, given the separately requested Sketchfab character and Mixamo animations.
- Specify hardware, resolution, and a frame-rate target to make laptop performance measurable.
- The prompt defines passing as >= 8.5 with zero errors, while its descriptive AAA label uses >8.5. Clarify this boundary and how rounds are counted before running the review loop; report remaining issues if the four-round cap is reached.
- Repeated login instructions and the spellings "Chingse" and "qualitv" are preserved from the source.

## Testing notes

- **Date and tool / model:** Not recorded.
- **Result:** Not recorded; saved for future use.

## Changes from source

Prompt wording unchanged. Removed surrounding blank lines and the encoded trailing space, and normalized line endings. Added metadata and usage notes.
