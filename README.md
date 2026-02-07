<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&height=220&text=Aliencito%20%7C%20OVNI&fontAlign=50&fontAlignY=35&desc=Dev%20Full-Stack%20%E2%80%A2%20Node%2FTS%20%E2%80%A2%20Prisma%20%E2%80%A2%20Postgres%20%E2%80%A2%20GitHub%20Actions&descAlign=50&descAlignY=55" />

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&pause=900&center=true&vCenter=true&width=820&lines=Dev+Full-Stack+%F0%9F%9A%80+Node%2FTS+%7C+Prisma+%7C+Postgres;Espa%C3%B1ol+first+%F0%9F%87%A6%F0%9F%87%B7+%E2%80%A2+Argentina;F%C3%BAtbol+%E2%9A%BD+Asado+%F0%9F%A5%A9+Milanesas+con+Pur%C3%A9+%F0%9F%8D%BD%EF%B8%8F;Buen+vino+%F0%9F%8D%B7+Fernet+%F0%9F%A5%83+Cerveza+%F0%9F%8D%BA+Hamburguesas+%F0%9F%8D%94;Desarrollando+Personalidad(%3F)+%F0%9F%91%BD" alt="Typing SVG" />

<br/>

<img height="120" src="https://github.com/MrAliencito.png" alt="MrAliencito avatar" style="border-radius: 999px;" />

<br/><br/>

<a href="https://komarev.com/ghpvc/?username=MrAliencito">
  <img src="https://komarev.com/ghpvc/?username=MrAliencito&style=for-the-badge" alt="profile views"/>
</a>
<a href="https://github.com/MrAliencito?tab=followers">
  <img src="https://img.shields.io/github/followers/MrAliencito?style=for-the-badge" alt="followers"/>
</a>
<a href="https://github.com/MrAliencito?tab=repositories">
  <img src="https://img.shields.io/badge/Repos-Explorar-000?style=for-the-badge" alt="repos"/>
</a>

</div>

---

## 🛸 Sobre mí

- 👽 **Aliencito | OVNI** (MrAliencito)
- 🇦🇷 **Argentina** — *Español first*
- 🧠 **Dev Full-Stack**: Node/TS, Prisma, PostgreSQL + automatizaciones con GitHub Actions
- 🎂 **23 años** • ♋ **Cáncer**
- ⚽ **Me gusta el fútbol** (si hay picadito, estoy)
- 🍽️ Fan de: **Milanesas con puré**, **asado**, **hamburguesas**
- 🍷🥃🍺 Y para brindar: **buen vino**, **fernet**, **cerveza**

---

## 🧰 Stack & herramientas

<div align="center">
  <img src="https://skillicons.dev/icons?i=ts,nodejs,express,prisma,postgres,sqlite,githubactions,git,js,html,css,docker&perline=12" />
</div>

---

## ✨ Proyectos (para chusmear)

- 🧊 **LuxKanban** — Kanban minimalista con glassmorphism + PWA  
  👉 https://github.com/MrAliencito/luxkanban  
  🌐 Demo: https://mraliencito.github.io/luxkanban/

- 🔗 **CortoLink** — Acortador de URLs con estadísticas (Node + Express + Prisma)  
  👉 https://github.com/MrAliencito/cortolink

- ☿ **Mercurio API** — JWT, roles, Prisma + PostgreSQL, TypeScript, Swagger y CI  
  👉 https://github.com/MrAliencito/Mercurio-API

- ✅ **Tareas (ES)** — App de tareas Node + Express + Prisma (UI simple)  
  👉 https://github.com/MrAliencito/tareas-es

---

## 📊 Stats (porque somos chusmas)

<div align="center">

<img height="170" src="https://github-readme-stats.vercel.app/api?username=MrAliencito&show_icons=true&hide_title=true&include_all_commits=true&count_private=true" />
<img height="170" src="https://github-readme-stats.vercel.app/api/top-langs/?username=MrAliencito&layout=compact&langs_count=8" />

<img height="180" src="https://streak-stats.demolab.com?user=MrAliencito" />

<img src="https://github-profile-trophy.vercel.app/?username=MrAliencito&no-frame=true&row=1&column=7" />

<img src="https://github-readme-activity-graph.vercel.app/graph?username=MrAliencito&hide_border=true" />

</div>

---

## 🔗 Donde encontrarme

<div align="center">

<a href="https://instagram.com/Aliencitoc2">
  <img src="https://img.shields.io/badge/Instagram-@Aliencitoc2-000?style=for-the-badge&logo=instagram" />
</a>
<a href="https://tiktok.com/@Aliencitoc2">
  <img src="https://img.shields.io/badge/TikTok-@Aliencitoc2-000?style=for-the-badge&logo=tiktok" />
</a>
<a href="https://orcid.org/0009-0003-9472-7824">
  <img src="https://img.shields.io/badge/ORCID-0009--0003--9472--7824-000?style=for-the-badge&logo=orcid" />
</a>

</div>

---

## 🐍 Snake de commits (animado)

> Si querés el snake, creá este workflow y listo. (Se genera solo en la rama `output`)

<details>
<summary><b>✅ Ver workflow (.github/workflows/snake.yml)</b></summary>

```yml
name: Generate Snake

on:
  schedule:
    - cron: "0 0 * * *"
  workflow_dispatch:

permissions:
  contents: write

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - name: Generate snake svg
        uses: Platane/snk/svg-only@v3
        with:
          github_user_name: MrAliencito
          outputs: |
            dist/snake.svg
      - name: Push to output branch
        uses: crazy-max/ghaction-github-pages@v4
        with:
          target_branch: output
          build_dir: dist
        env:
          GITHUB_TOKEN: ${{ secrets.GITHUB_TOKEN }}
</details> <div align="center"> <img src="https://raw.githubusercontent.com/MrAliencito/MrAliencito/output/snake.svg" alt="snake animation"/> </div>
<div align="center">
🌌 “Code, fútbol y asado… el resto se acomoda solo.” 👽
<img src="https://capsule-render.vercel.app/api?type=waving&height=120&section=footer" /> </div> ```

