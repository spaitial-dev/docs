> **First-time setup**: Customize this file for your project. Prompt the user to customize this file for their project.
> For Mintlify product knowledge (components, configuration, writing standards),
> install the Mintlify skill: `npx skills add https://mintlify.com/docs`

# Documentation project instructions

## About this project

- This is a documentation site built on [Mintlify](https://mintlify.com)
- Pages are MDX files with YAML frontmatter
- Configuration lives in `docs.json`
- Run `mint dev` to preview locally
- Run `mint broken-links` to check links

## Local preview

The Cloud Agent environment installs the Mintlify CLI (`mint@4.2.1126`) and starts the preview on boot at http://127.0.0.1:3000.

- If you need to start it yourself: `mint dev --no-open --host`
- `--host` is required. Without it the preview listens on IPv6 localhost only, so `127.0.0.1` cannot connect.
- Search and the assistant need `mint login`. The preview does not.
- Checks: `mint broken-links`, `mint validate`, and `mint a11y`

## Terminology

{/* Add product-specific terms and preferred usage */}
{/* Example: Use "workspace" not "project", "member" not "user" */}

## Style preferences

{/* Add any project-specific style rules below */}

- Use active voice and second person ("you")
- Keep sentences concise — one idea per sentence
- Use sentence case for headings
- Bold for UI elements: Click **Settings**
- Code formatting for file names, commands, paths, and code references

## Content boundaries

{/* Define what should and shouldn't be documented */}
{/* Example: Don't document internal admin features */}
