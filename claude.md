# Portfolio PRD — Vinisha Sunkara

## Overview

Build a **single-page scrollable personal portfolio** for Vinisha Sunkara, a Data Science graduate student at Northeastern University. The portfolio should present a polished, professional identity to recruiters and hiring managers in the data science, ML engineering, and software reliability domains.

---

## Visual Design Direction

- **Style**: Classic & Professional — refined, corporate-grade aesthetic
- **Theme**: Light background with a navy/slate primary palette, gold or teal accent, subtle textures
- **Typography**: A distinctive serif or editorial display font for headings (e.g. Playfair Display or DM Serif Display) paired with a clean, readable body font (e.g. Source Serif Pro or Lora)
- **Motion**: Subtle fade-in and slide-up scroll animations on section entry; hover states on cards and links
- **Layout**: Single-page, full-width sections, consistent vertical rhythm, sticky top navigation

---

## Navigation (Sticky Top Bar)

Links to anchor sections on the same page:

- Overview
- Experience
- Projects
- Skills
- Leadership & Research
- Resume (download button)
- GitHub icon link
- LinkedIn icon link
- Email icon link

---

## Sections

### 1. Hero / Overview

**Purpose**: First impression — who Vinisha is and what she does.

**Content**:
- Full name: **Vinisha Sunkara**
- Title: *Data Science Graduate Student | ML & Data Engineering*
- One-line bio drawn from resume summary: "Data Science graduate student skilled in Python, SQL, ML pipelines, and automated data workflows — passionate about system reliability and data-driven decision making."
- CTA buttons: **Download Resume** | **Contact Me**
- Social icons: GitHub, LinkedIn, Email

---

### 2. Work Experience

**Purpose**: Show professional credibility through internship roles.

**Layout**: Vertical timeline or card-based list, most recent first.

**Entries**:

#### RINL Vizag Steel Plant — Data Analyst Intern
*Dec 2023 – Jul 2024 | Vizag, India*
- Automated data pipelines in Python/SQL for cleaning and transformation
- Built ARIMA forecasting models for predictive equipment maintenance
- Designed Streamlit dashboards for operational performance monitoring
- Processed 15 years of employee healthcare data; performed trend analysis

#### Shiash Info Solutions — Data Analyst Intern
*Jan 2023 – Nov 2023 | Chennai, India*
- Built real-time object detection system using YOLOv7
- Implemented StrongSORT object tracking at 85% accuracy
- Developed a Python/BeautifulSoup web scraping and ETL service
- Deployed end-to-end ML pipeline on Azure with CI/CD and model registry

---

### 3. Projects

**Purpose**: Demonstrate applied technical skills through built systems.

**Layout**: Card grid (2 columns on desktop, 1 on mobile), each card with tech tags.

**Cards**:

#### Knee Injury Classification
*Python, Streamlit, ResNet, Logistic Regression*
- Used ResNet for feature extraction from Stanford's medical imaging dataset
- Applied logistic regression with stratified cross-validation for generalizable classification

#### Blood Bank System
*Microsoft SQL, Python, Streamlit*
- Built a data management system for donor registration and blood request tracking
- Automated data cleaning pipelines and generated donation trend dashboards

---

### 4. Skills

**Purpose**: Let recruiters quickly scan technical competencies.

**Layout**: Grouped skill tags by category, rendered as pill/badge components.

**Categories**:
- **Programming & Tools**: Python, Java, SQL, JavaScript, REST APIs, Pandas, NumPy, PySpark, Scikit-learn, PyTorch, TensorFlow
- **Testing & Automation**: PyTest, Selenium, Postman, Unit Testing, Regression Testing
- **ML & Statistics**: Logistic Regression, Random Forest, ANOVA, Statistical Modelling, Feature Engineering
- **Systems & Cloud**: AWS (EC2, Lambda), Azure, Docker, Git, CI/CD, ETL Pipelines, Jira, Agile
- **Databases**: MySQL, SQLite, MongoDB

---

### 5. Leadership & Research

**Purpose**: Highlight academic achievement and published work.

**Layout**: Two sub-sections — Education and Research Publication.

**Education**:
- **Northeastern University**, MS in Data Science | GPA: 3.72/4 | Sep 2024 – May 2026 | Boston, MA
  - Coursework: Data Mining, DBMS, Cloud Computing, NLP, ML, Business Intelligence, Statistical Methods
- **VIT-AP University**, B.Tech in Computer Science and Engineering | GPA: 9.1/10 | Jun 2020 – May 2024 | Amaravathi, India
  - Coursework: OS, Software Engineering, OOP in Java, Data Structures & Algorithms

**Research Publication**:
- *Sunkara Vinisha et al.*, "SHAP Analysis Based Gastric Cancer Detection" — International Research Journal of Engineering and Technology (IRJET), July 2022

---

### 6. Contact / Footer

**Purpose**: Easy ways to reach Vinisha.

**Content**:
- Email: vinisha9999vin@gmail.com
- Phone: +1 (857) 693-2530
- GitHub: https://github.com/VinishaS *(placeholder — update with actual URL)*
- LinkedIn: https://www.linkedin.com/in/vinisha-sunkara/ *(placeholder — update with actual URL)*
- Small footer note: "Built with ♥ by Vinisha Sunkara"

---

## Resume Download

- The Resume PDF (`Resume_Vinisha.pdf`) should be linked as a downloadable asset
- Appears as a primary CTA button in the Hero section and as a nav link

---

## Technical Specs

| Attribute | Value |
|-----------|-------|
| Type | Single HTML file (self-contained) |
| Framework | Vanilla HTML/CSS/JS — no build tools required |
| Fonts | Google Fonts (Playfair Display + Lora) |
| Icons | Font Awesome or inline SVGs |
| Responsiveness | Mobile-first, breakpoints at 768px and 1200px |
| Animations | CSS transitions + IntersectionObserver scroll reveals |
| Deployment | Drop-in static file — works on GitHub Pages, Netlify, etc. |

---

## Deliverable

A single `.html` file that:
1. Is fully self-contained (no external dependencies beyond CDN fonts/icons)
2. Renders all 6 sections above in order
3. Has a sticky nav that highlights the active section on scroll
4. Includes a working resume download button (links to `Resume_Vinisha.pdf`)
5. Opens GitHub, LinkedIn, and email in new tabs

---

*PRD authored for Claude build target. Update placeholder GitHub/LinkedIn URLs before deploying.*