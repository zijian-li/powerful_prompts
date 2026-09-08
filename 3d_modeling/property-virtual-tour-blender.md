# Property virtual tour in Blender

Reconstruct a property from listing photos and information, then animate a camera fly-through and render a virtual tour in Blender.

- **Tags:** 3d-modeling, blender, mcp, architecture, interior-design, virtual-tour, camera-animation, rendering
- **Tool / model:** AI assistant with page access and Blender MCP at localhost:9876
- **Status:** draft
- **Source:** Prompt supplied by the repository owner in conversation
- **Author:** Not specified
- **Added:** 2026-09-07

## When to use

Use when creating a detailed 3D property reconstruction and rendered tour based on a property listing's photos and other reference information.

## Inputs

This saved version has no placeholders. It uses the property URL and Blender MCP address below. Replace them when reusing it for a different property or connection.

| Input | Saved value |
| --- | --- |
| Property listing | https://www.airbnb.com/rooms/1647614247282916612 |
| Blender MCP address | localhost:9876 |

## Prompt

```text
Your job is to create a 3D virtual tour of this property: https://www.airbnb.com/rooms/1647614247282916612 You may refer to the photos and other relevant info from the page. Reconstruct the entire building and interior using blender MCP at this address localhost:9876. Make sure everything is very detailed and faithful, Also program the camera path to fly through the property like a virtual tour, and then render the scene.
```

## Usage notes

- Requires access to the listing photos and information, plus a running Blender MCP connection at the specified address.
- For greater fidelity, provide floor plans, dimensions, and additional photos when available. Identify inferred areas where the references do not show the layout or details.
- Optionally specify tour duration, camera route, render resolution, frame rate, and output location before running.

## Testing notes

- **Date and tool / model:** Not recorded.
- **Result:** Not recorded; saved for future use.

## Changes from source

Converted the Markdown property link to a plain URL for copying into the prompt. All other prompt wording is unchanged. Added metadata and usage notes.
