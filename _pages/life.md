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
  /* ---- Hobby pills (warm, low-saturation) ---- */
  .hobbies{ display:flex; flex-wrap:wrap; gap:9px; margin:.5em 0 1.2em; }
  .hobby{
    padding:6px 14px; border-radius:980px; font-size:.95em; font-weight:500;
    color:#7c4e2f; background:#f7f2ec; border:1px solid #ebe3d8;
    transition:background .2s ease;
  }
  .hobby:hover{ background:#f0e8de; }

  /* ---- Masonry photo wall (natural ratios, modest size) ---- */
  .masonry { column-count: 4; column-gap: 12px; }
  @media (max-width: 1024px) { .masonry { column-count: 3; } }
  @media (max-width: 760px)  { .masonry { column-count: 2; } }
  @media (max-width: 480px)  { .masonry { column-count: 1; } }

  .masonry img,
  .masonry .continue-card {
    width: 100%;
    display: inline-block;
    margin: 0 0 12px;
    border-radius: 12px;
    break-inside: avoid;
  }
  .masonry img {
    height: auto;
    border: 1px solid #ebe3d8;
    transition: transform 0.35s cubic-bezier(.4,0,.2,1);
  }
  .masonry img:hover { transform: scale(1.015); }

  .continue-card {
    background: #f7f2ec;
    color: #847668; font-size: .98em; font-style: italic;
    text-align: center; padding: 44px 16px;
    display: flex; align-items: center; justify-content: center;
    border: 1px solid #ebe3d8;
  }

  /* ---- Luka gallery ---- */
  .luka-intro{
    display:flex; gap:14px; align-items:flex-start;
    padding:16px 20px; margin:12px 0 20px;
    border-radius:16px;
    background:#f7f2ec; border:1px solid #ebe3d8;
    line-height:1.6; color:#3a332c;
  }
  .luka-intro .paw{ font-size:1.7em; line-height:1; }
  .luka-intro b{ font-weight:600; }
  .luka-intro .bday{ color:#847668; font-size:.93em; margin-top:4px; }
  .luka-intro a{ color:#96613d; }

  .luka-wall{ column-count:4; column-gap:12px; }
  @media (max-width:1024px){ .luka-wall{ column-count:3; } }
  @media (max-width:760px){ .luka-wall{ column-count:2; } }
  @media (max-width:480px){ .luka-wall{ column-count:1; } }

  .luka-wall figure{
    margin:0 0 12px; break-inside:avoid; display:inline-block; width:100%;
  }
  .luka-wall img{
    width:100%; height:auto; display:block;
    border-radius:12px; border:1px solid #ebe3d8;
    transition:transform .35s cubic-bezier(.4,0,.2,1);
  }
  .luka-wall figure:hover img{ transform:scale(1.015); }
  .luka-wall figcaption{
    margin-top:6px; font-size:.86em; color:#847668; font-weight:500;
    padding-left:2px;
  }
</style>

## Hello, World!

<div class="masonry">
  <img loading="lazy" decoding="async" src="/images/UK1.jpg" alt="UK Travel 1">
  <img loading="lazy" decoding="async" src="/images/UK2.jpg" alt="UK Travel 2">
  <img loading="lazy" decoding="async" src="/images/SG1.jpg" alt="Singapore Travel 1">
  <img loading="lazy" decoding="async" src="/images/SG2.jpg" alt="Singapore Travel 2">
  <img loading="lazy" decoding="async" src="/images/1.jpg" alt="1">
  <img loading="lazy" decoding="async" src="/images/2.jpg" alt="2">
  <img loading="lazy" decoding="async" src="/images/3.jpg" alt="3">
  <img loading="lazy" decoding="async" src="/images/4.jpg" alt="4">
  <img loading="lazy" decoding="async" src="/images/5.jpg" alt="5">
  <img loading="lazy" decoding="async" src="/images/cali1.jpg" alt="California">
  <img loading="lazy" decoding="async" src="/images/olando1.jpg" alt="Orlando">
  <img loading="lazy" decoding="async" src="/images/HWI1.jpg" alt="Hawaii 1">
  <img loading="lazy" decoding="async" src="/images/HWI2.jpg" alt="Hawaii 2">

  <div class="continue-card">…to be continued</div>
</div>

## 🐶 Meet Luka

<div class="luka-intro">
  <span class="paw">🐾</span>
  <div>
    This is <b>Luka</b>, my golden retriever and my favorite research break. 🥰 Here he is growing up, month by month.
    <div class="bday">🎂 Born March 20, 2026 &nbsp;·&nbsp; Based in Atlanta — if you have a pup too, let's set up a <b>playdate with Luka</b>! 🐕</div>
  </div>
</div>

<div class="luka-wall">
  <figure><img loading="lazy" decoding="async" src="/images/Luka/2m.jpg" alt="Luka at 2 months"><figcaption>2 months</figcaption></figure>
  <figure><img loading="lazy" decoding="async" src="/images/Luka/3m.jpg" alt="Luka at 3 months"><figcaption>3 months</figcaption></figure>
  <figure><img loading="lazy" decoding="async" src="/images/Luka/4month.jpg" alt="Luka at 4 months"><figcaption>4 months</figcaption></figure>
  <figure><img loading="lazy" decoding="async" src="/images/Luka/5m.jpg" alt="Luka at 5 months"><figcaption>5 months</figcaption></figure>
  <figure><img loading="lazy" decoding="async" src="/images/Luka/6m.jpg" alt="Luka at 6 months"><figcaption>6 months</figcaption></figure>
</div>
