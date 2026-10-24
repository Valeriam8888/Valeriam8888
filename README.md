<div id="header" align="center">
    <h1>Привет, меня зовут Валерия </h1>
    <h3>Frontend-разработчик</h3>
</div>

<div id="socials" align="center">
  <a href="telegram-url">
    <img src="https://img.shields.io/badge/Telegram-blue?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram"/>
  </a>
</div>

### Обо мне
- 🌱 В настоящее время изучаю Js,React,Node.js.
- 📄 Резюме [CV](cv-link)
- 📫 Связаться можно через [LinkedIn](linkedin-link), [email](mailto:email-address)

---

### Languages and tools

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg" title="js" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" title="html" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" title="css" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" title="react" width="40" height="40"/>&nbsp;
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-plain.svg" title="git" width="40" height="40"/>&nbsp;

### My stat

name: Update streak statson:  schedule:    - cron: "0 3 * * *" # Run every day at 03:00  push:    paths:      - ".github/workflows/streak-stats.yml" # Run any time this file is modified  workflow_dispatch: # Run manually from the Actions tabjobs:  build:    runs-on: ubuntu-latest    permissions:      contents: write    steps:      - uses: actions/checkout@v7      - name: Generate streak stats        uses: DenverCoder1/github-readme-streak-stats@v1        with:          options: user=${{ github.repository_owner }}&theme=default&disable_animations=true&locale=ru          path: profile/streak.svg      - name: Commit streak stats        run: |          git config user.name "github-actions[bot]"          git config user.email "github-actions[bot]@users.noreply.github.com"          git add profile/streak.svg          git commit -m "Update streak stats" || exit 0          git push

---
