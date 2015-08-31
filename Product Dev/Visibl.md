# Lab / Product Dev / Visibl
Purpose, Domains, Accountabilities defined by parent circle.

## Roles

### Lead Link - Cassus
### Rep Link - Anikó, mandate until 2015. nov 1.
### Facilitator - Erik, mandate until 2015. dec 1.
### Secretary - Anikó, mandate until 2015. dec 1.

Accountabilities:
- Make holiday schedule transparent towards the client through the Visibl dev team holidays calendar and in sync with the timesheet
(lab.coop_khb0ef170b9le7jidqkuco8484@group.calendar.google.com)


### Developer

Purpose: Product

Accountability:
- taking tasks from the backlog and implementing them

Checklist:
- notified Visibl of all noticeable changes

### Agile Pony - Cassus

Purpose: Efficient team

Domains:
- asana setup
- methodologies in use

### Tech lead - Cassus

Purpose: sustainable development

Domain:
- technical decisions not covered by steward roles

### Product Owner - ?

Accountabilities:
- Prioritizing the dev backlog
- Showing the product vision to the dev team
- Establishing acceptance criteria for the stories (and what’s not needed to do)
- Accepting stories as they are delivered
- Elaborating on stories as needed

Domains:
- speed / quality tradeoffs
- what improvements to release continuously and what to hold back for bigger releases

### PO-proxy - Cassus

Purpose: satisfied client and represents the PO, users within the team

Accountabilities:
- Manage client expectations


Domains:
- Backlog


## Steward Roles

Accountabilities:
- decides on foundation
- reviews code
- is responsible for quality

Checklist:
- was caught up with code review at some point last week
- test cases were written before starting implementation of last week’s tasks

### CSS - Anikó
### Testing - Cassus
### TradeDesk - David
### Ruby backend - David
### React - Cassus
### Analytics - Erik



## All functions & activities within the Circle

### Policy: Async governance process
We use the same Async governance process as TLC
A pull request becomes eligible for async once it is posted to #visibl on Slack

##### Meetings
- _Standup_: report last day’s achievments and the plan for next day on Slack #standup
- _Tactical, governance, demo_: retrospective before the demo meeting
  - go through the tickets
  - if a ticket is not DONE by the time of the retrospective:
    move it to the next sprint
  - next sprint planning: reestimate remaining tickets
  - fill the todo after the demo, create clarification tasks for anything uncertain
  - if there is a call for reactions of any kind, you may positively sign that you do not have a reaction by putting your hand on the table

##### Branching
- Use `master` branch
- Codeship deploys to production
- Use feature branches if needed
- Force push to `stage` to deploy your code to staging
- Prefix features branches with your name so we know which branch belongs to whom. eg. `cassus-pretty-icons`

##### Doing status
- Move the card to `Doing` before you start working on it.
- Don’t work on cards not in `Doing`.

##### Blocked status
- When you’re waiting for an answer from someone at Visibl, tag the task with `waiting for Visibl`.
- When you’re blocked by someone else, have the tag `blocked` on the task.
- Whether the card was in `Todo` or in `Doing`, the card stays in the same place when you tag it.
- Comment why it’s blocked.

##### Definition of DONE
- works locally
- has tests if it makes sense
- Looks good enough for the user to understand it (not less usable than the original version if there is such)
- codeship success
- deployed and works in production
- for any Visibl or user noticeable change, a screenshot (if static change), animgif screencast (if interaction change), and link (optional) shared in #development in Visibl Slack and attached to the Asana task. you don’t have to wait for a response, this is only to make our changes/progress more transparent.

##### A well defined task
- only contains at maximum 1 new UI component
- Acceptance criteria on the cards, as subtasks

##### Don’t use deadlines in Asana Visibl Dev Board

##### Before starting a task commit test cases without bodies and review them together
Our aim is to have the test titles ready before the estimation

##### For discussions that are not blocking a dev task, add a ticket to the `Visibl Discussions` project in Asana

##### If you run into foundation stuff, make a card for it so that others are aware

##### Codeship
- When you finish for the day, make sure that codeship is green. Revert if needed.

##### change infrastructure safely
- When configuring a third party service, work in a pair if you are not confident or there is no revert option.

##### Browser support
IE9 and up

##### Transparent client communication
Share any results of client communication that effects the group publicly. That can be easily done if you follow these guidelines:
 - When you chat with Visibl make sure to use a public slack channel.
 - When you email With Visibl make sure visibl@lab.coop is on CC
 - When you have a call with Visibl put the outputs to Asana tasks/comments or take notes to slack.

##### When handling an urgent task from Visibl, tell Visibl which task you’re interrupting.
