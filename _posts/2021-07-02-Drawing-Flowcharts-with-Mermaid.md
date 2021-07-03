---
layout: post
title: Drawing Flowcharts with Mermaid
excerpt_separator: <!--more-->
---
**[Mermaid](https://mermaid-js.github.io/)** is a Javascript based diagramming tool. It is nice that we can use Mermaid on Github page. I tried creating and styling flowcharts with Mermaid. It could be a handy tool. 

<div class="mermaid">
  graph TD
  A([Trouble]) --> B(Possible Reason 1) & C(Possible Reason 2)
  B --> D(Solution 1) & E(Solution 2)
  C --> F(Solution 1) & G(Solution 2)
  click D "https://www.google.com" _blank
  click E "https://www.google.com" _blank
  classDef simpleChart fill:#fff, stroke:#333, stroke-width:2px;
  class A,B,C,D,E,F,G simpleChart;
</div>


<div class="mermaid">
  graph LR
  A([Trouble]) --> B(Possible Reason 1) & C(Possible Reason 2)
  B --> D("Solution #128279;")
  C --> E(Solution)
  click D "https://www.google.com" _blank
  click E "https://www.google.com" _blank
  classDef simpleChart fill:#0189cf, stroke:#fff, color:#fff;
  class A,B,C,D,E simpleChart;
 </div>
<!--more-->
