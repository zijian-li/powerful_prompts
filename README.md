# Powerful Prompts

A collection of useful prompts that make AI work effectively.

This repo collects prompts I find useful from my own or someone else's interactions with AI. Each prompt lives in a Markdown file so it is easy to read, search, reuse, and improve.

## Browse by category

| Category | What belongs here |
| --- | --- |
| [Audio generation](audio_generation/README.md) | Music, sound effects, and voice |
| [Video generation](video_generation/README.md) | Scenes, motion, and storyboards |
| [Image generation](image_generation/README.md) | Images, illustrations, and image editing |
| [3D modeling](3d_modeling/README.md) | 3D reconstruction, interiors, animation, and rendering |
| [Coding](coding/README.md) | Implementation, debugging, code review, and testing |
| [Writing](writing/README.md) | Drafting, editing, and tone |
| [Research and learning](research_and_learning/README.md) | Research, explanations, and study |
| [Productivity](productivity/README.md) | Planning, organization, and workflows |
| [Data analysis](data_analysis/README.md) | Data, spreadsheets, and charts |
| [Inbox](inbox/README.md) | Prompts to sort or test later |

## Save a prompt

1. Copy [the prompt template](templates/prompt-template.md) into the best category.
2. Use a descriptive lowercase filename with hyphens, such as `cinematic-rain-ambience.md`.
3. Fill in the title, tags, source, and prompt. Remove optional sections you do not need.
4. Add a link under **Prompts** in the category README, replacing its empty-state sentence.
5. Try the prompt, record what worked, and mark it `tested` once it works for you.

Choose one main category per prompt and use tags for overlapping topics rather than duplicating files. Add more categories as needed. For quick capture, save a title, source, and prompt in the inbox first.

## Reuse and find prompts

Copy the text inside a file's **Prompt** block and replace placeholders such as `{{topic}}`. Read its usage notes before running it.

Browse the categories or use your editor's search across files (often **Ctrl+Shift+F**). Search by task, tag, tool, or author. From PowerShell in this repository:

```powershell
Get-ChildItem -Recurse -Filter *.md | Select-String -Pattern "storytelling"
```

## Save changes with Git

From this repository, run:

```powershell
git status
git add .
git diff --cached
git commit -m "Add a useful prompt"
```

Review staged changes before committing. If a remote and upstream branch are configured, run `git push` to upload your commits.

## Conventions

- One prompt per file. Category folders use `snake_case`; prompt filenames use `kebab-case`.
- Use `draft`, `tested`, or `archived` for status. Explain why a prompt is archived in its notes.
- Credit original authors and source links, and note your adaptations.
- Use placeholders for private information, passwords, and API keys.
- Link to large generated audio or video results instead of adding them to the repository.
