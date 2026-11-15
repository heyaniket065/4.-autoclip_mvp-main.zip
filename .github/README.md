<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=18,22,28&height=200&section=header&text=AutoClip%20AI%20Pipeline&fontSize=42&fontAlignY=35&animation=twinkling&fontColor=ffffff" width="100%" />

  <h3>🎬 AI-Powered Intelligent Video Slicing & Collection Recommendation System</h3>

  <p>
    <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/React-TypeScript-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" />
  </p>

  <p>
    <img src="https://img.shields.io/github/stars/heyaniket065/4.-autoclip_mvp-main.zip?style=social" />
    <img src="https://img.shields.io/github/forks/heyaniket065/4.-autoclip_mvp-main.zip?style=social" />
    <img src="https://img.shields.io/badge/AI_Models-Qwen_%2B_SiliconFlow-8A2BE2?style=flat-square" />
  </p>

</div>

> 🚨 **Notice / Project Archive**
>
> This repository (`autoclip_mvp`) is the early MVP edition preserved for development and self-hosting workflows.  
> Upstream repository reference: **[autoclip](https://github.com/zhouxiaoka/autoclip)**

---

# AutoClip - Intelligent Video Clipping Tool

🎬 An AI-based intelligent video slicing and collection recommendation system supporting automated Bilibili video downloading, subtitle extraction, smart AI clipping, and highlight collection generation.

## 📋 Version Changelog

### v1.1.1 (2025-08-17)
- 🐳 **One-Click Docker Deployment**: Containerized deployment support to simplify environment setup
- 🚀 **Multi-Stage Builds**: Optimized Docker image size for faster build times
- 🔧 **Production Environment Support**: Production-ready Docker configurations and deployment scripts
- 📦 **Data Persistence**: Data volume mounting support to ensure media and project safety
- 🛡️ **Health Checks**: Integrated container health checks for higher service reliability
- 📚 **Deployment Documentation**: Comprehensive Docker deployment guide and quick-start documentation

### v1.1.0 (2025-08-03)
- ✨ **SiliconFlow API Support**: Added SiliconFlow as an AI service provider
- 🔧 **Multi-API Provider Support**: Supports both Alibaba Qwen (DashScope) and SiliconFlow AI services
- 🎯 **Smart API Selection**: Automatically selects the configured AI provider dynamically
- 📝 **Configuration Optimization**: Added flexible API provider switching options
- 🐛 **Bug Fixes**: Fixed API connection testing issues

### v1.0.0 (2025-07)
- 🎉 **Initial Release**: Complete intelligent video slicing system
- 🔥 **Core Features**: AI video content analysis, smart clipping, and collection recommendations
- 📺 **Bilibili Integration**: Automated Bilibili video and subtitle downloading
- 🎨 **Web Interface**: Modern React + Ant Design frontend dashboard
- ⚡ **Real-Time Processing**: Live progress tracking and processing logs

---

## ✨ Key Features

- 🔥 **Smart AI Video Slicing**: Analyzes video transcripts using AI to automatically generate high-retention clips
- 📺 **Bilibili Video Downloader**: Built-in automated video and subtitle extraction from Bilibili links
- 🎯 **Smart Collection Recommendations**: AI analyzes clip topics and groups related clips into thematic collections
- 🎨 **Manual Collection Editor**: Drag-and-drop sorting, adding, or removing clips inside collections
- 📦 **One-Click Batch Export**: Package and download all generated clips and collections as a single ZIP archive
- 🌐 **Modern Web UI**: Built with React, TypeScript, and Ant Design
- ⚡ **Live Status & Logs**: Real-time pipeline execution status and detailed logs

---

## 🚀 Quick Start

### System Requirements

#### Development Environment
- Python 3.8+
- Node.js 16+
- AI Service API Key (DashScope / Qwen or SiliconFlow)

#### Docker Deployment (Recommended)
- Docker 20.10+
- Docker Compose 2.0+
- AI Service API Key (DashScope / Qwen or SiliconFlow)

---

### Installation Steps

#### 🐳 Docker Deployment (Recommended)

**One-click deployment without complex environment setup:**

```bash
# 1. Clone the repository
git clone [https://github.com/heyaniket065/4.-autoclip_mvp-main.zip.git](https://github.com/heyaniket065/4.-autoclip_mvp-main.zip.git)
cd 4.-autoclip_mvp-main.zip

# 2. Configure environment variables
cp env.example .env
# Edit .env and add your AI API key

# 3. Run one-click deployment
./docker-deploy.sh
