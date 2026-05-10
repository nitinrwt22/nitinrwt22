<div align="center">

<img src="assets/banner.svg" alt="Nitin Rawat — CS Student & Systems Builder" width="100%"/>

</div>

<br/>

<div align="center">

[![LeetCode](https://img.shields.io/badge/LeetCode-450%2B_Problems-FFA116?style=for-the-badge&logo=leetcode&logoColor=black)](https://leetcode.com/u/Nitin_Rwt2326/)
[![GitHub](https://img.shields.io/badge/GitHub-nitinrwt22-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/nitinrwt22)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Nitin_Rawat-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/nitin-rawat-477382312/)
[![Email](https://img.shields.io/badge/Email-nitin.rawat2326-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:nitin.rawat2326@gmail.com)

</div>

<br/>

---

## `> cat profile.txt`

```
OS          : Graphic Era Hill University, Dehradun
DEGREE      : B.Tech CSE · 2024–2028 · CGPA 8.78
PREV        : Army Public School, Clement Town, Dehradun · XII CBSE · 88.6%
LOCATION    : Dehradun, India
MISSION     : Build systems that actually work. Ship. Iterate.
STATUS      : 2nd Year (4th Sem) · Actively seeking internships
FOCUS       : DSA (C/C++) · Full-Stack Dev · Hackathons
SEEKING     : SWE Internship · Backend / Full-Stack roles
```

<br/>

---

## `> ls -la projects/`

<br/>

### `> ./run CodeMaster`

```
  ╔══════╗   ╔═══════╗   ╔═════╗   ╔══════════╗
  ║ SRC  ║──►║ LEXER ║──►║ AST ║──►║ REACT UI ║
  ╚══════╝   ╚═══════╝   ╚══╦══╝   ╚══════════╝
                             ║
                    ╔════════╩════════╗
                    ║  AVL · TRIE · G ║
                    ╚═════════════════╝
```

> **_A high-performance C static analysis engine that audits source code, resolves symbols in O(log N), and renders an interactive dependency graph — no external tools, no shortcuts._**

![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white)
![JSON](https://img.shields.io/badge/JSON-000000?style=flat-square&logo=json&logoColor=white)

| Component | Implementation | Complexity |
|---|---|---|
| Symbol lookup | AVL Tree–backed symbol table | O(log N) |
| Autocomplete | Trie over all identifiers | O(L) |
| Call graph | Directed graph + DFS traversal | O(V + E) |
| AST construction | Custom recursive descent parser | O(N) |
| Live dashboard | React + Vite, real-time JSON rendering | — |
| **Hardest decision** | _Preventing infinite loops in recursive AST traversal — solved with visited-node tracking + depth cap_ | — |

[![View Repo](https://img.shields.io/badge/GitHub-CodeMaster-0f2027?style=flat-square&logo=github)](https://github.com/nitinrwt22)

<br/>

---

### `> ./run atm-route-optimizer`

```
  ┌──────────────────────────────────────┐
  │  [₹ATM01] [₹ATM02] ··· [₹ATMnn]     │
  │       ↓  Priority Queue (MinHeap)    │
  │  [CRITICAL ATMs] ──► Knapsack DP     │
  │       ↓  ≤ ₹50L constraint           │
  │  [TRUCK LOADED] ──► TSP Route ──►    │
  └──────────────────────────────────────┘
```

> **_An end-to-end C++ logistics engine that monitors 100+ ATMs, ranks urgency with a Min-Heap, and dispatches optimally loaded trucks under a ₹50L cash constraint using 0/1 Knapsack DP._**

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
| **Hardest decision** | _Switching from O(N²) naive Knapsack to 1D DP array to stay real-time for 100+ ATM dispatch_ | — |

[![View Repo](https://img.shields.io/badge/GitHub-ATM_Optimizer-021B1A?style=flat-square&logo=github)](https://github.com/nitinrwt22)

<br/>

---

### `> ./run cramroom`

```
  ┌──────────────────────────────────────────┐
  │  [USER] ──► JWT Auth ──► [SESSION]       │
  │      ↕ WebSocket (pin · react · chat)    │
  │  [PostgreSQL state machine] ──► access   │
  │  Batched queries → 60% fewer DB hits     │
  └──────────────────────────────────────────┘
```

> **_A backend-driven Next.js study platform that enforces disciplined, time-bound collaborative sessions with real-time chat, JWT-gated access, and PostgreSQL state machines — no chaos, just structured prep._**

![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=flat-square&logo=postgresql&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

| Feature | Implementation |
|---|---|
| Auth & access control | JWT + role-based gates |
| Real-time chat | Express + WebSockets (pin, react) |
| Session state | PostgreSQL state machines |
| DB efficiency | 60% fewer round-trips via batched queries |
| **Hardest decision** | _Avoiding N+1 query chains in session transitions — refactored to batched PostgreSQL CTEs_ |

[![View Repo](https://img.shields.io/badge/GitHub-CramRoom-1a1a2e?style=flat-square&logo=github)](https://github.com/nitinrwt22)

<br/>

---

## `> htop --mode=skills`

```
── LANGUAGES ─────────────────────────────────────────────
C / C++         ████████████████░░░░  80%
JavaScript      ██████████████░░░░░░  70%
Python          █████████████░░░░░░░  65%

── WEB & STACK ───────────────────────────────────────────
HTML / CSS      ███████████████░░░░░  75%
React.js        ████████████░░░░░░░░  62%
Next.js         ███████████░░░░░░░░░  57%
Node / Express  ███████████░░░░░░░░░  57%
Tailwind CSS    ████████████░░░░░░░░  60%

── DATABASES ─────────────────────────────────────────────
PostgreSQL      ███████████░░░░░░░░░  55%
MySQL           ██████████░░░░░░░░░░  52%
Firebase        ████████░░░░░░░░░░░░  42%

── TOOLS & PLATFORM ──────────────────────────────────────
Git / GitHub    ████████████████░░░░  82%
VS Code         ██████████████████░░  90%
Postman / Figma ██████████░░░░░░░░░░  50%
Vercel          ████████████░░░░░░░░  60%

── CORE CS ───────────────────────────────────────────────
DSA             ████████████████░░░░  80%
OOP             ██████████████░░░░░░  72%
DBMS            ████████████░░░░░░░░  62%
System Design   ████████░░░░░░░░░░░░  42%  (learning)
```

<br/>

---

## `> git log --oneline achievements`

```
a3f91c2  [2024] Top 12 — HACK4DELHI @ NSUT Delhi (200+ teams competing)
e7d4b19  [2024] 5+ hackathons competed · still actively showing up
8b2c304  [2024] 450+ LeetCode problems solved · participating in contests
9c2a731  [2024] 150+ GitHub contributions · consistent shipping year-round
1f08e44  [2023] 88.6% · CBSE Class XII · Army Public School, Dehradun
d70a912  [2024] B.Tech CSE started · CGPA 8.78 after 3 semesters
```

<br/>

---

## `> stat github_activity`

<div align="center">

```
 ┌──────────────────────────────────────────────────┐
 │  🔴  🟡  🟢    nitin@github: ~/stats             │
 └──────────────────────────────────────────────────┘
```

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=nitinrwt22&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFD1&icon_color=FFB347&text_color=8899BB&rank_icon=github)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=nitinrwt22&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=00FFD1&text_color=8899BB)

![GitHub Streak](https://streak-stats.demolab.com?user=nitinrwt22&theme=tokyonight&hide_border=true&background=0D1117&stroke=00FFD1&ring=FFB347&fire=00FFD1&currStreakLabel=8899BB)

</div>

<br/>

---

## `> netstat -an --contacts`

```
Proto  Handle              Address                          Status
────────────────────────────────────────────────────────────────────
MAIL   Email               nitin.rawat2326@gmail.com        LISTENING
LINK   LinkedIn            nitin-rawat-477382312            ESTABLISHED
CODE   GitHub              nitinrwt22                       ACTIVE
OJ     LeetCode            Nitin_Rwt2326                    ACTIVE
TEL    Phone               +91 8126217910                   AVAILABLE
```

**→** [nitin.rawat2326@gmail.com](mailto:nitin.rawat2326@gmail.com) · [LinkedIn](https://www.linkedin.com/in/nitin-rawat-477382312/) · [GitHub](https://github.com/nitinrwt22) · [LeetCode](https://leetcode.com/u/Nitin_Rwt2326/)

<br/>

---

<div align="center">

*Nitin Rawat · B.Tech CSE '28 · Last commit: May 2026 · Built with black coffee and compiler errors*

</div>
