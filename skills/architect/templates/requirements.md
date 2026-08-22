---
name: requirements
description: Requirements for the solution.
---

# Document description

This document contains the requirements for the solution. The requirements are 
input for creating the architecture and implementation plan.


# Requirements

The requirements table (see table below) lists all the requirements for the 
solution. When making changes to the table, make sure the table format remains 
intact. The rows are sorted by ID.

A requirement has state. Explanation of a requirement's state:
- When a requirement is added, its state is set to `defined`.
- The `defined` state indicates that the solution is not yet tested against the 
  requirements.
- When a requirement definition or acceptance criteria is changed, its state is 
  reset to `defined`.
- When a solution is tested against the acceptance criteria of a requirement, 
  and the test passes successfully, then the requirement's state is set to 
  `pass`. If the test fails, then the requirement's state is set to `fail`.

The requirements table has these columns:
- ID - Unique identifier of the requirement. ID is a number with prefix "R". 
  Used as reference for traceability in the implementation plan. When a 
  requirement is added to an empty table, set the ID to "R1".
- Requirement name - Short descriptive name of the requirement.
- Requirement description - Complete and concise description of the 
  requirement.
- Acceptance criteria - Criteria that the solution must satisfy.
- Notes - Notes by the architect.
- State - `defined`, `pass`, `fail`

## Requirements table

| ID | Requirement name | Requirement description | Acceptance criteria | Notes | State |
| --- | --- | --- | --- | --- | --- |
