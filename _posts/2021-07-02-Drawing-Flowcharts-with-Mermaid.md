---
layout: post
title: Drawing Flowcharts with Mermaid
excerpt_separator: <!--more-->
---
**[Mermaid](https://mermaid-js.github.io/)** is a Javascript based diagramming tool. It is nice that we can use Mermaid on Github page. I tried creating and styling flowcharts with Mermaid. It could be a handy tool. 

<div class="mermaid">
  graph TD
  A([Trouble]) -->B{Investigation} -->C(Possible Reason 1) & D(Possible Reason 2)
  C --> E(Solution 1) & F(Solution 2)
  D --> G(Solution 1) & H(Solution 2)
  click E "https://www.google.com" _blank
  click G "https://www.google.com" _blank
  classDef simpleChart fill:#fff, stroke:#333, stroke-width:2px;
  class A,B,C,D,E,F,G,H simpleChart;
</div>

<br>
<br>
<div class="mermaid">
  graph LR
  A([Trouble]) --> F{Investigation} --> B(Possible Reason 1) & C(Possible Reason 2)
  B --> D("Solution #128279;")
  C --> E(Solution)
  click D "https://www.google.com" _blank
  click E "https://www.google.com" _blank
  classDef simpleChart fill:#0085bb, stroke:#fff, color:#fff;
  class A,B,C,D,E,F simpleChart;
 </div>
<!--more-->
