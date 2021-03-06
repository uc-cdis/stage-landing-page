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
      <p>Data STAGE <a href='https://www.nhlbi.nih.gov/science/data-storage-toolspace-access-and-analytics-big-data-empowerment-data-stage' target='_blank'>(Storage, Toolspace, Access and analytics for biG data Empowerment)</a> directly addresses the <a href='https://www.nhlbi.nih.gov/about/strategic-vision' target='_blank'>NHLBI Strategic Vision</a> objective of leveraging emerging opportunities in data science to open new frontiers in heart, lung, blood, and sleep (HLBS) research. This Strategic Vision consists of four mission-oriented goals:</p>
      <ul class='about__color-list'>
        <li class='about__color-list-item red'>
          Understand Human Biology
        </li>
        <li class='about__color-list-item green'>
          Reduce Human Disease
        </li>
        <li class='about__color-list-item orange'>
          Develop Workforce and Resources
        </li>
        <li class='about__color-list-item blue'>
          Advance Translational Research
        </li>
      </ul>
      <p>Building on the Data Commons infrastructure, Data STAGE offers specialized search functions, controlled access to data, and analytic tools via widely available programming interfaces. With these capabilities, NHLBI researchers and other scientists can use NHLBI datasets for scientific discovery.</p><br />
      <p>NHLBI’s Data STAGE is an innovative computing solution, meeting the needs our research community through a cloud-based platform for tools, applications, and workflows. It is a virtual shared space where scientists can access and work with the digital objects of biomedical research, such as data and software.</p>
    </div>
    <div class='about__access'>
      <h3>Do you have access to STAGE?</h3>
      <button class='about__button' onclick="window.location.href = '#getting-started'">Yes</button>
      <button class='about__button' onclick="openNoAccessPanel(); window.location.href = '#getting-started'">No</button>
      <button class='about__button' onclick="openCheckAccessPanel(); window.location.href = '#getting-started'">I Don't Know</button>
    </div>
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
          <li>Select your exploration tool. Exploration tools allow users to search NHLBI datasets, providing for quick and easy creation of virtual cohorts that can be exported to an analysis tool.</li>
          <li>Select your analysis platform. Analysis platforms provide tools to manipulate data and drive discovery.</li>
          <li>Select applicable workflows. Workflows specify input and search parameters, allowing for repeatable processes that reduce redundant work associated with complex analysis.</li>
        </ol>
      </div>
    </div>
  </div>
</div>
