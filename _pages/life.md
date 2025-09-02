---
layout: archive
title: "Life"
permalink: /life/
author_profile: true
---

## Personal Philosophy


## Hobbies and Interests



## Life Experiences

### Cultural Background
Growing up in China and now studying in the United States has given me a unique perspective on different cultures, educational systems, and ways of thinking. This cross-cultural experience has enriched my understanding of the world and helped me become more adaptable and open-minded.

## Travel and Exploration

### Fun Facts About Where I’ve Lived
- **Qingdao, China** 🌊: My hometown by the sea — amazing seafood, cool summers, and unforgettable memories.  
- **Chengdu, China** 🌶️: Best food in the world! I fell in love with hotpot while studying at Sichuan University.  
- **Atlanta, United States** 🌳: My current city — often called a “forest city” for its trees. Discovered incredible Korean food in Duluth!  

### Countries I've Traveled To
- **United Kingdom** ☔: A rainy country, but I had the best weather during my visit — lucky me! Thanks, UK!  
- **Singapore** 🔥: Hot hot! And I even won 25 bucks in the casino — unforgettable trip!  

<!-- Photo Wall (Masonry + CSS Lightbox) -->
<style>
  /* Masonry layout using CSS columns */
  .masonry {
    column-count: 3;        /* 桌面端三列；可以按需改成 4 */
    column-gap: 12px;
  }
  @media (max-width: 1024px) { .masonry { column-count: 2; } }
  @media (max-width: 640px)  { .masonry { column-count: 1; } }

  .masonry a {
    display: inline-block;  /* 让图片在列中正确换行 */
    width: 100%;
    margin: 0 0 12px;
    break-inside: avoid;    /* 关键：避免图片在列中被拆分，减少空隙 */
  }

  .masonry img {
    width: 100%;
    height: auto;           /* 根据原图比例自适应；高宽不同形成“大/小”错落感 */
    border-radius: 8px;
    box-shadow: 0 2px 12px rgba(0,0,0,0.12);
    vertical-align: middle;
  }

  /* 纯 CSS Lightbox（:target 技术） */
  .lightbox {
    position: fixed;
    inset: 0;
    background: rgba(0,0,0,0.85);
    display: none;
    align-items: center;
    justify-content: center;
    z-index: 9999;
    padding: 2vw;
  }
  .lightbox:target { display: flex; }
  .lightbox img {
    max-width: 96vw;
    max-height: 92vh;
    border-radius: 10px;
    box-shadow: 0 4px 24px rgba(0,0,0,0.4);
  }
  .lightbox:target::after {
    content: "✕";
    position: fixed;
    top: 12px;
    right: 16px;
    font-size: 24px;
    color: #fff;
  }
  /* 点击任何暗背景或图片外区域即可关闭（锚点回到 #） */
  .lightbox, .lightbox img { cursor: zoom-out; }
</style>

<div class="masonry">
  <!-- 缩略图（点击 → 放大） -->
  <a href="#img-uk1"><img src="/images/UK1.jpg" alt="UK Travel 1"></a>
  <a href="#img-uk2"><img src="/images/UK2.jpg" alt="UK Travel 2"></a>
  <a href="#img-sg1"><img src="/images/SG1.jpg" alt="Singapore Travel 1"></a>
  <a href="#img-sg2"><img src="/images/SG2.jpg" alt="Singapore Travel 2"></a>

  <!-- 如需更多图片，按下方格式继续添加（顺序随意，越多越像“照片墙”）
  <a href="#img-qingdao1"><img src="/images/QD1.jpg" alt="Qingdao"></a>
  <a href="#img-chengdu1"><img src="/images/CD1.jpg" alt="Chengdu"></a>
  <a href="#img-atl1"><img src="/images/ATL1.jpg" alt="Atlanta"></a>
  -->
</div>

<!-- Lightbox 大图（与上面 href 的 id 对应）。点击任意处返回页面（#）。 -->
<a href="#" class="lightbox" id="img-uk1"><img src="/images/UK1.jpg" alt="UK Travel 1 Large"></a>
<a href="#" class="lightbox" id="img-uk2"><img src="/images/UK2.jpg" alt="UK Travel 2 Large"></a>
<a href="#" class="lightbox" id="img-sg1"><img src="/images/SG1.jpg" alt="Singapore Travel 1 Large"></a>
<a href="#" class="lightbox" id="img-sg2"><img src="/images/SG2.jpg" alt="Singapore Travel 2 Large"></a>




## Personal Motto

*"It’s a long, long journey until I find where I am meant to be."*

---

*This page reflects my personal thoughts and experiences. I believe that sharing our journeys helps us connect with others and build a more understanding community.*  

