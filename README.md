# 汪硕 · Shuo Wang

软件工程在读（武汉学院，2028 届），方向是**大模型应用开发**。
偏好把重复工作封装成可复用工具，也偏好把大模型跑在本地、数据不出机器。

## 技术方向

- **大模型应用开发**：LangChain / Prompt Engineering / JSON Schema 结构化输出
- **RAG 检索增强**：文档加载与分割 / Embedding 向量化 / 余弦相似度检索 / 向量存储
- **AI Agent**：ReAct 行动框架 / middleware 中间件 / tools 工具开发
- **本地推理部署**：Ollama（qwen2.5:7b）/ OpenAI 兼容 API

## 技术栈

```
Python · C · SQL
LangChain · Ollama · Streamlit · Gradio
openpyxl · Git / GitHub
```

## 项目

### [JobMatch AI](https://github.com/97-sc/jobmatch-ai) — 本地大模型求职匹配助手

输入岗位 JD 与个人简历，自动输出匹配度评分（0-100）、已匹配 / 缺失技能清单与针对性改进建议，
并一键生成可下载求职信。全程基于 Ollama 本地推理，简历数据不出本机；
用 JSON Schema 约束模型输出，保证评分与建议稳定可解析。

`Python` `Streamlit` `Ollama` `JSON Schema`

### [OpenManus 二次开发](https://github.com/97-sc/OpenManus) — AI 智能体财报分析系统

基于开源 Agent 框架 OpenManus 的本地化二次开发，新增简体中文提示词、Gradio Web UI，
以及自研 FinancialReportTool——自动计算毛利率、净利率、ROE、ROA、资产负债率、流动比率、
速动比率等 7 项财务指标，支持多期对比并生成 Markdown 分析报告。

`Python` `OpenManus` `Gradio` `openpyxl`

## 证书

HCIA-AI 华为认证人工智能工程师 · HarmonyOS 应用开发者（基础 + 高级） · 软考初级信息处理技术员

## 联系

- Email：3552978352@qq.com
- 地点：湖北武汉
