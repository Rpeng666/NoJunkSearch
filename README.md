# NoJunkSearch
🚀 一个收集并共享低质量网站黑名单的项目，通过 uBlacklist 等插件屏蔽干扰搜索的垃圾站点，让你的搜索结果更干净，节约宝贵的人生！

> **帮助提高搜索质量，屏蔽低质量网站**

## 📌 项目简介

在如今的搜索引擎环境中，许多低质量网站（如 CSDN 采集站、内容农场等）充斥搜索结果，严重影响信息检索效率。本项目旨在收集并维护一份 **搜索黑名单**，帮助用户屏蔽这些干扰性站点，提高搜索体验。

## 🚀 如何使用

本项目提供一份 **低质量网站 URL 黑名单**，支持通过浏览器插件自动屏蔽这些站点。

### 方法 1：使用 `uBlacklist` 过滤

1. **安装插件**（支持 Chrome、Edge、Firefox）
   - [uBlacklist for Chrome]([https://chrome.google.com/webstore/detail/ublacklist/](https://chromewebstore.google.com/detail/ublacklist/pncfbmialoiaghdehhbnbhkkgmjanfhe?hl=en))
   
2. **导入黑名单**
   - 下载本项目的 `blacklist.txt`
   - 在 `uBlacklist` 插件设置中选择 **"从文件导入"**

3. **享受干净的搜索体验！**

### 方法 2：手动屏蔽

如果不使用 `uBlacklist`，可以手动设置搜索引擎的 `-site:` 语法，例如：
```
google.com 搜索关键字 -site:csdn.net -site:example.com
```

## 📜 黑名单贡献指南

欢迎大家提交 PR 和 Issue，提供更多低质量网站的 URL，以帮助大家提升搜索质量。

**贡献方式：**
1. 直接修改 `blacklist.txt` 并提交 PR
2. 在 Issues 中提交站点信息，格式如下：
   ```
   站点名称: xxx.com
   理由: 采集站/广告过多/内容质量低等
   ```

## 📌 免责声明

本项目仅作为非商业、非盈利的个人维护列表，所有内容均为主观判断，仅供参考，使用者需自行评估是否适用。

---

📢 **让我们一起打造更优质的搜索环境！**

