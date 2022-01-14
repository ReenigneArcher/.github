name: Bug Report
description: Create a bug report.
body:
  - type: textarea
    id: description
    attributes:
      label: Describe the Bug
      description: A clear and concise description of the bug.
    validations:
      required: true
  - type: textarea
    id: code
    attributes:
      label: Code Snippets
      description: >
        Add a code snippet that can be used to reproduce the bug.
        This will be automatically formatted into code, so no need for backticks.
      render: python
  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: A clear and concise description of what you expected to happen.
  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Add any other context about the bug here.
  - type: input
    id: os
    attributes:
      label: Operating System and Version
      placeholder: e.g. Windows 10, macOS 10.15, Ubuntu 20.04, etc.
    validations:
      required: true
  - type: input
    id: python
    attributes:
      label: Python Version
      placeholder: e.g. 3.9.6
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        Make sure to close your issue when it's solved! If you found the solution yourself please comment so that others benefit from it.
