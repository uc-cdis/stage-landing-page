---
title: "Products"
date: 2018-12-14T11:33:55-06:00
draft: false
type: "section"
order: 2
products:
  dockstore:
    name: Dockstore
    categories:
      - Workflow
    compatibilities:
      - Dockstore
      - FAIR4CURES
      - Gen3
      - Terra
    logo: img/dockstore.png
    documentation: https://docs.dockstore.org
    url: https://dockstore.org/
  fair4cures:
    name: FAIR4CURES
    categories:
      - Analysis
      - Exploration
    compatibilities:
      - Dockstore
      - FAIR4CURES
      - Gen3
    datasets:
      - TOPMed
      - GTEx
      - MODs
      - Public
    documentation: https://f4c.readme.io/docs
    url: https://f4c.sbgenomics.com
    logo: img/f4c-logo.svg
  gen3:
    name: Gen3
    categories:
      - Exploration
    compatibilities:
      - Dockstore
      - FAIR4CURES
      - Gen3
      - Terra
    datasets:
      - TOPMed
      - GTEx
      - Public
    documentation: https://gen3.org/get-started/
    url: https://gen3.datastage.io
    logo: img/gen3.png
  terra:
    name: Terra
    categories:
      - Analysis
    compatibilities:
      - Dockstore
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
  - MODs
  - Public
compatibilities:
  - Dockstore
  - FAIR4CURES
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
