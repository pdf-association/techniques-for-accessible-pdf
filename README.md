# Techniques for Accessible PDF

This repo contains the PDF Association's Techniques for Accessible PDF as [published on pdfa.org](https://pdfa.org/techniques-for-accessible-pdf/). The contents of this repo are intended primarily for developers, whereas the same content is presented in a friendlier manner on pdfa.org. Developers and end-users alike can post Issues in this repo as public comments on the Techniques. These will be reviewed by the PDF Association's [Accessibility Liaison Working Group](https://pdfa.org/community/pdf-accessibility-liaison-working-group/).

![PDF support](https://img.shields.io/badge/PDF-1.7%2C2.0-blue)
&nbsp;&nbsp;&nbsp;
![PDF subsets](https://img.shields.io/badge/PDF%20subsets-PDF%2FUA--1%2CPDF%2FUA--2-blue)
&nbsp;&nbsp;&nbsp;
![LinkedIn](https://img.shields.io/static/v1?style=social&label=LinkedIn&logo=linkedin&message=PDF-Association)
&nbsp;&nbsp;&nbsp;
![Twitter Follow](https://img.shields.io/twitter/follow/PDFAssociation?style=social)
&nbsp;&nbsp;&nbsp;
![YouTube Channel Subscribers](https://img.shields.io/youtube/channel/subscribers/UCJL_M0VH2lm65gvGVarUTKQ?style=social)

Get your [zero-cost copy of ISO 14289-1, ISO 14289-2, & ISO:TS 32005 now](https://pdfa.org/announcing-no-cost-access-to-pdfs-accessibility-standards/)!

## Stats

![Open Issues](https://img.shields.io/github/issues/pdf-association/techniques-for-accessible-pdf)
&nbsp;&nbsp;&nbsp;
![Closed Issues](https://img.shields.io/github/issues-closed-raw/pdf-association/techniques-for-accessible-pdf)

## About

This repository contains a tree of technique folders. 

## Technique folders

Each technique is identified by a `technique-info.yaml` file in a directory.
That directory contains four files that define the technique:

1. `technique-info.yaml`
    - A file containing all data fields for the technique, except for the
	    Description and Tests, which are in separate files listed below.
2. `README.md`
    - A GitHub markdown file containing the description of the example file
      and the accessibility technique.
3. `tests.md`
    - A file containing a list of tests to check whether or not a particular
	    PDF meets the requirements of the technique.
4. `<title>.pdf`
    - The PDF example file for the technique.

## Data fields in `technique-info.yaml`

Data fields for `technique-info.yaml` are specified in the [/config/](/config/)
directory of this repository. Most fields are fully specified in 
[/config/fields.yaml](/config/fields.yaml).

Most data fields only allow certain values from a predefined list. Those are
either specified in `fields.yaml` or in another `.yaml` in the `/config/`
directory. The `description:` entry for a given field will indicate what, if
any, other file to consult for that field.

### Timestamp fields

There are several "Checked" fields listed in `fields.yaml` that are of
`type: Timestamp`, such as "LWG Tool Checked". Each of these fields records the time
when the relevant validator or checker software yielded "expected results" for the
example PDF file for the technique.

"Expected results" means:
- A PASS example passes validation, unless the validator is in error.
- A FAIL example passes all checks unrelated to the failure that the
  example demonstrates, unless the validator is in error.

These "Checked" fields are timestamps, as opposed to true/false for example,
for two reasons:
1. If the sample PDF is updated, the timestamp helps indicate which checks need
   to be rerun.
2. If a different version of the same checker yields different results in the
   future, the timestamp records when the old version of the checker yielded
   expected results.
