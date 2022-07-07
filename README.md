# REDCap Tutorial

## Basic Instrument Design

> _Served on 2022-07-06, edited before archive_

### Appetizer

- Rule H

### Main Course

- Create _simple_ instruments
  - Using the online interface (Online Designer)
  - Using the data dictionary method

> _CSV to website to CSV (or PDF)_

### Side Dishes

- Behind the scenes (admins do these):
  - Create user accounts, need:
    - Email
    - First name, last name
    - Preferred username? (default will be concatenation of first and last name, all lowercase, no spaces)
  - Create project(s)
  - Add user(s) to project(s)

- Necessary side quests (admins do these on live):
  - Create event(s), we might call them 'timepoints'
  - Designate instrument(s) to event(s)
  - Enable survey(s), edit survey settings
    - These are packaged in the instrument ZIP now
  - Survey Login
  - Survey Queue
  - Create/Edit Report(s)

### Dessert

- Piping
- Action Tags
  - _e.g._ `@DEFAULT`, `@HIDDEN-PDF`, `@READONLY`, ...
- Instrument versions
- Data Import
- Basic HTML/CSS
  - Custom format/style in field labels
  - Creating _tables_ in instruments
    - It's rather gnarly...

### Next Course

- Topics (draft)
  - Review/Questions from previous course (hope you had some practice!)
  - Organizing the My Projects page
  - Calculated fields and `@CALCTEXT`
  - Inline image in descriptive text field
    - PIS & ICF
  - Smart Variables
    - `[record-name]`
    - `[survey-time-started:instrument:value]`
    - `[survey-time-completed:instrument:value]`
    - `[event-id]`
    - `[event-number]` (NoOo...)
    - `[event-name]`
    - `[event-label]`
    - `[arm-number]`
    - `[arm-label]`
  - Field Embedding
    - Tables (hands-on)
      - 'Simple' table
      - Tables with hidden rows/cells
  - Differences between development and production
  - Some interesting action tags:
    - `@FORCE-MINMAX`
    - `@IF`
    - `@SETVALUE`

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
      - Choices syntax: <number>, <choice description>
      - Field types
  - Copy field
  - Delete field
  - **Branching logic**
    - Syntax
      - Variable name in square brackets: `[variable_name]`
      - Checkbox fields: option number in round brackets `[var_name(5)]`
      - `=` and `<>`: quote values (especially for 0)
      - `<`, `>`, `<=`, `>=`: do <ins>not</ins> quote values
    - Drag-and-drop is your friend!

- Data dictionary method
  - When to use
    - When things get repetitive
    - Bigger instruments
    - Tables (future course)
  - Syntax for choices: delimited by `' | '`
  - Project vs. instrument
  - Where to download
  - How to edit
    - Excel (?)
    - Find-and-replace
  - Where/How to upload
  - What to upload
    - CSV file of whole project data dictionary
    - CSV file of instrument data dictionary in a ZIP file

- Hybrid
  - Create some fields online
  - Download and continue using data dictionary method
  - Upload and tidy up online
  - Mix-and-match

- Test/Evaluate loop
  - Setup:
    - Create a few fields in instrument (not the whole instrument)
    - Designate instrument(s) to event(s)
    - Create dummy subject(s)
    - Forms
      - How to access data entry page
    - Surveys
      - Survey setup procedure (per instrument)
      - How to access survey response page
    - Global survey config (admins)
      - Survey Login
      - Survey Queue
  - Loop:
    - Edit fields or create more fields for instrument
    - Have a look
    - Repeat...

- Exports
  - Reports (spreadsheets)
  - PDFs

