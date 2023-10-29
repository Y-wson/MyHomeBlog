---
home: true
modules:
  - BannerBrand
  - Blog
  - MdContent
  - Footer
bannerBrand:
  bgImage: "/bg.svg"
  title: 小森林物语
  description: 感受森林惬意时光，拥抱🤗知识的清新空气
  tagline: 银烛秋光冷画屏，轻罗小扇扑流萤
  buttons:
    - { text: Guide, link: "/docs/guide/introduce" }
    - {
        text: Default Style,
        link: "/docs/style-default-api/introduce",
        type: "plain",
      }
  socialLinks:
    - {
        icon: "LogoGithub",
        link: "https://github.com/vuepress-reco/vuepress-theme-reco",
      }
blog:
  socialLinks:
    - { icon: "LogoGithub", link: "https://github.com/recoluan" }
isShowTitleInHome: true
actionText: About
actionLink: /views/other/about
---

## 快速开始

**npx**

```bash
# 初始化，并选择 2.x
npx @vuepress-reco/theme-cli init
```

**npm**

```bash
# 初始化，并选择 2.x
npm install @vuepress-reco/theme-cli@1.0.7 -g
theme-cli init
```

**yarn**

```bash
# 初始化，并选择 2.x
yarn global add @vuepress-reco/theme-cli@1.0.7
theme-cli init
```
