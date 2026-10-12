# Whole-goal drift control

## Use the implementation

The runnable entry for an agent is [SKILL.md](SKILL.md). It directs the agent to perform the task with existing authorized tools; it is not a daemon or a deterministic classifier. An LLM/agent host capable of reading skill files and using the required tools is needed. No sibling repository is required.

1. Obtain this repository through your normal authorized Git workflow, retaining all package files together. Review the skill and resources before adoption.
2. Install the repository folder as a skill named `goal-drift-control` through your host's documented skill installer or skill directory. Do not overwrite an existing customized installation; compare and preserve it first. Hosts without skill discovery can explicitly read `SKILL.md` and its task-relevant resources from the checked-out folder.
3. Invoke it on an actual authorized work item: “Use $goal-drift-control to review the actual candidate against the original requirement and apply the disposition to the next authorized action.” Supply the original goal, existing work-item/destination reference and permitted effects. Let the agent recover available facts rather than supplying fictitious observations.
4. Inspect the actual output and tool effects. A successful file load or syntax check is not actual-use acceptance. Missing tools/authority must be reported precisely rather than replaced with a simulated success.

Updates replace only this package after review; preserve customization, active obligations and history. Removing its skill folder stops future discovery after the host refreshes, not obligations or pending work already created. Follow the host's documented reload behavior; no current-session activation is promised.

