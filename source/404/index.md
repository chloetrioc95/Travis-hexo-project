---
title: 404
date: 2021-03-30 22:15:02
comments: false
permalink: /404.html
---

<!-- markdownlint-disable MD039 MD033 -->

## 這是一個不存在的頁面

很抱歉，你目前存取的頁面並不存在。

預計將在約 <span id="timeout">5</span> 秒後返回首頁。

如果你很急著想看文章，你可以 **[點這裡](https://chloetrioc95.github.io/)** 返回首頁。

<script>
let countTime = 5;

function count() {
  
  document.getElementById('timeout').textContent = countTime;
  countTime -= 1;
  if(countTime === 0){
    location.href = 'https://chloetrioc95.github.io/'; 
  }
  setTimeout(() => {
    count();
  }, 1000);
}

count();
</script>