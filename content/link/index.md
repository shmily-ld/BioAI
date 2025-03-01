---
title: Links
date: 2025-03-01
type: page
---

## PyMOL 使用教程

[点击这里查看 PyMOL 使用教程](https://github.com/shmily-ld/PyMOL)

<div id="click-count">
  点击量: <span id="click-count-span">0</span>
</div>

<script>
  // 获取点击计数显示区域
  const clickCountSpan = document.getElementById('click-count-span');
  
  // 从本地存储获取当前点击量，如果没有则初始化为0
  let clickCount = localStorage.getItem('clickCount') ? parseInt(localStorage.getItem('clickCount')) : 0;
  
  // 更新显示的点击量
  clickCountSpan.textContent = clickCount;

  // 监听链接点击事件
  document.querySelector('a[href="https://github.com/shmily-ld/PyMOL"]').addEventListener('click', function() {
    // 增加点击量
    clickCount++;
    // 更新本地存储
    localStorage.setItem('clickCount', clickCount);
    // 更新页面显示
    clickCountSpan.textContent = clickCount;
  });
</script>
