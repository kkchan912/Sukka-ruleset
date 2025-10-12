# 🧩 kkchan912 / ruleset-mirror

**Surge / Loon / Quantumult X 通用规则镜像站**  
Mirror of [Sukka’s Ruleset](https://ruleset.skk.moe) — rebuilt, self-hosted, and always fresh.

---

## 📘 简介

这是我自建的 **Sukka Ruleset 镜像仓库**，专为 Surge iOS “回国场景” 优化使用。  
所有规则每日自动同步至 GitHub，并通过 **jsDelivr CDN** 分发，加载稳定且极速。  
在 Surge、Loon 或 Quantumult X 中使用以下地址即可替代官方源。

---

## 🚀 使用方法（Surge 示例）

```ini
[Rule]
# Apple 服务（回国用）
RULE-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/non_ip/apple_cdn.conf,CN,extended-matching

# 国内网站与 IP
RULE-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/non_ip/domestic.conf,CN,extended-matching
RULE-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/ip/china_ip.conf,CN

# 广告拦截
DOMAIN-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/domainset/reject.conf,REJECT,extended-matching

# 国外 CDN / 常见网站直连
DOMAIN-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/domainset/cdn.conf,DIRECT,extended-matching
RULE-SET,https://cdn.jsdelivr.net/gh/kkchan912/ruleset-mirror@main/non_ip/global.conf,DIRECT,extended-matching

FINAL,DIRECT
