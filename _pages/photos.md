---
title: "照片"
permalink: /photos/
layout: single
author_profile: true
---

这里用来存放多多的照片。先放几张测试照片，之后可以慢慢补充更多。

<style>
.dodo-gallery {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 22px;
  margin-top: 24px;
}

.dodo-card {
  text-align: center;
}

.dodo-card img {
  width: 100%;
  height: 260px;
  object-fit: cover;
  border-radius: 16px;
  box-shadow: 0 4px 14px rgba(0, 0, 0, 0.10);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
}

.dodo-card img:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.16);
}

.dodo-card p {
  margin-top: 8px;
  font-size: 0.95em;
  color: #555;
}

@media (max-width: 900px) {
  .dodo-gallery {
    grid-template-columns: repeat(2, 1fr);
  }

  .dodo-card img {
    height: 220px;
  }
}

@media (max-width: 600px) {
  .dodo-gallery {
    grid-template-columns: 1fr;
  }

  .dodo-card img {
    height: auto;
  }
}
</style>

## 多多照片墙

<div class="dodo-gallery">

  <div class="dodo-card">
    <img src="/images/dodo/dodo-01.jpg" alt="多多照片 1">
    <p>多多照片 1</p>
  </div>

  <div class="dodo-card">
    <img src="/images/dodo/dodo-02.jpg" alt="多多照片 2">
    <p>多多照片 2</p>
  </div>

  <div class="dodo-card">
    <img src="/images/dodo/dodo-03.jpg" alt="多多照片 3">
    <p>多多照片 3</p>
  </div>

</div>
