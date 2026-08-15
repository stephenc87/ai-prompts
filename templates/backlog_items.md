# Backlog Item Development Prompt

## Purpose

Use this prompt to develop or refine candidate product backlog items from project needs, ideas, risks, findings, user feedback, technical questions, or unfinished work.

The goal is to help structure possible work for team discussion without treating AI-generated items as committed sprint work.

## Inputs

I may provide:

* project context;
* requirements;
* risks or blockers;
* technical findings;
* user feedback;
* existing backlog items;
* unfinished work from previous sprints;
* lecture or project-owner guidance;
* ideas raised by team members.

Use only the information provided unless I explicitly ask you to introduce outside knowledge.

## Review and Development Process

For each possible backlog item:

1. Identify the underlying:

   * need;
   * problem;
   * uncertainty;
   * risk;
   * opportunity.

2. Explain briefly why it may be worth addressing.

3. Suggest an appropriate work type, such as:

   * user story;
   * technical story;
   * spike or research task;
   * bug;
   * documentation task;
   * risk/control action.

4. Draft a concise backlog title.

5. Draft a short description focused on the intended outcome.

6. Suggest a Definition of Done or observable evidence that would demonstrate completion.

7. Identify likely dependencies and related work.

8. Identify assumptions or questions that still require validation.

9. Indicate whether the item appears:

   * ready for refinement;
   * too broad and should be split;
   * dependent on another decision;
   * better suited to future work;
   * potentially unnecessary.

10. Suggest questions the team should answer before estimating or committing to the item.

## When Reviewing Multiple Items

Where several candidate backlog items exist:

* identify duplication or overlap;
* suggest possible ordering;
* distinguish genuine prerequisites from work that can happen in parallel;
* identify opportunities to merge or split items;
* highlight relationships between items;
* avoid inventing hard dependencies where they are not justified.

Where useful, show how broad work could mature through stages such as:

investigate → prototype → test → integrate → refine

## Constraints

Do not:

* treat generated backlog items as committed sprint work;
* assign tasks to team members;
* assign story points unless an agreed estimation method has been provided;
* automatically place items into a sprint;
* assume a technical choice has already been made;
* create dependencies simply because two topics are related;
* turn every idea into a backlog item.

Prefer small, testable outcomes over broad tasks such as:

* “research everything”;
* “build the architecture”;
* “solve hallucinations”;
* “implement the chatbot”.

Clearly distinguish between:

* backlog candidate;
* current sprint commitment;
* future work;
* unresolved question;
* hypothesis or technical option.

## Output

For each candidate item, provide:

**Title:**
**Work type:**
**Underlying need:**
**Description:**
**Definition of Done / evidence:**
**Dependencies or related work:**
**Assumptions / open questions:**
**Readiness:**

After reviewing all items, provide a short backlog-level summary covering:

* likely priorities;
* overlaps;
* dependencies;
* items that may need splitting;
* items that may be better left for later;
* questions the team should discuss before Sprint Planning.

## Final Instruction

Treat the backlog as a set of possibilities, not promises.

Help me prepare material for team refinement and decision-making rather than replacing collaborative planning.
