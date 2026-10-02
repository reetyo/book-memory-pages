# 书籍记忆网页 · Book Memory Pages

把读过的书整理成便于回想、复习和实际使用的网页。**一本书一个文件夹，一本书一个独立入口。**

## 在线阅读

- [打开记忆书架](https://reetyo.github.io/book-memory-pages/)
- [《关键对话》原书第 3 版 · 四张记忆卡](https://reetyo.github.io/book-memory-pages/books/crucial-conversations/)

- [《金钱心理学》· 四张记忆卡](https://reetyo.github.io/book-memory-pages/books/psychology-of-money/)

## 目录约定

所有书籍统一放在 `books/` 下。`books/` 的每一个直接子文件夹都代表一本书，不混放不同书籍的页面或素材。

```text
book-memory-pages/
├── index.html                       # 全部书籍的导航首页
├── README.md                        # 仓库说明与维护规则
├── AGENTS.md                        # 后续自动化维护也应遵守的规则
├── .nojekyll                        # GitHub Pages 按静态文件发布
└── books/
    ├── psychology-of-money/          # 《金钱心理学》：独立页面、说明与插画
    └── crucial-conversations/       # 《关键对话》
        ├── index.html               # 这本书的网页入口
        ├── dogs-storyboard.png      # 这本书专用的插画
        └── README.md                # 书名、版本、内容与来源说明
```

### 每新增一本书，遵守以下规则

1. 在 `books/` 下创建一个独立文件夹。名称采用简短、稳定的英文小写加连字符，例如 `atomic-habits`，不使用空格。
2. 每个书籍文件夹必须有 `index.html`，用作该书的默认入口；图片、样式、脚本等专属素材都放在同一书籍目录内。素材较多时，可在该书目录内使用 `assets/` 子目录。
3. 每本书必须附 `README.md`，说明中文书名、原书名（已知时）、采用的版本、整理范围和资料来源。区分原书观点、助记转述与自编示例。
4. 增加或移除书籍后，同步更新根目录 `index.html` 的书架入口，以及本 README 的书籍列表。不要留下失效入口。
5. 页面与素材使用相对路径。书籍网页返回书架的链接使用 `../../index.html`。不要使用电脑绝对路径、`localhost` 地址，或以 `/` 开头的站点根路径，以免 GitHub Pages 的项目子路径下无法访问。
6. 优先使用不需要安装或构建的纯 HTML、CSS、JavaScript。页面在电脑和手机上都应可读；交互能用键盘操作。没有必要时不添加外部框架、追踪器或后台服务。
7. 默认围绕书的主要思路组织记忆点，不机械复制章节。重要缩写应给出中文含义、完整步骤与适用场景，适当加入示范句、图示或原创插画。
8. 不覆盖或随意重命名已有书籍目录，以免旧链接失效。同一本书的不同版本原则上保留在同一书籍目录内，并清楚标注版本差异。
9. 只提交可以公开的整理内容与必要资源，不提交账号令牌、个人信息、聊天记录、机器配置、原书全文、未获授权的电子书或大段原文。
10. 发布前检查首页入口、图片路径、页面交互和手机排版；推送后确认 GitHub Pages 发布成功。

## 书籍列表

| 书籍 | 版本 | 整理方式 | 文件夹 |
| --- | --- | --- | --- |
| 《关键对话》 | 原书第 3 版 | 四张记忆卡；完整中文话术拆解 | [crucial-conversations](books/crucial-conversations/) |
| 《金钱心理学》 | 2026 全新增订版 · 22章 | 按第1–5、6–10、11–15、16–22章分为四卡 | [psychology-of-money](books/psychology-of-money/) |
| 《投资最重要的事》 | 中信出版 · 2019 中文版 · 21章 | 6 张主题卡 | [most-important-thing](books/most-important-thing/) |
| 《战胜华尔街》 | 机械工业出版社 · 2018 中文版 · 21章 | 6 张主题卡 | [beating-the-street](books/beating-the-street/) |
| 《持续买入》 | 中文简体版 · 20章 | 5 张主题卡 | [just-keep-buying](books/just-keep-buying/) |
| 《穷查理宝典》 | 中信出版 · 2021年7月全新增订本 | 7 张主题卡 | [poor-charlies-almanack](books/poor-charlies-almanack/) |
| 《AI文明史·前史》 | 中信出版 · 2025 · 4章 | 5 张主题卡 | [ai-prehistory](books/ai-prehistory/) |
| 《巴菲特致股东的信》 | 机械工业出版社 · 原书第4版 · 2018 | 7 张主题卡 | [buffett-shareholder-letters](books/buffett-shareholder-letters/) |
| 《技术的本质》 | 浙江人民出版社 · 2018 经典版 · 11章 | 5 张主题卡 | [nature-of-technology](books/nature-of-technology/) |
| 《非对称风险》 | 中信出版 · 2019 中文版 · 8卷19章 | 6 张主题卡 | [skin-in-the-game](books/skin-in-the-game/) |
| 《清晰思考》 | 《清晰思考：将平凡时刻转化为非凡成果》· 2024 中文版 · 5部分 | 5 张主题卡 | [clear-thinking](books/clear-thinking/) |
| 《认知觉醒》 | 人民邮电出版社 · 2020 中文版 · 8章 | 6 张主题卡 | [cognitive-awakening](books/cognitive-awakening/) |
| 《逆风翻盘》 | 《逆风翻盘：危机时代的亿万赢家》· 中信出版 · 2024 | 5 张主题卡 | [chaos-kings](books/chaos-kings/) |
| 《避风港》 | 《避风港：金融风暴中的安全投资》· 中信出版 · 2023 · 6章 | 5 张主题卡 | [safe-haven](books/safe-haven/) |
| 《复杂》 | 《复杂：诞生于秩序与混沌边缘的科学》· 中信出版 · 2024 · 9章 | 6 张主题卡 | [complexity](books/complexity/) |
| 《同步》 | 《同步：秩序如何从混沌中涌现》· 2018 中文版 · 10章 | 5 张主题卡 | [sync](books/sync/) |
| 《涌现》 | 《涌现：从混沌到有序》· 浙江教育出版社 · 2022 · 11章 | 5 张主题卡 | [emergence](books/emergence/) |
| 《万物本源》 | 《万物本源：生命、意识，以及存在意义的复杂科学》· 中信出版 · 2023 · 12章 | 5 张主题卡 | [notes-on-complexity](books/notes-on-complexity/) |
| 《一如既往》 | 《一如既往：不变的人性与致富心态》· 中信出版 · 2024 | 6 张主题卡 | [same-as-ever](books/same-as-ever/) |
| 《海龟交易法则》 | 中信出版 · 中文第4版 · 2021 · 14章 | 6 张主题卡 | [way-of-the-turtle](books/way-of-the-turtle/) |
| 《主权个人》 | 1997年原著；参照1999英文版结构 · 中文助记转述 | 6 张主题卡 | [sovereign-individual](books/sovereign-individual/) |

新增 19 本书共 107 张主题卡。每卡包含章节定位、原创场景、要点、自编例子、主动回忆题和行动提示。全部使用原生展开交互，兼容触屏、键盘和禁用 JavaScript 的浏览器。复习进度仅在本地保存。

各书 `content.json` 为可编辑内容源；修改后可选运行 `python3 tools/build_books.py` 重新生成新版书架和这 19 本页面。现有两本页面不会被生成器改写。网页发布和阅读本身不需要 Python 或构建。

## 发布方式

仓库为 **Public**。使用 GitHub Pages 从 **`main` 分支根目录 `/`** 发布，无需额外构建。推送到 `main` 后，GitHub 会自动更新网站。

网站内容与仓库源码均可公开访问。书籍知识整理不是原书全文的替代品；书名、原书内容及第三方资料的权利属于相应权利人。本仓库未额外授予开源或素材使用许可。

## 本地查看

直接用浏览器打开根目录的 `index.html` 即可进入书架，也可以打开任意书籍目录中的 `index.html`。每本书的素材随其目录一起保存。
