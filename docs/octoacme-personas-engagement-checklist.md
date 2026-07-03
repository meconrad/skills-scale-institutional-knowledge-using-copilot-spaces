# Personas Engagement Checklist

A lightweight checklist to help teams decide when to involve specialized personas during planning, implementation, and release.

## For each backlog item, consider these questions:

- Does this work touch sensitive data, auth, or compliance? If yes, engage: Security Lead
- Does this work change system boundaries or integrations? If yes, engage: Architect
- Will this change impact reliability, performance, or scaling? If yes, engage: SRE
- Are user flows or UI changes involved? If yes, engage: UX Researcher / Designer
- Do we need dashboards or event tracking for success metrics? If yes, engage: Analytics Engineer
- Is the release cross-team or user-impacting? If yes, engage: Release Manager and Delivery Lead
- Are there known cross-team dependencies? If yes, engage: Delivery Lead
- Will support and customer-facing teams need communication or runbooks? If yes, engage: Support / Customer Advocacy Lead

## Definition of Ready additions
When an item requires specialized review or input, ensure the following before pulling into a sprint:

- Required personas identified and assigned (names/emails)
- Acceptance criteria updated with persona-specific checks (e.g., "Security review completed")
- Instrumentation plan and dashboard owner defined (if metrics required)
- Release considerations documented (rollout plan, feature flags)

## Quick templates

- Persona engagement note (to add to PR or issue):
  - "Engage: [Persona] — reason: [brief reason], expected contribution: [e.g., review design, validate metrics], owner: @[team-member]"

- PR checklist additions example:
  - Security: security review complete — @security-lead
  - Data: instrumentation added and validated — @analytics-eng
  - Release: release plan documented and approved — @release-manager

## How to use
- Add this checklist to the project README or link from backlog templates.
- Use as a lightweight gating checklist during review or pull request approval.

