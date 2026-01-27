---
title: "🌈故事标本馆"
---

<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');
  body {
    background-color: #0f0f23;
    background-image: 
      radial-gradient(ellipse at 20% 20%, rgba(32, 82, 149, 0.2) 0%, transparent 40%),
      radial-gradient(ellipse at 80% 80%, rgba(72, 187, 255, 0.15) 0%, transparent 40%);
    font-family: 'Inter', sans-serif;
    color: #a0c8ff;
    max-width: 700px;
    margin: 5rem auto;
    padding: 2rem;
    line-height: 1.8;
    position: relative;
    overflow-x: hidden;
  }
  /* 星光效果 */
  body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: 
      radial-gradient(1px 1px at 20% 30%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 40% 70%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 60% 20%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 80% 50%, #fff 1px, transparent 0);
    background-size: 200px 200px;
    opacity: 0.3;
    z-index: -1;
  }
  .story-item {
    border-bottom: 1px solid rgba(160, 200, 255, 0.2);
    padding: 1.8rem 0;
    transition: all 0.3s ease;
  }
  .story-item:hover {
    padding-left: 1.5rem;
    border-bottom-color: #48bbff;
    background: rgba(72, 187, 255, 0.05);
    border-radius: 4px;
  }
  .story-title {
    font-size: 1.7rem;
    font-weight: 600;
    margin-bottom: 0.4rem;
    color: #c3dafe;
  }
  .story-title:hover {
    color: #48bbff;
  }
  .story-list {
    list-style: none;
    padding-left: 0;
    margin-top: 3rem;
  }
  .story-sub {
    font-size: 0.95rem;
    color: #8892b0;
    font-style: italic;
    letter-spacing: 0.5px;
  }
  .header {
    text-align: center;
    margin-bottom: 4rem;
    border-bottom: 2px solid rgba(72, 187, 255, 0.3);
    padding-bottom: 2rem;
  }
  .site-title {
    font-size: 3rem;
    margin-bottom: 0.5rem;
    letter-spacing: 3px;
    color: #ccd6f6;
  }
  .site-subtitle {
    color: #8892b0;
    font-size: 1.1rem;
  }
</style>

<div class="header">
  <h1 class="site-title">故事标本馆</h1>
  <p class="site-subtitle">每一则标题，都是一个待开启的世界</p>
</div>

<ul class="story-list">
  <li class="story-item">
    <a href="你的故事链接1" class="story-title">一个房间</a>
    <div class="story-sub">#现代寓言 · 阅读约需 4 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接2" class="story-title">她的早餐</a>
    <div class="story-sub">#悬疑 · 阅读约需 7 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接3" class="story-title">她的双亲</a>
    <div class="story-sub">#黑色幽默 · 阅读约需 5 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接4" class="story-title">五彩斑斓的黑天鹅</a>
    <div class="story-sub">#科幻浪漫 · 阅读约需 10 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接5" class="story-title">解脱的瞬间</a>
    <div class="story-sub">#硬核科幻 · 阅读约需 15 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接5" class="story-title">她的偶遇</a>
    <div class="story-sub">#硬核科幻 · 阅读约需 15 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接5" class="story-title">一个动词</a>
    <div class="story-sub">#硬核科幻 · 阅读约需 15 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接5" class="story-title">她离开之后</a>
    <div class="story-sub">#硬核科幻 · 阅读约需 15 分钟</div>
  </li>
  <li class="story-item">
    <a href="你的故事链接5" class="story-title">特别</a>
    <div class="story-sub">#硬核科幻 · 阅读约需 15 分钟</div>
  </li>
</ul>
---