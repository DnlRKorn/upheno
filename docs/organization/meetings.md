# The Unified Phenotype Ontology (uPheno) meeting series

The uPheno editors hold four regular calls at the moment (April 2024), organised by members of the Monarch Initiative and the Alliance and Genome Resources.
If you wish to join the meeting, you can open an issue on https://github.com/obophenotype/upheno/issues with the request to be added, or send an email to phenotype-ontologies-editors@googlegroups.com.

Meetings:

| Meeting | Timeslot | Meeting coordinators |
| ------- | -------- | -------------------- |
| Phenotype editors call | Friday 8am PT, ev. 4 weeks | Sue Bello (@sbello), Ray Stefancsik (@rays22) |
| Phenotype outreach call | Friday 8am PT, ev. 4 weeks | James McLaughlin (@jamesamcl), Arwa Ibrahim (@ar-ibrahim) |
| HP-MP harmonisation calls | Thursday 9am PT, ev. 4 weeks | Ray Stefancsik (@rays22), Sue Bello (@sbello) |
| OBA editors call | Friday 6:15am PT, Monthly on the third Friday | Ray Stefancsik (@rays22), Arwa Ibrahim (@ar-ibrahim) |

## Meeting preparation instructions

!!! note

    The instructions were created for the Phenotype editors call, but the general principles hold for all calls.

- The MC prepares the agenda in advance: everyone on the call is very busy and our time is precious.
- Every agenda item has an associated ticket on GitHub, and a clear set of action items should be added in [GitHub Tasklist syntax](https://docs.github.com/en/issues/tracking-your-work-with-issues/about-task-lists) to the _first comment_ on the issue.
    - If there are issues for any subtasks (e.g. PATO or Uberon edits), the list should be edited to link these.
    - Any items that do not have a subissue but do involve changes to patterns) should be edited to link to implementing PR.
    - It does not matter who wrote the first issue comment, the uPheno team can simply add a tasklist underneath the original comment and refine it over time.
    - Tag all issues which need discussion with "upheno call"
    - It _must_ be clear from the task list what the uPheno team should be doing during the call (discuss, decide, review). For example, one item on the task list may read: "uPheno team to decide on appropriate label for template".
    - Conversely, no issue should be added to the agenda that does not have a clear set of action items associated with it _that should be addressed during the call_. These actions may include making and documenting modelling decisions.
- Go through up to 10 issues on the [uPheno issue tracker](https://github.com/obophenotype/upheno/issues) before each meeting to determine how to progress on them, and add action items. Only if they need to be discussed, add the "upheno call" label.

## Meeting execution instruction

!!! note

    The instructions were created for the Phenotype editors call, but the general principles hold for all calls.

- Every meeting should start with a quick (max 5 min, ideally 3 min) overview of all the goals and how they processed. The MC should mention all blockers and goals, even the ones we did not make any progress on, to keep the focus on the priorities:
    - uPheno releases
    - uPheno documentation
    - Pattern creation
    - Patternisation: The process of ensuring that phenotype ontologies are using uPheno conformant templates to define their phenotypes.
    - Harmonisation: The process of ensuring that phenotype patterns are applied consistently across ontologies.
- For new pattern discussions:
    - Every new pattern proposal should come with a new GitHub issue, appropriately tagged.
    - The issue text should detail the use cases for the pattern well, and these use cases should also be documented in the "description" part of the DOSDP YAML file. Uses cases should include expected classifications and why we want them (and potentially classifications to avoid).  e.g. axis-specific dimension traits should classify under more abstractly defined dimension traits which in term should classify under Morphology. Add some examples of contexts where grouping along these classifications is useful.
- Agenda items may include discussion and decisions about more general modelling issues that affect more than one pattern, but these should also be documented as tickets as described above.

## After the meeting

- After every meeting, update all issues discussed on GitHub and, in particular, clarify the remaining action items.
- Ensure that the highest priority issues are discussed first.
