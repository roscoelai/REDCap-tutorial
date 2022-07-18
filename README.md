# REDCap Tutorial

[Part 1](./part-01.md)

## Instrument Design (Part 2)

> _"Not-so-basic"; Prepare to serve on 2022-07-21_

### Appetizer

- Organizing the My Projects page
- Any questions so far? (hope you had some practice!)
- Recap:
  - "Typical" instrument design procedure
    - Create
    - Edit -> Test -> Edit -> ...
    - Designate instrument(s) to event(s)
    - Activate survey(s)
    - Evaluation loop only necessary if caring about presentation
  - Friends:
    - Drag-and-drop branching logic
    - Rich text editor
    - Help pages for Action Tags, Piping, Field Embedding, Smart Variables, _etc._
  - 1 cause 4 effects
    - Data entry form
    - Survey
    - CSV export
    - PDF export
- Working fast
  - Multiple tabs

### Main Course

- Spend some time on field types
  - Brief look at each one
  - Calculated fields and `@CALCTEXT`
  - Inline image in descriptive text field
- Creating PIS & ICF
  - Screenshots
  - Minimizing uploaded/downloaded file sizes
  - The rest is like a normal instrument
  - Try to be boring
- Field Embedding
  - It's a hack!
- Tables
  - Tables are fictitious
  - Hidden cells or hidden rows (aesthetics)
  - HTML/CSS 101

### Dessert

- Data Import (it exists)
- Instrument versions discussion
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
- Some interesting action tags:
  - `@FORCE-MINMAX` (no need workarounds anymore!)
  - `@IF`
  - `@SETVALUE`
- 'Development' vs. 'Production'
- 'Instance' vs. 'Project'
  - What instances do we have?
  - Should we have more?

---

### Secret Menu

- Survey Queue
  - Must have a general idea
  - Must know the logic for the `END`s _in detail_
  - Especially:
    - When new instruments added in amendments
    - No access until after reconsent

---

