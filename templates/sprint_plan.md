# Create Sprint Tasks

Turn a project brief, goal, or set of requirements into a concise sprint objective and a practical, sequenced set of work items.

## Prompt

Using the information I provide:

1. Write a short sprint title.
2. Write a one-sentence sprint objective describing what the sprint should achieve.
3. Break the work into clear, actionable tasks.
4. Suggest relative effort for each task using story points: `1, 2, 3, 5, 8`.
5. Identify meaningful dependencies between tasks.
6. Identify tasks that can reasonably be worked on in parallel.
7. Suggest a practical order for completing the sprint.

Each task should:

* begin with an action
* describe one distinct piece of work
* be concise and easy to understand
* be specific enough to act on
* contribute directly to the sprint objective
* avoid unnecessary detail or invented requirements
* be small enough to make progress visible during the sprint
* avoid unnecessary dependency chains
* include research, planning, design, development, documentation, communication, or blockers only where relevant

Keep tasks at a reasonably consistent level of detail.

Do not use story points as hours. Estimate relative effort and complexity only.

Present the result as:

```text
Sprint: <title>

Objective: <objective>

ID        Points  Depends on  Task
PROJECT-1   2     —           <task>
PROJECT-2   3     PROJECT-1   <task>
PROJECT-3   5     —           <task>
```

Then provide:

## Suggested sequence

Describe the likely order of work and identify tasks that can proceed in parallel.

## Dependencies and blockers

Identify important dependencies, blockers, or sequencing concerns.

If information is insufficient to estimate effort or dependencies confidently, mark them as provisional rather than inventing certainty.

Project information:

Provide any relevant project goal, context, requirements, known work, constraints, current progress, team considerations, dependencies, and project key. This information may be structured or informal.

{{project_information}}