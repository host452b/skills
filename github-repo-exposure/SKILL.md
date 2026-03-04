---
name: github-repo-exposure
description: Maximize GitHub repository visibility through on-site SEO, visual branding, off-site backlinks, and growth hacking. Use when the user wants to promote a GitHub repo, improve discoverability, increase stars, optimize README for search, or asks about GitHub SEO strategy.
---

# GitHub Repo Exposure

A 4-phase playbook to maximize a GitHub repository's visibility and organic growth.

## Quick Start

Copy this checklist and track progress:

```
Exposure Progress:
- [ ] Phase 1: GitHub on-site SEO
- [ ] Phase 2: visual branding
- [ ] Phase 3: off-site backlinks
- [ ] Phase 4: growth hacking
```

For the full detailed checklist, see [checklist.md](checklist.md).

## Phase 1: GitHub On-Site SEO

These factors directly affect ranking in GitHub search and Google indexing.

### repo name

- include 2-3 core keywords in the name
- use hyphens, keep it concise
- good: `fast-llm-server`, `cuda-memory-pool`
- bad: `my-project-v1`, `test123`

### about / description

This becomes the Google meta description. Extremely high impact.

- start with an action verb ("A high-performance...", "Lightweight...")
- include 2-3 core keywords naturally
- keep under 350 chars

### topics (tags)

GitHub uses these as index keywords.

- fill up to 20 tags
- include: language (`python`, `cpp`), domain (`llm`, `compiler`), tools (`gh-actions`), competitor terms
- check what tags top repos in your niche use

### README structure

```markdown
# Project Name               ← H1 with keywords

[badges: build status, license, version, downloads]

One-paragraph description within the first 100 words, containing
core functionality and target audience.

## Features                   ← H2 sections for scanability
## Quick Start
## Installation
## Usage
## Benchmarks (if applicable)
## Contributing
## License
```

Key rules:
- first 100 words must contain the core value proposition
- use clear H1/H2 structure (search engines parse headings)
- add badges for visual professionalism (shields.io)
- include a "quick start" section — users decide within 30 seconds

## Phase 2: Visual Branding

First impression in social feeds determines click-through rate.

### social preview image

- go to Settings → General → Social preview
- upload a 1280×640 image
- include: project logo, name, one-line slogan
- this image appears when anyone shares the link on Twitter, Discord, Slack, etc.

**Never leave the default GitHub preview.** This is free advertising space.

### demo GIF / animation

- place a demo GIF or Asciinema recording at the top of the README, right after badges
- humans are visual — "seeing it work" is the strongest star-conversion signal
- keep the GIF under 10 seconds, loop it, show the core wow-factor

Tools: [asciinema](https://asciinema.org/), [vhs](https://github.com/charmbracelet/vhs), [peek](https://github.com/phw/peek)

## Phase 3: Off-Site Backlinks

Google authority is primarily driven by backlinks. More high-quality links → higher ranking.

### awesome lists

The single highest-ROI action for exposure.

1. search for `Awesome-{your-domain}` lists on GitHub
2. open a PR to add your project (follow their contribution guidelines)
3. target 3-5 relevant awesome lists

### community posting

| Platform | Tips |
|----------|------|
| Reddit | post to relevant subreddits (r/Python, r/MachineLearning, etc). write a "why I built this" narrative, not just a link drop |
| Hacker News | submit at US Eastern 8-9 AM for best visibility. front page = hundreds of stars in a day |
| Dev.to / Medium | write a deep-dive article on the implementation, link to the repo at the end |
| 掘金 / V2EX | for Chinese developer community coverage |

### documentation site

- deploy docs via GitHub Pages or Read the Docs
- this creates an independent domain pointing to your repo (extra backlink)
- well-structured docs also rank independently in Google

## Phase 4: Growth Hacking

### commit cadence

GitHub search favors active projects. Frequent small commits rank better than monthly big ones.

- aim for consistent weekly activity
- avoid long periods of zero commits

### release strategy

- create a GitHub Release for every meaningful update (even small ones)
- releases appear in the GitHub home feed and get picked up by aggregator bots
- use semantic versioning, write clear release notes

### LLM discoverability

Modern developers ask AI "what's a good library for X". Optimize for this:

- README must have a clear English description of **what** the project does and **who** it's for
- include comparison with alternatives (helps LLMs position your project)
- structured data (feature lists, benchmarks) is easier for LLMs to cite

### community engagement

- respond to every issue quickly and politely
- stars are vanity; active issues and PRs are the SEO lifeline
- enable GitHub Discussions for casual Q&A
- add a `CONTRIBUTING.md` to lower the barrier for contributors

## Execution Order

When applying this to a new repo, follow this priority:

1. **README + About + Topics** (30 min, highest ROI)
2. **Social preview image** (15 min)
3. **Demo GIF** (1-2 hours)
4. **Awesome list PRs** (30 min each)
5. **Community posts** (1 hour)
6. **Docs site** (2-4 hours)
7. **Ongoing: releases, commits, engagement** (continuous)
