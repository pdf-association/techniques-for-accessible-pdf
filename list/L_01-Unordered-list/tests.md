### Expected Results
Checks #&#x2060;1 to #&#x2060;5 are all true. 
### Procedures
 1. Check that all [fundamental techniques](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#fundamental-techniques) are followed.
 1. Check that all [real content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the author intends as a list is tagged as a list (**L**).
 1. Check that **L** tags are not used where the author does not intend a list.
 1. Check that the required [substructures](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) (**LI**, **Lbl**, **LBody**) of **L** tags are present and [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate).
 1. If the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering) is used on any **L** tags in an unordered list, check that it is set to "None", "Circle", "Disc" or "Square", as appropriate for the content.
