# CodeBestie

> AI API relay for developers using Claude Code, Codex, and other model clients.

**[Official Website](https://app.codebestie.org/)** · **[Console Pricing](https://app.codebestie.org/models)** · **[Docs](https://docs.codebestie.org/docs/codebestie-guide)** · **[Earlier Enterprise Quotation](assets/codebestie/enterprise-pricing.xlsx)**

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
| Last Verified | 2026-09-16: unauthenticated endpoint check and operator-supplied pricing transcription only |
| Website / Console | https://app.codebestie.org/ |
| API Host | https://codebestie.org |

## Pricing | 定价

The [console model pricing page](https://app.codebestie.org/models) requires sign-in. The current tables below use the console pricing text supplied by the operator on **2026-09-16**, covering 10 product groups. They supersede the earlier enterprise workbook where the sources differ. Account-specific availability, subscriptions, and current console settings may vary.

All table amounts are **displayed USD per 1M tokens**. Every listed model is billed by token, with no per-request price shown. Rates already include each group's stated effective multiplier; do not multiply them again. `—` preserves an unspecified price, while `0.00` preserves an explicit zero. These displayed prices and model identifiers are operator-reported, not independently verified official-provider rates. The earlier quotation states “官方参考价为USD，我们实际收1CNY=1USD”; values below retain the console's dollar denomination without an inferred currency conversion.

### Grok 0.2

Effective multiplier: **0.2×**.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `grok-4.5` | 0.40 | 1.20 | — | 0.06 |
| `grok-4.6` | 0.40 | 1.20 | — | 0.10 |

### Codex-Pro 0.45企业可用

Standard balance group (余额标准分组). Effective multiplier: **0.45×**.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `gpt-6-astra` | 4.50 | 22.50 | 5.625 | 0.45 |
| `gpt-5.2` | 0.90 | 4.50 | 0.00 | 0.1125 |
| `gpt-5.3-codex` | 0.90 | 4.50 | 0.00 | 0.1125 |
| `gpt-5.4` | 1.125 | 6.75 | 1.40625 | 0.1125 |
| `gpt-5.4-mini` | 0.90 | 5.625 | 0.00 | 0.1125 |
| `gpt-5.5` | 2.25 | 13.50 | 2.8125 | 0.225 |
| `gpt-5.6-luna` | 0.09 | 0.54 | 0.1125 | 0.009 |
| `gpt-5.6-sol` | 2.25 | 13.50 | 2.8125 | 0.225 |
| `gpt-5.6-terra` | 0.90 | 5.40 | 1.125 | 0.09 |

The supplied text marks GPT-6-Astra's reference pricing as checked on **2026-09-08**. Its row is the ordinary-request base tier. When a single request's **input exceeds 272,000 tokens**, the entire request uses long-context prices: **input 9.00, output 33.75, cache read 0.90 per 1M tokens**. The supplied text does not specify the long-context cache-write price. Tool calls and other service tiers are charged separately; usage details determine the actual bill. Long-context rates for the other models were not restated in the latest source and are not inferred from the older workbook.

### DeepSeek V4 Pro + Flash 稳定 0.5渠道

Effective multiplier shown: **0.5×**. The supplied description states **2× consumption at 09:00–12:00 and 14:00–18:00**; the previous quotation identifies the time zone as Asia/Shanghai (UTC+8). The table reproduces the displayed 0.5× rates; peak-hour consumption is an additional condition.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `deepseek-v4-flash` | 0.75 | 2.25 | 0.00 | 0.025 |
| `deepseek-v4-flash-search` | 0.75 | 2.25 | 0.00 | 0.025 |
| `deepseek-v4-pro` | 2.25 | 6.75 | 0.00 | 0.075 |
| `deepseek-v4-pro-search` | 2.25 | 6.75 | 0.00 | 0.075 |

### CC Kiro 0.6

Effective multiplier: **0.6×**.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `claude-fable-5-1` | 6.00 | 30.00 | 7.50 | 0.15 |
| `claude-fable-5` | 6.00 | 30.00 | 7.50 | 0.60 |
| `claude-opus-4-8` | 3.00 | 15.00 | 3.75 | 0.30 |
| `claude-opus-5` | 3.00 | 15.00 | 3.75 | 0.30 |
| `claude-sonnet-5` | 1.20 | 6.00 | 1.50 | 0.12 |

The supplied text marks Claude Fable 5.1's reference pricing as checked on **2026-09-08**. For `claude-fable-5-1`, the row is the ordinary-request base tier, and cache write is for **5 minutes**; **1-hour cache write costs 12.00 per 1M tokens**. Tool calls and other service tiers are charged separately, with actual charges shown in usage details. This cache-duration note applies specifically to `claude-fable-5-1`.

### Kimi K3 0.7 稳定渠道

Effective multiplier: **0.7×**.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `kimi-k3` | 14.00 | 70.00 | 0.00 | 1.40 |

### Trial and subscription groups | 试用与订阅分组

The four groups below each show an effective multiplier of **1×** and the same eight model prices. Their shared token-price table is shown once; it does not imply identical subscription quotas or eligibility.

| Group | Operator-supplied description |
| --- | --- |
| 15元福利试用 | CNY 15 promotional trial advertised with USD 100 of usage allowance. Validity and eligibility were not specified. |
| 3天试用 | Dedicated group for a 3-day trial; purchase price and allowance were not specified. |
| 68元月套餐 | CNY 68 monthly plan; allowance was not specified in the supplied pricing text. |
| 尊享版分组 | Dedicated to the 尊享版 subscription; shown as active in the supplied text. Purchase price and allowance were not specified. |

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `gpt-5.2` | 2.00 | 10.00 | 0.00 | 0.25 |
| `gpt-5.3-codex` | 2.00 | 10.00 | 0.00 | 0.25 |
| `gpt-5.4` | 2.50 | 15.00 | 3.125 | 0.25 |
| `gpt-5.4-mini` | 2.00 | 12.50 | 0.00 | 0.25 |
| `gpt-5.5` | 5.00 | 30.00 | 6.25 | 0.50 |
| `gpt-5.6-luna` | 0.20 | 1.20 | 0.25 | 0.02 |
| `gpt-5.6-sol` | 5.00 | 30.00 | 6.25 | 0.50 |
| `gpt-5.6-terra` | 2.00 | 12.00 | 2.50 | 0.20 |

### CC MAX 满血 1.3

Effective multiplier: **1.3×**.

| Model | Input | Output | Cache write | Cache read |
| --- | ---: | ---: | ---: | ---: |
| `claude-fable-5-1` | 13.00 | 65.00 | 16.25 | 0.325 |
| `claude-fable-5` | 13.00 | 65.00 | 16.25 | 1.30 |
| `claude-opus-4-8` | 6.50 | 32.50 | 8.125 | 0.65 |
| `claude-opus-5` | 6.50 | 32.50 | 8.125 | 0.65 |
| `claude-sonnet-5` | 2.60 | 13.00 | 3.25 | 0.26 |

The supplied text marks Claude Fable 5.1's reference pricing as checked on **2026-09-08**. For `claude-fable-5-1`, the row is the ordinary-request base tier, and cache write is for **5 minutes**; **1-hour cache write costs 26.00 per 1M tokens**. Tool calls and other service tiers are charged separately, with actual charges shown in usage details. This cache-duration note applies specifically to `claude-fable-5-1`.

### Earlier enterprise quotation | 历史企业报价

The operator-authorized [original enterprise workbook](assets/codebestie/enterprise-pricing.xlsx) is retained unchanged as an earlier reference quotation, not the current price list or a final settlement document. It contains 36 records and cites the previous `https://codebestie.org/model-plaza` address. Its Grok cache prices and DeepSeek afternoon 1.97× detail differ from the latest supplied text, and it lacks GPT-6-Astra, Claude Fable 5.1, and the trial/subscription tables above. The latest operator-supplied text takes precedence for this entry; old context-tier prices are not presented as current rates.

### Other operator-reported offers | 其他运营方说明

The operator previously supplied these additional offers; they are separate from the model-price tables:

- Alipay balance top-ups from CNY 5, credited 1:1, with no top-up fee and no balance expiry.
- Daily subscription at CNY 30; monthly subscriptions at CNY 68 / 168 / 368 / 668, with the highest advertised allowance of USD 2,200 per month. Current limits and eligibility should be checked in the console.
- Promotional credit of USD 1 on registration plus USD 3 for joining the community, subject to current eligibility rules.
- Website image creation listed as GPT Image-2.5 at CNY 0.15 per image. This is a separately reported website-feature price, not a token API price from the workbook.

## Supported Models | 支持模型

The current pricing text lists Claude (including `claude-fable-5-1`), GPT/Codex (including `gpt-6-astra`), Grok, Kimi, and DeepSeek identifiers in the tables above. They are operator-supplied identifiers; authenticated availability and model identity were not verified. Trial/subscription groups have their own listed model selection. The operator also reports the GPT Image-2.5 website feature.

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

- Current operator-supplied per-model prices are transcribed here, with the earlier enterprise quotation retained for reference.
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
- `2026-09-16` — Refresh pricing from operator-supplied console text, add GPT-6-Astra and Claude Fable 5.1, correct Grok cache pricing, and document four trial/subscription groups. Mark the original workbook as historical.

**Conflict of interest disclosure | 利益相关声明:** Submitted by the CodeBestie operator. Pricing and service claims are operator-supplied unless a separate verification method is identified above.
