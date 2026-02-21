# LinkedIn AI Content Automation System

An AI-powered automation workflow built using n8n that generates unique LinkedIn developer polls daily with duplicate detection and automated delivery.

## 🚀 Features

- Daily scheduled execution
- AI-generated developer-focused poll content
- Duplicate detection using Google Sheets
- Persistent content storage
- Automated email delivery
- 365-day no-repeat logic

## 🛠 Tech Stack

- n8n (Workflow Automation)
- OpenAI API (LLM generation)
- Google Sheets (Data storage & validation)
- Gmail Integration

## 🏗 Workflow Architecture

Schedule Trigger  
→ AI Generation  
→ Duplicate Check (Google Sheets)  
→ Conditional Logic  
→ Append Unique Record  
→ Email Delivery  

## ⚙ Setup Instructions

1. Import the provided JSON workflow into n8n.
2. Configure OpenAI API credentials.
3. Connect Google Sheets account.
4. Connect Gmail account.
5. Activate the workflow.

## 🎯 Objective

To build a scalable AI-driven content automation system ensuring consistent LinkedIn engagement without content repetition.
