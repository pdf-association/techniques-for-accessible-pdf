### Expected Results
Checks #&#x2060;3, #&#x2060;6, and #&#x2060;8 are false.
### Procedures
 1. Check that all [fundamental techniques](https://www.pdfa.org/glossary-of-accessibility-terminology-in-pdf/#fundamental-techniques) are followed.
 2. Check that all [real content](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#real-content) that the [author intends](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Authors_intent) as a heading is tagged as a heading.
 3. Check that [heading tags](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Heading_tag) are not used when the [author does not intend](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#Authors_intent) a heading.
 4. Check that either:
    - only **Hn** tags are used, or
    - only appropriately-nested **H** tags are used.
 5. Check that the first **Hn** tag, if any, is an **H1**.
 6. Check that the heading levels are appropriate to the content hierarchy of the document.
 7. Check that the [title](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#title-onpage) of the document has been tagged in a **Title** tag, or another appropriate tag.
 8. Check that, if the document's [title](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#title-onpage) is tagged as (or [role mapped](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#role-mapping) to) **H1**, the main section headings are tagged as (or [role mapped](https://pdfa.org/glossary-of-accessibility-terminology-in-pdf/#role-mapping) to) **H2**.
