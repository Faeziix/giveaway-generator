# Lead Magnet Knowledge Base

This project is a structured knowledge base for generating tailored lead magnet ideas and content for clients. It is NOT an application — it's documentation that Claude Code reads as context.

## On Conversation Start

Read `knowledge-base/core-reference.md` first. This single file consolidates the taxonomy, quick-match matrix, industry matrix, design principles, and naming conventions — everything needed for ideation in ONE read. Only read individual files when building out a selected idea (Step 3).

## Quick Context (no file reads needed)

The 6 categories: **Educate** (teach) → **Enable** (tools) → **Accelerate** (starting points) → **Diagnose** (assessments) → **Connect** (community) → **Validate** (proof).

Resource tiers: **Low** = Checklist, Cheat Sheet, Template, Swipe File (2-8 hrs) | **Medium** = Calculator, Quiz, SOP, Framework Collection (8-40 hrs) | **High** = Custom GPT, Benchmark Report, Guide, Video Training (40-100+ hrs).

Buyer stages: **Awareness** → Educate, Diagnose | **Consideration** → Validate, Enable | **Decision** → Accelerate, Enable.

Industries covered: B2B SaaS, E-commerce, Professional Services, Health & Fitness, Real Estate, Local Services, Creator/Coach, Agency.

---

## How to Use This With a Client

There are two tracks: **Fast Track** for quick ideation and **Full Track** for comprehensive briefs.

### Fast Track (recommended for most sessions)

#### Step 1: Gather Minimum Client Info
Ask for just 4 things (from `templates/client-intake.md` Fast Track section):
1. What does the business do?
2. Who is the ideal customer?
3. What is the #1 problem they solve?
4. What is the goal for this lead magnet?

Optional accelerators: buyer stage, team skills, existing content to repurpose.

#### Step 2: Quick-Match and Generate
**If the goal is TOF impressions/reach** (not email opt-ins), prioritize the TOF Viral Post playbook (`playbooks/tof-viral-post.md`) — see Section 7 of core-reference.md. Generate both the resource idea AND the LinkedIn post copy using the viral post formula.

Use `knowledge-base/core-reference.md` (should already be loaded from conversation start). Cross-reference:
- Section 2 (Quick Match) — match audience need + resources + buyer stage to format recommendations
- Section 3 (Industry Matrix) — find industry-specific patterns and adaptation notes
- Section 4 (Design Principles) — apply proven principles to strengthen ideas

Generate 3-5 ideas. For each idea, provide:
- **Title** — follow formulas in Section 5 of core-reference.md
- **Category** — which of the 6 taxonomy categories
- **Format** — specific format (checklist, calculator, template, etc.)
- **Why it works** — 2-3 sentences connecting to client's audience and pain points, referencing specific principles
- **Content outline** — 5-8 bullet points of what's inside
- **Effort estimate** — Low / Medium / High with approximate hours
- **Reference example** — cite from Section 6 of core-reference.md if one exists

Use `templates/lead-magnet-proposal.md` as the output structure.

#### Step 3: Build Out the Selected Idea
When the user picks an idea:
1. Read the relevant format playbook from `knowledge-base/playbooks/` (see `knowledge-base/playbooks/README.md` for the index)
2. Read the similar reference example from `knowledge-base/reference-library/` (check the Industry Adaptations section if the client's industry differs)
3. Produce a complete draft following the playbook's structure and anatomy guidelines
4. Apply naming conventions from Section 5 of core-reference.md

---

### Full Track (when client provides a complete brief)

#### Step 1: Gather Client Info
Read `templates/client-intake.md` for the full questionnaire. Ask the user for any missing fields. **Minimum required before proceeding:** industry, target audience, products/services, and pain points.

#### Step 2: Match to Taxonomy
Use `knowledge-base/core-reference.md` Section 1 for the full framework and Section 2 for the decision matrix. Based on the client's buyer stage and goals, identify the 2-3 best-fit categories.

#### Step 3: Select Formats
For each matching category, read the relevant category file (e.g., `knowledge-base/taxonomy/accelerate.md`) to see detailed format options. Cross-reference with the client's resource constraints. Check Section 3 (Industry Matrix) of core-reference.md for industry-specific recommendations.

#### Step 4: Generate 3-5 Ideas
Follow the same output format as Fast Track Step 2. Apply principles from Section 4 of core-reference.md to strengthen each idea.

#### Step 5: Build Out the Selected Idea
Same as Fast Track Step 3.

---

## Key Files

| File | Purpose | When to Read |
|------|---------|--------------|
| `knowledge-base/core-reference.md` | **Consolidated reference** — taxonomy, quick-match, industry matrix, principles, naming, reference library | Always (on conversation start) |
| `templates/client-intake.md` | What to ask about a client (Fast Track + Full Brief) | When gathering client info |
| `templates/lead-magnet-proposal.md` | Output structure for generated ideas | When formatting proposals |
| `knowledge-base/playbooks/tof-viral-post.md` | **LinkedIn comment-gate post formula** — 4 proven structures, anatomy, benchmarks | When goal is TOF impressions/reach |
| `knowledge-base/playbooks/` | How to build each format type | Only when building out a selected idea (Step 3) |
| `knowledge-base/reference-library/` | Linear's 16 giveaways as case studies (with industry adaptations) | Only when building out a selected idea (Step 3) |

### Individual Files (only needed for Full Track deep-dives)
| File | Purpose |
|------|---------|
| `knowledge-base/taxonomy/overview.md` | Full 6-category framework with detailed format lists |
| `knowledge-base/taxonomy/{category}.md` | Detailed format options per category |
| `knowledge-base/quick-match.md` | Full quick-match matrix (expanded version) |
| `knowledge-base/industry-matrix.md` | Full industry matrix with all adaptation notes |
| `knowledge-base/principles.md` | Full design principles with proof and examples |
| `knowledge-base/naming-conventions.md` | Full naming conventions with do's and don'ts |
