### 🔰[Quantifying creators’ contributions awkwardly](https://viadean.notion.site/Quantifying-creators-contributions-awkwardly-1551ae7b9a3280d78062fe5d3d185c03?pvs=4)
The issue of creators not getting paid for their data being used in AI training is a significant topic in the ethical and legal discussions surrounding artificial intelligence and machine learning. This concern arises because many AI systems are trained on vast datasets that may include copyrighted material, user-generated content, and other intellectual property, often without explicit consent or compensation to the creators.
```mermaid
---
title: Quantifying creators' contributions awkwardly
---
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
graph LR

A@{shape: text, label: "Original creatives"}
B@{shape: tag-doc, label: "Quantitative<br>contributions"}
C@{shape: docs, label: "Economic model"}
A:::c4

subgraph Mechanics
C:::c3-...-B:::c2-...-D:::c1
end
A-...-Mechanics:::c5
D-...-E:::c4

D@{shape: bow-rect, label: "revenue streams"}
E@{shape: text, label: "Creators"}


classDef c1 fill:#097523
classDef c2 fill:#097555
classDef c3 fill:#1f80e0
classDef c4 color:#e0531f
classDef c5 fill:#76a2ad

linkStyle 0,1,2,3 stroke:#ff3,stroke-width:4px,color:red;



```
