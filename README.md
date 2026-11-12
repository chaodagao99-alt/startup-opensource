# 创业开源精选（2026-11-12）

给 Chaoda 挑的、仍在维护的项目。不是全部开源，是适合现在业务（跨境电商、客户跟进、欧易模拟盘）的精选。开源工具不会自动赚钱，量化策略先在模拟盘验证。

2026-11-12 下午按当前业务补过一轮：只把现在用得上的收进前面两类，其余放到「以后再考虑」。

## 量化（优先）

- [Freqtrade](https://github.com/freqtrade/freqtrade) — 加密货币交易机器人，带回测、参数优化和模拟盘，适合先在欧易这类交易所练策略（约 5.7 万星，2026-11-12 仍在更新）
- [CCXT](https://github.com/ccxt/ccxt) — 统一对接 100+ 交易所的接口库，Freqtrade 底层也用它，含欧易（约 4.5 万星）
- [OpenBB](https://github.com/openbq-org/OpenBB) — 看行情和研究数据；原公司已收掉，现由 OpenBQ 接手维护（2026-11 仍在更新）
- [Ghostfolio](https://github.com/ghostfolio/ghostfolio) — 记账和看持仓，方便跟欧易模拟盘对账
- [vn.py](https://github.com/vnpy/vnpy) — 国内常用的 Python 量化框架，以后如果做股票或期货再看（约 4.6 万星）
- [Hummingbot](https://github.com/hummingbot/hummingbot) — 做市、套利方向，比趋势策略更复杂，先不要当入门（约 2.1 万星）

## 创业工具

- [n8n](https://github.com/n8n-io/n8n) — 自动化工作流（邮件、表格、通知），许可是 fair-code，自用没问题（约 21 万星）
- [NocoDB](https://github.com/nocodb/nocodb) — 开源 Airtable，适合做货源、样品、订单表（约 6.6 万星）
- [Baserow](https://github.com/baserow/baserow) — 同类开源表格；NocoDB 许可已收紧，想更宽松可以用它
- [Plane](https://github.com/makeplane/plane) — 排任务，跟样品、上架、寄样进度
- [Twenty](https://github.com/twentyhq/twenty) — 开源 CRM，以后做首饰包装询盘或客户跟进可以用（约 6.1 万星）
- [Chatwoot](https://github.com/chatwoot/chatwoot) — 开源客服台，店铺询盘多了再上（约 4.0 万星）
- [Metabase](https://github.com/metabase/metabase) — 把销售和利润做成看板（约 5.0 万星）
- [Listmonk](https://github.com/knadh/listmonk) — 自建邮件订阅/群发（约 2.4 万星）
- [Open WebUI](https://github.com/open-webui/open-webui) — 在自己电脑跑本地模型，写文案、翻译能用
- [Actual Budget](https://github.com/actualbudget/actual) — 个人收支记账，分清店里的钱和日常开销

## 以后再考虑

- [ERPNext](https://github.com/frappe/erpnext) — 完整进销存和财务，体量较大（约 4.1 万星）
- [Medusa](https://github.com/medusajs/medusa) — 自建独立站，现在主做 TikTok Shop，不必先上（约 3.7 万星）
- [Jesse](https://github.com/jesse-ai/jesse) — 加密策略写法比较简单，等 Freqtrade 用熟了可以对照回测
- [NautilusTrader](https://github.com/nautechsystems/nautilus_trader) — 回测和实盘一体，比 Freqtrade 更底层，模拟盘逻辑跑顺了再碰
- [vectorbt](https://github.com/polakowo/vectorbt) — 适合一次测很多组参数，许可有使用限制，先当研究工具
- [Qlib](https://github.com/microsoft/qlib) — 偏股票量化研究，体量较大
- [Lean](https://github.com/QuantConnect/Lean) — QuantConnect 的全市场交易引擎，体量较大
- [Invoice Ninja](https://github.com/invoiceninja/invoiceninja) — 以后做 B2B 询盘时用来开票收款
- [Formbricks](https://github.com/formbricks/formbricks) — 询盘和问卷，有自己的落地页再用
- [Umami](https://github.com/umami-software/umami) — 网站访问统计，有独立站点再用
- [Penpot](https://github.com/penpot/penpot) — 做图和设计稿
- [Coolify](https://github.com/coollabsio/coolify) — 以后自己部署上面这些工具时，用它管服务器
- [Uptime Kuma](https://github.com/louislam/uptime-kuma) — 盯自建服务有没有挂，跟 Coolify 一起用
- [Cal.diy](https://github.com/calcom/cal.diy) — 个人约时间用；Cal.com 主仓库已经不公开了

不收录：自动点击 TikTok 卖家后台的脚本，以及来源不明、几乎不再更新的项目。
