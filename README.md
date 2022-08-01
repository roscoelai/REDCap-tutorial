# REDCap Tutorial

[Part 1](./part-01.md)  
[Part 2](./part-02.md)

## Training (more like meeting) Part 3

> _Instrument design no longer the main objective_

### Appetizer

- Questions so far?
- Recap:
  - 1 cause ~~4~~5 effects, what to prioritize when effects come into conflict
    - Data entry form
    - Survey
    - CSV export
    - PDF export
    - Data dictionary (obviously, but not so obvious)

### Main Course

- REDCap formula/logic syntax review (as prerequisite)
- Survey Queue
  - The 'participant cannot access surveys' problem
  - The 'participant was (not) reimbursed' problem
  - At least have a general idea how the system works
  - Logic for `END`s (_in detail_)
  - Especially:
    - When new instruments added in amendments
    - No access until after reconsent
    - _etc._
  - Logic for Saqstats
  - Discussion:
    - Extension of windows

---

### Dessert

- Smart Variables (not tried before)
  - `[survey-time-started:instrument:value]`
  - `[survey-time-completed:instrument:value]`
- Action Tags (not tried before):
  - `@FORCE-MINMAX`
  - `@IF`
  - `@SETVALUE`


