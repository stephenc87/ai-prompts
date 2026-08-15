# Create Use Case

Turn a feature, user need, or workflow description into a clear, structured use case.

## Prompt

Using the information I provide, create a use case with the following sections:

## Use Case ID

Use the supplied ID where available. Otherwise suggest a simple identifier such as `UC-01`.

## Use Case Name

Give the use case a short, descriptive name.

## Goal

Describe what the user is trying to achieve and the intended outcome.

## Primary Actor

Identify the main user or role initiating the interaction.

## Supporting Actors

List systems, services, people, or external sources involved where relevant.

## Trigger

Describe what causes the use case to begin.

## Preconditions

List conditions that must already be true before the interaction can occur.

## Main Success Flow

Describe the normal successful interaction as numbered steps.

Keep each step:

* sequential
* concise
* observable where practical
* focused on what the actor or system does

## Alternative Flows

Describe valid variations from the main flow, such as:

* revising information
* cancelling
* providing missing information
* choosing another valid path

Name each alternative flow clearly.

## Exception Flows

Describe situations where the normal flow cannot continue, including:

* insufficient information
* unavailable or unreliable evidence
* errors
* permissions or access problems
* required human review or escalation

Include a safe next step where relevant.

## Postconditions

Describe the state after the use case finishes.

Where useful, distinguish between:

### Successful Outcome

What should be true after successful completion.

### Unsuccessful or Escalated Outcome

What should be true if the workflow cannot complete normally.

## Business Rules and Design Constraints

List important rules, safeguards, requirements, limitations, or design constraints that apply throughout the use case.

Do not invent business rules that are not supported by the supplied information.

## Example Scenario

Provide one concise, realistic example showing how the use case might occur.

Where useful, show:

* information supplied by the user
* assumptions or inferred information
* missing information
* resulting system behaviour

## Prototype or Implementation Coverage

Where relevant, identify the parts of the use case that should be demonstrated, designed, implemented, or tested.

Keep this focused on the supplied scope.

## Guidance

When creating the use case:

* preserve the intent of the supplied feature or workflow
* separate normal, alternative, and exception behaviour
* distinguish user actions from system actions
* make uncertainty and escalation explicit where relevant
* avoid inventing requirements, actors, decisions, or technical behaviour
* keep terminology consistent with the project information
* include only sections that add useful information
* identify important gaps or ambiguities rather than silently filling them

Use case information:

Provide any relevant feature description, user goal, actors, workflow, requirements, constraints, business rules, known exceptions, examples, prototype scope, or related project context. The information may be structured or informal.

{{use_case_information}}
