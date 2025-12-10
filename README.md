# Edge URL Shortener (CI/CD) 🚀

A **serverless URL shortener** built on **Cloudflare Workers** using only the **Cloudflare Free Tier**, with **CI/CD powered by GitHub Actions**.  
This project demonstrates how to design, deploy, and operate a **production-style edge application** with automated builds, tests, and deployments.

---

## 🎯 Project Goals

### 1. Learn Cloudflare Edge Computing
- Build and deploy a real-world application on **Cloudflare Workers**
- Handle HTTP requests at the edge with **low latency**
- Understand edge routing and redirects

---

### 2. Implement a Production-Style CI/CD Pipeline
- Automatically deploy on every push to the `main` branch
- Use **GitHub Actions** for continuous integration and deployment
- Inject secrets securely using **GitHub repository secrets**

---

### 3. Use Cloudflare Free-Tier Services Effectively
- Store URL data in **Cloudflare D1** (SQL-based database)
- Operate entirely within free quotas
- Avoid vendor lock-in or paid-only features

---

### 4. Apply Backend Engineering Best Practices
- Validate inputs (URL and short code)
- Handle errors and edge cases gracefully
- Support optional features like:
  - Click tracking
  - Expiring short URLs

---

### 5. Learn DevOps & Infrastructure Concepts
- Infrastructure as Code mindset
- Environment-based deployments (dev / prod)
- Rollback-safe deployments using Git-based workflows

---

### 6. Improve Security Awareness
- Protect admin endpoints using token-based authentication
- Store secrets securely (no hardcoded keys)
- Prepare the system for basic rate-limiting

---

### 7. Create a Portfolio-Ready Project
- Clean repository structure
- Clear documentation and goals
- Demonstrates:
  - Serverless architecture
  - CI/CD pipelines
  - Cloud-native backend design

---

## 🏗 High-Level Architecture

Client  
↓  
Cloudflare Worker (Edge)  
↓  
Cloudflare D1 (URL storage)  

---

## 🧪 Planned Features

- ✅ URL shortening and redirection
- ✅ Edge-based redirect logic
- ✅ Click tracking
- ✅ Expiry support (optional)
- 🔐 Admin API for managing links
- 📊 Analytics endpoint (future)
- 🧪 Unit tests in CI

---

## ⚙️ Tech Stack

- Cloudflare Workers
- Cloudflare D1
- GitHub Actions
- Wrangler CLI
- TypeScript / JavaScript

---

## 🚦 CI/CD Workflow

1. Code pushed to GitHub
2. GitHub Actions runs tests
3. Worker is deployed using Wrangler
4. Cloudflare Edge updates instantly

---

## 🆓 Cloudflare Free Tier Compliance

This project **only uses services available in the Cloudflare Free tier**:
- ✅ Workers
- ✅ D1
- ✅ Cron (optional)
- ✅ DNS & CDN

No paid or enterprise features required.

---

## 🧑‍💼 Author

**rhshourav**

