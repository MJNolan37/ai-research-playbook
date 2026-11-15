# Decision record

One short record per consequential decision. The part people skip, and the part that pays off later, is the alternatives: what else was on the table and why it was turned down.

## Template

```markdown
# Decision: <what was decided, in one line>

Date:    <when>
Owner:   <who decided>

## Options considered
1. <option>
2. <option>

## Decision
<the option chosen>

## Why the alternatives were rejected
- <option>: <reason>

## Evidence
<what the decision rests on, with links>

## Reversibility
<can this be undone, and what would have to change to revisit it>
```

## Filled example: holding the empirical gate in Project Parallax

This example was written for this template, after the fact, from the project's [public status page][a1] at its October 25, 2026 snapshot. It is not a copy of an original project document, and it is not a contemporaneous decision log. The background is in the [case study](../case-studies/parallax-validation-gate.md).

> **Decision: keep the empirical analysis closed; adopt no M=2 critical value.**
>
> **Date:** reflected in the public record at the October 25, 2026 snapshot. That page does not give the date of the original decision.
> **Owner:** me.
>
> **Alternatives reconstructed for this example**
>
> The status page documents the limitations and adoption status of each item below. It does not record an original deliberation among four options, so the list is my reconstruction, not a record of how the choice was framed at the time.
>
> 1. *The widely cited published value, 8.88.* The page records that it is the M=5 value and cannot serve as the M=2 threshold.
> 2. *The simulated finite-grid estimates.* The page records that they rose as the grid was refined, that the stated convergence criterion was not met, and that none is a critical value. It also records the methods assessment's point that small successive increments cannot, by themselves, bound the remaining discretization error.
> 3. *The redesigned simulation approach.* The page records that it was found implementable, that this is a feasibility finding and not acceptance of the design, and that it had not been run as a calibration.
> 4. *Holding the gate.* The page records the status as blocked, with no critical value frozen.
>
> **Evidence:** the [status page][a1]. The comparison with the published M=5 benchmark is recorded there as a reported observation with no frozen acceptance rule, so it was not a formal validation pass.
>
> **Reversibility:** Resolving the critical value and its methodological justification would address A1. Opening the empirical gate also requires the remaining project validation and implementation requirements to be satisfied.

[a1]: https://github.com/MJNolan37/Project-Parallax/blob/38411cc050696efde85d7702c9a11b9ad985c693/docs/A1_STATUS.md
