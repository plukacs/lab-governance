# Lab / Product Dev / Visibl
Purpose: Unspecified.

## Roles

### Lead Link - Cassus
### Rep Link - 
### Facilitator - Dávid
### Secretary - Anikó

## All functions & activities within the Circle

### Meetings
- _Standup_: report last day's achievments and the plan for next day on Slack #standup
- _Tactical, governance, demo_: retrospective before the demo meeting
  - go through the tickets
  - if a ticket is not DONE by the time of the retrospective:
    remove story point but keep in sprint; move remainging subtasks to the next sprint
  - next sprint planning: reestimate remaining tickets

### Branching
Use master branch
codeship merges to production
Use feature switches if needed.

### Definition of DONE
- works locally
- has tests, unit tests, integration tests including UI interaction and mocked server
- Looks good enough for the user to understand it (not less usable than the original version if there is such)
- (codeship success)
- (deployed and works in production)

### A well defined task
- only contains at maximum 1 new UI component
- Acceptance criteria on the cards, as subtasks

### Before starting a task commit test cases without bodies and review them together
Our aim is to have the test titles ready before the estimation
