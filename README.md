# Lesson Studio

A private teaching dashboard for English tutors — built for organising students, lessons and lesson planning in one place.

## Features

- **Timetable** — a weekly and monthly calendar of all your lessons.
- **Student profiles** — level (CEFR A1–C2), goals, teacher notes, what to do next, and full lesson history.
- **Auto-prepared lesson plans** — open a student and their next lesson plan is already written, built from their goals, progress and your materials. Edit it by hand, change it with AI, regenerate, or save it as a PDF.
- **Lesson types** — Speaking, Grammar, IELTS, Cambridge, Business English, and more.
- **Progress tracking** — rate lessons and watch progress build up per student.
- **Repeating lessons** — book a weekly slot once and it fills the timetable.
- **Screenshot import** — drop in a screenshot of your booking schedule and it reads the students and times.
- **Teaching toolkit** — list the books, apps and websites you use so every plan is built around them.

## Running it

This is a single, self-contained `index.html` file — no build step, no dependencies to install.

The AI features (lesson-plan writing, "change with AI", screenshot import), automatic cloud saving of your data, and PDF export are provided by the **Claude Artifacts** runtime and work when the page is opened as a Claude Artifact. Opened as a plain static file or on a normal web host, the app still runs and saves data to that one browser, but those AI and cloud features are unavailable.

## Privacy

Your students and lessons are stored privately to your own Claude account and are not shared with anyone.
