# 🚀 Awesome Coding Plan

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

> 各大模型/云厂商 Coding Plan 实际价值对比

> *注：本文不会讨论模型的具体智力水平，只建议使用各家的旗舰模型，且如果有数据安全性要求，不允许数据被用于训练，不建议购买 Coding Plan*

## 📖 术语说明

- **周期**：`5h` = 5小时 | `w` = 周 | `mo` = 月
- **额度倍率**：`当前周期额度 ÷ 包月价格`（认可该模型单位定价的前提下，倍率越高，代表性价比越高）

---

## 💡 核心选购建议

- 🎁 **个人想免费白嫖: `NVIDIA NIM`**
  - **特点**：glm-5/glm-4.7/minimax-m2.7 等开源模型，速率限制 Up to 40 rpm 速度无保证，不限量免费使用 [点此直达](https://build.nvidia.com/) 
  - **劣势**：无稳定性保证，首Token时间通常较高，速度因模型而异，部分模型为量化版本，注意甄别，免费不可持续

- 🏆 **养龙虾性价比首选：`MiniMax Coding Plan Plus` (￥49/月)**
  - **特点**：目前最实惠、额度限制最小、倍率最高，套餐包含 TTS 和图像生成（个人 ￥29 Starter 够用，但没有 TTS 和图像生成）
  - **劣势**：MiniMax M2.7 和 GLM 5.1 一样，并不是多模态模型，只支持文本输入
  
- 👥 **开发团队推荐：`Kimi Code Allegretto` (￥199/月)**
  - **特点**：支持多模态（图像输入），模型代码能力更优，较高强度的日常开发够用，送专属龙虾；如果团队使用量增加，可多买几个 ￥199 套餐，或升级至 ￥699 套餐（不如买 3 个 ￥199 套餐划算）
  - **劣势**：¥49 套餐毫无性价比，¥199 套餐倍率也一般

---

## 📊 数据对比 (TL;DR)

| 厂商                             | 价格(mo)      | 官方说明   | TPS  | 模型请求数/Tokens(5h) | 额度价值(5h)   | 额度倍率(5h) | 模型请求数/Tokens(w) | 额度价值(w)    | 额度倍率(w) | 模型请求数/Tokens(mo) | 额度价值(mo)     | 额度倍率(mo)  |
|--------------------------------|-----------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|------|---------|-----------|---------|--------|-----------|--------|--------|-------------|---------|
| Claude Pro (Claude Code claude-sonnet-4.6)       |  $20.00   |   <mark>测试期间有 2x 额度活动，3月28日活动已截止</mark> | /    | 706/2200万     |  $13.69   | 0.68    | 5650/1.8亿   |  $109.50  | 5.48   | 22600/7.2亿  |  $438       | 21.90   |
| ChatGPT Plus (Codex gpt-5.4)           |  $20.00   | 45-225 Local Messages* / 5h | /    | 490/2000万    |  $11.85   | 0.59    | 3062/1.2亿   |  $74   | 3.7   | 12250/4.8亿  |  $296       | 14.8   |
| NVIDIA NIM (glm-4.7) |  免费   |   glm-5/glm-4.7/minimax-m2.7 等开源模型 Up to 40 rpm 不限量使用  |      |         |           |     |        |           |      |     |             |     |
| MiniMax Coding Plan Plus （minimax-m2.7）      |  ￥49.00   | 1500次模型调用 / 5 小时 | 52.6 | 1360/6000万    |  ￥108.60  | 2.22    | 13600/6亿      | ￥1086         | 22.2     | 54400/24亿   |  ￥4344 |   88.65|
| Kimi Code Andante （kimi-k2.5）             |  ￥49.00   | Kimi Code 可调用| 40.6 | 359/1500万     |  ￥21.46   | 0.44    | 639/2100万    |  ￥30.34   | 0.62   | 2556/8400万   |  ￥121.36    | 2.48    |
| Kimi Code Allegretto（kimi-k2.5）           |  ￥199.00  | Kimi Code 20 倍额度  |  40.6    |  1307/6500万       |    ￥89.67       |    0.45     | 9073/3.57亿   |  ￥492.00  | 2.47   | 36292/14.28亿  |  ￥1,968.00  | 9.89    |
| 阿里云 Coding Plan Lite 基础套餐（已下线, qwen-3.5-plus） |  ￥40.00   | 每月请求额度至高 18,000 次<br/>最多 1,200 次/每 5 小时<br/>最多 9,000 次/每周<br/>最多 18,000 次/每月 | 52.5 | 1179/4000万    |  ￥52.83   | 1.32    | 8842/3亿   |  ￥396.00  | 9.90   | 17684/6亿  |  ￥792.00    | 19.80   |
| 火山方舟 Coding Plan Lite（doubao-seed-2.0-pro）            |  ￥40.00   | 数倍于 Claude Pro plan 的用量 | 86.6 | 148/1000万     |  ￥19.00   | 0.48    | 1138/7500万   |  ￥146.00  | 3.65   | 6275/3.2亿   |  ￥607.00    | 15.18   |
| GLM Coding Plan Lite（使用海外版订阅测试 glm-5.1）|  ￥49.00   | 3x Claude Pro 用量额度<br/>每 5 小时限额  最多约 80 次 prompts<br/>每周限额 最多约 400 次 prompts |   26.8   |    90/600万     |    ￥11.66       |  0.24   |      600/3200万  |     ￥62.19      |  1.27    |   2400/1.28亿   |       ￥248.76      |   5.08  |
| Fireworks Fire Pass（kimi-k2.5-turbo）|  $7/w*4   |   with no per-token charges for kimi-k2.5-turbo  |      |         |           |     |        |           |      |     |             |     |
| Xiaomi MiMo Token Plan Lite（非实测数据） |  ￥39.00   | 60,000,000 Credits 套餐月总量<br/>MiMo-V2-Pro 256k 上下文： 2x（消耗 1 Token = 2 Credits） |      |    /     |    /       |  /   |      /  |     /      |  /    |   ?/3000万   |      ?       |  ?   |


*说明：所有数据基于 3 月下旬针对该 Coding Plan 中的旗舰模型测试，价值评估目标为国产模型，Claude 和 ChatGPT 仅用于对比参考基线。*

## Tokenizer 效率评测 (中英混合场景)

本测试通过输入约 1 万字的长文本提示词（其中中文占比约 80%）来衡量各模型分词器的性能。
我们以 gpt-5.4 作为 100% 基准，数值越低，代表该模型的分词压缩率越高，在处理长文本时具有更明显的成本优势和响应速度优势。

| 模型 | 参数量 | 上下文长度 | Token 消耗比例 |
| :--- | :--- | :--- | ---: |
| kimi-k2.5🏞️ |1T A32B| 256K| 87.99% |
| gemini-3.1-pro-preview🏞️ || 1M | 92.73% |
| deepseek-v3.2 | 671B A37B | 128K | 95.30% |
| glm-5.1 |744B A40B| 200K | 95.93% |
| qwen-3.5-plus🏞️ |397B A17B| 1M | 95.97% |
| gpt-5.4🏞️ ||1.05M| 100.00% |
| mimo-v2-pro🏞️ |1T A42B|1M| 101.18% |
| doubao-seed-2.0-pro🏞️ ||256K| 101.50% |
| ⚠️claude-sonnet-4.6🏞️ ||1M| 154.11% |
| ⚠️minimax-m2.7 |230B A10B|200K| 179.67% |

*注：🏞️表示属于多模态模型，同时支持文本和图像输入，⚠️表示中文 Tokenizer 压缩率较低*

## AI IDE/CLI Plan

| 厂商                             | 价格(mo)      | 官方说明   | 备注 | 额度价值(mo)/Tokens     | 额度倍率(mo)  |
|--------------------------------|--------------|------|---------|-----------|---------|
| Factory Droid Pro |   $20.00  |   	20 million 	Standard Tokens (10 cached tokens = 1 Standard Token)   |    Usage-based    |     ~$48/~6000万 claude-opus-4.6     |  ~2.4   | 
| Cursor Pro |   $20.00  |   $20 of API usage each month<br/>Significantly more included usage when Auto or Composer 2 is selected   |    Usage-based    |      >=$20     |  >=1   | 
| Windsurf Pro |   $20.00  |   plan includes a usage allowance measured as a daily and weekly budget, daily quota is more than 1/7 of your weekly quota<br/>8-101 messages / day for Premium Model<br/>unlimited SWE-1.5      |   Quota-based     |           |     |         
| Augment Code INDIE |   $20.00  |   Includes 40,000 credits    |     Usage-based          |  $25.00   |   1.25     |         
| Kiro Pro |   $20.00  |   1,000 credits<br/>Pay-per-use overage ($0.04/credit)    |    Task-based    |     $40.00      |   2  |     
| Qoder Pro |   $20.00（限时 50% 折扣）  | 2,000 Credits<br/>更多的对话与智能体请求数   |   Usage-based     |          |     |  
| Antigravity Google AI Pro |   $19.99  |   High, generous quota, refreshed every five hours until weekly limit reached<br/>Higher weekly rate limit<br/>Google AI Plus $7.99: 200 AI credits<br/>Google AI Pro $19.99: 1,000 AI credits<br/>Google AI Ultra $249.99: 25,000 AI credits    |   Quota-based     |           |     |   
| Kilo Pass Starter |   $19.00  |  Up to 40% bonus credits |   Usage-based     |     ~$26.6      |    1.4 |   
| OpenCode Go |   $10.00  | $12.00/5h<br/>$30.00/w<br/>$60.00/mo<br/>包含 GLM-5.1, GLM-5, Kimi K2.5, MiMo-V2-Pro, MiMo-V2-Omni, MiniMax M2.5 和 MiniMax M2.7 | Quota-based | $60.00 | 6 |
| GitHub Copilot Pro |   $10.00  |   300 premium requests to use latest models, with the option to buy more<br/>Unlimited agent mode and chats with GPT-5 mini2<br/>Unlimited inline suggestions    |    1x 模型每条消息 $0.04，$12 内免费，Message-based    |   >>$12   |    >>1.2    |          
| Zed Pro |   $10.00  |    Unlimited edit predictions<br/>$5 of tokens included<br/>Usage-based billing beyond $5    |   Usage-based     |     $5.00/440万 Claude Sonnet 4.6      |   0.5  | 
| Trae Pro |   $10.00  |   $20 Basic usage + Bonus usage<br/>Unlimited Autocomplete     |     Usage-based       |   $20.00  |    2    |      
| CodeBuddy 个人专业版 |   ￥59.00  |    每月 2000 Credits（含体验版 500 Credits）    |     Usage-based       |    |        | 
