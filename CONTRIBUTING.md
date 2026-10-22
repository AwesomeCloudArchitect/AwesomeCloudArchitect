# Contributing

Thanks for helping build this out. The wiki only gets good through contribution — here's how
to make one.

## Ways to Contribute

- **Fill in a placeholder page.** Most pages currently exist only as a skeleton (front matter
  + empty headings). Pick one, write it, open a PR.
- **Propose a new page or section.** Open an issue using the *New Page Proposal* template
  before writing a large page, so we can agree it fits the structure first.
- **Fix or improve an existing page.** Corrections, better examples, updated references —
  small PRs are welcome and easy to review.
- **Review open PRs.** Reviewing is as valuable as writing; comment on accuracy, clarity, and
  whether the provider-independence rule is respected.

## Before You Start Writing

1. Check the [README](README.md) table of contents and the relevant folder's `index.md` to
   confirm where your topic belongs (or open a proposal issue if it doesn't fit anywhere yet).
2. Read the [Style Guide](STYLE_GUIDE.md) — especially the provider-independence rule.
3. Copy [PAGE_TEMPLATE.md](./template/PAGE_TEMPLATE.md) if you're starting a page from scratch, or edit
   the existing placeholder file if one already exists.

## Submitting

1. Fork the repo and create a branch: `git checkout -b page/<topic-slug>`.
2. Write the page, following the template structure.
3. Set `status: in-review` in the front matter and update `last_updated`.
4. Open a PR using the pull request template. Link the related issue if there is one.
5. A maintainer or topic maintainer reviews for accuracy, clarity, and provider-independence.
   Expect at least one round of feedback on substantial pages.
6. Once merged, a maintainer sets `status: stable` once the page has had a review pass and
   feels complete enough to rely on (pages can still be improved after that — `stable` isn't
   "finished forever").

## Becoming a Page Maintainer

If you contributed a page or know a topic well, add yourself to that page's `maintainers`
front-matter field in your PR. Maintainers aren't required to do all future updates
themselves, but are the first point of contact for questions or review requests on that page.

## Discussion & Proposals

Use **GitHub Discussions** for open-ended conversation (structure debates, "should we split
this topic", etc.) and **Issues** for concrete, actionable items (new page, correction, broken
link). This keeps issues actionable and discussions exploratory.

## Code of Conduct

Participation in this project is covered by our [Code of Conduct](CODE_OF_CONDUCT.md).
