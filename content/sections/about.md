---
title: "About"
date: 2018-12-14T11:24:40-06:00
draft: false
type: "section"
order: 1
---
<div id="about" class='about'>
  <h1>About</h1>
  <div class='about__content'>
    <div class='about__intro'>
      <p>Data STAGE <a href='https://www.nhlbi.nih.gov/science/data-storage-toolspace-access-and-analytics-big-data-empowerment-data-stage' target='_blank'>(Storage, Toolspace, Access and analytics for biG data Empowerment)</a> directly addresses the NHLBI Strategic Vision objective of leveraging emerging opportunities in data science to open new frontiers in heart, lung, blood, and sleep (HLBS) research. Building on the Data Commons infrastructure, Data STAGE offers specialized search functions, controlled access to data, and analytic tools via widely available programming interfaces. With these capabilities, NHLBI researchers and other scientists can use NHLBI datasets for scientific discovery.</p><br />
      <p>NHLBI’s Data STAGE is an innovative computing solution, meeting the needs our research community through a cloud-based platform for tools, applications, and workflows. It is a virtual shared space where scientists can access and work with the digital objects of biomedical research, such as data and software.</p>
    </div>
    {{< accesspanel >}}
  </div>
  <div class='getting-started'>
    <div class='getting-started__content'>
      <h2 id="getting-started">Getting Started</h2>
        <div class='access-panel'>
          <div class='access-panel__header' role='button' onclick="toggleNoAccessPanel()">
            <h3>No Access?</h3>
            <img class='access-panel__icon' src='img/icons/dropdown.svg'/>
          </div>
          <div class='no-access-panel__information closed'>
            <p>Without Data STAGE access, you will be limited in your data analysis abilities but can still utilize public datasets.</p>
            <button onclick="browsePublic()">Browse Products with Public Datasets</button>
          </div>
        </div>
        <div class='access-panel'>
          <div class='access-panel__header' role='button' onclick="toggleCheckAccessPanel()">
            <h3>Check Access</h3>
            <img class='access-panel__icon' src='img/icons/dropdown.svg' />
          </div>
          <div class='check-access-panel__information closed'>
            <p>To check if you have access to Data STAGE, please click the button below. You will be prompted
            to log into the Data STAGE portal.</p>
            <button onclick="fetchAccessToken()">Check Access</button>
            <div class='check-access-panel__projects closed'>
            </div>
          </div>
        </div>
        <ol>
          <li>Check your access here.</li>
          <li>Select your exploration tool. Exploration tools allow users to search NHLBI datasets, providing for quick and easy creation of virtual cohorts that can be exported to an analysis tool.</li>
          <li>Select your analysis tool. Analysis tools yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada.</li>
          <li>Select applicable workflows. Workflows yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada yada.</li>
        </ol>
      </div>
    </div>
  </div>
</div>
