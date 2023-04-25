# Requirement:

We want a project management system in which User can add, remove, update and view projects. Users has specific roles, based on which they can perform actions.

## User Roles and Actions:

· Project Manager – CRUD operations on project (Include Payment)
· Collaborator – CRU operations on project (Excluding Payments)
· Client – Track his projects progress of his project (optional)

## Functional Requirement:

- Every user should be able to perform CURD operation on their own account.
- Project should store:

  - Project name
  - Description
  - Deadline
  - Status
    - Paid
    - Under-review
    - Canceled
    - To-pay
  - Payment proof(image)

- Calculate the sum of project payments that needs to be paid to each collaborator and display it on Project Manager’s dashboard
- Optional:
  - Draw pie chart based on total projects done by collaborators, on the dashboard.
  - Handle the operations related to client, tracking the project.
