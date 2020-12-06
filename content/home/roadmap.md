---
widget: blank
headless: true
design:
# Choose how many columns the section has. Valid values: 1 or 2.
  columns: 1
weight: 300  # Order that this section will appear.

title: RDH Roadmap
subtitle: Draft version 0.9 (3-Dec-2020)
---

**Draft** Research Data Handling roadmap for The University of the West Indies, Cave Hill campus.

The Research Data Handling (RDH) Roadmap is a living document. Version 1, covering the period 2020-2022, has been approved by the Cave Hill campus Research Data Handling committee _(meeting metadata...)_. You can read more about the RDH committee _here_.

Version 1 includes objectives falling under **six** main categories:

1. **Planning:** Initial planning of the scope of planned RDH services
2. **Operation:** Development of campus structure to maintain these RDH services
3. **Infrastructure:** Initial creation and testing of software infrastructure to facilitate RDH
4. **Guidelines:** Plan and begin implementation of guidelines for best practice RDH
5. **Training:** Plan and begin creation of further RDH training materials 
6. **Support:** Plan and begin provision of RDH support to individual researchers 

### RDH implementation timeline
Version 1 of our roadmap covers the period from Sep 2020 when our RDH project began until Aug 2022. This first period covers phases 0 and 1 of the implementation process. 
- **Phase 0** _(Sep 2020 - Aug 2021)_ is largely a planning phase, with some pilot activity and early deliverables.
- **Phase 1** _(Sep 2021 - Aug 2022)_ involves initial rollout of primary services.
Phase 1 will include an assessment of progress, with the addition of further phases.

### RDM gantt chart 2020/21 (phase 0)

```mermaid
gantt
  dateFormat  YYYY-M
  axisFormat  %b
  todayMarker stroke-width:5px,stroke:#fb2d50,opacity:0.25

  %% section 1 - planning
  section Planning
  xxx     :done ,   task-a, 2020-9, 6w
  yyy               :active,  task-b, 2021-3, 12w
  zzz            :         task-c, after task-b, 24w
  aaa            :         task-d, after task-c, 20w

  %% section 2 - operations
  section Operation
  committee setup     :done ,   task-a, 2020-9, 6w
  committee ToR       :done ,   task-b, after task-a, 4w

  %% section 3 - infrastructure
  section Infrastructure
  xxx     :done ,   task-a, 2020-9, 6w
  yyy      : 8w
  
  %% section 4 - guidelines
  section Guidelines
  xxx     :done ,   task-a, 2020-9, 6w
  yyy      : 8w

  %% section 5 - training
  section Training
  xxx     :done ,   task-a, 2020-9, 6w
  yyy      : 8w  
  
  %% section 6 - support
  section Support
  xxx     :done ,   task-a, 2020-9, 6w
  yyy      : 8w  
  ```

### RDM gantt chart 2021/22 (phase 1)
```mermaid
gantt
  dateFormat  YYYY-M
  axisFormat  %b
  todayMarker stroke-width:5px,stroke:#fb2d50,opacity:0.25

  %% section 1 - planning
  section Planning
  xxx     :done ,   task-a, 2021-9, 6w
  yyy               :active,  task-b, 2022-3, 12w
  zzz            :         task-c, after task-b, 24w
  aaa            :         task-d, after task-c, 20w

  %% section 2 - operations
  section Operation
 xxx     :done ,   task-a, 2021-9, 6w
 yyy       :done ,   task-b, after task-a, 4w

  %% section 3 - infrastructure
  section Infrastructure
  xxx     :done ,   task-a, 2021-9, 6w
  yyy      : 8w
  
  %% section 4 - guidelines
  section Guidelines
  xxx     :done ,   task-a, 2021-9, 6w
  yyy      : 8w

  %% section 5 - training
  section Training
  xxx     :done ,   task-a, 2021-9, 6w
  yyy      : 8w  
  
  %% section 6 - support
  section Support
  xxx     :done ,   task-a, 2021-9, 6w
  yyy      : 8w  
  ```
   