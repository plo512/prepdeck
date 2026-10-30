# PrepDeck

A phone-first practice app for data and BI interviews. One static page, no build step.

- **SQL:** 18 graded exercises that run in the browser on a sample marketplace database (sql.js), 36 concept flashcards, and a free-query sandbox.
- **Interview:** 41 questions with a timer that turns amber at 90 seconds and red at 2 minutes, plus self-ratings and notes per attempt.
- **Quiz:** 58 multiple-choice questions across Power BI & DAX, modeling & ETL, cloud, stats & Python, and SQL theory.
- **Progress:** streak, answer-length trend, quiz accuracy by topic.

Progress saves in the browser's local storage, so each device keeps its own history.

## Run locally

Open `index.html` in a browser, or serve the folder:

```
python -m http.server 8000
```

## Deploy

GitHub Pages: Settings → Pages → Deploy from a branch → `main` / root.
