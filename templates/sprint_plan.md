# Create Sprint Tasks

Turn a project brief, goal, or set of requirements into a concise sprint objective and a practical set of work items.

## Prompt

Using the information I provide:

1. Write a short sprint title.
2. Write a one-sentence sprint objective describing what the sprint should achieve.
3. Break the work into clear, actionable tasks.

Each task should:

* begin with an action
* describe one distinct piece of work
* be concise and easy to understand
* be specific enough to act on
* contribute directly to the sprint objective
* avoid unnecessary detail or invented requirements
* include research, planning, design, development, documentation, communication, or blockers only where relevant

Keep tasks at a similar level of detail.

Present the result as:

```text
Sprint: <title>

Objective: <objective>

1. <task>
2. <task>
3. <task>
...
```

If a project or issue key is provided, use it instead of numbering:

```text
PROJECT-1 <task>
PROJECT-2 <task>
PROJECT-3 <task>
```

Project information:

{{project_information}}
