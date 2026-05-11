# Feature Engineering App

An interactive, multi-page Flask + Flowbite app covering Feature Creation and Feature Selection.

## Setup

1. **Install dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

2. **Set your Groq API key** in `app.py`:
   ```python
   GROQ_API_KEY = "your-actual-groq-api-key-here"
   ```
   Or set as environment variable:
   ```bash
   export GROQ_API_KEY="your-key"
   python app.py
   ```

3. **Add your company logo:**
   - Place your logo image at: `static/images/logo.png`
   - The navbar will automatically display it (falls back to "FE" text badge if not found)

4. **Add hero image (optional):**
   - Place at: `static/images/hero.png`
   - Recommended: transparent background PNG, ~500×500px
   - Shows on the home page right side with a gentle float animation

5. **Run the app:**
   ```bash
   python app.py
   ```
   Then open: http://localhost:5000

## Pages

| Page | URL | Topic |
|------|-----|-------|
| Home | / | Overview & navigation |
| Manual Features | /manual-features | Feature Creation Module 01 |
| Interaction Features | /interaction-features | Feature Creation Module 02 |
| Polynomial Features | /polynomial-features | Feature Creation Module 03 |
| Date-Time Features | /datetime-features | Feature Creation Module 04 |
| Aggregated Features | /aggregated-features | Feature Creation Module 05 |
| Correlation | /correlation | Feature Selection Module 06 |
| Chi-Square | /chi-square | Feature Selection Module 07 |
| ANOVA | /anova | Feature Selection Module 08 |
| Forward Selection | /forward-selection | Feature Selection Module 09 |
| Backward Elimination | /backward-elimination | Feature Selection Module 10 |
| RFE | /rfe | Feature Selection Module 11 |
| Quiz | /quiz | AI-Powered Knowledge Test |

## Features
- 🌗 Light/Dark mode toggle (persists across sessions)
- 🤖 Neelu chatbot powered by Groq Llama 3 — page-aware guidance
- 📊 Progress bar showing overall journey progress
- 🎮 Interactive demos on every page
- 📝 AI-generated quiz with instant feedback
- 🏆 Personalized quiz results from Neelu
