---
name: Website Update Request
about: Request an update to the Telos.net, 2k18 or Tekika websites
labels: []
projects: ["telosnetwork/58"]
body:
  - type: markdown
    attributes:
      value: |
        Use this form to request a feature update to a Telos managed website, or to report a bug or issue with the website. Please fill out the form below to the best of your ability. If you are reporting a bug, please include as much information as possible to help us reproduce the issue.
 - type: dropdown
    id: issue-type
    attributes:
      label: Issue Type
      description: What type of issue are you reporting?
      options:
        - Feature Request
        - Bug
      default: Feature Request
    validations:
      required: true
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please provide a detailed description of the issue or feature request
    validations:
      required: true
  - type: dropdown
    id: application
    attributes:
      label: Which application is this issue related to?
      multiple: true
      options:
        - Telos.net
        - 2k18
        - Tekika
