---
title: "Products"
date: 2018-12-14T11:33:55-06:00
draft: false
type: "section"
order: 2
products:
  dockstore:
    name: DockStore
    category: Workflow
    compatibilities:
      - DockStore
      - Gen3
      - Terra
    logo: img/dockstore.png
    documentation: https://docs.dockstore.org
    url: https://dockstore.org/
  gen3:
    name: Gen3
    category: Exploration
    compatibilities:
      - DockStore
      - Gen3
      - Terra
    datasets:
      - TOPMed
      - GTEx
      - Public
    documentation: https://gen3.org/get-started/
    url: https://gen3.org
    logo: img/gen3.png
  terra:
    name: Terra
    category: Analysis
    compatibilities:
      - DockStore
      - Gen3
      - Terra
    datasets:
      - Nurses' Health Study
      - UK Biobank
      - Human Cell Atlas
      - AMP Parkinson's Disease
      - TOPMed
      - GTEx
      - Public
    url: https://bvdp-saturn-prod.appspot.com
    documentation: https://bvdp-saturn-prod.appspot.com/#library/showcase
    logo: img/terra.svg
datasets:
  - GTEx
  - TOPMed
  - Public
compatibilities:
  - DockStore
  - Gen3
  - Terra
categories:
  - Exploration
  - Analysis
  - Workflow
---

<div id="products" class='products'>
  <h1>Products</h1>
  <div class='products__filters'>
    {{< dropdown "compatibilities" "Select compatible products" products >}}
    {{< dropdown "datasets" "Select datasets" products >}}
  </div>
  {{< productslist categories >}}
</div>
