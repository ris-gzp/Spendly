<div align="center">

# Spendly

### Track every rupee. Know where it goes.

A clean, modern personal expense tracker built with Flask — designed to help you log expenses, spot spending patterns, and stay on budget without the spreadsheet headache.

[![Python](https://img.shields.io/badge/Python-3.10+-3776AB?style=for-the-badge&logo=python&logoColor=white)](https://python.org)
[![Flask](https://img.shields.io/badge/Flask-3.1-000000?style=for-the-badge&logo=flask&logoColor=white)](https://flask.palletsprojects.com)
[![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)](https://sqlite.org)
[![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)](LICENSE)

<br>

<img src="Screenshot 2026-03-25 at 12.36.20 AM.png" alt="Spendly Landing Page" width="700">

</div>

---

## Features

| Feature | Description |
|---------|-------------|
| **Expense Logging** | Add expenses with amount, category, date, and description in seconds |
| **Category Breakdown** | Visual bar charts showing where your money goes — Food, Travel, Bills, and more |
| **Budget Tracking** | See how much you've spent this month and what's left in your budget |
| **Transaction History** | Browse and manage all your past transactions in one place |
| **User Authentication** | Secure registration and login to keep your data private |
| **Responsive Design** | Works beautifully on desktop, tablet, and mobile |

## Tech Stack

```
Frontend        HTML5 | CSS3 (Custom Properties) | Vanilla JavaScript
Backend         Python | Flask 3.1
Database        SQLite
Typography      DM Serif Display | DM Sans (Google Fonts)
Testing         pytest | pytest-flask
```

## Project Structure

```
Spendly/
├── app.py                    # Flask application & routes
├── database/
│   ├── __init__.py
│   └── db.py                 # Database connection & schema
├── static/
│   ├── css/
│   │   ├── style.css         # Global styles & design system
│   │   └── landing.css       # Landing page specific styles
│   └── js/
│       └── main.js           # Client-side JavaScript
├── templates/
│   ├── base.html             # Base template with navbar & footer
│   ├── landing.html          # Landing page with hero & dashboard mockup
│   ├── login.html            # User login page
│   ├── register.html         # User registration page
│   ├── terms.html            # Terms and Conditions
│   └── privacy.html          # Privacy Policy
├── requirements.txt          # Python dependencies
└── README.md
```

## Quick Start

**Prerequisites:** Python 3.10 or higher

```bash
# Clone the repository
git clone https://github.com/ris-gzp/Spendly.git
cd Spendly

# Create a virtual environment (recommended)
python -m venv venv
source venv/bin/activate        # macOS/Linux
venv\Scripts\activate           # Windows

# Install dependencies
pip install -r requirements.txt

# Run the app
python app.py
```

Open **http://localhost:5001** in your browser.

## Design Philosophy

Spendly uses a **warm, editorial design language** — no flashy gradients or neon colors. The UI is built around:

- **DM Serif Display** for headings — elegant and readable
- **DM Sans** for body text — clean and modern
- A muted **green accent** (`#1a472a`) that feels trustworthy for a finance app
- **Warm paper tones** (`#f7f6f3`) instead of stark white backgrounds
- Minimal, purposeful animations

Every design decision is intentional — this isn't a generic Bootstrap template.

## Roadmap

- [x] Landing page with hero section & dashboard mockup
- [x] User registration & login pages
- [x] Terms and Conditions & Privacy Policy pages
- [x] "How it works" video modal
- [ ] User authentication (session-based)
- [ ] SQLite database setup with schema
- [ ] Add / Edit / Delete expenses (CRUD)
- [ ] Category-wise spending breakdown
- [ ] Monthly spending summary & filters
- [ ] Profile page with user settings
- [ ] Data export (CSV)

## Screenshots

<div align="center">

| Landing Page | Dashboard Mockup |
|:---:|:---:|
| Hero section with CTA | Expense stats & category bars |

</div>

## Contributing

Contributions are welcome! Feel free to open an issue or submit a pull request.

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Built with care by [ris-gzp](https://github.com/ris-gzp)**

<sub>Track every rupee. Own your finances.</sub>

</div>
