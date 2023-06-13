---
marp: true
theme: uncover
class: invert
math: mathjax
title: Test
author: K
size: 16:9
---

# An intro

<!-- 
Some notes here that might be useful.
-->

## cake

the **cake** is a _lie_

```c#
var cake = false;
```

---

## Math is fun

$\mathcal{0}(n\log{n})$

$$
\begin{align}
x &= 0.5 + \frac{1+3}{2} \\
&= 2.5
\end{align}
$$

---

## Song 2

### Blur is dead

| Syntax      | Description | Test Text     |
| :---        |    :----:   |          ---: |
| Header      | Title       | Here's this   |
| Paragraph   | Text        | And more      |

---

## Mermaids

https://mermaid.js.org/intro/

<div class="mermaid">
graph TD
    subgraph SQL1
        SQL_Stage
        SQL_Live
    end
    subgraph WebV1
        LiveSite
        StageSite
    end
    subgraph WSV1
        FileManager
    end
    subgraph S3
        Logs
    end
    SQL_Stage--Publish-->SQL_Live
    StageSite-->SQL_Stage-->StageSite
    LiveSite-->SQL_Live-->LiveSite
    LiveSite-->FileManager
    FileManager-->Logs
</div>

---

<div class="mermaid">
timeline
    title History of Social Media Platform
    2002 : LinkedIn
    2004 : Facebook
         : Google
    2005 : Youtube
    2006 : Twitter
</div>

---

## Unicorns

<div class="mermaid">
gantt
  title My Product Roadmap
  dateFormat  YYYY-MM-DD
  section Cool Feature
  A task           :a1, 2022-02-25, 30d
  Another task     :after a1, 20d
  section Rad Feature
  Task in sequence :2022-03-04, 12d
  Task, No. 2      :24d
</div>

---

## Cakes

<div class="mermaid">
mindmap
  root((mindmap))
    Origins
      Long history
      ::icon(fa fa-book)
      Popularisation
    Research
      On effectiveness<br/>and features
      On Automatic creation
        Uses
            Creative techniques
    Tools
      Pen and paper
      Mermaid
</div>
