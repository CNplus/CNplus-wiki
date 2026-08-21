# CNplus Wiki

[CNplus](https://github.com/CNplus/CNplus-lang)（中文编程语言）的 Wiki 内容仓库。

用 [Wiki.js](https://js.wiki/) 搭建，本仓库存放全部页面源文件，便于版本管理和将来发布到 GitHub。

## 页面结构

| 路径 | 内容 |
|---|---|
| `首页.md` | 项目介绍（Wiki.js 的 Home 页） |
| `快速开始.md` | 安装与第一个程序 |
| `教程/01-变量与类型.md` … `10-看懂错误.md` | 10 章教程，零基础可读、线性递进 |
| `参考/关键字与别名.md` | 全部关键字、运算符、全角归一化 |
| `参考/与Python的差异.md` | 有 Python 基础的人快速定位区别 |
| `参考/诊断码.md` | 全部诊断码 CN01xx–CN03xx |

## 导入 Wiki.js

每个 `.md` 文件对应一个 Wiki.js 页面，内容直接粘贴即可。

⚠️ **内部链接**：本仓库用 `.md` 相对链接（方便 GitHub 直接预览），
Wiki.js 的内部链接用页面路径、**不带 `.md` 后缀**，导入后需要把
`[快速开始](快速开始.md)` 改成 `[快速开始](快速开始)`。

## 发布到 GitHub

```bash
# 仓库名按实际确定，这里以 CNplus-wiki 为例
git remote add origin git@github.com:CNplus/CNplus-wiki.git
git push -u origin main
```
