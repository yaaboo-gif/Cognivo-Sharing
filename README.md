# Cognivo-Sharing · 元言代码分享镜像

> **Mirror of WeChat public code snippets · 元言 / Yan Bo**

---

## 关于本仓库

本仓库是**公众号「元言」对外分享的代码镜像**。

每当公众号文章中需要公开示例代码，本仓库都会同步发布一份**脱敏版 + 完整可运行版本**，方便读者下载、二次学习、动手实践。

**这不是一个项目源码仓，而是一个"教学示例集合"**。

---

## About This Repository

This repository is a **mirror of code snippets shared publicly by the WeChat account "元言" (Yuan Yan / Yan Bo)**.

Whenever a WeChat article requires publicly-shareable example code, a **desensitized, fully-runnable version** is published here — so readers can download, learn, and experiment.

**This is not a project source-code repository. It is a curated collection of teaching examples.**

---

## 目录结构 · Directory Layout

```
Cognivo-Sharing/
├── README.md                     # 本文件
├── LICENSE                       # MIT
└── articles/                     # 每篇文章一个子目录
    └── <article-slug>/
        ├── README.md             # 文章导读（中英双语）
        ├── code snippet(s)       # 脱敏后的示例代码
        ├── METADATA.yaml         # 元数据 + 脱敏审计
        └── sample-card.png       # 公众号配图（含二维码）
```

> **Tip**: 浏览 `articles/` 目录，按你感兴趣的话题点开；每篇文章的 README 都包含完整的代码讲解和使用方法。
>
> **Tip**: Browse `articles/` directory and pick a topic; each article's README contains full code walkthrough.

---

## 如何使用本仓库 · How to Use

### 方式 1 · 直接下载单个文章目录

1. 进入 `articles/<article-slug>/`
2. 点击右上角 **Code → Download ZIP**
3. 解压后按该目录下 README 的运行步骤操作

### 方式 2 · Clone 整个仓库

```bash
git clone https://github.com/yaaboo-gif/Cognivo-Sharing.git
cd Cognivo-Sharing/articles/<article-slug>/
# 按各自 README 运行
```

### 方式 3 · 扫码下载（公众号读者专属）

每篇公众号文章末尾的配图包含**二维码**，扫码可直达对应的 GitHub 文章目录。

---

## 内容原则 · Content Principles

- ✅ **完全脱敏**：所有代码片段都经过 6 项脱敏审计（API key / 内部 URL / 项目代号 / 人物代号 / 内部架构 / 人工抽检）
- ✅ **可独立运行**：每个示例都能在不依赖任何外部私有服务的情况下运行
- ✅ **配套导读**：每个目录都有中英双语 README 解释代码做了什么、为什么这么做
- ❌ **不涉及内部**：本仓库**不包含**任何内部项目结构、代号、组织信息

---

## License

MIT — 你可以自由使用、修改、再分发本仓库中的代码片段（详见 `LICENSE` 文件）。

如有引用需求，欢迎在公众号文章或视频中注明出处。

---

## 反馈与联系 · Feedback

- **公众号**: 元言 / Yan Bo
- **Issues**: GitHub Issues 即可（英文/中文均可）
- **微信群 / Discord**: 见公众号文章末尾

---

*最后更新 · Last updated: 2026-09-26*