## 🔰[The dispute over pay package](https://viadean.notion.site/The-dispute-over-pay-package-1511ae7b9a3280cea39ad125be293cbe?pvs=4)

```mermaid
%%{init: {"flowchart": {"defaultRenderer": "elk"}} }%%
graph LR
 A@{shape: curv-trap,label: "Tesla CEO"}
 A:::CA
 G@{ shape: notch-rect, label: "Compensation" }
 G:::CG
 B@{shape: diamond, label: "Shareholders" }
 B:::CB
 A===G-->C
 C@{shape: hourglass,label: "wait"}
 C:::CC
 D@{shape: trap-b,label: "pay package"}
 D:::CG
 B-->C-->D
 E@{shape: brace-r,label: "Delaware judge<br>Chancellor"}
 F@{shape: bolt,label:"veto"}
 F:::CD
 H@{ shape: dbl-circ, label: "Veto" }
 H:::CD
 E-->H
 E==>F==>D-->H-...->A
 
 classDef CA fill:#2596be
 classDef CB fill:#873e23
 classDef CG fill:#148714
 classDef CC fill:#eab676
 classDef CD fill:#dc1014


```
