---
name: change-requests
description: Requests for changes in requirements.
---

# Document description

This document contains the change requests. A change request is a request for 
an addition to or change in requirements (and, consequently, the 
implementation plan). Change requests are provided by the stakeholders.

When processing a change request, set its state to `processing`, and augment 
the requirements in `docs/requirements.md` to reflect the change request, and 
then remove the change request from this document. A single change request can 
result in multiple new requirements, and/or changes in existing requirements.
Ensure the added requirements describe the test method and criteria.


# Change requests

The change requests table below lists the change requests. When making changes 
to the table, make sure the table format remains intact. When adding a change 
request, set the state to `defined`.

The table has these columns:
- ID - Unique identifier of the change request. ID is a number with prefix "C". 
  Change requests are temporary, do not use ID as reference in requirements. 
  When a change request is added to an empty table, set the ID to "C1".
- Stakeholder requirement - Description of the requirement, written by the 
  stakeholders.
- Architect notes - Notes by the architect.
- State - `defined`, `processing`

# Change requests table

| ID | Stakeholder requirement | Architect notes | State |
| --- | --- | --- | --- |
