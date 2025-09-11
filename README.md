<!-- README.md -->

# 🇨🇳 TeslaMate-CN-Docker

[![Docker Version](https://img.shields.io/badge/docker-%3E%3D%2020.10-brightgreen)](https://docs.docker.com/)
[![Map Proxy](https://img.shields.io/badge/map-proxy-brightgreen)](https://openstreetmap.org)
[![GitHub stars](https://img.shields.io/github/stars/gococonut/teslamate-cn-docker?style=social)](https://github.com/yourname/teslamate-cn-docker)

> 中国大陆可用的 TeslaMate 容器化方案 Teslamate 汉化 Teslamate 中文| TeslaMate Docker Solution for Mainland China

> [镜像 Repository](https://github.com/gococonut/teslamate)

## 🌟 特性 Features

- ✅ ​**完整汉化** - 界面全面中文化（汉化中）
- 🗺️ ​**地图访问** - 内置代理服务器解决 OpenStreetMap 访问问题
- 🗺️ ​**百度地图** - 支持百度地址逆地址解析，车辆位置信息更精准
- 🐳 ​**一键部署** - Docker Compose 一键部署

## 🚀 快速启动 Quick Start


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

### 

想记录分析特斯拉数据？可以  https://portal.mytesla.cc/login 体验一下，包含当前车辆状态，驾驶，停车，充电数据，电池健康度，并支持峰谷用电自动记录充电费用，车辆状态实时通知。

1️⃣ 新手用户：推荐即插即用的 Mytesla 数据伴侣，有问题随时问。 https://xhslink.com/m/4Vz6aOcb86w

2️⃣ 爱折腾的高手：关于 Teslamate 的部署（NAS/云）或使用问题。

家里部署参考：https://zhuanlan.zhihu.com/p/1943713771001455217
云服务器部署：https://zhuanlan.zhihu.com/p/1941504471587858269
