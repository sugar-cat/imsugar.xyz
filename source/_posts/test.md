---
title: 测试数据
date: 2019-11-02 20:52:00
categories: code
tags: [数据集,方案,学习]
urlname: ripping-artstation-models
---

# 测试页面
`git clone https://github.com/journey-ad/hexo-theme-typography themes/hexo-theme-typography`

``` html
body::before {
    content: "";
    top: 0;
    left: 0;
    right: 0;
    bottom: 0;
    opacity: .03;
    position: fixed;
    background: center/cover no-repeat;
    background-image: url(/images/bg_1.jpg);
}
```
## 清除主题缓存
` git rm -rf --cached themes/hexo-theme-typography`
## 重新添加到仓库
` git add themes/hexo-theme-typography/*`