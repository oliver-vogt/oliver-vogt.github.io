---
layout: home
title: ""
nav_title: "About"
---

<div style="margin-top: -1em;margin-bottom: 1em;">
  <span style="color: #0c246c; font-weight: bold; font-size: 2em;">
    Welcome
  </span>
</div>

<div class="intro-flex">
  <div class="intro-text">
    I am an Economist in the Monetary Policy Analysis Unit at the Swiss National Bank.
    <br><br>
    I hold a PhD in Economics from the University of British Columbia. I was previously a PhD intern at the International Monetary Fund and the Swiss National Bank.
    <br><br>
    My main research interests lie in International Finance and Macroeconomics, with a particular focus on exchange rates, capital flows and FX interventions.
    <br><br>
    You can find more details in my <a href="/cv">CV</a> or explore my <a href="/research">research</a>.
    <br><br>
    All views expressed are my own.
  </div>
  <img src="/assets/img/portrait.jpg" alt="Portrait of Oliver Vogt" class="intro-img" />
</div>

<!-- Add this CSS at the end of your index.md or in your main.scss -->
<style>
.intro-flex {
  display: flex;
  align-items: flex-start;
  gap: 32px;
  flex-direction: row; /* text left, image right */
}
.intro-text {
  flex: 1;
  min-width: 0;
}
.intro-img {
  width: 250px;
  max-width: 90vw;
  height: auto;
  border-radius: 4px;
}
@media (max-width: 800px) {
  .intro-flex {
    flex-direction: column;
    align-items: center;
    gap: 16px;
  }
  .intro-img {
    order: -1;
    width: 70vw;
    max-width: 320px;
    margin-left: 0;
    margin-bottom: 1em;
  }
  .intro-text {
    width: 100%;
    text-align: left;
  }
}
</style>