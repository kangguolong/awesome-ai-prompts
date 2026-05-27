---
name: Prompt request
description: Request a prompt template for a workflow
title: "Request: "
labels: ["prompt-request"]
body:
  - type: textarea
    id: workflow
    attributes:
      label: Workflow
      description: What workflow or problem should the prompt help with?
      placeholder: Describe the task, context, and intended user.
    validations:
      required: true
  - type: textarea
    id: current-process
    attributes:
      label: Current process
      description: How is this workflow handled today?
    validations:
      required: false
  - type: textarea
    id: desired-output
    attributes:
      label: Desired output
      description: What should the AI return when the prompt works well?
    validations:
      required: true
  - type: dropdown
    id: category
    attributes:
      label: Suggested category
      options:
        - coding
        - research
        - business
        - writing
        - productivity
        - decision-making
        - learning
        - tool-specific
        - misc
    validations:
      required: true
  - type: textarea
    id: constraints
    attributes:
      label: Constraints
      description: Mention tools, format, risks, exclusions, or quality requirements.
---
