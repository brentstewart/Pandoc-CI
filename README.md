# Pandoc-CI

This project is a demonstration of maintaining documentation via Github.  Contributors can clone the repo, create or update a markdown file, and create a PR.
On each pull or push to the repo, a CI process spawns throgh GitHub actions using _.github/workflows/test.yaml_.  It consolidates all the Markdown files and creates a single PDF (using alphabtetical order).  It also creates a Table of Contents and tacks that on the front.
The problem with team documentation is that everyone but one person always has an out of date copy of each portion.  Many times theres not a single copy that has all the up-to-date pieces.  This project shows how documentation can be created across the team and a current version made available to all members.  Further, it produces a pretty PDF version with each commit.

The actual included files are just "lorem ipsum" with enough formatting to generate a TOC.
