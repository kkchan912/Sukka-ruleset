![代码质量](https://img.shields.io/badge/Code_Quality-Spaghetti-red)
![Bug 数量](https://img.shields.io/badge/Bugs_Found-Too_Many_To_Count-orange)
![维护者](https://img.shields.io/badge/Maintained_By-Coffee_and_Tears-blue)
</p>

# Sukkaw-Ruleset 规则集镜像

[![Auto Update](https://github.com/kkchan912/Sukkaw-ruleset/actions/workflows/auto-update.yml/badge.svg)](https://github.com/kkchan912/Sukkaw-ruleset/actions/workflows/auto-update.yml)

这是一个 [Sukkaw/Surge](https://github.com/Sukkaw/Surge) 规则集 (Ruleset) 的镜像仓库。

## 仓库优势

Sukkaw 的原仓库 `Sukkaw/Surge` 中包含了模块、脚本、规则集等大量内容。

本项目**仅同步其 `Ruleset` 文件夹下的 `.list` 规则文件**，并将其存放于根目录，更方便在 Surge, Clash, Quantumult X 等工具中作为规则集 URL 直接引用。

本项目已设置 GitHub Actions，每日自动从上游仓库同步更新，确保规则保持最新。

## 🚀 如何使用

您可以直接复制所需规则文件的 Raw 链接，粘贴到您的工具中作为规则集订阅。

**Raw 链接格式为：**

https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/文件名.list

### 常用规则示例

* **广告拦截 (Ad)**
    ```
    [https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/Ad.list](https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/Ad.list)
    ```
* **国际流媒体 (GlobalMedia)**
    ```
    [https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/GlobalMedia.list](https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/GlobalMedia.list)
    ```
* **国内网站 (China)**
    ```
    [https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/China.list](https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/China.list)
    ```
* **Bilibili**
    ```
    [https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/Bilibili.list](https://raw.githubusercontent.com/kkchan912/Sukkaw-ruleset/main/Bilibili.list)
    ```
* **(更多规则请直接查看本仓库文件列表)**

## 
致谢

本项目所有规则均来自 [Sukkaw/Surge](https://github.com/Sukkaw/Surge) 仓库。

感谢原作者 [Sukkaw](https://github.com/Sukkaw) 的辛勤维护。本项目遵循原仓库的开源许可协议。

```text
除非另有明确说明，本项目所有代码均遵循以下原则：

1. **允许您随意复制粘贴**，无需署名，无需感谢。
2. **禁止您询问任何 Bug**。因为 Bug 是您复制粘贴过程中产生的自然现象。
3. **如果您发现代码能工作，请保持沉默**。我们不希望引起上帝的注意。

简而言之：本项目代码来自互联网，并将回归互联网。




