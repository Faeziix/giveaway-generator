# Lead Magnet Generator

A structured knowledge base that powers Claude Code to generate tailored lead magnet ideas, titles, and content drafts for any industry. Built on reverse-engineered patterns from 16 proven giveaways that generated 100-1,200+ comments per LinkedIn post.

This is **not an application** — it's a documentation system that Claude Code reads as context to produce high-quality lead magnet strategies.

## How It Works

Give Claude Code a client brief (as few as 4 inputs), and it will:

1. **Match** the client's audience, resources, and buyer stage to the best lead magnet formats
2. **Generate** 3-10 ideas with titles, content outlines, effort estimates, and reference examples
3. **Write** LinkedIn viral post copy using proven comment-gate formulas (for TOF distribution)
4. **Build out** full content drafts for selected ideas using format-specific playbooks

## Quick Start

Open the project in Claude Code. It will automatically read `CLAUDE.md` for instructions and `knowledge-base/core-reference.md` for the full framework.

**Fast Track** — provide 4 things:
1. What does the business do?
2. Who is the ideal customer?
3. What is the #1 problem they solve?
4. What is the goal for this lead magnet?

Claude handles the rest.

## What's Inside

### Knowledge Base (`knowledge-base/`)

| File | What It Does |
|------|-------------|
| `core-reference.md` | **Start here.** Consolidated taxonomy, quick-match matrix, industry matrix, 20 design principles, naming formulas, and reference library — everything for ideation in one file |
| `principles.md` | 20 transferable design principles (naming, format selection, content structure, idea quality, conversion psychology) |
| `naming-conventions.md` | 5 title formulas, 4 naming patterns, the "Insider Artifact" test for title quality |
| `quick-match.md` | 3-input decision matrix: audience need + resources + buyer stage → format |
| `industry-matrix.md` | 8 industries with pain points, best formats, example titles, and adaptation notes |

### Taxonomy (`knowledge-base/taxonomy/`)

6 categories that classify every lead magnet by what the prospect gets:

| Category | Verb | Examples |
|----------|------|---------|
| **Educate** | Learn | Cheat sheets, guides, video trainings |
| **Enable** | Do | Calculators, custom GPTs, spreadsheet tools |
| **Accelerate** | Start faster | Templates, frameworks, SOPs, swipe files, checklists |
| **Diagnose** | Understand | Quizzes, scorecards, self-assessments |
| **Connect** | Access | Private communities, events, beta access |
| **Validate** | Justify | Case studies, benchmark reports, comparison guides |

### Playbooks (`knowledge-base/playbooks/`)

Step-by-step creation guides for 13 formats:

| Effort | Formats |
|--------|---------|
| **Low** (2-8 hrs) | Checklist, Cheat Sheet, Template Collection, Swipe File |
| **Medium** (8-40 hrs) | Calculator, Quiz/Assessment, SOP, Framework Collection |
| **High** (40-100+ hrs) | Custom GPT, Benchmark Report, Guide/Ebook, Video Training |

Plus: **TOF Viral Post** (`tof-viral-post.md`) — the LinkedIn comment-gate distribution playbook with 4 proven post formulas, 9-part post anatomy, and performance benchmarks.

### Reference Library (`knowledge-base/reference-library/`)

16 reverse-engineered case studies from Linear (DTC creative agency), each with:
- Content structure and format breakdown
- What makes it effective (mapped to design principles)
- Industry adaptation notes (how to clone the pattern for other verticals)

### Templates (`templates/`)

| Template | Purpose |
|----------|---------|
| `client-intake.md` | Fast Track (4 questions) + Full Brief (60+ fields) |
| `lead-magnet-proposal.md` | Output structure for presenting ideas — includes title quality checks |

## Key Principles

The system enforces three quality gates on every idea:

1. **Artifact, not advice** — The lead magnet must feel like a stolen internal tool, not a blog post repackaged
2. **Denominate value in outcomes** — Frame value in results produced ("$500M+ in revenue"), not effort ("15 pages")
3. **The "I should NOT be giving this away" test** — If the creator isn't uncomfortable sharing it, it's too generic

## Project Structure

```
├── CLAUDE.md                        # Claude Code instructions + workflow
├── knowledge-base/
│   ├── core-reference.md            # Consolidated quick-start reference
│   ├── principles.md                # 20 design principles
│   ├── naming-conventions.md        # Title formulas + quality tests
│   ├── quick-match.md               # Decision matrix
│   ├── industry-matrix.md           # 8 industry adaptations
│   ├── taxonomy/                    # 6-category framework (7 files)
│   ├── playbooks/                   # 13 format creation guides + TOF viral post
│   └── reference-library/           # 16 case studies (Linear's giveaways)
├── templates/
│   ├── client-intake.md             # Client questionnaire
│   └── lead-magnet-proposal.md      # Proposal output template
└── archive/
    └── Linear - Resource Sheet.md   # Original Linear resource links
```
