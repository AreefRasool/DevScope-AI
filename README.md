# 🎯 DevScope AI — GitHub Portfolio Intelligence Platform

**DevScope AI** analyzes any public GitHub profile the way a technical recruiter would — pulling repository data, scoring portfolio quality, and turning it into a clean, visual report card. Just enter a username and get an instant **A+ to F grade**, a breakdown of language diversity, top repositories, documentation quality, and activity trends, all rendered in an interactive **Gradio** dashboard powered by **Plotly** analytics.

Built for developers who want an honest, data-driven look at how their GitHub profile would actually read to a hiring manager.

![Status](https://img.shields.io/badge/status-active-success)
![Python](https://img.shields.io/badge/python-3.9%2B-blue)
![Gradio](https://img.shields.io/badge/built%20with-Gradio-orange)
![GitHub API](https://img.shields.io/badge/data-GitHub%20REST%20API-181717)

---

## 🎯 Features

- **🔍 GitHub Profile Analysis** — Pulls live profile data directly from the GitHub REST API.
- **📦 Repository Analytics** — Breaks down every public repo by stars, forks, and language.
- **🏆 Portfolio Scoring System** — Converts raw GitHub stats into a single, weighted portfolio score.
- **🎓 Recruiter-Style Grades** — Translates the score into familiar grades (A+, A, B, C...).
- **🧩 Language Distribution Analysis** — Visualizes the tech stack spread across all repositories.
- **⭐ Top Repositories by Stars** — Surfaces the profile's strongest, most-starred projects.
- **👥 Followers & Activity Tracking** — Tracks community reach and recent contribution activity.
- **📄 Documentation Quality Assessment** — Checks for README presence and quality across repos.
- **🎨 Project Diversity Evaluation** — Rewards varied, well-rounded project portfolios over repetition.
- **📊 Interactive Plotly Charts** — Fully interactive visual analytics, not static images.
- **🖥️ Modern Gradio Dashboard** — Clean, recruiter-friendly UI for sharing or demoing live.

---

## 📸 Preview

### Dashboard
![Dashboard](dashboard.png)

### Portfolio Analysis
![Analysis](analysis.png)

### Analytics Charts
![Charts](charts.png)

---

## 🖥️ Tech Stack

| Tool | Purpose |
|------|---------|
| [Gradio](https://www.gradio.app/) | Interactive web dashboard |
| [Plotly](https://plotly.com/python/) | Data visualization & charts |
| [Pandas](https://pandas.pydata.org/) | Data wrangling & analysis |
| [Requests](https://docs.python-requests.org/) | GitHub REST API calls |
| [GitHub REST API](https://docs.github.com/en/rest) | Source of profile & repo data |
| Python 3.9+ | Core logic |

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/<your-username>/<repo-name>.git
cd <repo-name>
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```
Or directly:
```bash
pip install gradio requests pandas plotly
```

### 3. Run the app
```bash
python app.py
```

The app will launch locally and also generate a shareable public link via Gradio's `share=True`.

> 💡 **Running in Google Colab / Kaggle?** Upload `app.py`, install dependencies with `!pip install gradio requests pandas plotly`, then run the script — Gradio will give you a public shareable link.

---

## 🧠 How It Works

1. **Enter** a GitHub username
2. **Fetch** profile and repository data via the GitHub REST API
3. **Analyze** portfolio quality across multiple weighted factors
4. **Generate** a recruiter-style score and letter grade
5. **Display** insights, charts, and a full analytics breakdown

---

## 📐 Scoring Factors

The portfolio score is calculated from a weighted mix of:

- Repository Count
- GitHub Stars
- Followers
- Technology Diversity
- Documentation Quality
- README Presence
- Project Diversity
- Recent Activity

---

## 📊 Example Output

```
Portfolio Score: 95 / 100
Grade: A+

Metrics:
- Repositories : 24
- Followers    : 132
- Stars        : 410
- Forks        : 58
- Languages    : 7
```

---

## 📌 Future Improvements

- 🤖 AI-powered career recommendations based on profile gaps
- 📄 Resume analysis and GitHub-to-resume matching
- 📝 Deeper README quality scoring (structure, completeness, badges)
- 📈 Contribution graph & commit-streak analysis
- 🤝 Team collaboration scoring for org-based contributors

---

## 👤 Author

**Areef Rasool**

BSAI Student | AI, Development & Networking Enthusiast

Built with Python, Gradio, and the GitHub REST API.

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
