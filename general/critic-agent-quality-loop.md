# Critic agent quality improvement loop

Use a separate critic agent to evaluate a video and guide ranked improvements until it scores at least 8 out of 10, with a limit of three rounds.

- **Tags:** quality-review, critic-agent, multi-agent, iteration, video, visual-quality
- **Tool / model:** AI assistant supporting separate builder and critic agents, video frame extraction, and image inspection
- **Status:** tested
- **Source:** Prompt supplied by the repository owner in conversation
- **Author:** Not specified
- **Added:** 2026-09-07

## When to use

Append this to a creation task when you want an independent review and a bounded improvement loop. The saved wording targets video; adapt the inspection method when using it for another type of output.

## Inputs

No placeholders. Provide the video or its location, the original task requirements, and access to tools that can extract and inspect frames.

## Prompt

```text
Use a separate critic agent to take screenshots from random frames throughout the video to evaluate its consistency, correctness, and visual quality. It should provide a score from 0 to 10. 4-7 means it's usable but it would not pass as production- ready, 8 or above means it looks like a production ready professional product.

Loop until the critic agent gives a score of 8 or higher. Below that, the builder gets the ranked issue list and tries again, up to 3 rounds.
```

## Usage notes

- Use alongside the original task so the critic can assess correctness against the intended requirements.
- The prompt sets a target of 8/10 and caps the loop at three rounds. If the target is not met by the cap, report the final score and remaining issues.
- For repeatable use, clarify whether the initial review counts as one of the three rounds.
- For other outputs, replace video screenshots with suitable evidence while retaining the separate critic, scoring, ranked feedback, and round limit.

## Testing notes

- **Date and tool / model:** Not recorded.
- **What worked:** The repository owner reported finding this prompt useful for improving results.
- **What to improve:** Record scores, issues resolved, and results from future uses.

## Changes from source

Prompt wording unchanged. Normalized whitespace and removed the encoded trailing space. Added metadata and usage notes.
