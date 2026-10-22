# Style Guide

Conventions for keeping the wiki consistent as it grows with community contributions.

## Provider Independence

This is the one rule everything else serves: **a page's core content must be useful to
someone regardless of which cloud they run on.**

- Explain concepts, patterns, and trade-offs in provider-neutral terms first.
- If a provider-specific detail is genuinely necessary, put it in the page's optional
  **Provider Notes** section, clearly labeled per provider — never blend it into the main text.
- Avoid provider product names as section headers or page titles (e.g. write "Object Storage",
  not "S3").

## File & Folder Naming

- Folders: `NN-kebab-case-slug` at the top level (e.g. `01-foundations`), `kebab-case-slug`
  for sub-sections (e.g. `database-migration`).
- Files: `kebab-case-slug.md`, one topic per file.
- Every folder gets an `index.md` that lists and links its pages.

## Page Structure

Every content page starts from [PAGE_TEMPLATE.md](PAGE_TEMPLATE.md) and keeps its section
order: Overview → Key Concepts → Best Practices → Options & Trade-offs → Anti-Patterns →
(optional) Provider Notes → Related Topics → References. Skipping a section is fine if it
truly doesn't apply — don't force content to fill it.

## Front Matter

Every page starts with YAML front matter:

```yaml
---
title: "Human-readable title"
status: draft        # draft | in-review | stable
maintainers: []
tags: []
last_updated: YYYY-MM-DD
---
```

Update `last_updated` and `status` whenever you make a substantive edit.

## Writing Tone

- Write for a working architect, not a beginner or a marketing audience — skip motivational
  framing, get to the substance.
- Prefer concrete guidance ("use X when Y, because Z") over abstract statements.
- Where there's genuine debate or no single right answer, present the trade-offs rather than
  picking a winner — that's most of cloud architecture.
- Keep sentences short. Bullet points and tables over long paragraphs where they aid scanning.

## Linking

- Use relative links between pages (`../foundations/networking.md`), not absolute GitHub URLs,
  so links work in any fork/clone.
- Every new page should be linked from its folder's `index.md` and, for top-level pages, from
  the root `README.md`.

## Diagrams

Plain-text/Markdown-renderable diagrams are preferred so they render on GitHub without extra
tooling:

- [Mermaid](https://mermaid.js.org/) fenced code blocks (` ```mermaid `) for flow/sequence/
  architecture diagrams.
- ASCII diagrams for very simple cases.
- If an image is unavoidable, store it under `<folder>/assets/` next to the page and keep it
  as small as possible.
