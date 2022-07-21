---
marp: true
theme: academic
paginate: true
size: 16:9
math: katex
---

<!--
_class: cover
_paginate: false
-->

<br>
<br>

# title

#### subtitle

<br>
<br>
<br>

**FirstName FamilyName**
YYYY/MM/DD

---

<!-- _header: header -->

- $e^{i\pi} + 1 = 0$
  - nest$^1$
- `inline-code`
  - nest$^2$
- **bold** <citation>[1]</citation>

> 1: footnote
> 2: footnote

<!-- this become speaker note in powerpoint and html slide deck mode-->

---

<!-- _header: header -->

- $e^{i\pi} + 1 = 0$
  - nest$^1$
- `inline-code`
  - nest$^2$
- **bold**

> 1: footnote
> 2: footnote

<cover>
This is cover.<br>This is cover.
</cover>

---

<!-- _header: figure -->

1. [link](http://example.com)
2. $^{hello}$

![w:400 center](./sample.jpg)

> 1:footnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnotefootnote

---

<!--
_header: multiple-figure
_class: figure
-->

#### `_class: figure` convert table to mutiple-figure layout

<br/>
<br/>

|                        |                                |                        |
| ---------------------- | ------------------------------ | ---------------------- |
| ![w:200](./sample.jpg) | hello                          | ![w:200](./sample.jpg) |
| a                      | a                              | figure                 |
| ![w:200](./sample.jpg) | ![w:200](./sample.jpg)$^{[1]}$ | figure                 |
