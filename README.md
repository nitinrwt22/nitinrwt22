<div align="center">

<!-- ANIMATED TYPING HEADER -->
<a href="https://nitin-rawat-portfolio.vercel.app/">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=700&size=32&duration=3000&pause=1000&color=00FFD1&center=true&vCenter=true&multiline=true&repeat=false&width=700&height=80&lines=NITIN+RAWAT" alt="Nitin Rawat" />
</a>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=16&duration=2500&pause=800&color=FFB347&center=true&vCenter=true&multiline=true&width=700&height=50&lines=Systems+Builder+%7C+Backend+%26+DSA+Nerd+%7C+B.Tech+CSE+%2728" alt="subtitle" />

<br/>

<!-- BADGES ROW -->
[![Portfolio](https://img.shields.io/badge/🌐_Portfolio-nitin--rawat.vercel.app-00FFD1?style=for-the-badge&labelColor=0D1117)](https://nitin-rawat-portfolio.vercel.app/)
[![LeetCode](https://img.shields.io/badge/LeetCode-640%2B_·_1800%2B_Rating-FFA116?style=for-the-badge&logo=leetcode&logoColor=black&labelColor=0D1117)](https://leetcode.com/u/Nitin_Rwt2326/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nitin_Rawat-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=0D1117)](https://www.linkedin.com/in/nitin-rawat-477382312/)
[![GitHub](https://img.shields.io/badge/GitHub-nitinrwt22-ffffff?style=for-the-badge&logo=github&logoColor=white&labelColor=0D1117)](https://github.com/nitinrwt22)

<br/>

<!-- PROFILE VIEWS & STATS PILLS -->
![Profile Views](https://komarev.com/ghpvc/?username=nitinrwt22&color=00FFD1&style=flat-square&label=Profile+Views)
![GitHub followers](https://img.shields.io/github/followers/nitinrwt22?color=FFB347&style=flat-square&label=Followers)

</div>

<br/>

---

<div align="center">

```
╔══════════════════════════════════════════════════════════════════════╗
║                                                                      ║
║   $ whoami                                                           ║
║   > Nitin Rawat — 2nd Year CSE @ Graphic Era Hill University         ║
║                                                                      ║
║   $ cat mission.txt                                                  ║
║   > Build systems that scale. Ship fast. Think in algorithms.        ║
║                                                                      ║
║   $ echo $STATUS                                                     ║
║   > Actively seeking SWE Internship · Backend / Full-Stack roles     ║
║                                                                      ║
╚══════════════════════════════════════════════════════════════════════╝
```

</div>

---

## ⚡ About Me

```yaml
name        : Nitin Rawat
university  : Graphic Era Hill University, Dehradun
degree      : B.Tech CSE · 2024–2028
cgpa        : 8.78
school      : Army Public School, Clement Town, Dehradun · XII CBSE · 88.6%
location    : Dehradun, India 🇮🇳
focus       : [ Systems Programming, Backend Dev, DSA, Concurrency ]
currently   : [ Building PayLock, Grinding LeetCode, Shipping Projects ]
looking_for : SWE Internship · Backend · Full-Stack
```

---

## 🗂️ Projects

> *I don't just write code — I engineer systems. Here's proof.*

<br/>

### 🔒 PayLock — Concurrent Payment Transaction System

<div align="left">

```
  ┌─────────┐     ┌──────────────┐     ┌─────────────┐
  │  CLIENT │────►│  REST API    │────►│   MySQL DB  │
  └─────────┘     │  (Node.js)   │     └──────┬──────┘
                  └──────┬───────┘            │
                         │                    │ ACID
                  ┌──────▼───────┐     ┌──────▼──────┐
                  │  C++ Engine  │────►│  Mutex Lock │
                  │ (Concurrent) │     │  Atomics    │
                  └──────────────┘     └─────────────┘
```

> **_A production-grade concurrent payment backend integrating a C++ transaction engine with a Node.js REST layer — engineered to handle simultaneous requests without a single race condition._**

</div>

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

| Feature | Implementation | Detail |
|---|---|---|
| Concurrent transactions | Mutexes + atomic operations | Zero race conditions under load |
| Data integrity | ACID properties + DB constraints | Consistent state guaranteed |
| API layer | REST (Node.js / Express) | Transaction record management |
| Backend engine | C++ with concurrency primitives | High-throughput request handling |

[![View Repo](https://img.shields.io/badge/GitHub-PayLock-00FFD1?style=flat-square&logo=github&logoColor=black)](https://github.com/nitinrwt22/PayLock)

<br/>

---

### 📊 CodeMaster — C Code Analyzer & Symbol Browser

```
  ╔══════╗   ╔═══════╗   ╔══════╗   ╔══════════╗
  ║ SRC  ║──►║ LEXER ║──►║  AST ║──►║ REACT UI ║
  ╚══════╝   ╚═══════╝   ╚══╦═══╝   ╚══════════╝
                             ║
                    ╔════════╩════════╗
                    ║ AVL · TRIE · DFS║
                    ╚═════════════════╝
```

> **_A zero-dependency C99 static analysis engine: custom lexer → parser → AST, with hand-implemented AVL Tree, Trie, Max-Heap, and DFS-based call graph. Sub-30ms across 8 issue categories._**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![React](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

| Component | Implementation | Complexity |
|---|---|---|
| Symbol lookup | AVL Tree–backed symbol table | O(log N) |
| Autocomplete | Trie over all identifiers | O(L) |
| Call graph | Directed graph + DFS (29+ fn, 65+ edges) | O(V + E) |
| AST construction | Custom recursive descent parser | O(N) |
| Dead-code detection | DFS + adjacency-list graph | O(V + E) |
| Live dashboard | React 19 + HTML5 Canvas, real-time streaming | — |

[![View Repo](https://img.shields.io/badge/GitHub-CodeMaster-0f2027?style=flat-square&logo=github)](https://github.com/nitinrwt22/CodeMaster)

<br/>

---

### 🏧 ATM Route Optimizer

```
  ┌──────────────────────────────────────┐
  │  [₹ATM01] [₹ATM02] ··· [₹ATMnn]    │
  │       ↓  Priority Queue (Min-Heap)  │
  │  [CRITICAL ATMs] ──► Knapsack DP    │
  │       ↓  ≤ ₹50L constraint          │
  │  [TRUCK LOADED] ──► TSP Route ──►   │
  └──────────────────────────────────────┘
```

> **_An end-to-end C++ logistics engine monitoring 100+ ATMs, ranking urgency with a Min-Heap, and dispatching optimally loaded trucks under a ₹50L cash constraint using 0/1 Knapsack DP._**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Tailwind](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat-square&logo=tailwind-css&logoColor=white)
![Canvas](https://img.shields.io/badge/HTML5_Canvas-E34F26?style=flat-square&logo=html5&logoColor=white)

| Feature | Algorithm | Complexity |
|---|---|---|
| ATM urgency ranking | Priority Queue (Min-Heap) | O(log N) |
| Truck loading (₹50L cap) | 0/1 Knapsack DP | O(N × W) |
| Route clustering | K-Means | O(k × N × iter) |
| Route ordering | TSP approximation | O(N²) |
| Dashboard | Glassmorphic HTML5 Canvas | — |

[![View Repo](https://img.shields.io/badge/GitHub-ATM_Optimizer-021B1A?style=flat-square&logo=github)](https://github.com/nitinrwt22)

<br/>

---

### 📚 CramRoom — Collaborative Exam Prep Platform

```
  ┌──────────────────────────────────────────┐
  │  [USER] ──► JWT Auth ──► [SESSION]       │
  │      ↕ WebSocket (pin · react · chat)   │
  │  [PostgreSQL state machine] ──► access  │
  │  Batched queries → 60% fewer DB hits    │
  └──────────────────────────────────────────┘
```

> **_A full-stack collaborative exam platform: stateless Node.js/Express backend + PostgreSQL state machines enforcing time-bound study sessions, real-time events, and AI-powered PYQ analysis (in progress)._**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

| Feature | Implementation |
|---|---|
| Auth & access control | JWT + role-based gates |
| Real-time collaboration | WebSockets — async event handling |
| Session state | PostgreSQL state machines |
| DB efficiency | 60% fewer round-trips via batched CTEs |
| AI PYQ analyzer | NLP-based topic modeling *(in dev)* |

[![View Repo](https://img.shields.io/badge/GitHub-CramRoom-1a1a2e?style=flat-square&logo=github)](https://github.com/nitinrwt22/CramRoom-examsession)

---

## 🛠️ Tech Stack

<div align="center">

**Languages**

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)

**Frontend**

![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=next.js&logoColor=white)
![Tailwind](https://img.shields.io/badge/Tailwind-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)

**Backend & Databases**

![Node.js](https://img.shields.io/badge/Node.js-339933?style=for-the-badge&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=for-the-badge&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black)

**Tools & Platforms**

![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-2088FF?style=for-the-badge&logo=github-actions&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

**AI / ML**

![NLP](https://img.shields.io/badge/NLP-Topic_Modeling-8A2BE2?style=for-the-badge)
![LLM](https://img.shields.io/badge/LLM_Integration-Prompt_Eng-FF6B6B?style=for-the-badge)
![RAG](https://img.shields.io/badge/RAG-Retrieval_Augmented-00C9A7?style=for-the-badge)
![OCR](https://img.shields.io/badge/OCR_Pipelines-4ECDC4?style=for-the-badge)

</div>

---

## 🏆 Achievements

```
 ACHIEVEMENT LOG ─────────────────────────────────────────────────────────
                                                                          
  🥇  FINALIST   │ HACK4DELHI @ NSUT Delhi                               
                  │ AI misinformation detection — BERT + OCR + FastAPI   
                  │ Competed against 200+ teams                           
                                                                          
  ⚔️  COMPETITIVE │ 8+ Hackathons competed · still actively showing up   
                                                                          
  🧠  LEETCODE   │ 640+ problems solved · 1800+ contest rating           
                  │ → leetcode.com/u/Nitin_Rwt2326                       
                                                                          
  📦  SHIPPING   │ 4 production-grade projects built from scratch        
                                                                          
  🎓  ACADEMICS  │ CGPA 8.78 · B.Tech CSE · Graphic Era Hill University  
                  │ 88.6% · CBSE Class XII · Army Public School          
                                                                          
 ──────────────────────────────────────────────────────────────────────────
```

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nitinrwt22&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFD1&icon_color=FFB347&text_color=8899BB&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nitinrwt22&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFD1&text_color=8899BB)

![GitHub Streak](https://streak-stats.demolab.com?user=nitinrwt22&theme=tokyonight&hide_border=true&background=0D1117&stroke=00FFD1&ring=FFB347&fire=00FFD1&currStreakLabel=8899BB)

</div>

---

## 📬 Let's Connect

<div align="center">

```
┌─────────────────────────────────────────────────────────────────┐
│  I'm open to internship opportunities, collaborations,          │
│  and interesting systems problems. Let's build something real.  │
└─────────────────────────────────────────────────────────────────┘
```

[![Email](https://img.shields.io/badge/Gmail-nitin.rawat2326%40gmail.com-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nitin.rawat2326@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitin-rawat-477382312/)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit_Site-00FFD1?style=for-the-badge&logo=vercel&logoColor=black)](https://nitin-rawat-portfolio.vercel.app/)
[![LeetCode](https://img.shields.io/badge/LeetCode-Profile-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nitin_Rwt2326/)

</div>

<br/>

<div align="center">

*Nitin Rawat · B.Tech CSE '28 · Built with black coffee and compiler errors*

![wave](https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=6,11,20&height=80&section=footer)

</div>
