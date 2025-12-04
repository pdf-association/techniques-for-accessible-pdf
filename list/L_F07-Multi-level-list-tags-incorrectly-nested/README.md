This example demonstrates a failure condition that applies when a multi-level (nested) list is inappropriately tagged.

Nested **L** tags can only be a child of another **L** tag **OR** an **LBody** tag. An **L** tag cannot be a child of an **LI** tag, as demonstrated in this fail case.

If this example had been structured properly it would have shown the nested **L** tag as a child of the **LBody** instead of as a child of the **LI** tag.

