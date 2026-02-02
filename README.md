# Pinterest Scheduler for Telegram

A content management tool for manually publishing Telegram channel content to Pinterest boards.

## 🎯 Purpose

This application helps small business owners and content creators transfer visual content from their Telegram channels to Pinterest without manual re-uploading. Each Pin requires manual user selection and confirmation.

## ✨ Features

- ✅ OAuth 2.0 secure Pinterest authentication
- ✅ Manual selection of Telegram posts
- ✅ Board selection interface
- ✅ Customizable Pin titles and descriptions
- ✅ Rate limiting (max 50 pins/day)
- ✅ Duplicate detection

## 🚀 How It Works

1. User connects Pinterest account via OAuth 2.0
2. User selects specific post from their Telegram channel
3. User chooses target Pinterest board
4. User customizes Pin title and description
5. User clicks "Publish" to create Pin
6. Pin appears on selected Pinterest board

## 📸 Screenshots

[Add screenshots of your application interface here]

## 🔐 Privacy

We respect user privacy and comply with Pinterest API guidelines:
- No bulk automation
- No data selling
- Secure token storage
- Full privacy policy: [(https://raw.githubusercontent.com/alexky-creator/telegram-pinterest/refs/heads/docs/privacy.html)]

## 🛠 Tech Stack

- Python 3.11+
- FastAPI
- Pinterest API v5
- Telegram Bot API
- OAuth 2.0

## 📋 Pinterest API Access

- **Current Status:** Trial Access
- **API Version:** v5
- **Scopes Used:** boards:read, pins:write
- **Rate Limit:** 50 pins/user/day


