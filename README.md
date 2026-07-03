# Spendly 💸

<p align="center">
  <img src="https://img.shields.io/github/license/leoxmarcos/Spendly?style=flat-square&amp;color=2ecc71" alt="License" />
  <img src="https://img.shields.io/github/languages/top/leoxmarcos/Spendly?style=flat-square&amp;color=3498db" alt="Top Language" />
  <img src="https://img.shields.io/github/languages/count/leoxmarcos/Spendly?style=flat-square&amp;color=9b59b6" alt="Language Count" />
  <img src="https://img.shields.io/github/last-commit/leoxmarcos/Spendly?style=flat-square&amp;color=e74c3c" alt="Last Commit" />
  <img src="https://img.shields.io/github/issues/leoxmarcos/Spendly?style=flat-square&amp;color=f39c12" alt="Issues" />
  <img src="https://img.shields.io/github/stars/leoxmarcos/Spendly?style=flat-square&amp;color=ffd700" alt="Stars" />
  <img src="https://img.shields.io/badge/Built%20with-Claude%20Code-7c3aed?style=flat-square" alt="Built with Claude Code" />
</p>

<p align="center">
  <strong>An elegant expense tracking web app built with Flask and vanilla CSS/JS</strong>
</p>

<p align="center">
  <a href="#-features"><strong>Features</strong></a> •
  <a href="#-tech-stack"><strong>Tech Stack</strong></a> •
  <a href="#-getting-started"><strong>Getting Started</strong></a> •
  <a href="#-project-structure"><strong>Project Structure</strong></a> •
  <a href="#-built-with-claude-code"><strong>Built with Claude Code</strong></a> •
  <a href="#-roadmap"><strong>Roadmap</strong></a> •
  <a href="#-contributing"><strong>Contributing</strong></a> •
  <a href="#-license"><strong>License</strong></a>
</p>

---

## ✨ Features

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💸 Expense Management</h3>
      <ul>
        <li>Add expenses with category, amount, date and description</li>
        <li>Edit and delete existing expenses</li>
        <li>Instant form validation</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>📊 Visual Insights</h3>
      <ul>
        <li>Category-wise spending breakdown</li>
        <li>Monthly summary with progress bars</li>
        <li>Clean, responsive dashboard</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td valign="top">
      <h3>🔍 Smart Filtering</h3>
      <ul>
        <li>Filter by custom date ranges</li>
        <li>Quick presets: This week, This month</li>
        <li>Real-time updates</li>
      </ul>
    </td>
    <td valign="top">
      <h3>🔐 Authentication</h3>
      <ul>
        <li>User registration and login</li>
        <li>Session-based auth</li>
        <li>Secure password handling</li>
      </ul>
    </td>
  </tr>
</table>

### 🎨 Design Highlights
- **Modern UI** — Clean card-based layout with subtle animations
- **Responsive** — Works beautifully on mobile, tablet and desktop
- **Indian Rupee (₹)** — Native currency support
- **Accessible** — Semantic HTML, proper contrast, focus states

---

## 🛠 Tech Stack

| Layer | Technology |
|-------|------------|
| **Backend** | Flask 3.1, Python 3.10+ |
| **Frontend** | HTML5, CSS3 (Custom Properties), Vanilla JS |
| **Templating** | Jinja2 |
| **Database** | SQLite (file-based, zero config) |
| **Testing** | pytest, pytest-flask |
| **Dev Tools** | Flask debug mode, hot reload |

---

## 🚀 Getting Started

### Prerequisites
- Python 3.10 or higher
- pip (Python package manager)

### Installation

```bash
# 1. Clone the repository
git clone https://github.com/leoxmarcos/Spendly.git
cd Spendly

# 2. Create a virtual environment
python -m venv venv

# 3. Activate the environment
# Windows:
venv\Scripts\activate
# macOS/Linux:
source venv/bin/activate
python app.py

Project Structure
Spendly/
├── app.py                 # Flask application factory and routes
├── requirements.txt       # Python dependencies
├── package.json           # Frontend metadata (npm)
├── .gitignore
├── README.md
│
├── database/              # SQLite database (auto-created)
│   └── spendly.db
│
├── static/                # Static assets
│   ├── css/
│   │   └── style.css      # Main stylesheet
│   ├── js/
│   │   └── app.js         # Client-side interactions
│   └── logo.svg           # App logo
│
└── templates/             # Jinja2 templates
    ├── base.html          # Base layout
    ├── landing.html       # Marketing landing page
    ├── login.html         # Sign in page
    ├── register.html      # Sign up page
    ├── dashboard.html     # Main dashboard (TODO)
    ├── add_expense.html   # Add expense form (TODO)
    └── profile.html       # User profile (TODO)
🤖 Built with Claude Code
Powered by Claude Code
This project was entirely built using Claude Code — Anthropic's AI-powered coding agent that lives in your terminal. Every file, every route, every style was generated through natural language conversations with Claude.

🎯 What is Claude Code?
Claude Code is an agentic AI coding tool that:

🧠 Understands your entire codebase — reads, searches, and reasons across files
⚡ Writes, edits, and refactors code — from boilerplate to complex features
🔧 Runs commands and tests — executes bash, runs linters, validates changes
📚 Explains code — answers questions about any part of your project
🤝 Collaborates naturally — chat-driven workflow, no context switching
How this project was built:

📋 Plan — Designed Flask app structure and features conversationally
💻 Generate — Created all Python routes, templates, CSS and JS via prompts
🔧 Iterate — Refined UI, fixed bugs, added responsive design in real-time
📝 Document — This very README was written by Claude Code
💡 Example Prompts Used
Click to see example prompts
🚀 Get Started with Claude Code
# 1. Install Claude Code
curl -fsSL https://claude.ai/install.sh | sh

# 2. Navigate to your project
cd your-project

# 3. Start coding with AI
claude
📖 Learn more: claude.ai/code • Documentation • GitHub Repo
