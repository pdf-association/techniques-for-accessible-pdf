### Expected Results
Checks #&#x2060;1 to #&#x2060;8 are all true.
#### Procedure
 1. Check that all [fundamental techniques](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#fundamental-techniques) are followed.
 2. Check that all [real content](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the [author intends](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Authors_intent) as a heading is tagged as a heading.
 3. Check that [heading tags](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Heading_tag) are not used when the [author does not intend](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Authors_intent) a heading.
 4. Check that either:
    - only **Hn** tags are used, or
    - only appropriately-nested **H** tags are used.
 5. Check that the first **Hn** tag, if any, is an **H1**.
 6. Check that the heading levels are appropriate to the content hierarchy of the document.
 7. Check that no heading levels are skipped.
 8. Check that headings with heading levels higher than 6 use custom **Hn** tags [role mapped](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#role-mapping) appropriately.
