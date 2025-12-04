### Expected Results
Checks #&#x2060;1 through #&#x2060;8 are all true.
### Procedures
 1. Check that all [fundamental techniques](https://pdfa.org/understanding-pdf-accessibility-techniques) are followed.
 1. Check that all [real content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the author intends as a list is tagged as a list.
 1. Check that list tags are not used when the author does not intend a list.
 1. Check that the [substructures](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) of all **L** tags are [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate) (**LI**, **Lbl**, **LBody**). 
 1. If the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering) is used on one or more **L** tags in an unordered list, check that it is correctly set to "None", "Circle", "Disc" or "Square".
 1. Check that the caption of the List is tagged as **Caption**.
 1. Check that the **Caption** tag contains [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate) [substructure.](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure)
 1. Check that the **Caption** tag is placed at the same level as the **LI** tags, and is either the first or last child tag of its containing **L** tag.
