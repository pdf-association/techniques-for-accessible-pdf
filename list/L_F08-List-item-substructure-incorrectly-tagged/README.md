This example demonstrates the failure condition that applies when a list with at least one list item with  [substructure](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) is not tagged correctly, breaking the list's structure for AT users.

In this example, two list items include additional paragraphs. Each paragraph's **P** tag is incorrectly placed outside of the **L** tag.

Each **LBody** should be a parent of the complete [substructure](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#substructure) [content](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#content), in this case the **P** tags should be children of their respective **LBody** tags. 
