---
name: Model Build
description: Start a build process
title: "[Build]: "
labels: 
  - "build-model"
projects: []
assignees:
  - octocat
body:
  - type: markdown
    attributes:
      value: |
        Lets begin do build!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-variables
    attributes:
      label: What are the objectives?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "Add your vars"
    validations:
      required: true
  - type: checkboxes
    id: to-remember
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com)
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true

## Checks
- [ ] Tests
- [ ] Variables
