You are extracting a precise, buildable specification from a tutorial video so that it can be turned into an automated agent skill. Describe only what the video actually shows or says. Do not fill gaps with your own assumptions; if something is unclear or not shown, write "not shown".

Give a timestamp (MM:SS) for every item, and say whether it came from the picture (frame) or the speech (transcript).

Answer in this exact structure:

## 1. Goal
What the finished workflow does, in one or two sentences. Who it is for.

## 2. Inputs
Everything the workflow needs to start: files, URLs, accounts, API keys, settings, example data.

## 3. Tools and services
Every app, library, CLI, API, website or model used. Include exact names and any versions, plans or model IDs shown.

## 4. Setup steps
Installation and configuration in order. Copy commands, file paths, settings and environment variable names exactly as shown on screen, character for character.

## 5. Workflow steps
The core procedure, numbered, in order. For each step: what is done, the exact command/code/prompt/setting shown, and what the expected result looks like.

## 6. Code and prompts shown on screen
Transcribe any code, config, or prompt text visible on screen verbatim, each with its timestamp. Mark unreadable parts as [unreadable].

## 7. Outputs
What the workflow produces and where it ends up (file, message, dashboard, etc.), including formats.

## 8. Decisions and branches
Any "if X then Y" logic, options the presenter chooses between, and why.

## 9. Errors, warnings and gotchas
Problems the presenter mentions or hits, and how they are fixed.

## 10. Things mentioned but not shown
Steps the presenter skips, says are "off screen", or links to elsewhere.

## 11. Test cases
Concrete example inputs and their expected outputs that appear in the video, usable to check the finished skill works.
