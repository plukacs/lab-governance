# Lab / Visibl
Purpose, Domains, Accountabilities defined by parent circle.

## Roles

### Lead Link - Erik
### Rep Link - Anikó, mandate until 2015. nov 1.
### Facilitator - Cassus, mandate until 2016. feb 6.
### Secretary - Anikó, mandate until 2015. dec 1.

Accountabilities:
- Make holiday schedule transparent towards the client through the Visibl dev team holidays calendar and in sync with the timesheet
(lab.coop_khb0ef170b9le7jidqkuco8484@group.calendar.google.com)
- Capturing demo agenda


### Developer

Purpose: Product

Accountability:
- taking tasks from the backlog and implementing them

Checklist:
- notified Visibl of all noticeable changes
- test cases were written before starting implementation of last week’s tasks

### Agile Pony - Erik, Cassus

Purpose: Efficient team

Domains:
- asana setup
- methodologies in use

### Admin - David

Accountability:
- handling client related administration (contract, certificate of completion, timesheet)
- organizing docs on the drive

### Tech lead - Cassus

Purpose: sustainable development

Domain:
- technical decisions not covered by steward roles

### Product Owner - Primarily Simon, also Aquilles and Cassus

Purpose: Development backlog, released product

Accountabilities:
- Prioritizing the dev backlog
- Showing the product vision to the dev team
- Establishing acceptance criteria for the stories (and what’s not needed to do)
- Reading slack messages about finished stories, and making sure they are what the story author actually intended.
- Elaborating on stories as needed

Domains:
- speed / quality tradeoffs
- what improvements to release continuously and what to hold back for bigger releases
- Development backlog and it’s priorities
Decides between implementation alternatives
Accept/reject implementation proposals
Expected quality level
What improvements to release continuously and what to hold back for bigger releases
Establishing priorities and Strategies for the Circle


### Product Manager (Client Link) -- Aquiles
Purpose: Business needs, domain knowledge, network

Domains:
- Budget
- Product Vision
- Product Backlog (Epics)

Accountabilities:
- Establishing priorities and Strategies for the Circle
- Defining the potential business value of Epics
- Generating business needs
- Sharing resources from the client’s team
- Purchasing and Managing project specific services, external resources for the team


## Steward
Focuses:
 - CSS: Anikó
 - Testing: Cassus
 - TradeDesk: David
 - Ruby backend: David
 - React: Cassus

Accountabilities:
- decides on foundation
- reviews code
- is responsible for quality

Checklist:
- was caught up with code review at some point last week



## All functions & activities within the Circle

##### Policy: Async governance process
We use the same Async governance process as TLC
A pull request becomes eligible for async once it is posted to #visibl on Slack

##### Policy: Holidays / Home office / Sick leave notification and approval
You have to clearly distinguish between holidays, home office and sick leave. Mark it in your calendar as soon as you're aware of it.
- Holidays: Let your circles on Slack and your clients know 2x the length of your planned holiday (in workdays) before the start of it, but minimum 5 workdays before in writing
- Home office: Let your circles on Slack know on the previous day if you would like to work from home all day long.
In case of Holidays and Home office, letting them know within this period doesn't mean that it's not allowed, but  can be declined, if your plan is not safe to fail.
- Sick leave: notify ASAP and keep others uptodate about your how being and expected first day of work.

##### Meetings
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
- To deploy to `stage` run `npm run build:stage && npm run deploy:stage`
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

##### Transparent client communication
Share any results of client communication that effects the group publicly. That can be easily done if you follow these guidelines:
 - When you chat with Visibl make sure to use a public slack channel.
 - When you email With Visibl make sure visibl@lab.coop is on CC
 - When you have a call with Visibl put the outputs to Asana tasks/comments or take notes to slack.

##### When handling an urgent task from Visibl, tell Visibl which task you’re interrupting.

##### Tags we use on the Dev Board
- project tags: used to show a task belongs to a project; no color
- WaitingForVisibl: task is blocked, waiting for answer from Visibl; color:  orange
- Foundation, Bug: tasks that don't belong to any particular project, does not change priority; no color
- QuickFix:
  - drop what you're doing and fix it the fastest way possible
  - add followup tasks if needed to clean up; color: orange.
  - When you find a bug that prevents users from accessing the basic functionality of the site, it becomes a `quickfix`, even without consulting the PO.
  - Its ok to revert any commits that caused the problem. Notify everyone involved, and unfinish the tasks.

##### Work In Progress limit for projects
3

##### Scope Changes
If the scope of a task increases while working on it, add new tasks for the overflow.
If the scope of a task decreases while working on it, reduce the estimation.

##### Retroactive Estimation of Bug Cards
After you finish a bug card, estimate how many story points you could have finished with that time, and put your estimate as the size of the card.

##### Project info that's decided outside of governance
is tracked in the `project info` doc.
