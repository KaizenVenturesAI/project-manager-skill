# Client AI agent installation

Organize discovery, setup, training, and handoff around the client's business outcome. Adapt [../assets/client-profile.md](../assets/client-profile.md) and [../assets/project-record.md](../assets/project-record.md) where existing records do not cover them.

## Discover and size

Map today's workflow: trigger, input, human judgment, tools/accounts, output, frequency, time spent, failure cost, and accountable person. Select one frequent, painful workflow whose output the client can judge.

T-shirt sizes are initial scope estimates, not promises:

- **Small:** one bounded workflow with existing access and a clear verifier.
- **Medium:** several systems, a new integration, or meaningful exception handling.
- **Large:** substantial custom software, migration, or coordinated delivery across multiple departments.

Size implementation effort separately from readiness: missing access or an unresolved owner can block a small workflow without making it large. Break larger work into a useful first slice plus backlog. Record estimate assumptions and dependencies. Confirm scope, commercial terms, and support responsibilities from the engagement; do not inherit another client's rates or historical consultant pricing.

## Prepare the environment

Record intended client, accounts/workspace, device/cloud runtime, data sources, and task/knowledge destinations. Check required connections with harmless reads and writes only within agreed pilot scope. Use supported secret/auth flows; keep credentials and completed profiles outside the reusable package.

Verify current installation behavior against supported platform documentation. Inspect existing setup before changing it and preserve a recovery path for material changes. A connected account does not establish every capability works. Record capability evidence and dates.

## Deliver a useful workflow

Agree on sample inputs, expected output, quality threshold, exceptions, and verification source. Run the whole workflow. Relevant checks include wrong account/recipient, duplicate inputs, missing data, failed connections, interrupted runs, and correction/retry. Select checks proportional to this workflow.

For executive assistants use [chief-of-staff-onboarding.md](chief-of-staff-onboarding.md); for custom software use [software-delivery.md](software-delivery.md). Keep untested features in the backlog, not the installed-capability list.

## Teach and hand over

Have the client/operator start a representative task, inspect the result, correct/redirect it, find its record, and stop or recover it. Distinguish agent demonstration from client teach-back and record training still outstanding.

Hand over what works, invocation and tested package revision, account/operating owners without secrets, authority boundaries, how to pause/revoke access, sources of truth, evidence, limitations, recovery steps, support owner, and agreed review date. Separate follow-on opportunities from completed scope.

Measure cycle time, manual interventions, corrections, and recurring operating cost when available. Include baseline and sample size; distinguish projections from measured savings. Generalize lessons before updating the reusable method. Publishing client examples or testimonial claims requires permission.
