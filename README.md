# Techlytics ATS CV Review & Optimizer

An intelligent, client-side **Applicant Tracking System (ATS) Resume Reviewer, AI Optimizer, and Multi-Template Microsoft Word (`.docx`) Exporter**. Built with HTML, Tailwind CSS, JavaScript, and `docx.js`, this single-file application evaluates resumes against target job descriptions, suggests high-impact optimizations, and exports cleanly formatted Word documents without layout or hanging-indent bugs.

---

## ✨ Key Features

* **Dual-Engine ATS Scoring**:
  * **Local ATS Engine (Zero-Config)**: Runs deterministically in the browser using keyword extraction, metric detection, and rubric-based scoring—no API key required.
  * **Gemini AI Engine (Optional)**: Connect a Google Gemini API key (`gemini-2.5-flash`) for deep semantic evaluation and contextual resume rewriting.
* **4-Category ATS Breakdown**: Evaluates **Keyword Match**, **Skills & Tech Stack**, **Experience Alignment**, and **Formatting & Structure**.
* **Interactive Side-by-Side Editor**: Edit your tailored resume in real time with live structural previewing before exporting.
* **Multi-Template Microsoft Word (`.docx`) Export**:
  1. **Classic ATS Standard**: Single-column Calibri layout, full-width section borders, flush-right dates, and true hanging-indent bullets.
  2. **Modern Executive**: Deep Navy (`#1E3A8A`) Georgia headings, two-column role date tables, and a shaded summary callout box.
  3. **Minimalist Tech / Compact**: High-density `0.5"` margins, Segoe UI typography, and a categorized 2-column Skills Matrix table.

---

## 🚀 Quick Start & Deployment

### Run Locally
1. Clone or download this repository.
2. Open `automated_ats_cv_review_optimizer.html` in any modern web browser (Chrome, Edge, Firefox, Safari).

### Deploy on GitHub Pages
1. Rename `automated_ats_cv_review_optimizer.html` to `index.html`.
2. Push to your GitHub repository.
3. Go to **Settings > Pages**, select your main branch, and click **Save**. Your app will be live in seconds!

---

## ⚙️ Optional: Enabling Gemini AI

1. Click **API Settings** in the top navigation bar.
2. Paste your Google Gemini API key (stored securely in your browser's `localStorage`).
3. Click **Save Key**. The header badge will switch from **Local ATS Engine** to **Gemini AI Engine**.

---

## 🛠️ Tech Stack

* **Frontend**: HTML5, Tailwind CSS (CDN), Vanilla JavaScript (ES6+)
* **Document Generation**: `docx` v8.5.0 (client-side `.docx` binary generation)
* **Icons & Typography**: FontAwesome 6, Google Fonts (`Inter`)
* **AI Integration**: Google Gemini REST API (`gemini-2.5-flash`)

---

## 📄 License

This project is open-source and available under the [MIT License](LICENSE).
