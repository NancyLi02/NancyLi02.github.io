---
layout: archive
title: "Life"
permalink: /life/
author_profile: true
---

## Hobbies

<p class="hobbies">
  <span class="hobby">🥾 Hiking</span>
  <span class="hobby">🌍 Travel</span>
  <span class="hobby">📷 Photography</span>
  <span class="hobby">🐶 Puppy Parent</span>
</p>

<style>
  /* ---- Hobby pills ---- */
  .hobbies{ display:flex; flex-wrap:wrap; gap:10px; margin:.6em 0 1.4em; }
  .hobby{
    padding:8px 16px; border-radius:999px; font-size:1.02em; font-weight:600;
    color:#fff; background:linear-gradient(120deg,#6366f1,#7c3aed 55%,#c026d3);
    box-shadow:0 10px 24px -12px rgba(124,58,237,.7);
    transition:transform .25s cubic-bezier(.22,.61,.36,1);
  }
  .hobby:hover{ transform:translateY(-3px) scale(1.03); }

  /* ---- Masonry photo wall ---- */
  .masonry { column-count: 4; column-gap: 14px; }
  @media (max-width: 1024px) { .masonry { column-count: 2; } }
  @media (max-width: 640px)  { .masonry { column-count: 1; } }

  .masonry img,
  .masonry .continue-card {
    width: 100%;
    display: inline-block;
    margin: 0 0 14px;
    border-radius: 14px;
    box-shadow: 0 8px 26px -12px rgba(38,26,84,.4);
    break-inside: avoid;
  }
  .masonry img {
    height: auto;
    transition: transform 0.4s cubic-bezier(.22,.61,.36,1), box-shadow .4s ease;
  }
  .masonry img:hover {
    transform: scale(1.04);
    box-shadow: 0 22px 46px -16px rgba(66,44,140,.5);
    z-index: 1;
  }
  .continue-card {
    background: linear-gradient(135deg,#6366f1,#c026d3);
    color: #fff; font-size: 1.15em; font-style: italic; font-weight:600;
    text-align: center; padding: 56px 20px;
    display: flex; align-items: center; justify-content: center;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .continue-card:hover { transform: scale(1.03); box-shadow: 0 18px 40px -16px rgba(124,58,237,.6); }

  /* ---- Luka growth gallery ---- */
  .luka-intro{
    display:flex; gap:14px; align-items:center;
    padding:16px 20px; margin:14px 0 22px;
    border-radius:16px;
    background:linear-gradient(120deg,rgba(99,102,241,.10),rgba(192,38,211,.10));
    border:1px solid rgba(124,58,237,.18);
    line-height:1.6;
  }
  .luka-intro .paw{ font-size:2em; line-height:1; }

  .luka-grid{
    display:grid; grid-template-columns:repeat(auto-fill,minmax(190px,1fr));
    gap:16px; margin-top:8px;
  }
  .luka-card{
    position:relative; border-radius:16px; overflow:hidden;
    box-shadow:0 10px 28px -14px rgba(38,26,84,.45);
    aspect-ratio: 3/4;
    transition:transform .4s cubic-bezier(.22,.61,.36,1), box-shadow .4s ease;
  }
  .luka-card img{
    width:100%; height:100%; object-fit:cover; display:block;
    transition:transform .5s cubic-bezier(.22,.61,.36,1);
  }
  .luka-card:hover{ transform:translateY(-6px); box-shadow:0 26px 54px -18px rgba(66,44,140,.55); }
  .luka-card:hover img{ transform:scale(1.08); }
  .luka-card .cap{
    position:absolute; left:0; right:0; bottom:0;
    padding:26px 14px 12px;
    background:linear-gradient(to top,rgba(20,10,45,.82),transparent);
    color:#fff; font-weight:700; font-family:'Space Grotesk',sans-serif;
    letter-spacing:.02em;
  }
  .luka-card .cap small{ display:block; font-weight:500; opacity:.85; font-size:.8em; }
</style>

## 🐶 Meet Luka

<div class="luka-intro">
  <span class="paw">🐾</span>
  <div>This is <b>Luka</b>, my little golden retriever and my favorite research break. 🥰 Here's a look at him growing up, month by month.</div>
</div>

<div class="luka-grid">
  <div class="luka-card"><img loading="lazy" decoding="async" src="/images/Luka/2m.jpg" alt="Luka at 2 months"><div class="cap">2 Months<small>tiny & fluffy</small></div></div>
  <div class="luka-card"><img loading="lazy" decoding="async" src="/images/Luka/3m.jpg" alt="Luka at 3 months"><div class="cap">3 Months<small>curious explorer</small></div></div>
  <div class="luka-card"><img loading="lazy" decoding="async" src="/images/Luka/4month.jpg" alt="Luka at 4 months"><div class="cap">4 Months<small>growing fast</small></div></div>
  <div class="luka-card"><img loading="lazy" decoding="async" src="/images/Luka/5m.jpg" alt="Luka at 5 months"><div class="cap">5 Months<small>full of energy</small></div></div>
  <div class="luka-card"><img loading="lazy" decoding="async" src="/images/Luka/6m.jpg" alt="Luka at 6 months"><div class="cap">6 Months<small>handsome boy</small></div></div>
</div>

## Hello, World!

<div class="masonry">
  <img loading="lazy" decoding="async" src="/images/HWI1.jpg" alt="Hawaii 1">
  <img loading="lazy" decoding="async" src="/images/HWI2.jpg" alt="Hawaii 2">
  <img loading="lazy" decoding="async" src="/images/cali1.jpg" alt="California">
  <img loading="lazy" decoding="async" src="/images/olando1.jpg" alt="Orlando">
  <img loading="lazy" decoding="async" src="/images/UK1.jpg" alt="UK Travel 1">
  <img loading="lazy" decoding="async" src="/images/UK2.jpg" alt="UK Travel 2">
  <img loading="lazy" decoding="async" src="/images/SG1.jpg" alt="Singapore Travel 1">
  <img loading="lazy" decoding="async" src="/images/SG2.jpg" alt="Singapore Travel 2">
  <img loading="lazy" decoding="async" src="/images/1.jpg" alt="1">
  <img loading="lazy" decoding="async" src="/images/2.jpg" alt="2">
  <img loading="lazy" decoding="async" src="/images/3.jpg" alt="3">
  <img loading="lazy" decoding="async" src="/images/4.jpg" alt="4">
  <img loading="lazy" decoding="async" src="/images/5.jpg" alt="5">

  <!-- To be continued 卡片 -->
  <div class="continue-card">…to be continued</div>
</div>
