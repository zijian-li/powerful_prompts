# 30-second product commercial with Higgsfield

Generate a roughly 30-second, 16:9 product commercial from an Amazon listing using Higgsfield, combining multiple clips when needed.

- **Tags:** video-generation, commercial, product-advertising, higgsfield, matcha, clip-editing, 16:9
- **Tool / model:** AI assistant with Higgsfield MCP/CLI and access to product references
- **Status:** draft
- **Source:** Prompt supplied by the repository owner in conversation
- **Author:** Not specified
- **Added:** 2026-09-07

## When to use

Use when creating a short product commercial from listing images and specifications, with freedom to choose image and video generators and stitch generated clips together.

## Inputs

This saved version has no placeholders. Replace the product reference when adapting it to another product.

| Input | Saved value |
| --- | --- |
| Product | Tenzo Matcha Green Tea Powder |
| Product URL | Supplied in the prompt below; needs checking before reuse |
| Duration | Approximately 30 seconds |
| Aspect ratio | 16:9 |
| Generation tools | Higgsfield MCP/CLI; choice of image or video generator |

## Prompt

```text
your job is to make a ~30 second commercial, 16:9 about this product: https://www.amazon.com/Tenzo-Matcha-Green-Tea-Powder/dp/BOC49Y5YS7. you may use the images and product specs on that page for reference. use Higgsfield MCP/CLI to generate the content using whichever image or video generator you want, for the best result. if necessary, you may generate multiple clips and stitch them together for the 30 second commercial
```

## Usage notes

- The supplied product URL is split between a Markdown link and trailing text. Replace it with a complete, verified product URL before running; the product identifier is preserved as supplied.
- Requires access to Higgsfield MCP/CLI and the product images and specifications. Combining clips also requires a video editing tool.
- Optionally specify the audience, tone, key product benefits, call to action, music or voiceover preferences, and output location.

## Testing notes

- **Date and tool / model:** Not recorded.
- **Result:** Not recorded; saved for future use.

## Changes from source

Removed the Markdown escape before the tilde in "~30". Otherwise preserved the supplied prompt wording and product link formatting. Added metadata and usage notes.
