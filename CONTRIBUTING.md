# Contributing

Thanks for helping curate **awesome-llm-agent-skills-papers**! Quality matters more than quantity here — a small, well-organized list is more useful than a long, noisy one.

## Scope

This list is about **skills as first-class artifacts** for LLM agents (e.g., Anthropic-style skill folders, Voyager-style code skill libraries, learned options, induced procedures, retrievable prompts, callable tools), plus closely adjacent areas: tool use, function calling, procedural memory, and skill induction. General LLM-agent or chain-of-thought work without a skill abstraction is **out of scope**.

If you are unsure, open an issue first and we can discuss.

## Entry format

One line per entry, exactly:

```markdown
- **Title** — First Author et al. *Venue Year*. [paper](url) [code](url)
```

Rules:

- **Title** in bold; reproduce the paper's exact title (including subtitle).
- Use `First Author et al.` for 3+ authors; `Author A and Author B` for two; just `Author A` for one.
- *Venue Year* in italics. Use the most authoritative venue you can verify (e.g., `ICLR 2024`). If the paper is preprint-only, use `arXiv YYYY` where the year is the first arXiv submission year.
- Links: `[paper]`, `[code]`, `[blog]`, `[site]`, `[video]`, `[slides]` — in that order, only include those that exist. Use canonical URLs (arXiv abstract page, official project page, GitHub repo).
- No TL;DRs or summaries in v1 — keep entries one line.

## Ordering

Within each section, entries are **chronological (oldest first)**, by first arXiv submission date or publication date — whichever is earlier. New PRs that add an older paper should insert it in the right place, not append to the bottom.

## How to contribute

1. **Fork** the repo and create a branch.
2. **Add or edit** entries in `README.md`. Keep diffs minimal and focused.
3. **Verify your links** — every URL in your PR must resolve to the right paper/code/blog (no 404s, no wrong-paper redirects).
4. **Open a PR** with:
   - A short title (e.g., `Add Voyager to Skill Acquisition`).
   - In the description, a one-line justification per added paper explaining why it belongs in the chosen section.

## PR checklist

- [ ] Each new entry follows the format above exactly.
- [ ] Section choice is justified (paper foregrounds a skill abstraction relevant to that section).
- [ ] Entries are inserted in chronological order within the section.
- [ ] All links resolve and point to the correct work.
- [ ] No duplicate entries (search the README for the title before adding).
- [ ] Spelling, capitalization, and punctuation match the original paper title.

## Removing or correcting entries

If you spot a wrong year, venue, link, or section assignment, please open a PR with the fix — minor corrections do not need a prior issue.

## Code of conduct

Be kind, be specific, and assume good faith. Disagreements on scope or section assignment are fine and welcome — just keep them about the work, not the contributor.
