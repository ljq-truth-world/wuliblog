---
home: true
heroImage: https://cdn.jsdelivr.net/gh/xugaoyi/image_store/blog/20200409124835.png
heroText: 大学物理简明教程习题解答
tagline: 🚀ISBN:978-7-04-038901-2
actionText: 开始使用 →
actionLink: /pages/1/
bannerBg: none # auto => 网格纹背景(有bodyBgImg时无背景)，默认 | none => 无 | '大图地址' | background: 自定义背景样式       提示：如发现文本颜色不适应你的背景时可以到palette.styl修改$bannerTextColor变量



# 文章列表显示方式: detailed 默认，显示详细版文章列表（包括作者、分类、标签、摘要、分页等）| simple => 显示简约版文章列表（仅标题和日期）| none 不显示文章列表
postList: none
---

## 💚初始愿景

::: note 不是索要而是创造

 ~~此项目开始于2022年，意图在教学实践中，让受众从被动接受者过渡为实践创造者！期望以习题为承载，让未来的软件领域领导者了解~~

~~- 通识内容：物理（物质世界演变的自然语言，普适的面向对象逻辑）~~

~~- 专业技能：知识管理工具，版本管理工具~~

  

👨‍🦽**说人话版**：

物理不能挂，所以还是要学。 学物理的同时顺便学学Markdown、咋写知识笔记、git版本控制啥的，感觉离大厂又近来。

如果你有兴趣，可以Fork这个项目，然后贡献一道题目。在这个过程中，你应该可以能有所收获。

:::

<br/>

## 🛴快速开始


- 注册一个Github账号
- Fork本项目
- 在本地搭建环境：安装Git、nodeJS、yarn
- 在本地配置git环境，包括密钥，自己的远程库等
- 在本地拉取远程库，安装依赖，开始本地dev
```sh
yarn install
yarn dev
```
- 用Markdown编辑一个题目的答案，注意公式应该用latex语法
- 用Git添加(add)和commit后推送到远程
- 在Github页面Pull Request到我这个原始库
- 当我把你的贡献合并到当前库，你就完成了贡献。








<br/>


## 💥文件名约定
这是一个结构化站点，请参考[原始文档](https://doc.xugaoyi.com/pages/33d574/#%E5%91%BD%E5%90%8D%E7%BA%A6%E5%AE%9A)

docs目录下，

- 第一级目录应该为篇，包括：力学、狭义相对论、电磁学和量子力学
  - 在第一级目录中，应为每章建立一个文件夹
     - 在每一章的目录中，应为每一个课后习题建一个md文件，其命名应为[序号.章序号-序号.md]
     - 范例：第2章的2-10题目，命名为 10.2-10.md
     - 内容范例，参考[2-10题目](/pages/d0aa4b/)


## 🎖贡献者
::: tip 创造者
期待在各位的贡献
:::

::: cardList 2

```yaml
- name: 虚位以待
  desc: 每个人都是创造者
  link: 
  bgColor: '#f1f1f1'
  textColor: '#2A3344'
- name: 虚位以待
  desc: 每个人都是创造者
  link: 
  bgColor: '#f1f1f1'
  textColor: '#2A3344'
```
:::

