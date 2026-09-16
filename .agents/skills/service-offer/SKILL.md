---
name: service-offer
description: >-
  Formalise a reusable service offer from supplied context, especially for an IT services company.
  Use when the user invokes /service-offer or asks to structure, position, package, or present a service offer in Markdown or HTML.
user-invocable: true
metadata:
  internal: true
---

# service-offer

Transform the supplied context into a coherent, usable service offer without turning unknowns into facts.
This skill is suitable for an ESN and other service providers.

## Operating principles

- Preserve the supplied language unless the requester asks for another one.
- Work with incomplete context instead of waiting for a perfect brief.
- Ask only the missing questions that materially change the offer, then continue with explicit, reversible assumptions.
- Keep facts, assumptions, recommendations, and decisions visibly separate throughout the response.
- Never invent client names, references, certifications, compliance claims, delivery capacity, prices, margins, timelines, technical capabilities, or results.
- Keep the offer subordinate to integration, data, security, and operations fundamentals rather than presenting a technology, including AI, as an end in itself.
- State uncertainty plainly and identify the person or evidence needed to settle it.

## Start with a prioritized framing

Extract the provided information into four labelled registers before drafting.

| Register | Contains | Rule |
| --- | --- | --- |
| Facts | Provided and evidenced statements | Attribute the source when it matters. |
| Assumptions | Plausible placeholders needed to proceed | Mark them `À confirmer` and make them easy to replace. |
| Recommendations | Professional choices proposed from the evidence | Explain the rationale and expected trade-off. |
| Decisions | Choices that need ownership or validation | Name the decision owner, options, and consequence of delay. |

Then identify the gaps in priority order.

- **P0 - offer viability:** buyer or sponsor, target client segment, business problem, expected outcome, and reason to act now.
- **P1 - offer design:** current environment, integration and data constraints, delivery scope, differentiators, and buying path.
- **P2 - delivery confidence:** security and compliance expectations, operating model, stakeholders, procurement constraints, proof points, and commercial preferences.

Ask a short P0-first question list in this format: priority, question, why it changes the offer, and the default assumption that will be used if unanswered.
Do not ask more questions merely to complete a questionnaire.
After the questions, immediately continue with the provisional offer using the listed assumptions.
When P0 is unknown, describe the result as a proposition to validate rather than a committed offer.

## Reusable construction method

Use the following method in order, then apply it to the available context.

1. **Frame the mandate.**
   State the offer objective, intended reader, decision sought, and confidence level.
2. **Map clients and problems.**
   Describe the priority client profiles, their context, the jobs they need done, pains, risks, and buying triggers.
3. **Form the value proposition.**
   Connect each problem to an outcome, a credible mechanism, the required client contribution, and differentiating proof or evidence still needed.
4. **Package the service.**
   Define modular services with their purpose, activities, deliverables, entry criteria, exit criteria, dependencies, and optional extensions.
5. **Design the client journey.**
   Show the progression from discovery through assessment, design, delivery, handover, and run or continuous improvement.
6. **Set delivery boundaries.**
   Specify scope, exclusions, prerequisites, assumptions, responsibilities, and acceptance criteria.
7. **Make delivery trustworthy.**
   Describe the integration, data, security, and operational architecture and its guardrails at the level supported by the facts.
8. **Define governance and commerce.**
   Set decision forums, roles, cadence, escalation, commercial model options, pricing inputs, and contracting items to confirm.
9. **Plan adoption and growth.**
   Provide a go-to-market approach, an offer roadmap, risks, mitigations, and next actions.
10. **Check coherence.**
    Confirm that each promised outcome has a module, journey step, owner, prerequisite, safeguard, and commercially honest basis.

Present this method briefly before the applied offer when the requester asks for a method or reusable framework.
Otherwise, use it silently and make the resulting structure self-explanatory.

## Build the applied offer

Produce the following sections in the order that best serves the intended reader.
Omit only a section that is genuinely not applicable and say why it is omitted.

### 1. Offer summary

State the client situation, the service promise, the intended outcome, who it is for, and the confidence level.
Use outcome language rather than a list of technologies.

### 2. Priority clients and problems

For each priority client profile, state the context, problem, impact, trigger, existing alternatives, and evidence to validate.
Distinguish a segment hypothesis from a confirmed target market.

### 3. Value proposition

Describe the before-and-after situation, the delivery mechanism, differentiators, limitations, and proof required.
Make every claimed benefit traceable to an activity, deliverable, or operating practice in the offer.

### 4. Service modules

