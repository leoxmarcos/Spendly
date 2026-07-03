# Spendly 💸 
      
An elegant expense tracking web app built with Flask & vanilla CSS/JS 
Features • Tech Stack • Getting Started • Project Structure • Roadmap • Contributing • License 
--- ## ✨ Features 
💸 Expense Management
•	Add expenses with category, amount, date & description
•	Edit & delete existing expenses
•	Instant form validation	📊 Visual Insights
•	Category-wise spending breakdown
•	Monthly summary with progress bars
•	Clean, responsive dashboard
🔍 Smart Filtering
•	Filter by custom date ranges
•	Quick presets: This week, This month
•	Real-time updates	🔐 Authentication
•	User registration & login
•	Session-based auth
•	Secure password handling
### 🎨 Design Highlights - **Modern UI** — Clean card-based layout with subtle animations - **Responsive** — Works beautifully on mobile, tablet & desktop - **Indian Rupee (₹)** — Native currency support - **Accessible** — Semantic HTML, proper contrast, focus states --- ## 🛠 Tech Stack | Layer | Technology | |-------|------------| | **Backend** | Flask 3.1, Python 3.10+ | | **Frontend** | HTML5, CSS3 (Custom Properties), Vanilla JS | | **Templating** | Jinja2 | | **Database** | SQLite (file-based, zero config) | | **Testing** | pytest, pytest-flask | | **Dev Tools** | Flask debug mode, hot reload | --- ## 🚀 Getting Started ### Prerequisites - Python 3.10 or higher - pip (Python package manager) ### Installation ```bash # 1. Clone the repository git clone https://github.com/leoxmarcos/Spendly.git cd Spendly # 2. Create a virtual environment python -m venv venv # 3. Activate the environment # Windows: venv\Scripts\activate # macOS/Linux: source venv/bin/activate # 4. Install dependencies pip install -r requirements.txt # 5. Run the development server python app.py ``` The app will be available at **http://localhost:5001** ### Environment Variables (Optional) Create a `.env` file in the root directory: ```env SECRET_KEY=your-super-secret-key-here DATABASE_URL=sqlite:///spendly.db FLASK_ENV=development ``` --- ## 📁 Project Structure ``` Spendly/ ├── app.py # Flask application factory & routes ├── requirements.txt # Python dependencies ├── package.json # Frontend metadata (npm) ├── .gitignore ├── README.md │ ├── database/ # SQLite database (auto-created) │ └── spendly.db │ ├── static/ # Static assets │ ├── css/ │ │ └── style.css # Main stylesheet │ ├── js/ │ │ └── app.js # Client-side interactions │ └── logo.svg # App logo │ └── templates/ # Jinja2 templates ├── base.html # Base layout ├── landing.html # Marketing landing page ├── login.html # Sign in page ├── register.html # Sign up page ├── dashboard.html # Main dashboard (TODO) ├── add_expense.html # Add expense form (TODO) └── profile.html # User profile (TODO) ``` --- ## 🗺 Roadmap | Phase | Status | Description | |-------|--------|-------------| | **1** | ✅ Done | Project setup, landing page, auth UI | | **2** | ✅ Done | User registration & login | | **3** | 🔄 In Progress | Logout, session management | | **4** | ⏳ Planned | User profile page | | **5** | ⏳ Planned | Dashboard with expense list | | **6** | ⏳ Planned | Category management | | **7** | ⏳ Planned | Add expense form | | **8** | ⏳ Planned | Edit expense | | **9** | ⏳ Planned | Delete expense | | **10** | ⏳ Planned | Date range filtering | | **11** | ⏳ Planned | Charts & analytics (Chart.js) | | **12** | ⏳ Planned | Export to CSV/PDF | | **13** | ⏳ Planned | Dark mode toggle | | **14** | ⏳ Planned | PWA support | > **Want to contribute?** Check the [Issues](https://github.com/leoxmarcos/Spendly/issues) tab for tasks labeled `good first issue` or `help wanted`. --- ## 🤝 Contributing Contributions are what make the open source community amazing. Any contributions you make are **greatly appreciated**. ### How to Contribute 1. **Fork** the repository 2. **Create** your feature branch (`git checkout -b feature/AmazingFeature`) 3. **Commit** your changes (`git commit -m "Add some AmazingFeature"`) 4. **Push** to the branch (`git push origin feature/AmazingFeature`) 5. **Open** a Pull Request ### Development Guidelines - Follow the existing code style (PEP 8 for Python, consistent CSS/JS) - Write meaningful commit messages - Add tests for new functionality - Update documentation as needed - Ensure all tests pass before submitting PR --- ## 📸 Screenshots 
Landing Page	Sign In	Register
 	 	 
> 📝 *Screenshots coming soon — add them to `docs/screenshots/` folder* --- ## 📄 License Distributed under the **MIT License**. See `LICENSE` for more information. --- ## 🙏 Acknowledgments - Built with guidance from **Claude Code** (Anthropic) - Inspired by modern expense tracking apps - Icons & design patterns from open source community - Flask & Jinja2 documentation --- ## 📬 Contact **Leo Marcos** — [@leoxmarcos](https://github.com/leoxmarcos) **Project Link:** [https://github.com/leoxmarcos/Spendly](https://github.com/leoxmarcos/Spendly) --- 
Made with ❤️ and ☕ by Leo Marcos 
If you find Spendly useful, please consider giving it a ⭐ on GitHub! 
