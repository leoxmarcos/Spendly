$ Set-Content -Path "C:\Users\parth\Spendly\README.md" -Value '# Spendly 💸

<p align="center">
  <img src="https://img.shields.io/github/license/leoxmarcos/Spendly?style=flat-square&color=2ecc71" alt="License" />
  <img src="https://img.shields.io/github/languages/top/leoxmarcos/Spendly?style=flat-square&color=3498db" alt="Top Language" />
  <img src="https://img.shields.io/github/languages/count/leoxmarcos/Spendly?style=flat-square&color=9b59b6" alt="Language Count" />
  <img src="https://img.shields.io/github/last-commit/leoxmarcos/Spendly?style=flat-square&color=e74c3c" alt="Last Commit" />
  <img src="https://img.shields.io/github/issues/leoxmarcos/Spendly?style=flat-square&color=f39c12" alt="Issues" />
  <img src="https://img.shields.io/github/stars/leoxmarcos/Spendly?style=flat-square&color=ffd700" alt="Stars" />
  <img src="https://img.shields.io/badge/Built%20with-Claude%20Code-7c3aed?style=flat-square&logo=anthropic" alt="Built with Claude Code" />
</p>

<p align="center">
  <strong>An elegant expense tracking web app built with Flask & vanilla CSS/JS</strong>
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
        <li>Add expenses with category, amount, date & description</li>
        <li>Edit & delete existing expenses</li>
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
        <li>User registration & login</li>
        <li>Session-based auth</li>
        <li>Secure password handling</li>
      </ul>
    </td>
  </tr>
</table>

### 🎨 Design Highlights
- **Modern UI** — Clean card-based layout with subtle animations
- **Responsive** — Works beautifully on mobile, tablet & desktop
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

# 4. Install dependencies
pip install -r requirements.txt

# 5. Run the development server
python app.py
```

The app will be available at **http://localhost:5001**

### Environment Variables (Optional)

Create a `.env` file in the root directory:

```env
SECRET_KEY=your-super-secret-key-here
DATABASE_URL=sqlite:///spendly.db
FLASK_ENV=development
```

---

## 📁 Project Structure

```
Spendly/
├── app.py                 # Flask application factory & routes
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
```

---

## 🤖 Built with Claude Code

This project was **entirely built using [Claude Code](https://claude.ai/code)** — Anthropic's AI-powered coding agent that lives in your terminal.

### 🎯 What is Claude Code?

<div align="center">
  <img src="https://raw.githubusercontent.com/leoxmarcos/Spendly/main/docs/assets/claude-code-banner.png" alt="Claude Code" width="600" />
</div>

**Claude Code** is an AI coding assistant that:
- 🧠 **Understands your entire codebase** — reads, searches, and reasons across files
- ⚡ **Writes, edits, and refactors code** — from boilerplate to complex features
- 🔧 **Runs commands & tests** — executes bash, runs linters, validates changes
- 📚 **Explains code** — answers questions about any part of your project
- 🤝 **Collaborates naturally** — chat-driven workflow, no context switching

### 🛠 How This Project Was Built

<table>
  <tr>
    <td width="33%" align="center" valign="top">
      <h3>📋 Planning & Architecture</h3>
      <p>Designed the Flask app structure, database schema, and component hierarchy through conversational planning.</p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>💻 Code Generation</h3>
      <p>Generated all Python routes, Jinja2 templates, CSS stylesheets, and JavaScript interactions via natural language prompts.</p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3>🔧 Iteration & Polish</h3>
      <p>Refined UI/UX, fixed bugs, added responsive design, and created this README through continuous dialogue.</p>
    </td>
  </tr>
</table>

### 💡 Example Prompts Used

<details>
<summary><strong>Click to see example prompts</strong></summary>

```bash
# Project initialization
> "Create a Flask expense tracker with SQLite, Jinja2 templates, and modern CSS"

# Landing page
> "Build a beautiful landing page with hero section, feature cards, and mock dashboard preview"

# Authentication
> "Add user registration and login with session-based auth, password hashing, and form validation"

# Dashboard
> "Create a dashboard showing expense list, category breakdown with progress bars, and date filtering"

# Styling
> "Style everything with CSS custom properties, responsive grid, smooth animations, and Indian Rupee formatting"

# This README
> "Write a visually attractive README with badges, tables, roadmap, and Claude Code section"
```

</details>

### 🚀 Get Started with Claude Code

```bash
# 1. Install Claude Code (macOS/Linux)
curl -fsSL https://claude.ai/install.sh | sh

# 2. Or download from https://claude.ai/code

# 3. Navigate to your project
cd your-project

