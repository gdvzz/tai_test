---
title: TBAI
layout: home
# nav_order: 0
nav_exclude: true
---


<!-- 嵌入 Pagefind 搜索组件 -->
<div id="search"></div>
<script src="/pagefind/pagefind-ui.js"></script>
<script>
  window.addEventListener('DOMContentLoaded', () => {
    new PagefindUI({
      element: "#search",
      basePath: "/", // 若站点有 baseurl，需对应调整（如 /just-the-docs-template/）
      // 中文搜索优化配置
      searchLabel: "搜索文档...",
      placeholder: "输入中文关键词搜索",
      emptySearchResults: "未找到匹配结果",
      filters: {
        lang: {
          label: "语言",
          options: [
            { value: "zh", label: "中文" },
            { value: "en", label: "英文" }
          ]
        }
      }
    });
  });
</script>

# TBAI
{: .no_toc }
`更新-260421` \| `发布-260420`


存放信息。

网站文件移动到 /docs 目录下。

基本可用。123

仓库改名为 jtdsh