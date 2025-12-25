---
title: 摄影师小鼠
description: 2025-10
date: 2025-10-09
slug: test-chinese
image: beautiful.jpg
#categories:
 #   - Test
  #  - 测试
---
## 图片

<style>
.image-grid {
  display: grid;
  grid-template-columns: 1fr 2fr 1fr;
  gap: 15px;
  margin-bottom: 15px;
}
/* 两侧图比例更“高” */
.image-grid img:first-child,
.image-grid img:last-child {
  aspect-ratio: 3 / 4; /* 宽 : 高 = 3:1 → 看起来更扁长 */
}

/* 中间图保持原比例 */
.image-grid img:nth-child(2){
  aspect-ratio: 3 / 2;
}
</style>

![Photo by 摄影师小鼠,<br>at BNU](confusion.jpg) ![Photo by Luca Bravo on Unsplash](beautiful.jpg) 

<div style="display: grid; grid-template-columns: 1fr 2fr 1fr; gap: 15px;margin-bottom: 15px;">
  <img src="beautiful.jpg" alt="图1" style="width: 100%; height: 150px; object-fit: cover;">
  <img src="beautiful.jpg" alt="图2" style="width: 100%; height: 150px; object-fit: cover;"> <!-- 高度减半 -->
  <img src="beautiful.jpg" alt="图3" style="width: 100%; height: 150px; object-fit: cover;">
  <img src="beautiful.jpg" alt="图4" style="width: 100%; height: 150px; object-fit: cover;">
  <img src="beautiful.jpg" alt="图5" style="width: 100%; height: 150px; object-fit: cover;"> <!-- 高度减半 -->
  <img src="beautiful.jpg" alt="图6" style="width: 100%; height: 150px; object-fit: cover;">
</div>

<div class ="image-grid">
  <img src="autumn.jpg" alt="图1" style="width: 100%; height: auto; object-fit: cover; border-radius: 10px;">
  <img src="beautiful.jpg" alt="图2" style="width: 100%; height: auto; object-fit: cover; border-radius: 10px;">
  <img src="autumn.jpg" alt="图3" style="width: 100%; height: auto; object-fit: cover; border-radius: 10px;">
</div>

<div style="display: grid; grid-template-columns: 1fr 1fr; gap: 15px;margin-bottom: 15px;">
   <img src="autumn.jpg" alt="图4" style="width: 100%; height: auto; object-fit: cover;">
  <img src="autumn.jpg" alt="图5" style="width: 100%; height: auto; object-fit: cover;"> <!-- 高度减半 -->
</div>