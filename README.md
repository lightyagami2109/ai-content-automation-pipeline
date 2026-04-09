# AI Content Automation Pipeline (n8n + Gemini API + PostgreSQL)

## Overview
This project automates AI content generation using n8n workflows. It accepts a topic via webhook, generates structured content using Gemini API, extracts JSON fields, and stores the output in PostgreSQL.

Workflow:
Webhook → Gemini API → JSON Parsing → PostgreSQL Storage

## Tech Stack
- n8n
- Google Gemini API
- PostgreSQL
- REST Webhooks

## Features
- Accepts topic input via webhook
- Generates quiz questions
- Generates LinkedIn post content
- Generates Twitter thread content
- Stores structured results in PostgreSQL
