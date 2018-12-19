---
title: "Products"
date: 2018-12-14T11:33:55-06:00
draft: false
order: 2
products:
  dockstore:
    name: DockStore
    category: Workflow
    compatibilities:
      - Gen3
      - Terra
    logo: img/dockstore.png
    documentation: https://dockstore.org
    url: https://docs.dockstore.org/
  gen3:
    name: Gen3
    category: Exploration
    compatibilities:
      - Terra
    datasets:
      - TOPMed
      - GTEx
    documentation: https://gen3.org
    url: https://gen3.org
    logo: img/gen3.png
  terra:
    name: Terra
    category: Analysis
    compatibilities:
      - Gen3
    datasets:
      - Nurses' Health Study
      - UK Biobank
      - Human Cell Atlas
      - AMP Parkinson's Disease
      - TOPMed
      - GTEx
    url: https://bvdp-saturn-prod.appspot.com
    documentation: https://bvdp-saturn-prod.appspot.com/#library/showcase
    logo: img/terra.svg
datasets:
  - GTEx
  - TOPMed
compatibilities:
  - DockStore
  - Gen3
  - Terra
categories:
  - Exploration
  - Analysis
  - Workflow
---

<div class='products'>
  <h1 id="products">Products</h1>
  <div class='tools__filters'>
    {{< dropdown "compatibilities" "Select compatible products" products >}}
    {{< dropdown "datasets" "Select datasets" products >}}
  </div>
  {{< toolslist categories >}}
</div>
