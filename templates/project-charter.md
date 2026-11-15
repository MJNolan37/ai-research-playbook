# Project charter

A charter is half a page written before the work starts. It holds what should not change without a decision: the objective, the scope and the gates. Day-to-day status goes in a separate, shorter state log, so the charter doesn't turn into a status dump and the status log doesn't quietly rewrite the charter.

## Template

```markdown
# Charter: <project name>
Version: <n>   Date: <date>   Owner: <who decides>

## Objective
One or two sentences. What question does this answer, or what does it produce, and for whom?

## Scope
In:  <what this project covers>
Out: <what it deliberately leaves alone>

## Constraints
<privacy, sources, time, tools, anything that limits how the work may be done>

## Roles
<who or what does which job; who has decision authority>

## Milestones
1. <milestone, with how it will be accepted>
2. ...

## Definition of done
<a short checklist someone other than the builder could verify>

## Stop gates
<points where work halts until the owner decides, and what must be true to pass>
```

```markdown
# State log: <project name>
As of: <date>
Current stage:        <where the work is>
Open items:           <what is unresolved>
Next authorized step: <what may happen next>
Next owner:           <who acts next>
```

## Filled example: this repository

This playbook was drafted by an AI builder under my brief, and I reviewed and corrected the work. The example separates what the brief required at the start from what I added during review, so the charter doesn't look more complete in hindsight than it was.

> **Charter: AI Research Playbook, v0.1** (condensed from the build brief, November 15, 2026)
> Owner: me
>
> **Objective.** Show how I plan AI-assisted work, keep decision authority, and learn from each build, in a form a generalist reviewer can follow in a minute.
>
> **Scope.**
> In: a README, a guide, two case studies, three templates, diagrams.
> Out: new research results; projects whose public claims were still being reconciled; code copied from other repositories (link instead).
>
> **Constraints.** No employer or client information. No private notes linked or quoted. Every factual claim has a source. No claim of autonomy, built integrations or measured accuracy gains. What I learned is stated by me, not inferred.
>
> **Roles.** I decide scope, wording and release. An AI builder drafts files and runs checks. Other AI tools gave separate reviews of the brief; I adopted their suggestions only where I judged they added value.
>
> **Milestones.**
> 1. Build plan approved by me before any file is written.
> 2. README and guide drafted; accepted by my review against the brief.
> 3. Case studies drafted; accepted the same way.
> 4. Templates and diagrams drafted; final privacy scan and claim check.
>
> **Definition of done.**
> - A generalist gets the three takeaways from the README in 60 seconds.
> - No overclaims; the research project is described as untested.
> - Diagrams render and match actual practice.
> - At least one template works for someone with a single AI tool.
>
> **Stop gates.**
> - Nothing is published until the privacy scan and claim check pass and I approve.
> - A conflict between sources is flagged to me, not resolved silently.

> **Clarifications I added during review** (same day, after the first drafts)
> - Narrow each claim to what its cited record establishes.
> - Tie project status to the date of the record it comes from.
> - Don't assign credit or blame to a tool where the record doesn't establish it.
> - Describe my own actions as reported unless they've been confirmed.
> - Published claims must match the verified evidence; discrepancies between working notes and the public record must be reconciled.
> - Lead with the research case. Cut the second case study down to a short supporting example.

> **State log**
> As of: November 15, 2026
> Current stage: all files drafted, none published.
> Open items: my final approval; checking the assembled repository on GitHub in light and dark themes; license.
> Next authorized step: my review of the complete set.
> Next owner: me.
