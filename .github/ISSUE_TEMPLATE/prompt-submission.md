---
name: Prompt submission
description: Suggest a new prompt template for the repository
title: "Prompt: "
labels: ["prompt-submission"]
body:
  - type: textarea
    id: use-case
    attributes:
      label: Use case
      description: What real workflow does this prompt help with?
      placeholder: Describe the workflow and user need.
    validations:
      required: true
  - type: textarea
    id: prompt
    attributes:
      label: Prompt
      description: Paste the proposed prompt template.
      render: text
    validations:
      required: true
  - type: textarea
    id: variables
    attributes:
      label: Variables
      description: List placeholders and what each one means.
    validations:
      required: true
  - type: textarea
    id: expected-output
    attributes:
      label: Expected output
      description: What should a good response look like?
    validations:
      required: true
  - type: dropdown
    id: category
    attributes:
      label: Category
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
    id: notes
    attributes:
      label: Notes, assumptions, or limitations
      description: Include any risks, tool-specific behavior, or review notes.
---
