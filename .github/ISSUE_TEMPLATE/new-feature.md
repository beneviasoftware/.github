name: "New scope"
about: "A deliverable part of a shaped pitch"
type: Scope
body:
  - type: markdown
    attributes:
      value: |
        ### Purpose
        A scope represents one meaningful piece of a pitch that can be completed and demoed independently.

  - type: input
    id: outcome
    attributes:
      label: "Desired Outcome"
      description: "What will be true once this scope is complete?"
      placeholder: "e.g. User can reset password via email link"

  - type: textarea
    id: approach
    attributes:
      label: "Approach / Notes"
      description: "How do we intend to implement this?"
      placeholder: "Describe the approach at a high level including sketches, pseudo-code, etc..."
