---
title: "Tools"
date: 2018-12-14T11:33:55-06:00
draft: true
order: 2
products:
  dockstore:
    name: DockStore
    capabilities:
      - Docker
    logo: img/dockstore.png
    documentation: https://dockstore.org
    url: https://docs.dockstore.org/
  gen3:
    name: Gen3
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
  terra:
    name: Terra
    capabilities:
      - Data Analysis
    compatibilities:
      - Gen3
    datasets:
      - Nurses' Health Study
      - UK Biobank
      - Human Cell Atlas
      - AMP Parkinson's Disease
      - TopMED
      - GTex
    url: https://bvdp-saturn-prod.appspot.com
    documentation: https://bvdp-saturn-prod.appspot.com/#library/showcase
    logo: img/terra.svg
datasets:
  - GTex
  - TopMED
compatibilities:
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
  {{< dropdown "capabilities" "Select capabilities" products >}}
  {{< dropdown "compatibilities" "Select compatible tools" products >}}
  {{< dropdown "datasets" "Select datasets" products >}}
</div>
{{< toolslist products >}}
