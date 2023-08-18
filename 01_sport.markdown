---
layout: page
title: Sport
permalink: /sport/
---
<style>
    #carousel {
        width: 100%;
        display: grid;
        grid-template-columns: 1fr 1fr 1fr;
        grid-template-rows: 1fr;
        gap: 0.5vh 1vw;
        grid-template-areas:
            "pnl-1 pnl-2 pnl-3";
        overflow-x: auto;
        white-space:nowrap;
    }

    .slide {
        display: grid;
        width: 28vh;
        grid-template-columns: 100%;
        grid-template-rows: 80% 20%;
        grid-template-areas:
            "image"
            "txt";
    }
    .image {
        padding: 1vh;
        grid-area: image;
    }
    .text {
        display: flex;
        text-align: center;
        justify-content: center;
        align-items: center;
        color: #ffffff;
        background-color: #6e829a;
        border-radius: 0 0 2vh 2vh;
        grid-area: txt;
    }
    #introfade {
        height: 1.5vh;
    }
    .heading {
        font-weight: 600;
        color: #000;
        text-align: left
    }
</style>

<h1 class="heading">Recent Projects</h1>
<div id="carousel">
    <div id="pnl-1" class="slide">
        <div id="img-1" class="image"><img src="../assets/sport/braids.jpg"/></div>
        <div id="txt-1" class="text"> > player movement patterns <br/> > algebraic braids </div>
    </div>
    <div id="pnl-2" class="slide">
        <div id="img-2" class="image"><img src="../assets/sport/net.jpg"/></div>
        <div id="txt-2" class="text"> > passing behaviour <br/> > hypernetworks </div>
    </div>
    <div id="pnl-3" class="slide">
        <div id="img-3" class="image"><img src="../assets/sport/waves.jpg"/></div>
        <div id="txt-3" class="text"> > team movement dynamics <br/> > flow fields </div>
    </div>
</div>
<div id="introfade">
</div>