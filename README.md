<div align="center">

```
███████╗██╗  ██╗ █████╗ ██╗   ██╗ ██████╗ ███╗   ██╗
██╔════╝██║  ██║██╔══██╗╚██╗ ██╔╝██╔═══██╗████╗  ██║
███████╗███████║███████║ ╚████╔╝ ██║   ██║██╔██╗ ██║
╚════██║██╔══██║██╔══██║  ╚██╔╝  ██║   ██║██║╚██╗██║
███████║██║  ██║██║  ██║   ██║   ╚██████╔╝██║ ╚████║
╚══════╝╚═╝  ╚═╝╚═╝  ╚═╝   ╚═╝    ╚═════╝ ╚═╝  ╚═══╝
```

### Hi there, I'm Shayon 👋

**Final-year Computer Science Student @ Swansea University · Graduating 2027**  
**Java & Spring Boot Backend · Based in Wales 🏴󠁧󠁢󠁷󠁬󠁳󠁿 · Open to graduate software engineering roles across the UK**

[![LinkedIn](https://img.shields.io/badge/LinkedIn-shayon--dhar-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shayon-dhar/)
[![Profile Views](https://komarev.com/ghpvc/?username=shayondhar&style=flat-square&color=0e75b6)](https://github.com/ShayonDhar)

</div>

---

## About Me

I'm a final-year BSc Computer Science student at Swansea University, graduating in 2027. I mostly build backends in Java and Spring Boot, and I'm currently working on my dissertation: a chess coaching app that uses a language model to explain Stockfish's analysis, with rule-based checks to catch explanations that don't match the board.

- 🔭 **Currently building:** my dissertation, *Explaining Chess Engine Evaluations with Large Language Models* (Flutter + Stockfish + a locally served LLM)
- 🏠 **Recently shipped:** [Aelwyd](https://github.com/ShayonDhar/wales-mortgage-calculator), a full-stack mortgage affordability dashboard for Welsh home buyers
- 🖥️ **On the side:** running a self-hosted Ubuntu server with Docker and KVM virtual machines
- 🎓 **Studying:** BSc Computer Science @ Swansea University (final year)
- ♟️ **Off the keyboard:** 1300 on chess.com and climbing
- 💼 **Looking for:** graduate software engineering roles starting September 2027, anywhere in the UK

---

## 🚀 Featured Projects

### [🏠 Aelwyd — Welsh Mortgage Affordability Dashboard](https://github.com/ShayonDhar/wales-mortgage-calculator)

A full-stack dashboard that estimates how much someone can borrow and compares it with average sale prices from **HM Land Registry Price Paid Data** for Welsh postcode areas.

**Highlights:**
- Spring Boot REST API with a layered controller / service / repository design, DTOs and request validation
- `BigDecimal` arithmetic for all financial calculations, a 4.5× loan-to-income affordability limit, and year-by-year amortisation schedules
- Land Registry data downloaded, cleaned and loaded into PostgreSQL; area averages cached with Spring `@Cacheable`
- React + TypeScript dashboard, plus JUnit/Mockito and Vitest test suites
- I wrote the backend; the frontend, tests and docs were built with GitHub Copilot assistance, as documented in the project README

`Java 25` `Spring Boot 4` `PostgreSQL` `React` `TypeScript` `Docker Compose` `Maven`

---

### ♟️ Explaining Chess Engine Evaluations with LLMs *(dissertation, in progress)*

A mobile chess coaching app for beginners and intermediate players. Stockfish analyses each move on the phone, and a locally served open-source LLM turns the engine's numbers into a plain-English explanation.

**Plan:**
- Import games as PGN or positions as FEN, then classify moves (inaccuracy, mistake, blunder) from Stockfish's evaluation
- Extract factual claims from each explanation (pieces, squares, captures, checks) and verify them against the board and the engine's evaluation, regenerating rejected explanations up to a fixed limit
- Evaluate how much validation reduces factual errors, alongside pass rate, regenerations and latency

**Built so far:** an interactive Flutter board with legal-move validation using `dartchess`, move highlighting and unit tests.

`Flutter` `Dart` `dartchess` `Stockfish` `LLMs`

---

### [💎 JewelThieves](https://github.com/ShayonDhar/JewelThieves)
> *Team project for the CS-230 Software Engineering module @ Swansea University*

A Java recreation of the 1997 game *Jewel Chase* from the Microsoft Entertainment Pack, built from scratch with no game frameworks, using JavaFX and custom ASCII-based level files.

**Highlights:**
- 3 enemy types, including a Smart Thief that finds its route with Breadth-First Search
- Colour-matched movement rules, levers and gates, proximity bombs and time-extension clocks
- Save/load game state, player profiles and per-level top-10 leaderboards

`Java` `JavaFX` `FXML` `CSS` `OOP`

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Haskell](https://img.shields.io/badge/Haskell-5D4F85?style=flat-square&logo=haskell&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Frameworks & Libraries**

![Spring Boot](https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JUnit](https://img.shields.io/badge/JUnit-25A162?style=flat-square&logo=junit5&logoColor=white)

**Databases & Infrastructure**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnubash&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">

<img height="160" src="https://streak-stats.demolab.com?user=shayondhar&theme=tokyonight&hide_border=true" />

</div>

---

## 📫 Get in Touch

I'm open to graduate software engineering opportunities and always happy to chat about projects.

[![LinkedIn](https://img.shields.io/badge/Connect_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shayon-dhar/)

---

<div align="center">
  <sub>Built with ☕ and too many Stack Overflow tabs</sub>
</div>
