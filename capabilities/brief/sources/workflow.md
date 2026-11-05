# Understand the product brief

Read the actual brief/README and referenced files, not only the user's paraphrase or later review questions. Use [source and evaluation guidance — reference](../../../references/brief/index.json) to interpret evidence. Use [constraint extraction — reference](../../../references/brief/index.json) for interacting conditions or when formats, standards, supported environments, or input limits materially affect correctness.

Build a compact source map covering the parts that exist:
- Product goal, roles, core tasks, explicit exclusions.
- Input formats, schemas, examples, units, dates/time zones, invalid inputs.
- Output/export contract, persistence, deployment/run instructions, required artifacts.
- Delivery context: execution environment, stakeholders, handoff artifacts, time budget, tool constraints, and any provided delivery procedure.
- Acceptance criteria and any supplied review rubric; exact weights **only when available**, otherwise mark them unknown.

Convert requirements into observable acceptance conditions. Record source and locator for each. Distinguish mandatory constraints from optimization goals and informal usability signals. Keep stakeholder clarifications traceable and flag conflicts that materially affect delivery.

Reconcile the original brief with the current user's clarifications and accepted preferences. A later correction can change the required outcome without replacing the original goal. When handing work to a fresh context, retain those user-authored constraints with their source and scope; exclude prior implementation answers and evaluator hints separately. Do not call a preference violated when it was never supplied, or silently treat an omitted requirement as a product exclusion.

Explain priority using mandatory completion, correctness impact, dependency, user value, and available time. Keep these delivery priorities separate from external evaluation. Do not introduce invented numerical weights or predicted scores.

For a missing original, label reconstructed material as secondary evidence, identify missing sections, and continue bounded work. Ask for the missing source only when its absence blocks a material decision. A remembered statement is not a verified current contract.

Generate only useful project records, using existing owner documents where possible. Organize substantial records under the actual product domains or responsibilities: keep an area's stakeholder questions and answers, requirements, specifications, decisions and acceptance evidence together, with an entry that makes the relevant detail discoverable. Do not turn the source map above into an ever-growing set of root-level Markdown files or one flat `docs/` collection. Preserve a shared interview or meeting record once and link its relevant evidence from affected areas. Keep the project-wide overview short and route to those owners through hierarchical references. A focused single area can remain shallow; do not create empty document categories or impose a fixed domain template.

Recheck ownership within each affected area as the brief grows. Peer questions, specifications and acceptance records are appropriate for one coherent workflow. If those records each contain different independently governed policies or lifecycles, move each subresponsibility's related records into its own child area. Keep common product constraints at their shared owner and reference them. Stop at cohesive leaves, allow mixed depths, and preserve unrelated branches when only one workflow changes.

Before handoff, follow representative product questions through the reference entries to the actual owner documents and evidence. Check that unresolved questions have not become confirmed policies and that moves preserve source locators and incoming links. Graph validity and sensible content ownership are separate checks.

Do not write project-specific confidential material into this source, its public examples, or evaluation reports. See [synthetic brief examples — reference](../../../references/brief/index.json) for distinctions that apply across domains.
