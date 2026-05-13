<div align="center">

  <h1>Rating Content Indicator</h1>
  <p><b>An AI-powered solution to summarize, categorize, and track user review satisfaction.</b></p>

  <img src="https://img.shields.io/badge/Status-Planning-lightgrey?style=for-the-badge&logo=blueprint" alt="Planning">
  <!-- <img src="https://img.shields.io/badge/Status-Developing-orange?style=for-the-badge&logo=visualstudiocode" alt="Developing"> -->
  <!-- <img src="https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge&logo=checkmarx" alt="Completed"> -->
  <!-- <img src="https://img.shields.io/badge/Status-Maintenance-blue?style=for-the-badge&logo=wrench" alt="Maintenance"> -->

  <br>
  
  <p>
    <a href="#about">About</a> •
    <a href="#features">Features</a> •
    <a href="#tech-stack">Tech Stack</a> •
    <a href="#prerequisites">Prerequisites</a> •
    <a href="#configuration">Configuration</a> •
    <a href="#installation">Installation</a> •
    <a href="#usage">Usage</a> •
    <a href="#license">License</a> •
    <a href="#contact">Contact</a>
  </p>
</div>

---

## About

The **Rating Content Indicator** was developed to streamline the collection and organization of business reviews. Powered by AI, the system categorizes reviews into satisfaction levels and key topics, providing quick, actionable insights that help teams make data-driven decisions.
>**Why this project?**  
>Manual review analysis is slow and inconsistent. This tool automates the process, ensuring every review is accurately classified and structured for reporting.

---

## Features

- [ ] **Review Analysis** - Comprehensive data organization with advanced filtering for efficient management.
- [ ] **Categorized Reporting** - Generates detailed reports based on selected filters and metrics.
- [ ] **AI Integration** - Autonomous AI agent that scrapes, categorizes, and routes review data without manual intervention.
- [ ] **Cross-Platform** - Fully functional across different operating systems and environments.

---

## Tech Stack

<p>
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JAVASCRIPT">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="PYTHON">
  <img src="https://img.shields.io/badge/Groq-F55036?style=for-the-badge&logoColor=white" alt="GROQ">
</p>

---

## Prerequisites
Before getting started, ensure you have:
*   Python 3.8 or higher installed.
*   The latest version of `pip` (Python package manager).

---

## Configuration

This project uses environment variables to manage sensitive credentials.

1. Create a `.env` file in the root directory:

  ```bash
  cp .env.example .env
  ```

2. Fill in your AI credentials:

  ```env
  # AI Provider
  AI_API_KEY=sua_chave_aqui

  # Application Settings
  APP_ENV=development
  DEBUG=True
  ```

3. Ensure `.env` is listed in your `.gitignore`- **never commit your API keys**
>Refer to `.env.example` for a full list of available variables and descriptions.

---

## Installation

```bash
# 1. Clone the repository
git clone https://github.com/15LUCASARAUJO/Rating-content-indicator.git
cd Rating-content-indicator

# 2. Create a virtual environment
python -m venv venv

# 3. Activate the virtual environment
#    Windows:
.\venv\Scripts\activate
#    macOS/Linux:
source venv/bin/activate

# 4. Install dependencies
pip install -r requirements.txt
```

---

## Usage

```bash
# Start the application
python app.py
```
>Usage instructions may vary depending on your setup. Check the internal documentation or available CLI flags for more details.

---

## License

This project is licensed under the **MIT License** — see the [LICENSE.md](LICENSE.md) for details.

---

## Contact

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/lucas-araujo-de-paula-8463b9271)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/15LUCASARAUJO)
</div>

---

<div align="center">
  <sub>Made by <a href="https://github.com/15LUCASARAUJO">Lucas Araujo</a></sub>
</div>
