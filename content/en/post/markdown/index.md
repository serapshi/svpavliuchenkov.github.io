---
title: Markdown markup language.
Summary: Learning how to design reports with the lightweight Markdown markup language is easy!
date: 2023-11-24
math: true
authors:
  - admin
tags:
  - Markdown
image:
  caption: 'Embed rich media such as videos and LaTeX math'
---

## Markdown Basics
- To create a title, use the ( # ) sign.
- To bold text, enclose it in double asterisks.
- To italicize text, enclose it in single asterisks.
- To bold and italicize text, enclose it in triple asterisks.
asterisks.
- Citation blocks are created by using the > symbol:
- An unordered (bulleted) list can be formatted with asterisks or dashes.
- To nest one list within another, add an indentation for the items in the child list.
- An ordered list can be formatted with appropriate numbers
- To nest one list in another, add an indentation for the items in the child list
- The Markdown syntax for an embedded link consists of a [link text] part representing the hyperlink text, and a (file-name.md) part representing the URL or filename of the file being linked to.
- Markdown supports both embedding code fragments in a sentence and placing them between sentences as separate enclosed blocks. Fenced code blocks are an easy way to emphasize syntax for code snippets. The general format of enclosed code blocks
- Upper and lower indices are written as A\~2\~0 and 10\^19\^.
- In-text formulas are done in the same way as LaTeX formulas.
## Processing Markdown files
- We will use Pandoc https://pandoc.org/ to process Markdown files. Specifically, we will need the program pandoc , pandoc-citeproc https://github.com/jgm/pandoc/releases, pandoc-crossref; https://github.com/lierdakil/pandoc-crossref/releases.
- Convert the README.md file as follows: - pandoc README.md -o README.pdf


## Conclusion

- When creating such files, the main thing is not to be afraid to make mistakes and try to create perfect reports. I hope my text will help you to remember important places in Markdown syntax. 
