# Spec: <skill name>

- **Source video:** <URL>
- **Read A:** Claude via watch `--engine local` → `read-a-claude.md`
- **Read B:** Gemini via watch `--engine gemini` → `read-b-gemini.md`
- **Label counts:** confirmed N · single source N · conflict N · inferred N · resolved N

Labels: `[confirmed]` both reads agree · `[single source: claude|gemini]` one read only ·
`[conflict]` reads disagree (both versions kept) · `[inferred]` not in the video, added to
make the skill work · `[resolved]` conflict settled by the user.

## Skill identity
- Name (kebab-case): `<name>` [inferred]
- Trigger description: <when Claude should use this skill, in the user's words> [inferred]

## Goal
- <one-sentence outcome> [confirmed] (02:10)

## Inputs
- <input> [confirmed] (00:45)

## Tools and services
- <tool, exact name/version> [single source: gemini] (01:30)

## Setup
1. `<exact command>` [confirmed] (03:05)
2. [conflict] Claude: `npm i foo@2` (03:40, frame) · Gemini: `npm i foo@3` (03:41)

## Workflow
1. <step> — `<exact command/prompt>` → expected: <result> [confirmed] (04:12)

## Code and prompts (verbatim)
```text
<transcribed text>
```
[confirmed] (05:00)

## Outputs
- <what and where, format> [confirmed] (07:20)

## Decisions and branches
- If <condition> then <action> [single source: claude] (06:15)

## Errors and gotchas
- <problem> → <fix> [confirmed] (08:02)

## Gaps filled (not in the video)
- <e.g. retry on API rate limit> [inferred]

## Test cases
| Input | Expected output | Label |
|---|---|---|
| <example> | <result> | [confirmed] (09:10) |
