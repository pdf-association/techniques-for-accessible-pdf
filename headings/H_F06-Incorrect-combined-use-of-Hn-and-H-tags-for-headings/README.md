This example demonstrates a failure condition in which the document contains both **H** tag(s) and **Hn** tag(s). In this case the document contains an **H** tag and an **H1** tag.

In PDF/UA, two different mechanisms to tag headings are introduced: (1) the use of nested H tags (2) the use of numbered Hn tags according their outline level. You have to choose one mechanism. It is not allowed to mix both.

NOTE: Due to a lack of suitable tools, the **H** tag, while defined in PDF's 1.7 specification, is impractical, and its use is not recommended.
