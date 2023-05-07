---
name: Title
about: Describe this issue template's purpose here.
title: ''
labels: enhancement
assignees: ''

---

# title

## What should be added

## where

## why
body:
- type: dropdown
  id: download
  attributes:
    label: How did you download the software?
    options:
      - Homebrew
      - MacPorts
      - apt-get
      - Built from source
  validations:
    required: true
