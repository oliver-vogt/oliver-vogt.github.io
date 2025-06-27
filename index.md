---
layout: home
title: ""
nav_title: "About"
---

<div style="margin-top: -1em;">
  <span style="color: #0c246c; font-weight: bold; font-size: 2em;">
    Welcome
  </span>
</div>

<div class="intro-flex">
  <img src="/assets/img/portrait.jpeg" alt="Portrait of Oliver Vogt" class="intro-img" />
  <div class="intro-text">
    I am a PhD candidate at the <a href="https://economics.ubc.ca/" target="_blank" rel="noopener">Vancouver School of Economics, University of British Columbia</a>. I was previously a PhD intern at the International Monetary Fund and the Swiss National Bank.
    <br><br>
    My main research interests lie in International Finance and Macroeconomics, with a particular focus on FX interventions and capital flows.
    <br><br>
    When I step away from the keyboard, you'll likely find me outdoors. I particularly enjoy cycling along Vancouver’s <a href="#BCCycling">coastal roads</a> or through the <a href="#AlpsCycling">high Alps</a> when I'm back home in Switzerland.
    <br><br>
    You can find more details in my <a href="/cv">CV</a> or explore my <a href="/research">research</a>.
  </div>
</div>

<!-- Linked Pictures -->
<div id="AlpsCycling" style="display:none; position:fixed; z-index:1000; left:0; top:0; width:100vw; height:100vh; background:rgba(0,0,0,0.7); align-items:center; justify-content:center;">
  <div style="background:#fff; padding:2em; border-radius:8px; max-width:90vw; max-height:90vh; display:flex; flex-direction:column; align-items:center; position:relative;">
    <a href="#" style="position:absolute; top:0.5em; right:1em; font-size:2em; color:#0c246c; text-decoration:none; font-weight:bold;">&times;</a>
    <img src="/assets/img/Alps_cycling.jpeg" style="max-width:80vw; max-height:80vh; margin-bottom:0.5em;" />
    <div style="color:#444; font-size:1.1em; text-align:center;">Stelvio Pass, Italy</div>
  </div>
</div>
<div id="BCCycling" style="display:none; position:fixed; z-index:1000; left:0; top:0; width:100vw; height:100vh; background:rgba(0,0,0,0.7); align-items:center; justify-content:center;">
  <div style="background:#fff; padding:2em; border-radius:8px; max-width:90vw; max-height:90vh; display:flex; flex-direction:column; align-items:center; position:relative;">
    <a href="#" style="position:absolute; top:0.5em; right:1em; font-size:2em; color:#0c246c; text-decoration:none; font-weight:bold;">&times;</a>
    <img src="/assets/img/BC_cycling.jpeg" style="max-width:80vw; max-height:80vh; margin-bottom:0.5em;" />
    <div style="color:#444; font-size:1.1em; text-align:center;">Bowen Island, British Columbia</div>
  </div>
</div>

<!-- Add this CSS at the end of your index.md or in your main.scss -->
<style>
  #AlpsCycling:target {
    display: flex !important;
  }
  #BCCycling:target {
    display: flex !important;
  }
.intro-flex {
  display: flex;
  align-items: flex-start;
  margin-top: 1em;
  gap: 32px;
}
.intro-text {
  flex: 1;
  min-width: 0;
}
.intro-img {
  width: 240px;
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