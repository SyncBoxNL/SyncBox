name: Feature Request
description: Request a new feature or a change to an existing feature!
title: "[Feature]: "
labels: ["enhancement"]

body:
  - type: markdown
    attributes:
      value: |
        Thanks for requesting changes to make SyncBox even better for everyone! Please note: when submitting this feature request, you're giving us permission to use your idea without any conditions!
    
        Make sure to keep an eye on this request, because we might ask you for more information!
- type: input
    id: title
    attributes:
      label: Summary
      description: Please give us a summary of your idea in as few words as possible
      placeholder: Summary of your idea...
    validations:
      required: true
  - type: textarea
    id: feature
    attributes:
      label: Feature
      description: Please describe your feature request in as much detail as possible. How does your feature look on different devices, like a phone and a desktop? If you have a drawing of the feature, attach it here too! 
      placeholder: Your idea...
    validations:
      required: true
