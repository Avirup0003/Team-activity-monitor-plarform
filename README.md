# 🚀 Team Activity Monitor

<div align="center">
  <img src="https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=nodemon&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js" />
  <img src="https://img.shields.io/badge/Google%20Gemini-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Google Gemini" />
  <img src="https://img.shields.io/badge/Jira-0052CC?style=for-the-badge&logo=jira&logoColor=white" alt="Jira" />
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" />
</div>

<br />

<div align="center">
  <img src="https://img.icons8.com/color/96/000000/group.png" alt="Team Activity Monitor Logo" width="80" height="80" />
  <h1>AI-Powered Team Activity Insight Tool</h1>
  <p><em>Get instant insights into what your team members are working on</em></p>
</div>

---

## ✨ What This Project Does

Ask natural language questions like **“What is John working on these days?”** and get AI-powered summaries combining:

- 📋 **JIRA Issues** - Current tasks and progress
- 💻 **GitHub Activity** - Recent commits and pull requests
- 🤖 **AI Summaries** - Clean, readable explanations using OpenAI or Google Gemini

This eliminates the need to manually check multiple tools, giving you a **quick snapshot** of team activity.

---

## 🎯 Key Features

### 🔗 Integrations
- **JIRA Cloud API** - Fetch assigned issues and status updates
- **GitHub REST API** - Pull commit history and active PRs
- **AI Summarization** - OpenAI GPT or Google Gemini for natural language summaries

### 🎨 Modern UI/UX
- 🌈 **Animated gradient backgrounds** with smooth transitions
- 💎 **Glassmorphism design** with backdrop blur effects
- 🌓 **Dark/Light mode toggle** with smooth animations
- 📱 **Fully responsive** design for all devices
- 🎭 **Interactive modal** for displaying results
- ✨ **Floating logo animation** and gradient button effects

### 🧠 Smart Processing
- **Intelligent name detection** from natural language queries
- **Error handling** with graceful fallbacks
- **Rate limit management** with API switching
- **Markdown support** in output formatting

---

## 🚀 Quick Start

### Prerequisites
- Node.js (v16 or higher)
- npm or yarn
- JIRA Cloud account with API access
- GitHub Personal Access Token
- OpenAI API key or Google Gemini API key

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/your-username/team-activity-monitor.git
   cd team-activity-monitor
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Set up environment variables**
   
   Edit `.env` with your API keys:
   ```env
   JIRA_BASE_URL=your-domain.atlassian.net
   JIRA_EMAIL=your-email@example.com
   JIRA_API_TOKEN=your-jira-api-token

   GITHUB_TOKEN=your-github-personal-access-token

   # Choose one AI provider
   OPENAI_API_KEY=your-openai-api-key
   GEMINI_API_KEY=your-gemini-api-key
   ```

4. **Start the application**
   ```bash
   npm start
   ```

5. **Open your browser**
   ```
   http://localhost:3000
   ```

---

## 📝 Usage Examples

Try these sample queries:

- "What is John working on these days?"
- "Show me Sarah's recent activity"
- "What has Mike been working on this week?"
- "Tell me about Aditya's current projects"

The system will:
1. Extract the team member's name
2. Fetch their JIRA issues and GitHub activity
3. Generate an AI-powered summary
4. Display results in a beautiful modal

---

## 🏗️ Project Structure

```
team-activity-monitor/
├── src/
│   ├── ai-client.js          # AI summarization logic
│   ├── github-client.js      # GitHub API integration
│   ├── jira-client.js        # JIRA API integration
│   ├── query-parser-client.js # Name extraction utilities
│   └── server-client.js      # Express server setup
├── public/
│   ├── index.html            # Main UI interface
│   ├── style.css             # Modern CSS with animations
│   └── script.js             # Frontend JavaScript
├── config/
│   └── config.js             # Configuration management
├── .env                      # Environment variables
├── package.json              # Dependencies and scripts
└── README.md                 # This file
```

---

## 🎨 UI Preview

<div align="center">
  <img src="https://via.placeholder.com/800x400/667eea/ffffff?text=Team+Activity+Monitor+UI" alt="UI Preview" width="80%" />
  <p><em>Modern glassmorphism design with gradient backgrounds</em></p>
</div>

### Design Highlights
- **CSS Grid Layout** for unique element positioning
- **Floating animations** and pulse effects
- **Responsive breakpoints** for mobile optimization
- **Smooth transitions** between light/dark modes
- **Professional color scheme** with blue/cyan gradients

---

## 🤖 AI Integration


### Google Gemini (Recommended - Free)
- No API costs for development
- Fast response times
- Excellent summarization quality


**Automatic fallback** ensures the system works even if one API is unavailable.

---

## 🔧 API Endpoints

### POST `/ask`
Main endpoint for activity queries.

**Request:**
```json
{
  "question": "What is Aditya working on?"
}
```

**Response:**
```json
{
  "answer": "Aditya is currently working on the user authentication module..."
}
```

---

## 🧪 Testing

The application has been tested with various scenarios:

- ✅ Valid team member names
- ✅ Invalid/unknown names (graceful error handling)
- ✅ Users with no recent activity
- ✅ API rate limits and fallbacks
- ✅ Network connectivity issues
- ✅ Dark/light mode switching
- ✅ Responsive design on different screen sizes

---

## 🚀 Deployment

### Local Development
```bash
npm run dev  # With nodemon for auto-restart
```

### Production Deployment
```bash
npm start
```

### Docker Support (Future)
```dockerfile
# Dockerfile will be added for containerized deployment
```

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request



<div align="center">
  <p><strong>Built with ❤️ for efficient team collaboration</strong></p>
  <p>
    <a href="#-team-activity-monitor">Back to Top</a> •
    <a href="#-quick-start">Get Started</a> •
    <a href="#-contributing">Contribute</a>
  </p>
</div>
