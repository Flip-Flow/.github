# FlipFlow

**Intelligent security infrastructure for modern web applications**

FlipFlow builds security and observability tooling that helps teams understand how their web applications behave in real time, identify vulnerabilities, and strengthen their attack surface before issues reach production.

Our platform combines deterministic instrumentation with advanced reasoning systems to turn raw application behaviour into actionable security intelligence.

---

## Products

### Cleo
Cleo is FlipFlow’s flagship security analysis platform.

It provides deep visibility into web application behaviour through:

- Live browser instrumentation using Chrome DevTools Protocol (CDP)
- Network traffic reconstruction and analysis
- Domain and application scanning
- Authentication flow and token path mapping
- Security finding extraction and classification
- Visual intelligence reporting

Cleo helps security teams, engineers, and product owners understand not just what their application does, but how it behaves under real conditions.

---

## What makes FlipFlow different

Most security tools rely on static scanning or surface-level analysis. FlipFlow focuses on runtime behaviour and system-level understanding.

We combine three layers of intelligence:

### 1. Instrumentation layer
A deterministic engine that captures real application behaviour.

- CDP-based browser monitoring
- Network request and response reconstruction
- Session-level traffic analysis
- Endpoint discovery and mapping

### 2. Analysis layer
A structured system that converts raw signals into security findings.

- Vulnerability detection logic
- Heuristic-based classification
- Evidence extraction and correlation
- Attack surface mapping

### 3. Reasoning layer (Cleo intelligence system)
A proprietary interpretation engine that:

- Prioritises security findings based on context
- Builds multi-step attack narratives
- Correlates evidence across sessions
- Generates structured remediation guidance

---

## Architecture overview

Web Application
      |
      v
FlipFlow Instrumentation Layer
      |
      +-- CDP Session Monitor
      +-- Network Reconstruction Engine
      +-- Domain Scanner
      |
      v
Analysis Engine
      |
      +-- Finding Extraction
      +-- Evidence Correlation
      +-- Security Classification
      |
      v
Cleo Reasoning System (Proprietary)
      |
      +-- Prioritisation Logic
      +-- Attack Path Modelling
      +-- Security Narrative Generation
      |
      v
Output Layer
      |
      +-- Visual Intelligence Dashboard
      +-- Reports
      +-- Export Formats (JSON, PDF, HAR, Playwright)

---

## Key capabilities

- Real-time application traffic monitoring
- Automated security scanning for web applications
- Authentication and session flow analysis
- Token and credential movement tracking
- Attack path reconstruction
- Structured vulnerability reporting
- Evidence-based security findings
- Visual network and behaviour graphs

---

## Deployment options

### Hosted platform
FlipFlow provides a fully managed version of Cleo with:

- Continuous application monitoring
- Scheduled security investigations
- Team collaboration features
- Centralised reporting and audit logs
- Enterprise integrations

### Self-hosted deployment
FlipFlow components can be self-hosted for internal security use cases.

- Full control over instrumentation layer
- Local execution of scanning engines
- Optional integration with Cleo reasoning system
- Extensible plugin architecture

---

## Enterprise features

- Role-based access control (RBAC)
- Single sign-on (SSO)
- Audit logging
- Compliance mapping (SOC 2, GDPR, OWASP)
- Secure data retention policies
- API and webhook integrations
- Dedicated support and onboarding

---

## Security model

FlipFlow is designed for authorised security testing and defensive use cases only.

The platform is intended to help organisations identify and remediate vulnerabilities in systems they own or are explicitly authorised to test.

---

## Technology stack

- Node.js and TypeScript backend
- React frontend
- Chrome DevTools Protocol (CDP)
- Supabase for authentication and storage
- Distributed job processing for scheduled scans
- Structured reporting and visualisation engine

---

## Use cases

- Application security testing (DAST-style workflows)
- Pre-production security validation
- Authentication flow auditing
- API and endpoint discovery
- Fraud and bot detection analysis
- Security compliance reporting

---

## Company

FlipFlow is building the next generation of security intelligence systems by combining real-time instrumentation with structured reasoning systems.

We focus on turning complex application behaviour into clear, actionable intelligence for engineering and security teams.

---

## Product: Cleo

Cleo is available at:

https://cleo.flipflow.app

Pricing and enterprise information:

https://pricing.flipflow.app/  
https://enterprise.flipflow.app/

---

## Contributing

We welcome contributions to open FlipFlow components.

Repositories include instrumentation, scanning engines, and reporting systems.

The Cleo reasoning system and intelligence layer are proprietary and not open for external contributions.

---
