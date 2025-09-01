```md
# Silas Moracha (mcmnyages) — Portfolio & Projects

Welcome — I’m Silas (GitHub: @mcmnyages). This repository is the central index for my work: academic projects, Android apps, SQL exercises, and an evolving collection of React and React Native apps. For a visual portfolio and contact info, visit my site: https://mcmnyages.github.io/silas_moracha.io/

Quick links
- Portfolio (GitHub Pages): https://mcmnyages.github.io/silas_moracha.io/
- GitHub: https://github.com/mcmnyages

Featured repositories
- mcmnyages/WORLD_MySQL — MySQL schemas, sample data and SQL exercises
- mcmnyages/CIT-415-Year-4 — Year 4 course projects and coursework
- mcmnyages/Android_Studio_Projects — Android Studio sample apps (Java/Kotlin)
- mcmnyages/classwork — Class assignments, small demos and exercises
- (Upcoming) React and React Native apps — mobile & web projects in progress

About this repo
This repository serves as a landing README that helps visitors quickly understand my work and find the right project. Each project contains its own README with project-specific details, run instructions, and screenshots where applicable.

Tech snapshot
- Frontend: React, React Native, Expo
- Mobile: Android (Java / Kotlin), Android Studio, Gradle
- Backend / Tools: Node.js, Express (when applicable)
- Database: MySQL
- Languages: Java, Kotlin, JavaScript (ES6+), SQL

Common quick start (by project type)

- Web (React)
  - Prereqs: Node >= 16, npm or yarn
  - Install: npm install
  - Dev: npm run start
  - Build: npm run build

- Mobile (React Native / Expo)
  - Prereqs: Node, npm/yarn, Expo CLI (if using Expo), or native toolchains for Android/iOS
  - Install: npm install
  - Run (Expo): expo start
  - Run (Android native): cd android && ./gradlew assembleDebug

- Android Studio projects
  - Open the project in Android Studio
  - Ensure required SDKs and a JDK are installed
  - Build/Run using the IDE or ./gradlew assembleDebug from the android directory

- SQL / MySQL
  - Import a schema or dump:
    mysql -u <user> -p <database> < schema.sql
  - Use sample data only; never commit production secrets.

Repository layout suggestions
- README.md — Project overview (this file)
- CONTRIBUTING.md — Contribution rules & PR guidance
- .gitignore — Node / Android / general ignores
- .github/workflows/ — CI definitions (optional)
- docs/ — Additional docs, screenshots, API notes
- sql/ — Database schema and seeds
- android/ — Android Studio project files
- src/ or app/ — Frontend / mobile source

Contributing
- Branching: feature/<short-name> or fix/<short-name>
- Commit messages: imperative tense (e.g. "Add login button")
- Pull requests: target main (or develop if used), include a short description and testing steps
- Tests & linting: add tests where practical and keep lint rules passing

Security & secrets
- Never commit .env, API keys, keystores, or other secrets.
- Use GitHub Secrets for CI and encrypted storage for signing keys.

Contact
- Portfolio / site: https://mcmnyages.github.io/silas_moracha.io/
- GitHub: https://github.com/mcmnyages
- Email: add an email address to your profile if you want direct contact

License
If you prefer a permissive license, add a LICENSE file (MIT is a common choice).

What I prepared
- A modern, concise README that links to your portfolio, highlights your main repos, and gives quick run instructions for the common project types you maintain.

Suggested next steps
- Add screenshots and repo-specific run instructions inside each repo.
- Add CONTRIBUTING.md and .gitignore to standardize contributions.
- Add CI workflows for React / Android projects to run builds and checks automatically.
```
