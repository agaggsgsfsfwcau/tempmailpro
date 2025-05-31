# Temp Mail Pro - Disposable Email Service

![Temp Mail Pro Screenshot](https://via.placeholder.com/800x400?text=Temp+Mail+Screenshot)

## 🌟 Overview
Temp Mail Pro is a web application that provides temporary, disposable email addresses, perfect for:
- Website registrations
- Email verifications
- Protecting your primary email from spam
- Maintaining privacy online

## 🚀 Features

### ✨ Core Features
- **Automatic Email Generation**: Instantly create random email addresses
- **Custom Usernames**: Option to specify your preferred username
- **Full Inbox Management**: View, read, and organize received emails
- **HTML Email Support**: Safe rendering of HTML messages in sandboxed iframes
- **Multiple Accounts**: Manage several disposable emails simultaneously
- **Auto-Refresh**: Inbox updates every 15 seconds (with visual progress indicator)

### 🔐 Account Management
| Feature | Description |
|---------|-------------|
| Create Accounts | Random or custom username options |
| Edit Accounts | Change usernames anytime |
| Delete Accounts | Remove accounts with one click |
| Copy Email | Instant copy to clipboard |
| Account History | View creation and last-used dates |

### 🎨 User Experience
- **Dark/Light Mode**: Toggle between color schemes
- **Visual Notifications**: Snackbar alerts for actions
- **Sound Alerts**: Optional notification sounds
- **Responsive Design**: Works on all device sizes
- **Intuitive UI**: Material Design inspired interface

## 🛠️ Technical Implementation

### Frontend
- Vanilla HTML5, CSS3, JavaScript (no frameworks)
- CSS Variables for easy theming
- Material Icons integration
- Fully responsive layout

### Backend Integration
```mermaid
graph LR
    A[Client] -->|API Calls| B[mail.tm API]
    B --> C[Domain Management]
    B --> D[Account Creation]
    B --> E[Email Retrieval]
