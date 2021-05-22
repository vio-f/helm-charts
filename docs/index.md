---
layout: home
---

# [](#header-1)Quick Start

```bash
helm repo add vio-f https://vio-f.github.io/helm-charts/
helm install vio-f/<CHART_NAME>
```
## [](#header-2)Available Charts

> <LIST of Charts>
<ul>
{% for chart in site.index.entries %}
  <li>{{ chart[0] }} (  
  	{% for properties in chart %}
		{{ properties[0].version }}
  	{% endfor %}
   )</li>
{% endfor %}
</ul>

---
