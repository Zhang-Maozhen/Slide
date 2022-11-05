---
theme: academic
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.
  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS
css: unocss
---

# 文献管理

References Management

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    开始介绍 <carbon:arrow-right class="inline"/>
  </span>
</div>


<div class="abs-br m-6 flex gap-2">
  <button @click="$slidev.nav.openInEditor()" title="Open in Editor" class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon:edit />
  </button>
  <a href="https://zhang-maozhen.github.io/" target="_blank" alt="GitHub"
    class="text-xl icon-btn opacity-50 !border-none !hover:text-white">
    <carbon-logo-github />
  </a>
</div>
<!--
将对文献进行介绍
-->


---

# 文献管理软件

两个免费文献管理软件推荐，实现文献信息同步、文献抓取、阅读标注、翻译和文献标签等基本功能

<div grid="~ cols-2 gap-2" m="-t-2">

Zootero：https://www.zotero.org/

Mendeley：https://www.mendeley.com/

> Zotero 强大而灵活，不太好驾驭
>
> 需要安装各种拓展插件

> Mendeley 基本够用，但不够强大。
>
> 安装即可用

<img src="https://mz-pico-1311932519.cos.ap-nanjing.myqcloud.com/image/image-20221030191637024.png" alt="image-20221030191637024" style="zoom:70%;" />

![image-20221030191444021](https://mz-pico-1311932519.cos.ap-nanjing.myqcloud.com/image/image-20221030191444021.png)

</div>

知乎对于两款软件优劣对比的话题：[如何对比 Zotero 和 Mendeley 两款文献管理的优劣?](http://www-quic.zhihu.com/question/292241691/answer/2204622823)

---

# Zotero
