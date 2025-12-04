### Expected Results
Checks #&#x2060;1 to #&#x2060;6 are all true. 
### Procedures
 1. Check that all [fundamental techniques](https://pdfa.org/understanding-pdf-accessibility-techniques) are followed.
 1. Check that all [real content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the author intends as a list is tagged as a list.
 1. Check that list tags are not used when the author does not intend a list.
 1. Check that the [substructures](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) of all **L** tags are [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate) (**LI**, **Lbl**, **LBody**). 
 1. Check that the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering) on all **L** tags in ordered lists is correctly set to "Decimal", "UpperRoman", "LowerRoman", "UpperAlpha" or "LowerAlpha".
 1. Check that the sublist **L** tags are within **L** and in the correct logical content order.
