# figures (English)

```echarts
{
  "width": 560, "height": 340,
  "title": {"text": "Coverage of 121 posts", "left": "center", "top": 6, "textStyle": {"color": "#1f2937", "fontSize": 15}},
  "color": ["#2b66c4", "#f3a33c", "#2f9e44"],
  "legend": {"bottom": 6, "textStyle": {"color": "#1f2937", "fontSize": 12}},
  "series": [{
    "type": "pie",
    "radius": ["42%", "68%"],
    "center": ["50%", "52%"],
    "label": {"formatter": "{b}\n{c} posts", "color": "#1f2937", "fontSize": 12},
    "data": [
      {"name": "Covered", "value": 94},
      {"name": "Not applicable", "value": 25},
      {"name": "To write", "value": 2}
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
:Open NOW.md to see the task;
:Do the task in TASKS.md (1 minute);
:Check the box in TASKS.md;
:Progress is saved in PROGRESS.md;
stop
@enduml
```
