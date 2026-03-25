# CLAUDE.md — Jun Hur's Portfolio Site

## Commit Message Rules

Always use **Conventional Commits** format. Every commit must follow this structure:

```
type(scope): short imperative subject (max 72 chars, no period)

Optional body — explain the "why", not the "what". Wrap at 72 chars.
```

### Types
| Type | When to use |
|------|-------------|
| `feat` | New section, feature, or component |
| `fix` | Bug fix or content correction |
| `style` | Visual/UI-only changes, no logic change |
| `refactor` | Restructuring without behavior change |
| `content` | Text, copy, or data updates |
| `chore` | File moves, renames, asset cleanup |

### Examples
```
feat(projects): add full-screen detail overlay with image gallery
fix(education): correct BS graduation year from 2026 to 2025
style(projects): replace emoji icons with screenshot thumbnails
fix(images): rename assets to ASCII and fix broken image paths
content(crisk): add chatbot feature description and screenshot
chore(assets): reorganize images into asset/ directory
feat(nav): show full name instead of initials in logo
feat(links): add website links to experience companies and project cards
```

### Never write
- `Update site`
- `Fix stuff`
- `Add changes`
- Generic messages that don't describe what changed

## Asset Rules

- All images go in the `asset/` folder
- Filenames must use **ASCII only** — no spaces, no Korean characters
- Use hyphens as separators (e.g. `robot-hyundai.jpeg`, `crisk-chatbot.png`)
- Korean or spaced filenames will break browser URL loading
