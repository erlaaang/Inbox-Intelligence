# Inbox Intelligence Platform

A personal email analytics and automation platform built using Gmail API, n8n, PostgreSQL, Gemini AI, Docker, and Apache Superset.

## Features:

* Automated email ingestion from Gmail
* Hybrid rule-based and AI-powered classification
* Priority scoring
* Recruiter opportunity tracking
* Daily email analytics
* Interactive dashboards

## Architecture:
Gmail → n8n → Rule Engine → Gemini Fallback → PostgreSQL → Superset

## Optimization:
Implemented rule-based classification to reduce LLM usage by approximately 70%, lowering operational costs while maintaining classification coverage.

## How To Use:
powershell >> docker compose up -d
check status docker compose ps