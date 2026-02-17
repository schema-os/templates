# templates

**Type:** Shared Resource Repository
**Access:** team

Proposal templates, processes, and standards

## About This Repository

This is a **Shared Resource Repository** - for team-wide knowledge and resources.

Store shared entities like:
- Templates and boilerplates
- Best practices and standards
- Research and references
- Techniques and methods
- Frameworks and methodologies
- External examples and inspiration

## Getting Started

This repository is part of a Studiograph workspace. Entities are stored as markdown files with YAML frontmatter.

### File Structure

Organize your files however makes sense for your team. Common patterns:
- By entity type (e.g., `clients/`, `projects/`, `meetings/`)
- By date (e.g., `2026/02/`)
- By project or topic
- Flat structure (all files in root)

### Creating Entities

Each entity is a markdown file with YAML frontmatter:

```markdown
---
entity_type: example
entity_id: my-entity
created_at: 2026-02-15T00:00:00Z
updated_at: 2026-02-15T00:00:00Z
created_by: username
updated_by: username
tags: [tag1, tag2]
---

# Entity content goes here

Use [[wikilinks]] to reference other entities.
```
