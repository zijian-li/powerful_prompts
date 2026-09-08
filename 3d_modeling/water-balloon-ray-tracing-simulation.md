# Interactive water balloon ray tracing simulation

Build a realistic browser-based 3D animation of a bullet piercing a water balloon, with fluid motion, adjustable parameters, and free camera inspection.

- **Tags:** 3d-simulation, ray-tracing, fluid-simulation, browser, interactive, physics, animation, no-external-libraries
- **Tool / model:** AI coding assistant with browser development and testing tools
- **Status:** draft
- **Source:** Prompt supplied by the repository owner in conversation
- **Author:** Not specified
- **Added:** 2026-09-07

## When to use

Use when requesting an interactive browser simulation that combines realistic rendering, water deformation, spray, and adjustable physical and visual settings without external web libraries.

## Inputs

No placeholders. Optionally specify target browsers and hardware, a frame-rate target, and preferred default simulation settings.

## Prompt

```text
Make a ray tracing 3D simulation of a bullet piercing through a water balloon, making the balloon pop and the water bursting, deforming from the original shape, and eventually falling to the ground. There should be mist and spray from where the bullet pierces through the water. Make it look as realistic and physically accurate as possible.

The animation must meet the following requirements:

Allow me to freeze the animation at any point in time and view the scene from any angle.

Add different sliders for settings like bullet speed, balloon size, lighting, gravity, and other parameters.

Make it run efficiently on a standard web browser.

Do not use Three.js or any other external web libraries
```

## Usage notes

- Retain the no-external-web-libraries constraint when adapting this prompt.
- Define a target browser, hardware baseline, and performance budget so efficiency can be evaluated concretely.
- Document any physical or rendering approximations used to balance realism and browser performance.
- Check that pausing freezes the simulation while camera controls remain usable, and that parameter changes behave consistently.

## Testing notes

- **Date and tool / model:** Not recorded.
- **Result:** Not recorded; saved for future use.

## Changes from source

Prompt wording unchanged. Normalized paragraph spacing. Added metadata and usage notes.
