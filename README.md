<!-- README.md -->

# 🇨🇳 TeslaMate-CN-Docker

[![Docker Version](https://img.shields.io/badge/docker-%3E%3D%2020.10-brightgreen)](https://docs.docker.com/)
[![Map Proxy](https://img.shields.io/badge/map-proxy-brightgreen)](https://openstreetmap.org)
[![GitHub stars](https://img.shields.io/github/stars/gococonut/teslamate-cn-docker?style=social)](https://github.com/yourname/teslamate-cn-docker)

> 中国大陆可用的 TeslaMate 容器化方案 Teslamate 汉化 Teslamate 中文| TeslaMate Docker Solution for Mainland China

> [镜像 Repository](https://github.com/gococonut/teslamate)

## 🌟 特性 Features

- ✅ ​**完整汉化** - 界面全面中文化
- 🗺️ ​**地图访问** - 内置代理服务器解决 OpenStreetMap 访问问题
- 🗺️ ​**百度地图** - 支持百度地址逆地址解析，车辆位置信息更精准
- 🐳 ​**一键部署** - Docker Compose 一键部署

## 🚀 快速启动 Quick Start

### 前置要求 Prerequisites

- Docker 20.10+
- Docker Compose 2.12+
- Tesla 账户 API 凭证

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
```
