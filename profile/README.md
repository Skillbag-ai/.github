# SkillBag

SkillBag is an open, file-based standard for portable and composable AI agent
skills.

It defines how an agent discovers, installs, composes, and runs local skills
from repository files. The goal is simple: keep agent behavior versioned,
auditable, reusable, and portable across providers.

## Links

- Website: https://skillbag.ai
- Standard entrypoint: https://skillbag.md
- Core standard: https://github.com/Skillbag-ai/skillbag
- Utility skills: https://github.com/Skillbag-ai/skillbag-utils
- Document skills: https://github.com/Skillbag-ai/skillbag-docs
- Resource skills: https://github.com/Skillbag-ai/skillbag-resources
- Example workspace: https://github.com/Skillbag-ai/skillbag-example

## Repositories

| Repository | Purpose |
| --- | --- |
| `skillbag` | Core standard and canonical `SKILLBAG.md` source. |
| `skillbag-utils` | Reusable utility skills for maintaining SkillBag workspaces. |
| `skillbag-docs` | Reusable document-processing skills for PDFs and office document workflows. |
| `skillbag-resources` | Reusable skills for local knowledge bases, resource ingestion, sync, indexing, and query. |
| `skillbag-example` | Minimal example showing how a repository bootstraps SkillBag. |

## What SkillBag Standardizes

- `SKILLBAG.md` as the workspace entrypoint
- `.skills/` as the installed skill root
- `.skills/SKILLS.md` as the low-cost discovery catalog
- dependency declaration and validation rules
- precedence across conversation, user, project, standard, and skill defaults
- deterministic lifecycle tags such as `#run/always` and `#run/last`
- installation behavior that preserves local edits

## Governance

SkillBag is currently a founder-led draft standard. The project is designed to
move toward a public working group or neutral foundation-style home if serious
multi-vendor adoption requires formal neutrality.

Start here:

- Governance: https://github.com/Skillbag-ai/skillbag/blob/main/GOVERNANCE.md
- Conformance: https://github.com/Skillbag-ai/skillbag/blob/main/CONFORMANCE.md
- Adopters: https://github.com/Skillbag-ai/skillbag/blob/main/ADOPTERS.md
- Sustainability: https://github.com/Skillbag-ai/skillbag/blob/main/SUSTAINABILITY.md

## Conformance

SkillBag does not yet have an official certification program. Until a public
test suite and certification process exist, projects should use precise claims
such as:

- "Uses the SkillBag file layout."
- "SkillBag-compatible source."
- "Implements the SkillBag workspace-entry lifecycle."
- "Experimental SkillBag support."

Avoid claiming "SkillBag certified" until certification exists.

## Participation

Useful contributions include:

- implementation feedback from agents and developer tools
- precise issue reports about ambiguous standard behavior
- pull requests that improve normative wording
- utility skills that solve common workspace problems
- validator and conformance-suite work
- public adoption statements

## Support

The standard remains open. Sponsorship should fund shared ecosystem work such
as documentation, validation, conformance tests, security review, and maintainer
time.

Organizations interested in adoption, sponsorship, or working-group
participation should open an issue in the core repository.
