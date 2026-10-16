# ApproveFlow — Day 1

## Project goal

ApproveFlow is a backend API application for managing employee
purchase and expense approval requests.

## User roles

- Employee: creates and submits purchase or expense requests.
- Manager: reviews requests assigned to them.
- Finance: reviews requests that exceed the configured threshold.
- Admin: manages users, roles, manager assignments and the threshold.

## Approval rules

- Requests at or below the threshold require Manager approval.
- Requests above the threshold require Manager approval followed by Finance approval.
- Rejection ends the workflow.
- A submitted request cannot be edited.
- Decisions must be recorded with a timestamp and history.

## Technology stack

- Python
- Django
- Django REST Framework
- PostgreSQL
- Redis
- Celery and Celery Beat
- Docker and Docker Compose
- pytest and pytest-django

## Day 1 learning questions

1. What is an API?
2. What is the difference between Django and DRF?
3. What is a database model?
4. What is Docker?
5. What is a Git branch?
6. What is a pull request?
