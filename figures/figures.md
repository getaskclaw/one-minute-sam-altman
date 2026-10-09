# figures

```echarts
{
  "width": 560, "height": 340,
  "title": {"text": "121 篇文章的覆盖情况", "left": "center", "top": 6, "textStyle": {"color": "#1f2937", "fontSize": 15}},
  "color": ["#2b66c4", "#f3a33c", "#2f9e44"],
  "legend": {"bottom": 6, "textStyle": {"color": "#1f2937", "fontSize": 12}},
  "series": [{
    "type": "pie",
    "radius": ["42%", "68%"],
    "center": ["50%", "52%"],
    "label": {"formatter": "{b}\n{c} 篇", "color": "#1f2937", "fontSize": 12},
    "data": [
      {"name": "已覆盖", "value": 94},
      {"name": "不适用", "value": 25},
      {"name": "待写", "value": 2}
    ]
  }]
}
```

```plantuml
@startuml
skinparam DefaultFontColor #1f2937
skinparam ArrowColor #5b6b8c
skinparam ActivityBackgroundColor #eef2fb
skinparam ActivityBorderColor #5b6b8c
skinparam ActivityFontColor #1f2937
start
:打开 NOW.md 看当前任务;
:到 TASKS.md 做它（≤1 分钟）;
:在 TASKS.md 打勾;
:进度记在 PROGRESS.md;
stop
@enduml
```
