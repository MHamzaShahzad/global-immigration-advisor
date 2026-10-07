# Global Immigration Advisor: Claude Skill

A [Claude skill](https://docs.claude.com/en/docs/agents-and-tools/agent-skills/overview) that turns Claude into a senior global immigration and relocation consultant. It assesses an individual's, couple's, or family's profile. It then identifies, ranks, and plans the strongest realistic **legal** pathways to work permits, residence, permanent residence (PR), and citizenship worldwide.

## What it does

- **Builds a client profile** from CVs and conversation. It computes ages, age-points deadlines, and post-degree experience, and asks only questions that change the answer.
- **Assesses couples as couples.** Each adult is evaluated as a potential main applicant, and the skill looks for countries where both partners' routes fit together.
- **Covers every route family**: points-based migration, employer-sponsored permits, talent routes, study-to-PR, job-seeker visas, family, business and investor routes, and digital nomad visas.
- **Checks current rules before quoting figures**, preferring official government sources and flagging reforms that are proposed but not yet in force.
- **Ranks routes** by eligibility, likelihood, cost, time to PR and citizenship, spouse work rights, presence requirements, and tax.
- **Delivers an action plan** with document checklists, long-lead items, and 30/60/90-day next steps.
- **Stays within strict legal and ethical boundaries.** It gives no guarantees and refuses deceptive strategies, offering lawful alternatives instead.

## Structure

```
SKILL.md                        # Main instructions and workflow
references/
  intake-checklist.md           # Client intake and document checklist
  official-sources.md           # Official immigration sources by country
  report-template.md            # Structure for a full assessment
```

## Installation

- **Claude.ai:** Settings → Capabilities → Skills → upload the packaged `.skill` / zip of this folder.
- **Claude Code:** copy this folder into `~/.claude/skills/global-immigration-advisor/`.

## Disclaimer

This skill provides immigration information and planning support. It is not legal advice. Immigration rules change frequently, so confirm critical decisions with a licensed professional in the destination country.
