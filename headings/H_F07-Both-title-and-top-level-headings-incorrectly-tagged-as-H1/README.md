This example demonstrates a failure condition in which both the document's title and main section headings are all tagged as **H1**. This is incorrect, as the document's title is not part of the heading hierarchy.

PDF/UA-1 requires the first heading in a document to be an **H1** and that heading levels are not skipped. It allows multiple **H1** headings in a document. 

If a title is tagged as **H1**, however, the main section headings must be tagged as **H2**. 