Use a table with module, client objective, activities, deliverables, prerequisites, and options.
Make modules composable without hiding dependencies between them.
Examples may include discovery, assessment, target design, implementation, data migration, integration, enablement, managed transition, and continuous improvement only when supported by the context.

### 5. Client journey

Describe the journey by phase with client actions, provider actions, decisions, outputs, and exit criteria.
Make handover and the transition to operations explicit.

### 6. Scope, exclusions, and prerequisites

Separate included work, excluded work, client responsibilities, provider responsibilities, dependencies, assumptions, and acceptance criteria.
Turn unresolved boundary choices into decisions rather than silently absorbing them into scope.

### 7. Architecture and guardrails

Describe only the architecture level needed to make the offer credible.
Cover these foundations explicitly when relevant:

- Integration interfaces, ownership, failure handling, and change control.
- Data sources, quality, lineage, retention, access, and migration or reconciliation needs.
- Security identity and access, least privilege, secrets, threat or risk review, compliance evidence, and incident responsibilities.
- Operations observability, service levels to agree, support model, resilience, backup or recovery, release management, and runbook ownership.

For every proposed automation or AI capability, state the human accountability, data boundaries, validation or fallback path, and operational monitoring required.
Do not promise an architecture decision before the relevant discovery, security review, and client approval have occurred.

### 8. Governance

Define roles, accountable decision makers, delivery cadence, steering forums, escalation path, risk management, quality review, and change control.
Use named roles rather than invented people.

### 9. Commercial model

Describe commercial options without fabricating figures.
State the charging unit, included capacity or deliverables, variable cost drivers, assumptions, change-control mechanism, and information required to price each option.
Use labels such as fixed scope, time and materials, subscription, retainer, consumption, or hybrid only when they fit the offer.
Mark every amount, rate, volume, duration, and discount as `À chiffrer` unless supplied by the requester.

### 10. Go-to-market plan

Define the priority segment, positioning, message, proof assets, channels, partners, qualification criteria, sales-to-delivery handoff, and learning metrics.
Do not claim market demand, conversion rates, or competitive position without evidence.

### 11. Roadmap, risks, and next actions

Sequence the shortest credible path from validation to first delivery and then scale-up.
List risks with likelihood or uncertainty, impact, early signal, mitigation, owner, and decision deadline where known.
End with the smallest concrete next actions, the evidence to collect, and the decisions to obtain.

## Response shape

Use this sequence when the input is incomplete:

1. `Questions prioritaires`.
2. `Hypothèses de travail`.
3. `Méthode de construction`.
4. `Offre de service provisoire`.
5. `Décisions et prochaines actions`.

Keep the fact, assumption, recommendation, and decision labels visible in the applied offer.
A short evidence register or a `Statut` column is preferable to repeating disclaimers in every paragraph.
Use concise tables where comparison helps, but explain significant trade-offs in prose.

## Markdown delivery

When Markdown is requested, provide one self-contained document with a title, executive summary, stable heading hierarchy, plain-language tables, and the registers above.
Use descriptive link text and avoid relying on colour, icons, or a table alone to convey a critical distinction.
Do not include placeholder numbers that could be mistaken for a quote.

## HTML delivery

When HTML is requested, produce a complete standalone HTML document as well as the Markdown source when both formats are requested.
Do not make the HTML a fragment or require external CSS, JavaScript, fonts, images, or network access.
Use semantic `header`, `main`, `section`, `nav`, `footer`, headings in order, native lists, and real tables with `caption`, `thead`, `th`, and `scope` where tables are used.
Set the document language with `lang`, include UTF-8 and viewport metadata, and give it a specific descriptive `title`.
Include a visible-on-focus skip link, readable responsive typography, sufficient colour contrast, a print-friendly stylesheet, and styles that preserve meaning in monochrome.
Escape supplied text before inserting it into HTML, avoid inline event handlers, and use no script unless an explicitly requested interaction cannot be delivered with semantic HTML and CSS.
Keep the Markdown and HTML semantically equivalent, including every assumption, exclusion, decision, and commercial caveat.

## Final review

Before delivering, verify the following.

- The offer answers a concrete client problem and does not lead with a solution looking for one.
- Every fact is distinguishable from an assumption, recommendation, or pending decision.
- Each module has a boundary, output, prerequisite, and relationship to the journey.
- Scope, exclusions, responsibilities, and acceptance are clear enough to prevent accidental commitment.
- Integration, data, security, and operations are treated as delivery foundations.
- Commercial content explains how pricing is determined without invented figures.
- Risks, decision owners, and next actions are actionable.
- Requested Markdown and HTML are complete, coherent, and accessible.
