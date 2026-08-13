摩域2体育官网客服【Q-——333307——】摩域2体育官网客服【 辋芷《888yx●vip》 】
摩域2体育官网客服【Q-——333307——】摩域2体育官网客服【 辋芷《888yx●vip》 】

 从零搭建个人博客：Github Pages + Hugo 完整教程（2025亲测有效）

你是否想过拥有一个完全免费、无广告、可自定义的博客？Github Pages 搭配 Hugo 静态站点生成器，简直是开发者写技术博客的绝配。今天这篇文章，我将手把手带你走通全流程，小白也能轻松上手。

 为什么选择 Hugo + Github Pages？

- 极速构建：Hugo 号称“世界上最快”的静态站点生成器，几十篇文章秒级出站。
- 零成本发布：Github 提供免费托管，自定义域名也支持。
- 版本管理：所有文章以 Markdown 存储，天然适配 Git 工作流。

 一、前置准备

1. 注册 Github 账号（已注册的伙伴直接跳过）。
2. 安装 Git：Mac 执行 `brew install git`，Windows 直接去官网下安装包。
3. 下载 Hugo：务必注意！你的系统是 Windows 请选 `hugo_extended` 版，Mac 可直接用 `brew install hugo`。

 二、三分钟本地搭站

在终端或命令行执行：

```bash
hugo new site my-blog
cd my-blog
git init
```

这样项目骨架就建好了。接着安装一个你喜欢的主题，比如 `PaperMod`：

```bash
git clone https://github.com/adityatelange/hugo-PaperMod.git themes/PaperMod
echo "theme = 'PaperMod'" >> hugo.toml
```

运行 `hugo server -D`，浏览器打开 `http://localhost:1313`，立刻就能预览博客首页。

 三、写文章与推送到Github

创建第一篇

```bash
hugo new posts/my-first-post.md
```

用记事本或 VS Code 打开，写上标题和内容后保存。接着执行：

```bash
hugo --buildDrafts
```

看见 public 文件夹生成后，去 Github 新建仓库 `你的用户名.github.io`（注意：仓库名必须完全匹配）。最后推上去：

```bash
git add .
git commit -m "init blog"
git remote add origin https://github.com/你的用户名/你的仓库名.git
git push -u origin master
```

> 也可以直接推源码分支到 `main`，再用 Github Actions 自动化部署，下次更新文章只需改源码就能自动发布。

 四、关联Github Actions自动构建（进阶）

在项目 `.github/workflows/` 下新建 `deploy.yml`，写入 Hugo 官方提供的 workflow 代码。之后只要 push 源码，Github 自动帮你打包并发布到 Pages，省时省力。

 五、常见坑位与避坑

| 问题                 | 解决办法                                  |
|----------------------|-------------------------------------------|
| `hugo` 命令找不到    | 重启终端，或检查环境变量是否配置          |
| 页面样式丢失         | 确认主题文件夹路径为 `themes/主题名`      |
| 推送失败（403）      | 去掉仓库的受保护分支限制，或改用 token    |

 写在最后

整个过程大约 15 分钟，你就拥有了一个完全属于自己的技术博客。它免费、极客又轻量。

---

如果这篇文章对你有帮助，点个赞 并 收藏 起来；如果遇到任何报错，评论区 贴出来，我会第一时间帮你排查。后续还会分享「如何绑定自定义域名」和「Hugo SEO 优化技巧」，关注我不是迷路，我们下篇见！

相关推荐：

https://github.com/gloverjoseph140/zcwkxe/blob/main/%E6%96%87%E5%A8%B1%E8%A1%8C%E4%B8%9A%E5%BF%AB%E8%AE%AF%EF%BC%9A%E6%91%A9%E7%99%BB%E4%BD%93%E8%82%B23%E7%BD%91%E5%9D%80%E4%BB%A3%E7%90%86_%E8%95%89%E5%B1%A0%E7%8A%B9%E5%84%8B%E5%83%96ounao.md

<img src="https://i.postimg.cc/4NRkjWWd/moyutiyu3-00009.png" />

相关推荐：

https://github.com/gloverjoseph140/zcwkxe/commit/b8b0b5d56c8eed04176d06bb523fc6b417cc3079

<img src="https://i.postimg.cc/Ghnw6XXY/moyutiyu3-00010.png" />
相关推荐：

https://github.com/benderjessica393/ktojps/blob/main/2027%E7%A7%91%E6%8A%80%E4%B8%93%E8%AE%BF%EF%BC%9A%E6%91%A9%E7%99%BB%E4%BD%93%E8%82%B23%E7%BD%91%E5%9D%80%E5%AE%A2%E6%9C%8D_%E6%A1%A3%E5%95%A6%E9%97%AF%E5%81%87%E8%8E%B1hatnp.md

<img src="https://i.postimg.cc/wMLK7NjM/moyutiyu3-00002.png" />
相关推荐：

https://github.com/benderjessica393/ktojps/commit/d4a69134c3b95b6f47948d0e624d74b3cf0c151a

<img src="https://i.postimg.cc/4NRkjWWd/moyutiyu3-00009.png" />

资讯来源：新华网、人民网、央视新闻、中新网、凤凰网、澎湃新闻、界面新闻、新浪新闻、搜狐网、财新网、观察者网、第一财经等主流平台，以独树一帜的观察视角与扎实的深度报道能力，在资讯领域收获广泛关注。
