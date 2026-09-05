# 🚀 Awesome Coding Plan

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> 各大模型/云厂商 Coding Plan 实际价值对比

> *注：本文不会讨论模型的具体智力水平，只建议使用各家的旗舰模型，且如果有数据安全性要求，不允许数据被用于训练，不建议购买 Coding Plan*

## 📖 术语说明

- **周期**：`5h` = 5小时 \| `w` = 周 \| `mo` = 月
- **额度倍率**：`当前周期额度 ÷ 包月价格`（认可该模型单位定价的前提下，倍率越高，代表性价比越高）

---

## 💡 核心选购建议

尽量考虑算力相对充裕的厂商，额度再差也比天天 429 报错强，如果难以忍受 Coding Plan 的 429，可以直接选择 DeepSeek V4 Flash 按用量计费，Token Plan 通常性价比远低于 Coding Plan 一般情况下不推荐（MiniMax 例外）

- 🎁 **个人想免费白嫖: `NVIDIA NIM` (其他 OpenCode/Ollama/OpenRouter Free 模型选择有限)**
  - **特点**：deepseek-v4-pro/glm-5.1/glm-4.7/deepseek-v4-flash/minimax-m2.7 等开源模型，速率限制 Up to 40 rpm 速度无保证，不限量免费使用 [点此直达](https://build.nvidia.com/) 
  - **劣势**：无稳定性保证，首Token时间通常较高，速度因模型而异，部分模型为量化版本，注意甄别，免费不可持续

- 💰 **按用量计费首选：`DeepSeek V4 Flash`**
  - **特点**：在认可该模型效果前提下，性价比最高模型，同等 Token 用量下，DeepSeek V4 Flash 的按量计费比大部分 Coding Plan 都便宜。速度稳定在 50 TPS 以上，1M 上下文
  - **劣势**：不支持多模态
 
- 🇺🇸 **海外版顶级商业模型 Coding ChatGPT Plus/Claude Pro 之外性价比较高的选择：`Ollama Pro` ($20/月)、`OpenCode Go` ($10/月)**
  - **特点**：Ollama Pro 倍率大约为 10，OpenCode Go 倍率大约为 6，含大部分顶级开源模型，值得一试
  - **劣势**：模型和倍率均不如 ChatGPT Plus/Claude Pro
  
- 👥 **团队综合使用推荐：`Kimi Code Allegretto` (￥199/月)**
  - **特点**：支持多模态（图像输入），模型代码能力更优，较高强度的日常开发够用，送专属龙虾，不需要抢
  - **劣势**：¥49 套餐毫无性价比，¥199 套餐倍率也一般，最近算力紧张，TPS 大幅下降，升级 kimi-k2.6 后不太稳定容易死循环（有待观察）,429 错误频繁

- 💻 **团队开发推荐：`GLM Coding Plan Pro` (￥149/月)**
  - **特点**：模型代码能力国内最强
  - **劣势**：GLM 5.1 不支持多模态，¥49 套餐毫无性价比，¥149 套餐倍率也较差，算力紧缺，429 错误频繁，同时也很难抢到

---

## 📊 数据对比 (TL;DR)

| 厂商                             | 价格(mo)      | 官方说明   | TPS  | 模型请求数/Tokens(5h) | 额度价值(5h)   | 额度倍率(5h) | 模型请求数/Tokens(w) | 额度价值(w)    | 额度倍率(w) | 模型请求数/Tokens(mo) | 💰额度价值(mo)     | ⏫额度倍率(mo)  |
|--------------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|---------|-----------|---------|--------|-----------|--------|--------|-------------|---------|
| [Claude Pro](https://claude.ai/upgrade) (Claude Code claude-opus-4.8)       |  $20.00   | 2026-5-6 后 5h 额度翻倍, 5-13 至 8-31 周额度增加 50%（统计数据为额度增加后的统计数据）  | /    | 359/3966万     |  $31.84   | 1.59    | 3590/3.97亿  |  $318.4  |  15.9  | 14360/15.88亿  |  $1273.6       | 63.6   |
| [ChatGPT Plus](https://chatgpt.com/pricing) (Codex gpt-5.6-sol)           |  $20.00 | 45-225 Local Messages* / 5h | /    | /    |  /   | /    | 2190/1.54亿   |  $109.12   | 5.46   | 8760/6.16亿  |  $436.48       | 21.82   |
| [Ollama Pro](https://ollama.com/pricing) |  $20   |   includes $60 of monthly usage |  /   |  /   |  /   |  /   |  /  |  /   |  /  |  / |    $60     |  3  |
| [OpenCode Go](https://opencode.ai/go) |   $10.00 (首月 $5)  | 包含 GLM-5.1, Kimi K2.6, MiMo-V2.5-Pro, DeepSeek V4 Pro, Qwen3.6 Plus 和 MiniMax M2.7 等 | / |   /  |  $12   |  1.2   |  /  |  $30   |  3  |  / |    $60     |  6  |
| [Standard Compute Starter](https://standardcompute.com/pricing) | $19.00 | 每月 $20 平台计算预算，耗尽后暂停请求；兼容 OpenAI Chat Completions 和 Anthropic Messages。预算不是按第三方模型零售价测得的等值额度 | / | / | / | / | / | / | / | / | / | / |
| [OpenRouter](https://openrouter.ai) |  部分模型限免 50 reqs/day   |  hy3-preview/minimax-m2.5/qwen3-coder 等模型限免  |      |         |           |     |        |           |      |     |             |     |
| [NVIDIA NIM](https://build.nvidia.com) (glm-4.7) |  免费   |   deepseek-v4-pro/glm-5.1/glm-4.7/deepseek-v4-flash/minimax-m2.7 等开源模型 Up to 40 rpm 不限量使用  |      |         |           |     |        |           |      |     |             |     |
| [MiniMax Coding Plan Plus](https://platform.minimaxi.com/subscribe/token-plan) （minimax-m2.7）      |  ￥49.00   | 1500次模型调用 / 5 小时（目前已改套餐，该数据为老数据） | 52.6 | 1360/6000万    |  ￥108.60  | 2.22    | 13600/6亿      | ￥1086         | 22.2     | 54400/24亿   |  ￥4344 |   88.65|
| [Kimi Code Andante](https://www.kimi.com/membership/pricing) （kimi-k2.5）             |  ￥49.00   | Kimi Code 可调用| 27.98| 359/1500万     |  ￥21.46   | 0.44    | 639/2100万    |  ￥30.34   | 0.62   | 2556/8400万   |  ￥121.36    | 2.48    |
| [Kimi Code Allegretto](https://www.kimi.com/membership/pricing)（kimi-k2.5）           |  ￥199.00  | Kimi Code 20 倍额度  |  27.98   |  1307/6500万       |    ￥89.67       |    0.45     | 9073/3.57亿   |  ￥492.00  | 2.47   | 36292/14.28亿  |  ￥1,968.00  | 9.89    |
| [阿里云 Coding Plan Lite 基础套餐](https://www.aliyun.com/benefit/scene/codingplan)（已下线, qwen-3.5-plus） |  ￥40.00   | 每月请求额度至高 18,000 次<br/>最多 1,200 次/每 5 小时<br/>最多 9,000 次/每周<br/>最多 18,000 次/每月 | 52.5 | 1179/4000万    |  ￥52.83   | 1.32    | 8842/3亿   |  ￥396.00  | 9.90   | 17684/6亿  |  ￥792.00    | 19.80   |
| [火山方舟 Coding Plan Lite](https://www.volcengine.com/activity/codingplan)（每天 00:00 限量释放库存，售完即止，doubao-seed-2.0-pro）            |  ￥40.00   | 数倍于 Claude Pro plan 的用量 | 86.6 | 148/1000万     |  ￥19.00   | 0.48    | 1138/7500万   |  ￥146.00  | 3.65   | 6275/3.2亿   |  ￥607.00    | 15.18   |
| [GLM Coding Plan Lite](https://bigmodel.cn/glm-coding)（使用海外版订阅测试 glm-5.1）|  ￥49.00   | 3x Claude Pro 用量额度<br/>每 5 小时限额  最多约 80 次 prompts<br/>每周限额 最多约 400 次 prompts |   26.8   |    90/600万     |    ￥11.66       |  0.24   |      600/3200万  |     ￥62.19      |  1.27    |   2400/1.28亿   |       ￥248.76      |   5.08  |
| [GLM Coding Plan Pro](https://bigmodel.cn/glm-coding)（glm-5.1）|  ￥149.00   | 5x Lite 用量额度<br/>最多约 400 次 prompts<br/>最多约 2000 次 prompts |   26.8   |    450/3000万     |    ￥58.3       |  0.39   |      3000/1.6亿  |     ￥310.95      |   2.09   |   12000/6.4亿   |       ￥1243.8      |   8.35  |
| [Fireworks Fire Pass](https://app.fireworks.ai/fire-pass)（kimi-k2.6-turbo）|  $7/w*4   |   with no per-token charges for kimi-k2.6-turbo  |      |         |           |     |        |           |      |     |             |     |
| [Xiaomi MiMo Token Plan Pro](https://platform.xiaomimimo.com/#/token-plan) (mimo-v2.5-pro)|  ￥329.00   | 380亿 Credits 套餐月总量 |   46.7   |         |          |    |        |           |      |   13亿   |      ￥381       |  1.12   |


## 模型参数数据

本测试通过输入约 1 万字的长文本提示词（其中中文占比约 80%）来衡量各模型分词器的性能。
我们以 gpt-5.4 作为 100% 基准，数值越低，代表该模型的分词压缩率越高，在处理长文本时具有更明显的成本优势和响应速度优势。

| 模型 | 发布时间 | 参数量 | 权重大小 (GB) | 上下文长度 | Token 消耗比例 | 满血版最低 GPU 要求 |
| :--- |  :--- | :--- | :--- | :--- | ---: | :--- |
| kimi-k2.5🏞️ | 2026-01-27 | 1T A32B| 554.3 (INT4) |256K| 87.99% | <ul><li>4xB300 288G [对华出口管制]</li><li>8xB200 192G [对华出口管制]</li><li>8xH200 141G</li><li>8x昇腾 910C 128G</li><li>2x8xA100 80G</li></ul> |
| kimi-k2.6🏞️ |  2026-04-20 | 1T A32B| 554.3 (INT4) |256K| 87.99% | <ul><li>4xB300 288G [对华出口管制]</li><li>8xB200 192G [对华出口管制]</li><li>8xH200 141G</li><li>8x昇腾 910C 128G</li><li>2x8xA100 80G</li></ul> |
| kimi-k2.7-code🏞️ |  2026-06-12 | 1T A32B| 554.3 (INT4) |256K| 87.60% |  |
| minimax-m2.7 | 2026-03-18 | 230B A10B | 447.8 | 200K| 89.23% | <ul><li>8xA100 80G</li><li>4xH200 141G</li></ul>  |
| kimi-k3🏞️ |  2026-07-16 | 2.8T A104B | 1453.6 (FP4) | 1M | 90.13% | <ul><li>8xB300 288G [对华出口管制]</li><li>8xMI355X 288G [对华出口管制]</li><li>2x8xH200 141G</li></ul> |
| minimax-m3🏞️ | 2026-06-01 | 428B A23B | 809.5 | 1M | 90.54% |   |
| hy3 | 2026-04-23 | 295B A21B | 556.5 | 256K | 92.22% | <ul><li>8xA100 80G</li><li>8x昇腾 910C 128G</li></ul> |
| gemini-3.1-pro-preview🏞️ | 2026-02-19 | ~3T | | 1M | 92.73% | |
| gemini-3.5-flash🏞️ | 2026-05-20 | ~300B | | 1M | 93.62% | |
| grok-4.20🏞️ | 2026-02-17 | ~500B | | 2M | 94.36% | |
| grok-4.3🏞️ | 2026-04-30 | ~500B | | 1M | 94.36% | |
| deepseek-v3.2 | 2025-12-01 | 685B A37B | 1276.7 | 128K | 95.30% |  |
| deepseek-v4-flash | 2026-04-24 | 284B A13B | 148.6 (FP4) | 1M | 95.30% | <ul><li>1xB300 288G [对华出口管制]</li><li>2xB200 192G [对华出口管制]</li><li>2x昇腾 950PR 128G</li><li>4xH100[FP8] 80G</li></ul> |
| deepseek-v4-pro | 2026-04-24 | 1.6T A49B | 805.3 (FP4) | 1M | 95.30% | <ul><li>4xB300 288G [对华出口管制]</li><li>8xB200 192G [对华出口管制]</li><li>8x昇腾 950PR 128G</li><li>2x8xH200[FP8] 141G</li></ul> |
| glm-4.7 | 2025-12-23 | 355B A32B| 333.7 (FP8) | 200K | 95.93% | <ul><li>8xH100 80G</li><li>4xH200 141G</li><li>2x8xA100[FP16] 80G</li><li>8x昇腾 910C[FP16] 128G</li></ul> |
| glm-5.1 | 2026-04-08 | 744B A40B| 704.2 (FP8) | 200K | 95.93% | <ul><li>8xB200 192G [对华出口管制]</li><li>8xH200 141G</li><li>2x8xH100 80G</li></ul> |
| glm-5.2 | 2026-06-13 | 744B A40B| 703.7（FP8） | 1M | 95.69% | <ul><li>8xB200 192G [对华出口管制]</li><li>8xH200 141G</li><li>2x8xH100 80G</li></ul>  |
| qwen-3.5🏞️ | 2026-02-16 | 397B A17B | 378.2 (FP8) | 1M | 95.97% | <ul><li>8xH100 80G</li><li>4xH200 141G</li><li>2x8xA100[FP16] 80G</li><li>8x昇腾 910C[FP16] 128G</li></ul> |
| qwen-3.6-plus🏞️ | 2026-04-02 | 397B A17B || 1M | 95.97% | |
| qwen-3.7-plus🏞️ | 2026-06-01 | 397B A17B || 1M | 95.38% | |
| muse-spark-1.1🏞️ | 2026-07-16 |  || 1M | 97.36% | |
| grok-4.5🏞️ | 2026-07-09 | ~1.5T || 500K | 99.96% | |
| gpt-5.4🏞️ | 2026-03-05 | ~3T | |1.05M| 100.00% | |
| gpt-5.5🏞️ | 2026-04-24 |  | |1.05M| 100.00% | |
| doubao-seed-evolving🏞️ | 2026-06-23 |  | |1M| 100.94% | |
| mimo-v2.5🏞️ | 2026-04-22 | 310B A15B | 293.4 (FP8) | 1M | 101.18% |<ul><li>8xH100 80G</li><li>4xH200 141G</li><li>2x8xA100[FP16] 80G</li><li>8x昇腾 910C[FP16] 128G</li></ul> |
| mimo-v2.5-pro🏞️ | 2026-04-22 | 1T A42B | 962.4 (FP8)| 1M | 101.18% | <ul><li>8xB200 192G [对华出口管制]</li><li>8xH200 141G</li><li>2x8xH100 80G</li></ul> |
| doubao-seed-2.0-pro🏞️ |2026-02-14| | | 256K| 101.50% | |
| ⚠️claude-sonnet-4.6🏞️ |2026-02-17| ~1T | |1M| 152.86% | |
| ⚠️claude-opus-5🏞️ |2026-07-25|  | |1M| 165.58% | |
| ⚠️claude-opus-4.8🏞️ |2026-05-28|  | |1M| 165.60% | |
| ⚠️claude-fabel-5🏞️ |2026-06-10|  | |1M| 165.60% | |
| ⚠️claude-sonnet-5🏞️ |2026-07-01|  | |1M| 165.96% | |
| ⚠️claude-opus-4.7🏞️ |2026-04-16|~5T | |1M| 166.75% | |
| ⚠️claude-haiku-4.5🏞️ | 2025-10-15 |||200K| 203.96% | |
| ⚠️claude-opus-4.6🏞️ |2026-02-05|~5T||1M| 203.96% | |

*注：🏞️表示属于多模态模型，同时支持文本和图像输入，⚠️表示中文 Tokenizer 压缩率较低*

## AI IDE/Plugin Plan

| 厂商                             | 价格(mo)      | 官方说明   | 备注 | 额度价值(mo)/Tokens     | 额度倍率(mo)  |
|--------------------------------|--------------|------|---------|-----------|---------|
| [Factory Droid Pro](https://factory.ai/pricing) |   $20.00  |   	20 million 	Standard Tokens (10 cached tokens = 1 Standard Token)   |    Usage-based    |     ~$48/~6000万 claude-opus-4.6     |  ~2.4   | 
| [Cursor Pro](https://cursor.com/pricing) |   $20.00  |   $20 of API usage each month<br/>Significantly more included usage when Auto or Composer 2 is selected   |    Usage-based    |      >=$20     |  >=1   | 
| [Windsurf Pro](https://windsurf.com/pricing) |   $20.00 (2 week free trial)  |   plan includes a usage allowance measured as a daily and weekly budget, daily quota is more than 1/7 of your weekly quota<br/>8-101 messages / day for Premium Model<br/>unlimited SWE-1.5      |   Quota-based     |           |     |         
| ⚠️[Kiro Pro](https://kiro.dev/pricing) |   $20.00 (新注册首月免费，退出付款页丢失免费资格) |   1,000 credits<br/>Pay-per-use overage ($0.04/credit)<br/>Get 500 bonus credits usable within 30 days when you first sign up    |    Usage-based    |     $40.00      |   2  | 
| [Augment Code INDIE](https://www.augmentcode.com/pricing) |   $20.00  |   Includes 40,000 credits    |     Usage-based          |  $25.00   |   1.25     |             
| [Qoder Pro](https://qoder.com/pricing) |   $20.00（为期 2 周的 Pro 试用及 300 Credits）  | 2,000 Credits<br/>更多的对话与智能体请求数   |   Usage-based     |          |     |  
| [Antigravity in Google AI Pro](https://antigravity.google/pricing)<br/><br/>[Gemini Code Assist/Gemini CLI in Google AI Pro](https://codeassist.google/)  |   $19.99（Pixel 手机用户免费试用一年  |   **Antigravity**<br/>High, generous quota, refreshed every five hours until weekly limit reached<br/>Higher weekly rate limit<br/>Free: 50 AI credits/d<br/>Google AI Plus $7.99: 200 AI credits/mo<br/>Google AI Pro $19.99: 1,000 AI credits/mo<br/>Google AI Ultra $249.99: 25,000 AI credits/mo<br/><br/>**Gemini Code Assist/Gemini CLI**<br/>On June 18, 2026, Gemini CLI and Gemini Code Assist IDE extensions will stop serving requests for Google AI Pro and Ultra, as well as those using it free of charge using Gemini Code Assist for individuals.<br/>Maximum requests per user per day<br/>Free: 1000/d<br/>Google AI Pro $19.99: 1500/d<br/>Google AI Ultra $249.99: 2000/d    |   Quota-based     |           |     |  
| [Kilo Pass Starter](https://kilo.ai/pricing) |   $19.00  |  Up to 40% bonus credits |   Usage-based     |     ~$26.6      |    1.4 |   
| [Trae Pro](https://www.trae.ai/pricing) |   $10.00 (Free for 7 days)  |   $20 Basic usage + Bonus usage<br/>Unlimited Autocomplete     |     Usage-based       |   $20.00 + 随机赠送 Bonus（有反馈收到 $130）  |    >2    |  
| [GitHub Copilot Pro](https://github.com/features/copilot/plans) |   $10.00  |   $15 monthly total credits for Pro    |   Usage-based     |   $15   |    1.5    |          
| [Zed Pro](https://zed.dev/pricing) |   $10.00  |    Unlimited edit predictions<br/>$5 of tokens included<br/>Usage-based billing beyond $5<br/>14-day free trial. No credit card required.    |   Usage-based     |     $5.00/440万 Claude Sonnet 4.6      |   0.5  | 
| [CodeBuddy 个人专业版](https://www.codebuddy.cn/pricing) |   ￥59.00  |    每月 2000 Credits（含体验版 500 Credits）<br/>限时活动：下单当月同时加赠 2000 Credits 一次性到账（赠送部分有效期为自到账日起1个月）    |     Usage-based       |    |        | 

## 非严谨能力测试

找了一个 gemini-3.5-flash 一个关于网络代理协议不匹配 BUG 解决失败的烂摊子让其他模型接手修复，以下是各个模型的完成情况：

| 模型                          | Agent Harness | Tokens     | 成本 ($) | 耗时      | 通过率                              |
| --------------------------- | ------------- | ---------- | ------ | ------- | -------------------------------- |
| deepseek-v4-flash-0731 high | opencode      | 5,324,169  | 0.04   | 12min   | ✅3/3                             |
| grok-4.5 high               | grok build    | 1,005,853  | ~0.5   | 2min    | ✅3/3                             |
| gpt-5.6-sol high            | codex         | 1,004,195  | 1.09   | 11min   | ✅3/3                             |
| claude-opus-4.8 high        | claude code   | 2,008,418  | 2.60   | 9min    | ✅3/3                             |
| deepseek-v4-pro-0813        | opencode      | 6,096,418  | 0.11   | 18min   | ⚠️2/3                            |
| claude-opus-5 high          | claude code   | 2,396,381  | 3.08   | 10min   | ⚠️2/3                            |
| gpt-5.6-terra high          | codex         | 590,028    | 0.50   | 5min    | ⚠️2/3                            |
| gpt-5.5 high                | codex         | 1,072,688  | 1.29   | 6min    | ⚠️2/3                            |
| claude-fabel-5 high         | claude code   | 3,482,397  | 8.25   | 18min   | ⚠️2/3                            |
| qwen-3.8-max high           | opencode      | 20,869,362 | 8.42   | 1h24min | 1/1 暂时只测试了一轮，由于 token 效率极低，没继续测试 |
| gpt-5.6-luna high           | codex         | 1,321,527  | 0.40   | 7min    | ❌1/3                             |
| kimi-k3                     | opencode      | 2,228,706  | 1.47   | 28min   | ❌1/3                             |
| kimi-k2.7-code              | opencode      | 4,051,232  | 0.94   | 15min   | ❌1/3                             |
| deepseek-v4-pro max         | opencode      | 591,738    | 0.05   | 5min    | ❌0/3                             |
| claude-sonnet-5 high        | claude code   | 1,070,526  | 0.56   | 5min    | ❌0/3                             |
| gpt-5.4 high                | codex         | 2,879,757  | 1.60   | 12min   | ❌0/3                             |
| glm-5.2 max                 | opencode      | 8,145,637  | 2.62   | 42min   | ❌0/3                             |
| qwen-3.7-max                | opencode      | 401,720    | 0.49   | 3min    | ❌0/3                             |

*通过该场景可在一定程度侧面反映模型解决问题的能力，作为日常编码模型选择参考，测试轮次不够多，部分模型效果评估可能存在偏差*

---

*如果你也在做 Agent Harness 研究，可以关注我的另外一个项目 [Awesome Agent Harness](https://github.com/mahonzhan/awesome-agent-harness)*
