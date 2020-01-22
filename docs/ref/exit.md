---
title: exit – Reference – kdb+ and q documentation
description: exit is a control word that terminates a kdb+ process with a specified exit code.
author: Stephen Taylor
keywords: exit, kdb+, kill, q, return code, terminate
---
# `exit`




_Terminate kdb+_

`Syntax`: `exit x`, `exit[x]`

where `x` is a positive integer, terminates the kdb+ process with `x` as the exit code.

```q
q)exit 0        / typical successful exit status
..

q)exit 42
```
```bash
$ echo $?
42
```

<i class="fas fa-book"></i> 
[`.z.exit`](dotz.md#zexit-action-on-exit) (action on exit) 
<br>
<i class="fas fa-book-open"></i> 
[Controlling evaluation](../basics/control.md), 
[Debugging](../basics/debug.md)

