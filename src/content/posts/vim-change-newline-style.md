---
title: "vim 改变 newline 风格 (dos or unix)"
description: "how-to"
pubDate: "2024-7-28"
categories: ["how-to", "vim", "unix", "dos", "newline"]
---

ref: https://stackoverflow.com/questions/2613800/how-to-convert-dos-windows-newline-crlf-to-unix-newline-lf

ref: https://unix.stackexchange.com/questions/32001/what-is-m-and-how-do-i-get-rid-of-it

在 vim 中执行以下两行可以把 dos 类型的 CRLF 改为 unix LF:

```
:set ff=unix
:e ++ff=dos 
```

