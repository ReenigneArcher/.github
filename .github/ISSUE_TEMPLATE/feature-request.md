name: Feature Request
description: Request a new feature.
body:
  - type: textarea
    id: description
    attributes:
      label: Describe the feature
      description: A clear and concise description of the feature. Mention any issues that this would solve.
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Desired solution
      description: A clear and concise description of any solutions that you have considered.
  - type: textarea
    id: additional
    attributes:
      label: Additional Context
      description: Add any other context here.
  - type: markdown
    attributes:
      value: |
        Thank you for creating a feature request! Please comment if you find workarounds or solutions before the 
        feature request is implemented.
