---
name: News Request
description: Make a news request
title: "[NEWS REQUEST]: "
labels: ["news", "web"]
body:
  - type: textarea
    id: news-body-en
    attributes:
      label: Text in English
      value: "Please input the article body in English"
    validations:
      required: true
  - type: textarea
    id: news-body-tr
    attributes:
      label: Text in Turkish
      value: "Please input the article body in Turkish"
    validations:
      required: true
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this request, you agree that the all information given for the article is correct and consented from their respective stakeholders.
      options:
        - label: I, hereby, declare that all information supplied for the article is accurate and has been consented to by their respective stakeholders.
          required: true
---