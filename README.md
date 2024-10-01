# Miscellaneous RobinLe Specifications

This repository contains miscellaneous specifications in a
[RFC](https://www.ietf.org/rfc/rfc1951.txt)-like style (72-column pure
ASCII `.txt` files), including a Table of Content with
dummy-page-numbers ("#" instead of numbers).

I chose this format because ...
- it can quite easily be correctly displayed on any device, as long as
  there is a text viewer with a monospace font;
- it is easy to parse and convert to a simple website, with links to the
  different chapters or sub-chapters;
- it looks rather pleasent while being quite simple.


## Differences to RFCs

- The specifications are not divided into pages, leading to additional
  differences:
  - there are no FORMFEED characters (`U+000C`);
  - there are no page footers or headers.
- The specifications aren't actually RFCs and are only created by me,
  not by a working group. So the document header is heavily reduced.


## Template File

The file `template.txt` can be used as a template for new specification
files.


## Versioning

At the deepest level, all specification directories contain files with
the naming scheme `vX.Y.txt`, where `X` and `Y` are integers.

Since I reserve the right to change these specification files after the
initial release, these version numbers refer to the version of the file
type, not the version of the specification.


## Modification Policy

I reserve the right to change specifications after I initially released
them. Reasons for this can be:
- typos;
- before creating a sample/example implementation, I didn't notice a
  conceptual mistake or that a certain part of the specification is
  over- or underspecified;
- I found a significantly better solution to a problem than the solution
  I initially chose.

However, once a 2nd version is present, no technical changes changes
will be made to the previous versions.
