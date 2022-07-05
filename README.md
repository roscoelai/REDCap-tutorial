# REDCap Tutorial

## Basic Instrument Design

### Appetizer

- Rule H

### Main Course

- Create _simple_ instruments
  - Using the online interface (Online Designer)
  - Using the data dictionary method

> _CSV to website to CSV_

### Side Dishes

> Get some coffee/tea!

- Behind the scenes (admins do these):
  - Create project(s)
  - Add user(s)
  - Creating user accounts (?)

- Necessary side quests (admins do these on live):
  - Create event(s)
  - Designate instrument(s) to event(s)
  - Enable survey(s)
  - Survey Login
  - Survey Queue
  - Create/Edit Report

### Dessert

- Action Tags
  - _e.g._ `@DEFAULT`, `@HIDDEN-PDF`, `@READONLY`, ...
- Instrument versions
- Data Import
- Basic HTML/CSS
  - Custom format/style in field labels
  - Creating _tables_ in instruments
    - It's rather gnarly...

---

## General Workflow

- Online Designer
  - THE Record ID field, and the first instrument
  - Create/Edit instrument
  - Copy instrument
  - Create/Edit field
    - Field attributes
      - Variable name will be the important one (also the less familiar one)
      - Field label will be the obvious one
      - Field types
  - Copy field
  - Delete field
  - Branching logic
    - Syntax (here, calculated fields, survey queue, reports, ...)
    - Gotchas

- Data dictionary method
  - When to use
    - When things get repetitive
    - Bigger instruments
    - Tables (they are quite annoying)
  - Project vs. instrument
  - Where to download
  - How to edit
    - Excel (?)
    - Find-and-replace
  - Where/How to upload

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

- Exports
  - Spreadsheets
  - PDF

- Moving to live/production
  - Differences between development and production

