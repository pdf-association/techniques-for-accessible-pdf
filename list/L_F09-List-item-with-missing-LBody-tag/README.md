This example demonstrates a failure condition that applies when a list with at least one list item with [substructure](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) is not tagged correctly.

In this example, there are two list items that each contain multiple paragraphs of text. Each individual paragraph should be tagged in its own **P** tag and nested as children of their respective **LBody** tags. Each **LBody**'s second paragraph, however, is incorrectly tagged in separate **LI** tags. 

The complete [substructure](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) [content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#content) should be nested in the **LBody** of the related parent **LI** tag.

