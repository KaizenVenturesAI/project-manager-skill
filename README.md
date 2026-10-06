# Kaizen Project Manager

A reusable delivery skill for business projects, AI agent installations, and Chief of Staff onboarding. Built for Kaizen Ventures' consulting workflow and configurable for each client's people, goals, tools, and operating style.

The coordinator translates an outcome into small milestones, routes execution, verifies results, and maintains the operating record. Mode guides cover client installs, executive-assistant onboarding, and software/Mission Control delivery.

## What clients receive

- Discovery, T-shirt sizing, first useful workflow, verification, training, and handoff guidance.
- A private operating-profile template for identity, goals, authority, context, and tools.
- A project-record template for milestones, decisions, evidence, blockers, and value.
- Onboarding that checks source coverage and practical judgment, not just file reading.

The package includes no client identities, contacts, private records, rates, or credentials. Complete templates in the client's private workspace.

## Install the complete package

Use the **entire folder**, including `references/`, `assets/`, and `agents/`. The earlier upstream single-file installation omits the Kaizen mode guides.

For a fresh local macOS/Linux installation with Git:

```sh
mkdir -p "$HOME/.agents/skills"
git clone https://github.com/KaizenVenturesAI/project-manager-skill.git "$HOME/.agents/skills/kaizen-project-manager"
```

If the destination exists, inspect it and preserve local edits before updating. For managed deployments, check out the tested full commit SHA and record it in the handoff; avoid silently following future changes. This instruction-only package requires no setup script or account access.

In Codex invoke `$kaizen-project-manager`. In ChatGPT select the installed skill with `@` where supported, or ask the assistant to load `kaizen-project-manager/SKILL.md` and the relevant references from its connected computer. Verify the target assistant can read both the entrypoint and a mode guide. Local installation alone does not establish activation in a cloud Dot. Local skills require an available connected computer. If discovery does not refresh, start a new chat or restart the app as appropriate.

For existing onboarding:

> Use Kaizen Project Manager to continue my Chief of Staff onboarding. Reuse the review already underway. Build a sourced private operating profile, reconcile current priorities and role boundaries, and demonstrate judgment with draft-only rehearsals. Track reviewed, rehearsed, accepted, and enabled separately.

For a client install:

> Use Kaizen Project Manager to deliver our agreed first workflow. Recover discovery context and existing setup, identify the smallest useful milestone, verify the result, and prepare training and a support handoff. Keep client details in our private project record.

## Deployment checklist

1. Record and install the tested package revision in the client's environment.
2. Complete relevant profile fields from discovery and verified sources.
3. Verify capabilities in the intended accounts and agree on the first outcome.
4. Run the workflow and inspect evidence; installation does not prove reliability.
5. Complete client teach-back and support handoff; capture remaining scope separately.

The skill adapts to existing trackers, private Spaces, knowledge bases, and engineering tools. Mission Control, OpenClaw, Slack, and other vendors are optional. It supplies neither credentials nor standing permission for external actions or recurring automation.

## Validation and provenance

Version 1.0.0 is an initial Kaizen adaptation. [Behavioral scenarios](evaluations/scenarios.md) support repeatable evaluation; real outcomes should guide revisions.

This repository is a fork of [finna/project-manager-skill](https://github.com/finna/project-manager-skill), reviewed at `3180b828d3514d39ec9eea63dafea8af4231e878`, and retains that history. Upstream supplied the implementation-coordination and exact-build verification pattern; this adaptation adds business delivery and Chief of Staff onboarding. Upstream declared no license at that revision; this repository adds no license and does not represent that upstream redistribution rights have been resolved.

Platform references: [Build skills](https://learn.chatgpt.com/docs/build-skills) and [Meet dots](https://learn.chatgpt.com/docs/dots). Verify current host support on each install.
