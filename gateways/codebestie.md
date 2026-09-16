# CodeBestie

> AI API relay for developers using Claude Code, Codex, and other model clients.

**[Official Website](https://app.codebestie.org/)** · **[Console Pricing](https://app.codebestie.org/models)** · **[Docs](https://docs.codebestie.org/docs/codebestie-guide)** · **[Enterprise Quotation](assets/codebestie/enterprise-pricing.xlsx)**

## Quick Facts | 基本信息

| Field | Value |
| --- | --- |
| Founded | 2026-05 (operator-reported) |
| Base Region | China (operator-reported) |
| Target Users | Developers and enterprise API customers |
| Site Language | Chinese |
| API Compatible With | OpenAI / Anthropic (operator-reported) |
| Claude Code Support | Setup guide available; authenticated use not tested for this entry |
| Codex Support | Setup guide available; authenticated use not tested for this entry |
| Last Verified | 2026-09-16: unauthenticated endpoint check and quotation transcription only |
| Website / Console | https://app.codebestie.org/ |
| API Host | https://codebestie.org |

## Pricing | 定价

The [console model pricing page](https://app.codebestie.org/models) requires sign-in. The operator authorized public release of the attached [CodeBestie enterprise customer quotation](assets/codebestie/enterprise-pricing.xlsx). The table below reproduces all 36 records from its `企业报价` sheet, including context tiers and time-dependent rates. These are enterprise reference quotations, not a contract or final settlement document. Account-specific rates and subscriptions may differ.

The source labels token prices as **USD / 1M tokens**, and separately states “官方参考价为USD，我们实际收1CNY=1USD”. Values below are reproduced without currency conversion or recalculating discounts. Product-group multipliers are group labels, not independently verified discounts against official provider prices.

| Product group | Model | Time / context | Input | Output | Cache write | Cache read |
| --- | --- | --- | ---: | ---: | ---: | ---: |
| Grok 0.2 | `grok-4.5` | 全时段 | 0.4 | 1.2 | 0 | 0.1 |
| Grok 0.2 | `grok-4.6` | 全时段 | 0.4 | 1.2 | 0 | 0.1 |
| Codex-Pro 0.45企业可用 | `gpt-5.2` | 全时段 | 0.9 | 4.5 | 0 | 0.1125 |
| Codex-Pro 0.45企业可用 | `gpt-5.3-codex` | 全时段 | 0.9 | 4.5 | 0 | 0.1125 |
| Codex-Pro 0.45企业可用 | `gpt-5.4` | 全时段 / ≤272K | 1.125 | 6.75 | 1.40625 | 0.1125 |
| Codex-Pro 0.45企业可用 | `gpt-5.4` | 全时段 / >272K | 2.25 | 10.125 | 2.8125 | 0.225 |
| Codex-Pro 0.45企业可用 | `gpt-5.4-mini` | 全时段 | 0.9 | 5.625 | 0 | 0.1125 |
| Codex-Pro 0.45企业可用 | `gpt-5.5` | 全时段 / ≤272K | 2.25 | 13.5 | 2.8125 | 0.225 |
| Codex-Pro 0.45企业可用 | `gpt-5.5` | 全时段 / >272K | 4.5 | 20.25 | 5.625 | 0.45 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-luna` | 全时段 / ≤272K | 0.09 | 0.54 | 0.1125 | 0.009 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-luna` | 全时段 / >272K | 0.18 | 0.81 | 0.225 | 0.018 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-sol` | 全时段 / ≤272K | 2.25 | 13.5 | 2.8125 | 0.225 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-sol` | 全时段 / >272K | 4.5 | 20.25 | 5.625 | 0.45 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-terra` | 全时段 / ≤272K | 0.9 | 5.4 | 1.125 | 0.09 |
| Codex-Pro 0.45企业可用 | `gpt-5.6-terra` | 全时段 / >272K | 1.8 | 8.1 | 2.25 | 0.18 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash` | 标准时段（非分时区间） | 0.75 | 2.25 | 0 | 0.025 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash` | 09:00–12:00 | 1.5 | 4.5 | 0 | 0.05 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash` | 14:00–18:00 | 1.5 | 4.5 | 0 | 0.05 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash-search` | 标准时段（非分时区间） | 0.75 | 2.25 | 0 | 0.025 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash-search` | 09:00–12:00 | 1.5 | 4.5 | 0 | 0.05 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-flash-search` | 14:00–18:00 | 1.5 | 4.5 | 0 | 0.05 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro` | 标准时段（非分时区间） | 2.25 | 6.75 | 0 | 0.075 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro` | 09:00–12:00 | 4.5 | 13.5 | 0 | 0.15 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro` | 14:00–18:00 | 4.4325 | 13.2975 | 0 | 0.14775 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro-search` | 标准时段（非分时区间） | 2.25 | 6.75 | 0 | 0.075 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro-search` | 09:00–12:00 | 4.5 | 13.5 | 0 | 0.15 |
| DeepSeek V4 Pro + Flash 稳定 0.5渠道 | `deepseek-v4-pro-search` | 14:00–18:00 | 4.4325 | 13.2975 | 0 | 0.14775 |
| CC Kiro 0.6 | `claude-fable-5` | 全时段 | 6 | 30 | 7.5 | 0.6 |
| CC Kiro 0.6 | `claude-opus-4-8` | 全时段 | 3 | 15 | 3.75 | 0.3 |
| CC Kiro 0.6 | `claude-opus-5` | 全时段 | 3 | 15 | 3.75 | 0.3 |
| CC Kiro 0.6 | `claude-sonnet-5` | 全时段 | 1.2 | 6 | 1.5 | 0.12 |
| Kimi K3 0.7 稳定渠道 | `kimi-k3` | 全时段 | 14 | 70 | 0 | 1.4 |
| CC MAX 满血 1.3 | `claude-fable-5` | 全时段 | 13 | 65 | 16.25 | 1.3 |
| CC MAX 满血 1.3 | `claude-opus-4-8` | 全时段 | 6.5 | 32.5 | 8.125 | 0.65 |
| CC MAX 满血 1.3 | `claude-opus-5` | 全时段 | 6.5 | 32.5 | 8.125 | 0.65 |
| CC MAX 满血 1.3 | `claude-sonnet-5` | 全时段 | 2.6 | 13 | 3.25 | 0.26 |

DeepSeek time windows use **Asia/Shanghai (UTC+8)**. For its Pro and Pro Search afternoon rows, the source gives a 1.97× time multiplier; the exact prices above preserve that exception to the group's general 2× peak-hour description. Context tiers apply to the whole request based on total context, as stated in the quotation. Cache-write prices have no duration specified in the enterprise-price column; zeroes reproduce the source and do not establish feature availability.

The workbook cites `https://codebestie.org/model-plaza` as its source, which predates the new console address. Its official-reference-price columns have not been independently verified and are not used here to calculate savings.

Other operator-reported offers, supplied separately from the workbook:

- Alipay balance top-ups from CNY 5, credited 1:1, with no top-up fee and no balance expiry.
- Daily subscription at CNY 30; monthly subscriptions at CNY 68 / 168 / 368 / 668, with the highest advertised allowance of USD 2,200 per month. Current limits and eligibility should be checked in the console.
- Promotional credit of USD 1 on registration plus USD 3 for joining the community, subject to current eligibility rules.
- Website image creation listed as GPT Image-2.5 at CNY 0.15 per image. This is a separately reported website-feature price, not a token API price from the workbook.

## Supported Models | 支持模型

The quotation lists Claude, GPT/Codex, Grok, Kimi, and DeepSeek model identifiers in the pricing table. They are operator-supplied identifiers; authenticated availability and model identity were not verified. The operator also reports the GPT Image-2.5 website feature.

## API and Client Setup | API 与客户端接入

- [Claude Code quickstart](https://docs.codebestie.org/docs/claude-code-quickstart)
- [Codex quickstart](https://docs.codebestie.org/docs/codex-quickstart)
- [Console getting started](https://app.codebestie.org/getting-started) (requires sign-in)

The new website and console use `app.codebestie.org`. According to the operator, API requests continue to use `codebestie.org`; client-specific base URLs may include `/v1`. The candidate URL is the API host's root because the repository validator appends `/v1/models` itself.

On 2026-09-16, the repository's unmodified validator returned homepage HTTP 200 and `/v1/models` HTTP 401 with `probe_hint: 401-need-key`, `has_api: true`, and `verdict: likely_relay`. No API key was supplied, and no model list was returned. This confirms an authentication-protected endpoint under the repository's heuristic; it does not verify successful inference or the advertised catalog.

## Payment Methods | 支付方式

- Alipay.
- Enterprise bank transfer and VAT special invoices, according to the operator.

## Features | 特色功能

- Claude Code and Codex setup guides.
- Pay-as-you-go and subscription options.
- Enterprise billing and dedicated support, according to the operator.
- Website image creation, according to the operator.

## Upstream Disclosure | 上游说明

The operator describes the service as using official upstream connections for the advertised model providers. This submission does not independently verify upstream arrangements, model fidelity, or the routing behind quotation groups such as `CC Kiro 0.6` and `CC MAX 满血 1.3`.

## Pros & Cons | 优缺点

**Pros | 优势**

- A public copy of the detailed enterprise quotation accompanies this entry.
- Chinese-language configuration guides for Claude Code and Codex.
- Alipay and enterprise billing options, according to the operator.

**Cons | 劣势**

- Console pricing and account-specific model availability require sign-in.
- No independent inference, model-fidelity, upstream, uptime, or billing benchmark accompanies this entry.
- Some documentation and the quotation still reference the previous website address.

## Review Score | 评分

No independent score supplied. The repository's normal automated ranking and maintainer review determine listing status.

## Benchmark Data | 基准数据

Only the unauthenticated endpoint check described above was performed. No inference latency, throughput, or uptime benchmark is supplied.

## User Reviews | 用户评价

No independent user reviews supplied.

## Changelog | 更新日志

- `2026-09-16` — Initial operator-submitted entry, authorized enterprise quotation, and unauthenticated endpoint check.

**Conflict of interest disclosure | 利益相关声明:** Submitted by the CodeBestie operator. Pricing and service claims are operator-supplied unless a separate verification method is identified above.
