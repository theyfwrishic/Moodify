<div align="center">

# moodify

### A mood-tracking journal that gives you personalised wellbeing advice

Slide to describe how you feel, get a kind response and a small next step, and watch your mood over time.

[![Python](https://img.shields.io/badge/Python-app-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Google Gemini](https://img.shields.io/badge/Google-Gemini-8E75B2?logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![Browser demo](https://img.shields.io/badge/demo-HTML%20%2B%20JS-F7DF1E?logo=javascript&logoColor=black)](#try-the-browser-demo)

**By Team Stack Underflow**

![moodify check-in screen](docs/screenshots/check-in.png)

</div>

---

## About

In today's fast-paced and digitally connected world, mental wellbeing matters more than ever. Despite growing awareness, millions of people still struggle with their mental health and face barriers to getting effective care.

**moodify** is a Python-based mood-tracking journal. You use sliders to describe how you're feeling, and moodify returns a personalised response based on your emotions in that moment. It gives you an interactive way to reflect on your feelings throughout the year.

> moodify offers general wellbeing suggestions. It is not a medical tool and doesn't replace professional help. If you're struggling, please reach out to someone you trust or a mental health professional.

## Features

| Feature | What it does |
|---|---|
| **Mood sliders** | Rate your happiness, anger and anxiousness from 1 to 5 |
| **Personalised response** | An acknowledgement of how you're feeling, written in a warm, non-judgemental tone |
| **A gentle next step** | One small, practical thing you can do right now |
| **Your route this week** | A three-step plan for today, tomorrow and this week |
| **Mood journal** | Every check-in is saved, with a trend chart of your last 14 entries and a full history table |

## Screenshots

| Personalised advice | Mood journal |
|---|---|
| ![Advice screen](docs/screenshots/advice.png) | ![Journal with trend chart](docs/screenshots/journal.png) |

## Try the browser demo

`index.html` is a self-contained prototype that runs in any modern browser, with no install needed. You can also publish it with GitHub Pages.

In the demo:

- **Advice is generated on the device** from built-in responses, instead of calling Gemini like the full app.
- **Responses are grouped into four moods:** feeling bright, high anxiety or anger, feeling low, and somewhere in the middle.
- **Journal entries are saved in your browser's local storage.** They never leave your device, and you can clear them at any time.

## How it works

1. Open the **check-in** tab and move the three sliders.
2. Press **submit**.
3. Read what moodify noticed, the suggested next step and your route for the week.
4. Open the **journal** tab to see your mood trend and past entries.

## Tech stack

| Part | Built with |
|---|---|
| Full app | Python, with Google Gemini for the personalised responses |
| Browser demo | HTML, CSS and JavaScript, saving to browser local storage |
| Fonts | Josefin Sans and Poppins from Google Fonts |

## Project structure

```
moodify/
├── index.html          # Self-contained browser demo
└── docs/
    ├── moodify-Stack-Underflow-Presentation.pdf
    └── screenshots/
```

## Privacy

In the browser demo, your check-ins stay in your own browser and are never sent anywhere. In the full app, your slider values are sent to Google Gemini to generate the response.

## Roadmap

- [ ] Add a free-text journal entry alongside the sliders
- [ ] Track more emotions
- [ ] Weekly and monthly mood summaries
- [ ] Reminders to check in
- [ ] Links to helplines and support services

## Team

**Team Stack Underflow**

| Name | Role |
|---|---|
| Abyaz | Developer |
| Abhinav | Developer |
| Ojasva | UI design |
| Rishi Chowdhury | Presentation |

## License

Released under the [MIT License](LICENSE).