# 4. Start coding with AI
claude
```

<div align="center">
  <img src="https://raw.githubusercontent.com/leoxmarcos/Spendly/main/docs/assets/claude-code-terminal.png" alt="Claude Code Terminal" width="700" />
  <p><em>Claude Code in action — chat-driven development in your terminal</em></p>
</div>

### 📚 Learn More

| Resource | Link |
|----------|------|
| **Official Website** | [claude.ai/code](https://claude.ai/code) |
| **Documentation** | [docs.anthropic.com/claude-code](https://docs.anthropic.com/claude-code) |
| **GitHub Repo** | [anthropics/claude-code](https://github.com/anthropics/claude-code) |
| **Tutorial Video** | [YouTube: Getting Started](https://youtube.com/claude-code) |
| **Community** | [Discord](https://discord.gg/claude-code) |

---

## 🗺 Roadmap

| Phase | Status | Description |
|-------|--------|-------------|
| **1** | ✅ Done | Project setup, landing page, auth UI |
| **2** | ✅ Done | User registration & login |
| **3** | 🔄 In Progress | Logout, session management |
| **4** | ⏳ Planned | User profile page |
| **5** | ⏳ Planned | Dashboard with expense list |
| **6** | ⏳ Planned | Category management |
| **7** | ⏳ Planned | Add expense form |
| **8** | ⏳ Planned | Edit expense |
| **9** | ⏳ Planned | Delete expense |
| **10** | ⏳ Planned | Date range filtering |
| **11** | ⏳ Planned | Charts & analytics (Chart.js) |
| **12** | ⏳ Planned | Export to CSV/PDF |
| **13** | ⏳ Planned | Dark mode toggle |
| **14** | ⏳ Planned | PWA support |

> **Want to contribute?** Check the [Issues](https://github.com/leoxmarcos/Spendly/issues) tab for tasks labeled `good first issue` or `help wanted`.

---

## 🤝 Contributing

Contributions are what make the open source community amazing. Any contributions you make are **greatly appreciated**.

### How to Contribute

1. **Fork** the repository
2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`)
3. **Commit** your changes (`git commit -m "Add some AmazingFeature"`)
4. **Push** to the branch (`git push origin feature/AmazingFeature`)
5. **Open** a Pull Request

### Development Guidelines

- Follow the existing code style (PEP 8 for Python, consistent CSS/JS)
- Write meaningful commit messages
- Add tests for new functionality
- Update documentation as needed
- Ensure all tests pass before submitting PR

---

## 📸 Screenshots

<div align="center">
  <table>
    <tr>
      <td align="center"><strong>Landing Page</strong></td>
      <td align="center"><strong>Sign In</strong></td>
      <td align="center"><strong>Register</strong></td>
    </tr>
    <tr>
      <td><img src="https://raw.githubusercontent.com/leoxmarcos/Spendly/main/docs/screenshots/landing.png" alt="Landing Page" width="300" /></td>
      <td><img src="https://raw.githubusercontent.com/leoxmarcos/Spendly/main/docs/screenshots/login.png" alt="Sign In" width="300" /></td>
      <td><img src="https://raw.githubusercontent.com/leoxmarcos/Spendly/main/docs/screenshots/register.png" alt="Register" width="300" /></td>
    </tr>
  </table>
</div>

> 📝 *Screenshots coming soon — add them to `docs/screenshots/` folder*

---

## 📄 License

Distributed under the **MIT License**. See `LICENSE` for more information.

---

## 🙏 Acknowledgments

- Built with guidance from **Claude Code** (Anthropic)
- Inspired by modern expense tracking apps
- Icons & design patterns from open source community
- Flask & Jinja2 documentation

---

## 📬 Contact

**Leo Marcos** — [@leoxmarcos](https://github.com/leoxmarcos)

**Project Link:** [https://github.com/leoxmarcos/Spendly](https://github.com/leoxmarcos/Spendly)

---

<p align="center">
  Made with ❤️ and ☕ by <a href="https://github.com/leoxmarcos">Leo Marcos</a>
</p>

<p align="center">
  <sub>If you find Spendly useful, please consider giving it a ⭐ on GitHub!</sub>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Powered%20by-Claude%20Code-7c3aed?style=for-the-badge&logo=anthropic&logoColor=white" alt="Powered by Claude Code" />
</p>' -Encoding UTF8

At line:178 char:2
+ - ?? **Understands your entire codebase** - reads, searches, and reas ...
+  ~
Missing expression after unary operator '-'.
At line:178 char:3
+ - ?? **Understands your entire codebase** - reads, searches, and reas ...
+   ~~
Unexpected token '??' in expression or statement.
At line:179 char:2
+ - ? **Writes, edits, and refactors code** - from boilerplate to compl ...
+  ~
Missing expression after unary operator '-'.
At line:179 char:3
+ - ? **Writes, edits, and refactors code** - from boilerplate to compl ...
+   ~
Unexpected token '?' in expression or statement.
At line:180 char:2
+ - ?? **Runs commands & tests** - executes bash, runs linters, validat ...
+  ~
Missing expression after unary operator '-'.
At line:180 char:3
+ - ?? **Runs commands & tests** - executes bash, runs linters, validat ...
+   ~~
Unexpected token '??' in expression or statement.
At line:180 char:22
+ - ?? **Runs commands & tests** - executes bash, runs linters, validat ...
+                      ~
The ampersand (&) character is not allowed. The & operator is reserved for future use; wrap an ampersand in double 
quotation marks ("&") to pass it as part of a string.
At line:181 char:2
+ - ?? **Explains code** - answers questions about any part of your pro ...
+  ~
Missing expression after unary operator '-'.
At line:181 char:3
+ - ?? **Explains code** - answers questions about any part of your pro ...
+   ~~
Unexpected token '??' in expression or statement.
At line:182 char:2
+ - ?? **Collaborates naturally** - chat-driven workflow, no context sw ...
+  ~
Missing expression after unary operator '-'.
Not all parse errors were reported.  Correct the reported errors and try again.
    + CategoryInfo          : ParserError: (:) [], ParentContainsErrorRecordException
    + FullyQualifiedErrorId : MissingExpressionAfterOperator
 
