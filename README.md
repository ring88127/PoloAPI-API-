# 🍥 PoloAPI — 新一代大模型网关与AI资产管理系统

Release | 构建状态 | GoReportCard  
:--|:--|:--  
✅ 稳定版发布 | 🐳 Docker 支持 | 🧩 代码质量优秀  

## 📝 项目说明
> PoloAPI 是在 One API 的基础上二次开发的企业级大模型聚合与管理系统。  
> 集成了主流 AI 模型（OpenAI、Claude、Gemini、DeepSeek 等）及多渠道负载能力，  
> 帮助开发者与企业轻松搭建多模态 AI 服务网关与资产管理系统。

## ⚠️ 注意事项
- 本项目仅供学习研究使用，不保证稳定性，也不提供任何技术支持。  
- 使用者必须遵守 OpenAI 使用条款 和相关法律法规。  
- 根据《生成式人工智能服务管理暂行办法》，请勿向中国地区公众提供未经备案的生成式AI服务。

## 🤝 合作伙伴
Cherry Studio · 北京大学 · UCloud 优刻得 · 阿里云 · IO.NET

## 📚 文档资源
https://docs.poloapi.com  
🤖 Ask DeepWiki

## ✨ 主要特性
- 🎨 全新UI与多语言支持  
- 💳 在线计费与充值  
- 🔐 模型与令牌管理  
- ⚡ 接口格式兼容（OpenAI / Claude / Gemini）  
- 💰 缓存计费与自动重试  
- 📈 数据看板与统计分析  
- 🤖 全面模型支持（Claude, GPT, Gemini, Cohere, Jina, Midjourney 等）

## ⚙️ 环境变量配置
| 变量 | 功能 | 默认值 |
|------|------|--------|
| GENERATE_DEFAULT_TOKEN | 是否生成默认令牌 | false |
| STREAMING_TIMEOUT | 流式超时 | 300 |
| CRYPTO_SECRET | Redis 加密密钥 | — |
| AZURE_DEFAULT_API_VERSION | Azure 默认版本 | 2025-04-01-preview |

## 🚀 部署方式
### 使用 Docker Compose
`bash
git clone https://github.com/poloapi/poloapi.git
cd poloapi
docker-compose up -d`
### 使用 Docker 镜像
`bash
docker run --name poloapi -d --restart always \
-p 3000:3000 -e TZ=Asia/Shanghai \
-v /home/ubuntu/data/poloapi:/data \
poloapi/poloapi:latest`
### 🌟 关于 PoloAPI
PoloAPI 是一个强大的 AI API 聚合平台，专注于提供稳定、高效的 API 连接与管理服务。
了解更多请访问官网：https://www.poloapi.com
