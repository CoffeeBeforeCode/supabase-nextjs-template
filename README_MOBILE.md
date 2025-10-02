# Solo-Pro Mobile App

The mobile companion app for Solo-Pro - relationship intelligence for solo consultants. Built with React Native, Expo, and Supabase.

## 📱 Platform Support

- **iOS** - Full native support
- **Android** - Full native support
- **Shared Backend** - Powered by Supabase

## 🚀 Current Features

This mobile app is built on a production-ready foundation that includes:

### Authentication
- Email/Password authentication
- Multi-factor authentication (MFA/2FA) with TOTP
- QR code enrollment for authenticator apps
- Password reset via email
- Email verification
- Deep link handling for password reset
- Persistent sessions

### User Management
- User profile display
- Password change functionality
- MFA device management
- Multiple MFA device support
- User settings and preferences

### File Management (2FA Protected)
- Secure file upload with document picker
- Drag and drop support
- File sharing with time-limited URLs
- File download
- File deletion with confirmation
- Progress indicators
- Maximum file size: 50MB

### Task Management (2FA Protected)
- Create, read, update, delete tasks
- Task filtering (All/Active/Completed)
- Mark tasks as urgent
- Mark tasks as done
- Task descriptions
- Real-time updates
- Row-level security

### Internationalization (i18n)
- **Supported Languages:**
  - English (en)
  - Polish (pl)
  - Chinese Simplified (zh)
- Automatic device language detection
- In-app language switching
- Persistent language preferences
- Language selector on login/register screens

### UI/UX
- Tab-based navigation with icons
- Safe area support for all devices
- Loading states and spinners
- Error handling with alerts
- Success notifications
- Native modal dialogs
- Themed color scheme
- Responsive layouts

## 🛠️ Tech Stack

### Core
- **React Native** 0.81.4
- **Expo SDK** 54
- **React** 19.1.0

### Navigation & Routing
- **Expo Router** 6.0.8 (file-based routing)
- **React Navigation** (bottom tabs)

### Backend
- **Supabase** (Authentication, Database, Storage)
- **@supabase/supabase-js** 2.58.0

### UI Components
- **Lucide React Native** (icons)
- **React Native QRCode SVG** (MFA QR codes)
- **React Native Safe Area Context**

### Internationalization
- **i18next** 25.5.2
- **react-i18next** 16.0.0
- **expo-localization** 17.0.7

### File & Storage
- **Expo Document Picker** 14.0.7
- **Expo Clipboard** 8.0.7
- **Expo Sharing** 14.0.7
- **Expo Web Browser** 15.0.7

### State Management
- React hooks (useState, useEffect, useContext)
- AsyncStorage for persistent storage

## 📦 Getting Started

### Prerequisites

- Node.js 18+
- Yarn or npm
- Expo CLI
- iOS Simulator (Mac) or Android Emulator
- Supabase project

### 1. Backend Setup

Set up your Supabase backend. You need:
- Supabase Project URL
- Supabase Anon Key
- Migrations applied
- Storage bucket configured
- RLS policies enabled

### 2. Install Dependencies
```bash
