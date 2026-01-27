---
title: "🌈故事标本馆"
---
<style>
  @import url('https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600&display=swap');
  
  body {
    /* 调亮背景：从 #0f0f23 改为 #1a1a2e，并减少渐变深度 */
    background-color: #1a1a2e;
    background-image: 
      radial-gradient(ellipse at 20% 20%, rgba(56, 123, 214, 0.15) 0%, transparent 40%),
      radial-gradient(ellipse at 80% 80%, rgba(72, 187, 255, 0.1) 0%, transparent 40%);
    font-family: 'Inter', sans-serif;
    color: #c3d7f2; /* 调亮文字颜色 */
    max-width: 700px;
    margin: 5rem auto;
    padding: 2rem;
    line-height: 1.8;
    position: relative;
    overflow-x: hidden;
    min-height: 100vh;
  }
  
  /* ========== 真正的闪烁星星效果 ========== */
  body::before {
    content: '';
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    /* 创建更多星星点 */
    background-image: 
      radial-gradient(1.5px 1.5px at 10% 20%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 20% 35%, #fff 1px, transparent 0),
      radial-gradient(1.5px 1.5px at 30% 80%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 40% 60%, #fff 1px, transparent 0),
      radial-gradient(2px 2px at 50% 30%, #fff 1.5px, transparent 0),
      radial-gradient(1px 1px at 60% 70%, #fff 1px, transparent 0),
      radial-gradient(1.5px 1.5px at 70% 40%, #fff 1px, transparent 0),
      radial-gradient(1px 1px at 80% 90%, #fff 1px, transparent 0),
      radial-gradient(2px 2px at 90% 15%, #fff 1.5px, transparent 0),
      radial-gradient(1px 1px at 95% 55%, #fff 1px, transparent 0);
    background-size: 300px 300px;
    opacity: 0.4;
    z-index: -1;
    /* 关键：添加闪烁动画 */
    animation: twinkle 8s ease-in-out infinite alternate;
  }
  
  /* 闪烁动画定义 */
  @keyframes twinkle {
    0%, 100% { opacity: 0.3; }
    50% { opacity: 0.7; }
  }
  /* ========== 星星效果结束 ========== */
  
  /* 调亮分隔线颜色 */
  .story-item {
    border-bottom: 1px solid rgba(160, 200, 255, 0.35); /* 增加不透明度 */
    padding: 1.8rem 0;
    transition: all 0.3s ease;
  }
  
  /* 悬停效果增强 */
  .story-item:hover {
    padding-left: 1.5rem;
    border-bottom-color: #64d9fe; /* 更亮的青色 */
    background: rgba(100, 217, 254, 0.08); /* 更明显的悬停背景 */
    border-radius: 6px;
  }
  
  .story-title {
    font-size: 1.7rem;
    font-weight: 600;
    margin-bottom: 0.4rem;
    color: #d8e6ff; /* 调亮标题颜色 */
  }
  
  .story-title:hover {
    color: #64d9fe;
    text-shadow: 0 0 10px rgba(100, 217, 254, 0.3); /* 添加微光效果 */
  }
  
  .story-list {
    list-style: none;
    padding-left: 0;
    margin-top: 3rem;
  }
  
  .story-sub {
    font-size: 0.95rem;
    color: #94a9cc; /* 调亮副标题颜色 */
    font-style: italic;
    letter-spacing: 0.5px;
  }
  
  .header {
    text-align: center;
    margin-bottom: 4rem;
    border-bottom: 2px solid rgba(100, 217, 254, 0.4); /* 更亮的边框 */
    padding-bottom: 2rem;
  }
  
  .site-title {
    font-size: 3rem;
    margin-bottom: 0.5rem;
    letter-spacing: 3px;
    color: #e1ebff; /* 调亮主标题 */
    text-shadow: 0 0 15px rgba(100, 217, 254, 0.2);
  }
  
  .site-subtitle {
    color: #94a9cc;
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