### Expected Results
Checks #&#x2060;1 to #&#x2060;7 are all true.  
### Procedures
 1. Check that all [fundamental techniques](https://pdfa.org/understanding-pdf-accessibility-techniques) are followed.
 1. Check that all [real content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the author intends as a list is tagged as a list.
 1. Check that list tags are not used when the author does not intend a list.
 1. Check that the [substructures](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) of all **L** tags [semantically appropriate](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#semantically-appropriate) (**LI**, **Lbl**, **LBody**). 
 1. Check that the [ListNumbering attribute](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering) on all **L** tags in ordered lists is correctly set to "Decimal", "UpperRoman", "LowerRoman", "UpperAlpha" or "LowerAlpha".
 1. If the list item contains additional content, check that it is tagged in the most semantically appropriate way.
 1. Check that the complete [content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#content) of each list item with [substructure](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) is tagged correctly as a child of its parent **LBody** tag. 

 
