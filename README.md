<!-- README.md -->
# 🇨🇳 TeslaMate-CN-Docker 

[![Docker Version](https://img.shields.io/badge/docker-%3E%3D%2020.10-brightgreen)](https://docs.docker.com/) 
[![Map Proxy](https://img.shields.io/badge/map-proxy-brightgreen)](https://openstreetmap.org)
[![GitHub stars](https://img.shields.io/github/stars/gococonut/teslamate-cn-docker?style=social)](https://github.com/yourname/teslamate-cn-docker)

> 中国大陆可用的TeslaMate容器化方案 teslamate 汉化  teslamate 中文| TeslaMate Docker Solution for Mainland China


## 🌟 特性 Features
- ✅ ​**完整汉化** - 界面/文档/时间格式全面中文化  
- 🗺️ ​**地图访问** - 内置代理服务器解决OpenStreetMap访问问题
- 🚀 ​**零外部依赖** - 无需第三方地图API密钥
- 🐳 ​**一键部署** - Docker Compose全自动配置
- 📍 ​**区域优化** - 时区(Asia/Shanghai)/充电站名称/单位制式本地化

## 🚀 快速启动 Quick Start

### 前置要求 Prerequisites
- Docker 20.10+
- Docker Compose 2.12+
- Tesla账户API凭证

### 部署步骤 Deployment
```bash
# 克隆仓库
git clone https://github.com/gococonut/teslamate-cn-docker.git
cd teslamate-cn-docker

# 配置环境变量
cp .env.example .env
nano .env  # 修改环境变量

# 启动服务
docker-compose up -d
