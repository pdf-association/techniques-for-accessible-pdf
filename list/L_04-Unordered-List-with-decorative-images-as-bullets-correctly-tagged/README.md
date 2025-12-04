The objective of this technique is to show how to tag a list in which non-standard characters are used as list item labels. 

In this case, the **Lbl** tags contain **Span** tags that contain the graphical element, with a [Unicode](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#unicode) character as [ActualText](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#actualtext). 

Due to the nature of the list item label, the **[ListNumbering](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering)** attribute must either not be set or be set to "None". In this technique, the **[ListNumbering](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#listnumbering)** attribute is not set, which defaults to "None".
