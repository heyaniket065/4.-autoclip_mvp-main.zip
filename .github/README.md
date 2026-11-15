<div align="center">

  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=18,22,28&height=200&section=header&text=AutoClip%20AI%20Pipeline&fontSize=42&fontAlignY=35&animation=blinking&fontColor=ffffff" width="100%" />

  <h3>🎬 AI-Powered Intelligent Video Slicing & Collection Recommendation System</h3>

  <p>
    <img src="https://img.shields.io/badge/Python-3.8+-3776AB?style=for-the-badge&logo=python&logoColor=white" />
    <img src="https://img.shields.io/badge/React-TypeScript-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
    <img src="https://img.shields.io/badge/FastAPI-009688?style=for-the-badge&logo=fastapi&logoColor=white" />
    <img src="https://img.shields.io/badge/Docker-Ready-2496ED?style=for-the-badge&logo=docker&logoColor=white" />
    <img src="https://img.shields.io/badge/License-MIT-success?style=for-the-badge" />
  </p>

  <p>
    <img src="https://img.shields.io/github/stars/heyaniket065/4.-autoclip_mvp-main.zip?style=social" />
    <img src="https://img.shields.io/github/forks/heyaniket065/4.-autoclip_mvp-main.zip?style=social" />
    <img src="https://img.shields.io/badge/Maintained%20by-Aniket%20Bhalerao-blueviolet?style=flat-square" />
  </p>

</div>

---

## 📖 Overview

**AutoClip** is an end-to-end AI-driven video slicing and collection recommendation platform. It supports automated video downloading, subtitle extraction, LLM-powered highlight scoring, smart video clipping, and automated compilation generation with a modern web interface.

---

## 📋 Version Changelog

### v1.1.1 (2025-08-17)
- 🐳 **One-Click Docker Deployment**: Containerized deployment support to simplify environment setup.
- 🚀 **Multi-Stage Builds**: Optimized Docker image size for faster builds.
- 🔧 **Production Support**: Production-ready Docker configurations and deployment scripts.
- 📦 **Data Persistence**: Volume mounting support to keep processed clips and data safe.
- 🛡️ **Health Checks**: Integrated container health checks for improved service reliability.
- 📚 **Deployment Docs**: Comprehensive Docker deployment guide and quick-start documentation.

### v1.1.0 (2025-08-03)
- ✨ **SiliconFlow API Support**: Added support for SiliconFlow as an AI model provider.
- 🔧 **Multi-API Provider Support**: Switch seamlessly between DashScope (Qwen) and SiliconFlow.
- 🎯 **Smart API Selection**: Automatically routes requests to the configured AI provider.
- 📝 **Configuration Optimization**: Added dynamic API provider switching options.
- 🐛 **Bug Fixes**: Resolved API connection testing issues.

### v1.0.0 (2025-07)
- 🎉 **Initial Release**: Complete AI-powered video slicing pipeline.
- 🔥 **Core Features**: AI video content analysis, smart clipping, and collection clustering.
- 📺 **Video & Subtitle Downloader**: Automated video and SRT subtitle extraction.
- 🎨 **Web Dashboard**: Modern React + TypeScript + Ant Design frontend.
- ⚡ **Real-Time Processing**: Live progress tracking and processing logs.

---

## ✨ Key Features

- 🔥 **Intelligent Video Slicing**: Analyzes video transcripts with AI to extract high-retention clips automatically.
- 📺 **Automated Video & Subtitle Fetching**: Supports direct video download and subtitle extraction.
- 🎯 **Smart Collection Recommendations**: AI clusters related clips into thematic compilations.
- 🎨 **Manual Collection Editor**: Drag-and-drop clip reordering, plus adding or removing clips manually.
- 📦 **One-Click Batch Export**: Package and download all generated clips and collections in a single ZIP archive.
- 🌐 **Modern Web UI**: Built with React, TypeScript, and Ant Design.
- ⚡ **Live Status & Logs**: Real-time pipeline progress and execution monitoring.

---

## 🚀 Quick Start

### Prerequisites

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

#### 🐳 Option 1: Docker Deployment (Recommended)

Deploy in minutes without manual dependency configuration:

```bash
# 1. Clone the repository
git clone [https://github.com/heyaniket065/4.-autoclip_mvp-main.zip.git](https://github.com/heyaniket065/4.-autoclip_mvp-main.zip.git)
cd 4.-autoclip_mvp-main.zip

# 2. Configure environment variables
cp env.example .env
# Edit .env and add your AI API keys

# 3. Run one-click deployment
./docker-deploy.sh
