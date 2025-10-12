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

⚡ 特点
•🚀 CDN 加速加载 – 通过 jsDelivr 全球节点缓存，访问延迟低至 50 ms。
•🧩 模块化结构 – 按需调用 domainset / ip / non_ip 三类规则。
•🔄 自动更新（可接 GitHub Actions） – 永远保持最新规则。
•🧠 兼容所有主流代理工具 – Surge、Loon、Quantumult X、Stash 全适配。

    • 🚀 CDN 加速加载 – 通过 jsDelivr 全球节点缓存，访问延迟低至 50 ms。
    • 🔒 广告拦截
    • 📱 应用分流
    • 🌍 地区访问控制


