# REDCap Tutorial

## Basic instrument design

---

## Main Course

- Create _simple_ instruments
  - Using the online interface (Online Designer)
  - Using the data dictionary method

### Side Dishes

- Behind the scenes:
  - Create project(s)
  - Add user(s)
  - Creating user accounts (?)

- Necessary side quests:
  - Create event(s)
  - Designate instrument(s) to event(s)
  - Enable survey(s)
  - Survey Login
  - Survey Queue

---

## General Workflow

- Online Designer
  - Create instrument
  - Copy instrument
  - Create field
  - Copy field
  - Delete field
  - Branching logic
    - Editing gotchas

- Data dictionary
  - When to use
    - Big instruments
  - Where to get:
    - Whole project level
    - Instrument level
  - How to edit
    - Excel (?)
  - Where to upload

- Test/Evaluate loop
  - Designate instrument(s) to event(s)
  - Create dummy subject(s)
  - Forms
    - Accessing the data entry page
  - Surveys
    - Survey setup procedure (per instrument)
  - Global survey config
    - Survey Login
    - Survey Queue

---

### So you wanna learn REDCap?

###### _... or don't, but have to anyway_

---

## 01 Instrument Design

- Welcome the to Online Designer page!
  - FYI (for now)
    - Form Display Logic
    - Survey Queue
    - Survey Login
    - Survey Notifications
  - Hands-on
    - Create
    - Upload
  - The Data Dictionary tab
    - The fastest way to make mass changes
      - ... unless your project's too big

- Intrument design page
  - Add field
    - Field attributes (internal)
      - Variable name
        - Need to start caring about this
      - Label
        - This will be the column names when exporting labels
        - So, take note!
        - Introducing the 'display vs. export' problem
          - I prioritize display, since participant will see it
      - Field type
      - Field validation
      - Action tags
    - Field attributes (external)
      - Branching logic

- Where to look for help/reference?

- Advice: Keep a tight feedback loop
  - Don't be a sniper (yet)!

## 02 Events Management

> _... huh, we doing events now?_

### For setting up tests

- For us 'event' == 'timepoint'
- Define events
- Designate instrument to events
  - Must be done to have something to test
- Back to Online Designer
  - Survey config (for surveys)
  - Survey Queue
    - I guess it's hands-on after all...
- Create dummy subject
  - Take the chance to review workflow
  - ... or short-circuit it

### 03 Differences Between Development and Production

- Instrument names (the non-display one)



