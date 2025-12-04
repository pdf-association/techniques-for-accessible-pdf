### Expected Results
Checks #&#x2060;1 through #&#x2060;8 are all true. 
### Procedures
 1. Check that all [fundamental techniques](https://pdfa.org/understanding-pdf-accessibility-techniques) are followed.
 1. Check that all [real content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the author intends as a list is tagged as a list.
 1. Check that list tags are not used when the author does not intend a list.
 1. Check that the [substructures](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) of all **L** tags are [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate) (**LI**, **Lbl**, **LBody**). 
 1. Check that the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#ListNumbering-attribute) on all **L** tags in ordered lists is correctly set to "Decimal", "UpperRoman", "LowerRoman", "UpperAlpha" or "LowerAlpha".
 1. If the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering) is used on one or more **L** tags in an unordered list, check that it is correctly set to "None", "Circle", "Disc" or "Square".
 1. For those list items that include nested lists, check that the nested list's **L** tag is a child of the **LBody** of its containing list item. 
 1. For inline lists, check that the Placement [attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#attribute) is set at **L**, **LI**, **Lbl** and **LBody** to Inline.
