# Presentation

Contains the mechanisms through which external users and systems interact
with the application.

## Responsibilities

- Define HTTP endpoints and API routes.
- Handle incoming requests and outgoing responses.
- Validate and serialize external data.
- Translate external requests into application use cases.

## Dependencies

- May depend on the application layer.
- Should not contain business rules.
- Should not directly implement persistence logic.
