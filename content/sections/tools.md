---
title: "Tools"
date: 2018-12-14T11:33:55-06:00
draft: true
order: 2
products:
  DockStore:
    capabilities:
      - Docker
    logo: img/dockstore.png
  Gen3:
    capabilities:
      - Authentication
      - Authorization
      - Data Exploration
      - Data Upload
      - Docker
      - Indexing
    compatibilities:
      - Terra
    datasets:
      - TopMED
      - GTex
    documentation: https://gen3.org
    url: https://gen3.org
    logo: img/gen3.png
  Terra:
    capabilities:
      - Data Analysis
    compatibilities:
      - Gen3
    datasets:
      - TopMED
      - GTex
    logo: img/terra.svg
datasets:
  - GTex
  - TopMED
tools:
  - DockStore
  - Gen3
  - Terra
capabilities:
  - Authentication
  - Authorization
  - CWL
  - Data Exploration
  - Data Analysis
  - Data Upload
  - Docker
  - Indexing
---

<h2 id="tools">Tools</h2>
<div class='tools__filters'>
  {{< dropdown "capabilities" "Select capabilities" >}}
  {{< dropdown "tool" "Select compatible tools" >}}
  {{< dropdown "datasets" "Select datasets" >}}
</div>
{{< toolslist products >}}
