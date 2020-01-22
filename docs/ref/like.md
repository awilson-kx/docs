---
title: like – Reference – kdb+ and q documentation
description: like is a q keyword that matches text to a pattern.
author: Stephen Taylor
keywords: like, kdb+, pattern, match, q, regex, regular expression, string
---
# `like`



Syntax: `x like y`, `like[x;y]`

Match text/s `x` to pattern in string `y`. Where `x` is

-   a symbol atom or list
-   a string or list of strings
-   a dictionary whose `value` is a symbol list, or list of strings

The result is a boolean list indicating which items in `x` match the pattern `y`.

In pattern `y` certain characters have special meaning:

- `?` matches any character
- `*` matches any sequence of characters
- `[]` embraces a list of alternatives, any of which matches
- `^` at the beginning of a list of alternatives indicates characters that are _not_ to be matched

Special characters can be matched by bracketing them.

<i class="fas fa-book"></i> 
[`ss`, `ssr`](ss.md),
[Regular Expressions in q](../basics/regex.md),
[Strings](../basics/strings.md)<br>
<i class="fas fa-graduation-cap"></i>
[Using regular expressions](../kb/regex.md) 


