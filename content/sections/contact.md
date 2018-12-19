---
title: "Contact"
date: 2018-12-14T11:33:53-06:00
draft: true
order: 3
logos:
  general: img/stage-logo.svg
  calcium: img/calcium.png
contactInformation:
  general:
    general:
      title: General Inquiries
      email: stagecc@lists.renci.org
  calcium:
    gen3:
      title: Gen3
      email: gen3@example.com
    terra:
      title: Terra
      email: saturn-dev@broadinstitute.org
    dockstore:
      title: DockStore
      email: dockstore@example.com

---

<div id="contact" class='contact'>
  <h1>Contact</h1>
  <div class='contact__content'>
    <div class='contact__info'>
      <img class='contact__logo' src="{{< param "logos.general" >}}"/>
      {{< makelist "contactInformation.general" >}}
    </div>
    <div class='contact__info'>
      <img class='contact__logo' src="{{< param "logos.calcium" >}}"/>
      {{< makelist "contactInformation.calcium" >}}
    </div>
  </div>
</div>
