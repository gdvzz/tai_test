---
title: TBAI
layout: home
nav_exclude: true
---

<!-- Pagefind 搜索框 -->
<style>
  /* 让搜索框宽一点、好看一点 */
  #search {
    margin: 20px 0;
    max-width: 800px;
  }
</style>
<div id="search"></div>

<!-- 正确加载 Pagefind（自动识别路径，永不报错） -->
<script>
  // 自动获取站点根路径，兼容 GitHub Pages
  const base = document.querySelector('base')?.href || '/';
  const script = document.createElement('script');
  script.src = base + 'pagefind/pagefind-ui.js';
  script.onload = function() {
    new PagefindUI({
      element: "#search",
      baseUrl: base,
      showImages: false,
      showEmptyFilters: false,
      // 中文界面
      translations: {
        search: "搜索文档...",
        placeholder: "输入中文关键词搜索",
        noResults: "未找到匹配结果",
        loading: "加载中..."
      }
    });
  };
  document.head.appendChild(script);
</script>

# TBAI
{: .no_toc }
`更新-260421` \| `发布-260420`

存放信息。

网站文件移动到 /docs 目录下。

基本可用。123

仓库改名为 jtdsh

测试-260428
测试-260428-2

