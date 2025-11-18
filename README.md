# Bopkit Status

[![Uptime](https://img.shields.io/badge/status-operational-success)](https://status.bopkit.com)

Real-time status and uptime monitoring for Bopkit services.

## 📊 [View Live Status Page →](https://status.bopkit.com)

### What We Monitor

This repository monitors the health and availability of all critical Bopkit services through automated uptime checks:

#### 🏥 Health & Readiness Checks

- **✅ System Health** - Overall system health endpoint (`/api/healthz`)
- **🚀 Service Readiness** - Service readiness and availability (`/api/readyz`)

#### 🛠️ Core Components

- **🗄️ Database** - Database connectivity and performance
- **📧 Email Notifications** - Email service functionality
- **🎥 Video Processing** - FFmpeg video processing capabilities
- **🌐 Website** - Frontend application availability
- **🔑 Sign In / Authentication** - Google OAuth authentication services
- **🔄 Background Jobs** - Inngest background job processing
- **💳 Payment Processing** - PayPal payment integration
- **🎨 Image Processing** - Sharp image manipulation services
- **💾 Storage & Media** - Supabase storage and media delivery
- **📹 YouTube Integration** - YouTube API integration

### About

This status page uses GitHub Actions to automatically monitor service endpoints and update the status page. All monitoring data is stored in this repository, providing full transparency and historical tracking.

---

**[Bopkit](https://www.bopkit.com)** | **[Support](https://www.bopkit.com/support)**

© 2025 Bopkit. All rights reserved.