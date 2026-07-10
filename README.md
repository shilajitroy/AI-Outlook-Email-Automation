# AI-Powered Outlook Email Automation

## Overview

This project automates Outlook email processing using n8n and Google Gemini AI.

The workflow classifies incoming emails and automatically forwards important business emails while ignoring newsletters and promotional emails.

## Features

- Outlook Email Trigger
- Google Gemini AI Classification
- Automatic Email Forwarding
- Duplicate Detection
- Microsoft Graph API Integration
- REST API Integration

## Technologies

- n8n
- Microsoft Outlook
- Microsoft Graph API
- Google Gemini API
- REST API
- OAuth2

## Workflow

Outlook Trigger

↓

Duplicate Check

↓

Get Full Email

↓

Gemini AI

↓

Condition

↓

Forward Email

## Setup

1. Import workflow.json into n8n.
2. Configure Outlook credentials.
3. Configure Gemini API Key.
4. Publish workflow.

## Author

Shilajit Roy
