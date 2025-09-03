---
title: "Ollama - Self-hosted Multi Language Model"
description: "Dual-PC self-hosted server infrastructure for LLM deployment and networking study"
showDate: true
date: "2024-12-01"
showAuthor: true
showReadingTime: true
tags: ["Ubuntu Server", "Cloudflare", "Docker", "Prometheus", "Grafana", "Ollama"]
---

## Project Overview

**Duration:** 12 months  
**Team:** Solo project  
**Purpose:** Networking study and self-hosted AI infrastructure

## Tech Stack

**Operating System:** Ubuntu Server  
**Containerization:** Docker  
**Networking:** Cloudflare Tunnel  
**Monitoring:** Prometheus, Grafana  
**AI Platform:** Ollama

## Architecture

Built a dual-PC infrastructure optimizing for both energy efficiency and computational power:

- **Low-Energy PC** - Hosts website via Cloudflare tunnel with personal domain
- **High-Energy Server** - Handles compute-intensive tasks including large language models

## Key Features

- 🖥️ **Dual-PC Setup** - Optimized resource allocation between networking and computing
- 🐳 **Full Containerization** - All services Dockerized for efficient management
- 🔄 **Auto-Restart** - Automatic service recovery and management
- 📊 **Performance Monitoring** - Real-time metrics with Prometheus
- 📈 **Log Visualization** - Streamlined analysis through Grafana dashboards
- 🌐 **Secure Access** - Cloudflare tunnel integration with personal domain

## Technical Implementation

- Containerized website, Cloudflare tunnel, and LLM services
- Implemented comprehensive monitoring stack for performance tracking
- Configured automated restart mechanisms for service reliability
- Established secure remote access through Cloudflare infrastructure

## Learning Outcomes

- Advanced networking concepts and tunnel configuration
- Container orchestration and service management
- Infrastructure monitoring and observability
- Self-hosted AI deployment strategies
- Energy-efficient server architecture design