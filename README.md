# AI Evaluator 📚✨

An intelligent assignment evaluation system powered by Google Gemini AI that automates grading and provides personalized feedback through Google Classroom integration.

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Version](https://img.shields.io/badge/version-1.0.0-green.svg)

## 🌟 Features

### Core Functionality

- **Smart Evaluation & Grading**

  - One-click batch processing
  - AI-powered content analysis
  - Automated scoring system
  - Multi-format submission support

- **Google Classroom Integration**

  - Seamless authentication
  - Automatic grade syncing
  - Real-time updates
  - Bulk assignment handling

- **Personalized Feedback**
  - Detailed improvement suggestions
  - Strength/weakness analysis
  - Custom feedback templates
  - Multi-language support

### Analytics & Interface

- **Performance Tracking**

  - Progress monitoring
  - Class statistics
  - Individual student insights
  - Trend analysis

- **User-Friendly Design**
  - Intuitive dashboard
  - Mobile responsive
  - Dark/light themes
  - Accessibility features

## 🚀 Getting Started

### Prerequisites

```bash
Node.js >= 18.0.0
npm >= 9.0.0
MongoDB >= 6.0
```

### Environment Setup

1. **Google Cloud Setup**

```bash
# Create a Google Cloud Project
# Enable required APIs:
- Google Classroom API
- Google Drive API
- Google OAuth 2.0
```

2. **Create Environment File**

```bash
# .env file configuration
NEXT_PUBLIC_GOOGLE_CLIENT_ID=your_client_id
NEXT_PUBLIC_GOOGLE_CLIENT_SECRET=your_client_secret
MONGODB_URI=your_mongodb_connection_string
GEMINI_API_KEY=your_gemini_api_key
NEXTAUTH_URL=http://localhost:3000
NEXTAUTH_SECRET=your_nextauth_secret

# Optional configurations
NODE_ENV=development
PORT=3000
```

3. **MongoDB Setup**

```bash
# Local Development
- Install MongoDB Community Edition
- Start MongoDB service
- Create a new database

# OR use MongoDB Atlas
- Create free cluster
- Get connection string
- Add IP to allowlist
```

4. **Google Credentials**

```bash
# Google Cloud Console Steps
1. Create OAuth 2.0 credentials
2. Add authorized redirect URIs:
   - http://localhost:3000/api/auth/callback/google
   - https://yourdomain.com/api/auth/callback/google
3. Download client configuration
```

5. **Gemini API Setup**

```bash
# Google AI Studio
1. Create API key
2. Set usage quotas
3. Enable required models
```

### Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/ai-evaluator.git
cd ai-evaluator
```

2. Install dependencies

```bash
npm install
```

3. Set up environment variables

```bash
cp .env.example .env
# Add your configuration details
```

4. Run the development server

```bash
npm run dev
```

## 🛠️ Tech Stack

### Frontend

- Next.js 14
- TypeScript
- TailwindCSS
- Shadcn UI

### Backend

- Node.js
- Express.js
- MongoDB
- WebSocket

### AI/Integration

- Google Gemini API
- Google Classroom API
- Google OAuth 2.0
- Google Drive API

## 📊 System Architecture

```
Client Layer
   ↓
API Layer (REST + WebSocket)
   ↓
Authentication (Google OAuth)
   ↓
Service Layer (Assignment Processing)
   ↓
Database Layer (MongoDB)
```

## 🔜 Future Enhancements

- Enhanced AI Feedback System
- Advanced OCR with handwriting recognition
- AI Voice Assistant integration
- Smart YouTube lecture recommendations
- Multi-language support

## 💰 Pricing

### Free Tier Limits

- Google Classroom API: 1M reads & 100K writes/day
- Gemini API: 60 requests/minute
- MongoDB Atlas: 512MB storage
- Vercel Hobby: Basic hosting

### Minimum Costs (Beyond Free Tier)

- Estimated $30-40/month
- Custom domain: $10/year

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Team

- Omsingh Bais - Lead Developer
- Samiksha Gaiki - UI/UX Designer


## 📞 Support

For support, email msnghbais@gmail.com

---

Made with ❤️ for educators and students
