The objective of this technique is to show how to tag a document title that appears on the page. 

In this example, the title of the document has been placed in a **Title** tag role mapped to **P** to acommodate most current-generation software, which is based on PDF 1.7. This method distinguishes the on-page document title from the document's heading(s) and is a best practice for tagging an on-page title. 

Due to the lack (prior to PDF 2.0) of a **Title** tag for page content, it became common practice to tag an on-page title using **H1** or some other tag role mapped to **H1**. The PDF Accessibility LWG does not recommend this method in a PDF/UA context because document titles and headings serve different purposes.

The _title_ is the name of the document as provided on the page. Its purpose can vary, but titles are generally intended to help readers understand what the document is about. Titles are commonly located at the top of a page, and formatted prominently (e.g., larger font, bold, or centered). A document may or may not have an on-page title.

In contrast to titles, _headings_ structure and organize the content within the document sections. Headings are important, especially in longer documents, to help with navigation and readability.

**NOTE:** As the **Title** tag was not specified for PDF 1.7 (or earlier) files, for software that only supports PDF 1.7 or earlier, **Title** is a custom tag. PDF/UA requires that custom tags are role mapped to a standard tag.
**Title** was introduced as a standard tag in PDF 2.0. Accordingly, PDF 2.0 software is able to represent any on-page content tagged with **Title** as the document's title. This approach will be covered in a PDF 2.0-specific Technique, to be developed.

### Document metadata and PDF/UA

PDF/UA requires that a title be present in the PDF file's metadata. This metadata is unrelated (technically) to the on-page title (if any) and thus must be set independently. PDF/UA does not require a title on the page, or that the document metadata precisely matches any on-page title. PDF/UA requires that the document metadata title clearly identifies the document.

Read this article for [detailed information about tagging titles in PDF documents](https://pdfa.org/how-to-tag-titles-in-pdf-documents/).