Implementation and real-use evidence belong on the [owning work item](https://github.com/jack61714z/goal-drift-control/issues/1) and its linked candidate review. Until those observations are saved, actual use remains pending. Explicit invocation does not prove automatic selection or background event coverage.


## Purpose and adoption boundary

Use this guide to keep a bounded task and its cumulative direction aligned with the user's original outcome. It can be used with existing requirements, work orders, reviews, and ordinary prose. It does not require another document, a new template, a tracker, a common schema/runtime, or synchronized versions of other guidance.

This repository includes an independently invocable agent skill. The package is not activated merely by publication. It grants no operational authority and does not change installed rules or prove improved behavior. Use and redistribution are governed by the MIT license in this repository. Existing host permissions, approvals, privacy rules, writer constraints, and required review independence remain effective. Progressive Investigation (PI), an investigation method, and an existing Chat–Codex handoff system (C2C) remain independent; their active contracts are unchanged.

## Recover the actual task

Here PI means Progressive Investigation, an investigation method, and C2C means Chat/Codex communication tooling. These are examples of existing host capabilities, not required dependencies of this guide.

Recover the original intended outcome, the current work slice, effective scope decisions, actual state, and authoritative source. Distinguish the parent outcome from this slice. Use existing task identities and relationships where available; clarification is not a new work unit.

Know the permitted work and effects, exclusions, freezes, deferrals, dependencies, and exact exceptions with their authority. An exception permits its specific action under its conditions; a real defect does not reopen deferred scope. Include acceptance evidence and authorized delivery destination/audience. Preserve identity, revision, candidate, authority and other host metadata wherever material to the decision; a short semantic summary is not universally sufficient.

Give executor and responsible supervisor/reviewer the actual applicable goal/scope/acceptance substance. A locator alone is insufficient when they need the contents to act. Copies are projections of the authority source, not competing requirements. Resolve relevant conflicts before the affected action. This is information consistency, not a mandatory binding object or field layout.

## Make the next action answer to the whole

Before dispatch, acceptance of a result or repair, dependent publication, or completion, compare the concrete proposed next action with the original goal, cumulative work and direction, exclusions, exceptions and evidence.

Review these seven axes proportionately:

- Goal: does this action and the cumulative outcome serve the original intended result?
- Scope: are boundaries, deferrals, freezes and exact exceptions respected?
- Interfaces: are affected interactions and consumers understood and supported?
- Architecture: does the resulting structure remain appropriate to the goal?
- Ownership: are responsibility, authority and actual execution clear?
- Runtime/data/security: what behavior, data handling and security effects matter?
- Dependencies: what prerequisites, affected consumers and remaining parent obligations exist?

Use concise combined prose for simple work. These are not seven stages. For a non-applicable or unknown axis, explain why and which decisions the uncertainty limits. Reuse valid evidence. A local success or green check does not certify the whole, erase supported material drift, or override scope.

Supported conflict changes the action: narrow, stop, or redirect the affected step and withhold dependent effects. Continue independent authorized work. Do not add an approval ceremony to ordinary authorized actions.

Where material uncertainty prevents a decision, state the required observation and allowed investigation. Use the already-configured PI method or other appropriate existing reasoning support; this guide does not redefine its core or triggers. Broader understanding does not authorize broader implementation. Return actual observations and limitations to the responsible decision-maker.

## Review actual evidence and finish the right thing

The executor reports actual cumulative changes, checks, failures, omissions, evidence limits and remaining obligations in the existing result format. The responsible reviewer inspects actual artifacts and affected context, distinguishing inspection from supplied summaries and unread links. Responsibility for one's own dispatch or acceptance cannot be discharged by forwarding another verdict. One actor may hold multiple responsibilities if the host permits; consulting a second model does not itself establish independence.

Check both directions: important requirements have evidence, and important changes serve requirements. Each material finding needs its evidence, consequence and smallest justified disposition. Distinguish defects, necessary evidence gaps, optional hardening and deferred work; no findings and explicit uncertainty are valid conclusions.

Distinguish what is true of the observed candidate, whether it falls under the effective acceptance claim, and its current disposition. A label such as rejected, resolved or deferred cannot establish all three. Preserve supporting and contrary evidence; a real defect can remain outside this slice without becoming false or disappearing.

For a behavioral claim, use observations that reach the relevant decision or effect boundary, a discriminating counterexample where needed, and legitimate success controls. Check the test's expected result against the authoritative requirement; changing an expectation or repeating a green summary is not evidence that the required behavior occurred. Apply this proportionately, without imposing a new universal test framework.

Accept the reviewed slice, request a bounded repair or specific missing evidence, or retain a genuinely unresolved decision. Acceptance binds the actual candidate and effective scope; changed objects require reassessing affected conclusions. Report the next concrete action and any dependent effects held back.

Keep source delivery, merge, installation, loading, observed behavior, runtime outcome and parent completion as separate claims where relevant. A missing observation blocks only the claims/decisions it prevents. Closing a slice does not complete an unfinished parent. After workflow repair, return to the original deliverable's next incomplete transition.

## Independent use and maintenance

Example: an existing PR review can use the seven axes and reject an out-of-scope repair using its current prose. No template installation, task-tracker integration or new closure process is necessary.

This document owns alignment decisions and drift dispositions. It does not own Issue/PR closure retrospectives, task registration, work-record formatting, PI investigation lifecycle or C2C transport. Other existing obligations still apply because of their own authority, not because this document imports them. Update this guide independently; no sibling document/version is required. Changing a deployed host contract remains a separate authorized migration, preserving its identities, approvals, candidate semantics and history.

It owns the alignment judgment before dispatch and subsequent decisions, not the tool operation that sends an assignment. Both the dispatcher and the responsible reviewer retain their own applicable responsibility.

Reading this document can establish document coverage, not operational adoption or efficacy. No experiment or document-revision efficacy result is claimed.

Replace or remove this guide independently under the active host's authority. Preserve existing scope decisions, review obligations, history and unresolved dispositions; no sibling update is required.

## Revision, maintenance and license

Initial public document revision: 2026-10-12. Maintainer: jack61714z. Corrections may be proposed through this repository. Revised independently; sibling versions are not prerequisites. Publication does not activate this guidance, and behavioral efficacy remains unverified.

This document includes adapted policy and record material from [codex-with-chatgpt](https://github.com/jack61714z/codex-with-chatgpt), licensed under MIT, Copyright (c) 2026 codex-with-chatgpt contributors. New contributions are Copyright (c) 2026 jack61714z. See [LICENSE](LICENSE) for the complete MIT terms and preserved notices.

