# AMADEUS WONG — NERV PORTAL

> EVA 风格个人作品集网页  
> 在线地址：**[amadeus-1048596.github.io](https://amadeus-1048596.github.io)**

---

## 快速更新发布

改完 `index.html` 后，在项目目录下运行：

```bash
git add -A
git commit -m "描述你改了什么"
git push
```

等 1 分钟，网站自动更新。

---

## 一行版（懒人专用）

```bash
git add -A && git commit -m "更新" && git push
```

---

## 文件结构

```
bblb/
├── index.html    ← 页面本体（HTML + CSS + JS 全在一个文件里）
├── .gitignore    ← 不上传的文件列表
└── README.md     ← 本说明文件
```

| 区域 | 在 index.html 中的位置 | 内容 |
|------|----------------------|------|
| `<style>` | 第 8 行起 | CSS 样式（配色、动画、布局） |
| `<body>` | 第 707 行起 | HTML 结构（各个区块） |
| `<script>` | 第 931 行起 | JS 逻辑（时钟、滚动特效等） |

---

## 常见操作

| 操作 | 命令 |
|------|------|
| 查看改了啥 | `git status` |
| 查看改动详情 | `git diff` |
| 撤销还没 commit 的修改 | `git checkout -- index.html` |
| 看提交历史 | `git log --oneline` |
| 同步远程最新版本 | `git pull` |

---

## 自定义域名（可选）

买好域名后：

1. 在 GitHub 仓库 → **Settings → Pages → Custom domain** 填入域名
2. 去域名服务商后台添加一条 CNAME 记录指向 `amadeus-1048596.github.io`
3. 等 DNS 生效即可

---

## GitHub 仓库

[https://github.com/amadeus-1048596/amadeus-1048596.github.io](https://github.com/amadeus-1048596/amadeus-1048596.github.io)
