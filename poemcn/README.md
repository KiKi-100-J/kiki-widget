# 每日诗词插件用法

## 1、效果预览

[![Live Demo](https://img.shields.io/badge/KiKiDemo-点击查看-lightseagreen?style=for-the-badge&logo=vercel)](https://kiki-100-j.github.io/kiki-widget/poemcn/opemcn.html)


## 2、快速上手

> **参数均是可选，不传参则调用默认值**

### 2.1、随机诗句

#### 🎁 致谢 [今日诗词](https://www.jinrishici.com/) 开放 API

```
https://kiki-100-j.github.io/kiki-widget/poemcn/opemcn.html
```

| 参数    | 含义         | 备注                                              |
| :------ | :----------- | :------------------------------------------------ |
| theme   | 诗歌主题     | 参考 https://open.saintic.com/sentence.html       |
| catalog | 诗歌子分类   | 同上，使用拼音（比如子分类夏天，传入 xiatian）    |
| author  | 是否显示作者 | true（默认）/ false                               |
| name    | 是否显示诗名 | true（默认）/ false                               |
| color   | 字体颜色     | 英文字符串 或者 16 进制（其中 # 号使用 %23 代替） |
| size    | 字体大小     | 传入数字即可（对应单位 px）                       |
