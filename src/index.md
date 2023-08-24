---
# 语言 （可选）
lang: zh-cn
# 网页关键词和描述
keywords: Hexo主题,个人简历
description: 这是一个通过 Hexo Resume 主题制成的简历
# 简历标题
resume_title: 简历
# 应聘者姓名
name: 王守帅
avatar: https://blog.shoushuai.top/logo.png
# 联系方式
contact:
  - icon: fas fa-globe-asia
    text: https://docs.shoushuai.top
    url: https://docs.shoushuai.top
  # 邮箱
  - icon: fas fa-envelope
    text: wssgryx@163.com
    url:
  # 电话号码
  - icon: fab fa-github
    text: wss-git
    url: https://github.com/wss-git
## PDF下载链接
# download:
#   title: 下载简历
#   icon: fas fa-download fa-fw
#   url: https://github.com/xaoxuu/resume-docs
---



## <i class="fas fa-flag"></i> 掌握技能

- 熟悉 JS，熟悉面向对象、闭包、作用域链，熟悉 ES6、异步编程、Promise
- 熟悉 React 框架， MVVM 模式，例如数据绑定原理、生命周期，熟悉组件化开发 
- 熟悉通过 Nodejs 搭建 Web 服务器，express、koa 等
- 数据库: 使用阿里云 OTS 、简单使用 prisma
- 能看简单 java 和 python 代码
- 熟悉 Serverless 技术


## <i class="fas fa-user-tie"></i> 工作经验


#### 2022.01 - 至今





## <i class="fas fa-award"></i> 精选项目


{% raw %}
<btns rounded>
<a href='https://apps.apple.com/cn/app/heart-mate-pro-hrm-utility/id1463348922?ls=1'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/heartmate/icon.png'>
  心率管家
</a>
<a href='https://apps.apple.com/cn/app/c%E5%85%BB%E8%80%81/id1458315594'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-cyanglao/icon.png'>
  C养老
</a>
<a href='https://apps.apple.com/cn/app/c-life%E5%85%BB%E8%80%81/id1393937890'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/het-clife/icon.png'>
  C-Life养老
</a>
<a href='https://apps.apple.com/cn/app/linksmart/id1109303355'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-linksmart/icon.png'>
  LinkSmart
</a>
<a href='https://apps.apple.com/cn/app/hitfit/id1207738581'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-hitfit/icon.png'>
  HitFit
</a>
<a href='https://apps.apple.com/cn/app/%E8%85%95%E8%83%BD%E5%8A%A9%E6%89%8B/id1138242219'>
  <img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/ht-fiyta/icon.png'>
  飞亚达腕能助手
</a>
</btns><br>
{% endraw %}


### A项目

#### 2000/01 ~ 2019/01：于XX公司开发，团队项目，维护至今

啦啦啦

### B项目

#### 1900/01 ~ 2000/01：于XX公司开发

啦啦啦

### C项目

#### 1800/01 ~ 1900/01：于XX公司开发

啦啦啦

## <i class="fab fa-github"></i> 开源贡献


### Volantis

#### 2017 ~ 至今，一个简约的卡片式Hexo博客主题

- 完全自由的模块化、易于定制化设计
- 移动端优化
- 源码：https://github.com/xaoxuu/hexo-theme-volantis
- 官网：https://volantis.js.org/

### ProHUD

#### 2019/08 ~ 至今，易于定制、接口简单的HUD库

- 使用Swift5编写。
- 包含顶部通知横幅、弹窗、底部操作表三种使用场景的UI控件。
- 易于配置UI从而满足公司各业务线的UI要求，接口调用简单明了。
- 源码：https://github.com/xaoxuu/ProHUD

<fancybox>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot01.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot02.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot03.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot04.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot05.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot06.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot07.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot08.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot09.png'>
<img src='https://cdn.jsdelivr.net/gh/xaoxuu/cdn-assets/proj/prohud/screenshot10.png'>
</fancybox>

## <i class="fas fa-phone-alt"></i> 与我联系

目前状态为：在职，考虑换工作，100年内可到岗。

<i class="fas fa-envelope fa-fw"></i> your email
<i class="fas fa-phone-alt fa-fw"></i> 1xxxxxxxxxx


## 主题配置

```yaml
cdn:
  # These base libraries cannot be deleted
  jquery: https://cdn.jsdelivr.net/npm/jquery@3.4.1/dist/jquery.min.js
  vue: https://cdn.jsdelivr.net/npm/vue@2.5.21/dist/vue.min.js
  # When these CDN resources are deleted, local resources are loaded.
  common: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/common.js
  escape: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/css.escape.js
  smooth_scroll: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/js/smooth-scroll.min.js
  css: https://cdn.jsdelivr.net/gh/xaoxuu/hexo-theme-resume@1.0.0/source/css/style.min.css
  # Optional plug-in: image zoom
  fancybox:
    css: https://cdn.jsdelivr.net/npm/@fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.css
    js: https://cdn.jsdelivr.net/gh/fancyapps/fancybox@3.5.7/dist/jquery.fancybox.min.js

# robots meta tag
robots: noindex,nofollow

# the footer of your site
copyright: '[Copyright © 2017-2020 Mr. X](https://xaoxuu.com)'
```


## <i class="fas fa-user-graduate"></i> 教育背景

烟台职业学院 软件工程 2017年毕业

## 评论

{% raw %}
<script src="https://utteranc.es/client.js"
        repo="xaoxuu/hexo-theme-resume"
        issue-number="18"
        theme="github-light"
        crossorigin="anonymous"
        async>
</script>
{% endraw %}
