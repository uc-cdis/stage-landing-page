---
title: "Contact"
date: 2018-12-14T11:33:53-06:00
draft: true
order: 3
logos:
  general: img/datastage-logo.svg
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
      email: terra@example.com
    dockstore:
      title: DockStore
      email: dockstore@example.com

---

<h2 id="contact">Contact</h2>
<div class='contact'>
  <div class='contact__info'>
    <img class='contact__logo' src="{{< param "logos.general" >}}"/>
    {{< makelist "contactInformation.general" >}}
  </div>
  <div class='contact__info'>
    <img class='contact__logo' src="{{< param "logos.calcium" >}}"/>
    {{< makelist "contactInformation.calcium" >}}
  </div>
</div>
