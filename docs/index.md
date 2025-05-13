# Jenkins Self-Service Documentation
<!-- File: docs/jenkins-self-service/index.md -->

---
id: jenkins-self-service
title: Jenkins Pipeline Automation
description: Complete guide for self-service Jenkins pipelines in Backstage
---

<!-- ==================== -->
<!-- 1. QUICK START       -->
<!-- ==================== -->
## 🚀 Quick Start

### For Pipeline Users
```yaml
Steps:
  1. Go to "Create" → "Jenkins Pipeline"
  2. Fill required fields:
     - name: your-service
     - repositoryUrl: your-repo-url
     - language: JavaScript/Java/Python
  3. Submit (auto-registers in catalog)

# Verify Jenkins connectivity:
curl -u $JENKINS_USER:$JENKINS_TOKEN $JENKINS_URL/api/json

# Required environment variables:
JENKINS_USER=backstage-integration
JENKINS_TOKEN=glpat-xxxxxx
JENKINS_BASE_URL=https://jenkins.example.com
