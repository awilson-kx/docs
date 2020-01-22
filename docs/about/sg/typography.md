---
title: Style Guide – Typography – About – kdb+ and q documentation
hero: Site style guide
description: Rules for using sentence and title case, admonitions, and ordered and unordered lists
author: Stephen Taylor
keywords: kdb+, q, style, typography
---
# <i class="fas fa-pen-nib"></i> Typography



## Case

Use title case for **proper names**, e.g. _Python_, _C#_, _WebSocket_, _GitHub_. 
Among the notable exceptions are _macOS_, _q_ and _kdb+_.

Also use title case for the names of **panels, tabs and dialogs** in a UI, e.g. _Dashboard Manager_, _Connection Editor_. 

The **language** is _q_. 
The **database, process and product** are all known as _kdb+_. 
Although both are proper names they are both set in lower case, except where they begin sentences or headings. 


## Headings

Set headings in sentence case, i.e., in lower case except for

-   the first letter
-   acronyms, e.g. _IPC_, _HTTP_, _API_
-   proper names, e.g. _Python_, _C#_, _WebSocket_, _GitHub_, _macOS_

Apply inline code style where appropriate. 

Use hash characters, not underlines, to mark H1s and H2s. (Underlines break the site indexing script.) 

Minimize punctuation within a heading and end it without punctuation. 

Number headings in an article only when there are many references in the text to the numbers. Where there are a few references to heading numbers, replace them with the italicized heading texts, linked to the headings. 


## Ordered and unordered lists

Use numbered lists only 

-   where it is necessary to refer to a list item, e.g. “as in (3) above”
-   where the order is significant, e.g. in a sequence of instructions 

Where 

-   a list has no more than five items; 
-   the items are short; and
-   its items are clauses of a single sentence

suffix all but the last item with a semicolon, and use "and" or "or" before the last item if desired, as in this sentence. 
Otherwise, leave the ends of list items unpunctuated. 


## Admonitions

Use [admonitions](https://squidfunk.github.io/mkdocs-material/extensions/admonition/) for warnings, tips and notes.
Use them sparingly. 

!!! note "Example"

    This shows how it’s done.

In the Markdown source, the admonition above looks like this:

```markdown
!!! note "Example"

    This shows how it’s done.
```


## Tables

Make column headers lower case, except for proper names and code objects. 

Prefer text code blocks for tables with many columns or columns that do not 
need to be wrapped. E.g.

```txt
label          symbol
errorClass     symbol
description    string
problemText    string
errorMessage   string
startLine      long
endLine        long
startIndex     long
endIndex       long
```


