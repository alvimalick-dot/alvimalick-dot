<h3 align="left">👋 Hi, I'm Abdul Moeed Alvi</h3>

*Systems-obsessed engineer who thinks in registers and scales in distributed infrastructure.*

5th-semester CS undergraduate at FAST-NUCES Islamabad, shipping production-grade projects across x86 Assembly game engines, graph-algorithm AI planners, and multi-table relational backends. Actively seeking competitive software engineering internships in systems, backend, or AI/ML.

---

### 📊 Current Stack & Focus

<table>
<tr>
<td valign="top" width="50%">

**🛠️ What I'm working on**
- Low-level systems programming in x86 Assembly & C++
- Fullstack relational database applications
- AI-driven optimization & heuristic search
- Backend engineering with transactional integrity at the core

</td>
<td valign="top" width="50%">

**🧠 Core Philosophy**
- Build from first principles — hardware up, not framework down
- Zero tolerance for data corruption or silent failure states
- Optimize for measurable throughput, not just working code
- Seeking systems/backend/AI-ML internship opportunities

</td>
</tr>
</table>

---

### 🧰 Technical Skills Matrix

**Languages**

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=white)
![Assembly](https://img.shields.io/badge/x86_Assembly-6E4C13?style=flat-square&logo=assemblyscript&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

**Databases & Backend**

![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white)
![Oracle](https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white)
![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white)
![PHP/XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=flat-square&logo=xampp&logoColor=white)

**Systems & Frameworks**

![SFML](https://img.shields.io/badge/SFML-8CC445?style=flat-square&logo=cplusplus&logoColor=white)
![JavaFX](https://img.shields.io/badge/JavaFX-EA2D2E?style=flat-square&logo=openjdk&logoColor=white)
![Maven](https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white)
![OS Concepts](https://img.shields.io/badge/OS_%7C_Process_Scheduling-2C2C2C?style=flat-square&logo=linux&logoColor=white)
![VGA](https://img.shields.io/badge/VGA_%2F_Hardware_Interrupts-1A1A1A?style=flat-square&logo=chip&logoColor=white)

**Developer Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)
![AI Planning](https://img.shields.io/badge/AI_Planning_%7C_Graph_Algorithms-4B0082?style=flat-square&logo=graphql&logoColor=white)

---

### 📂 Engineering Architecture Portfolio

**Super Mario Clone (COAL)** | ![Assembly](https://img.shields.io/badge/x86_Assembly-6E4C13?style=flat-square&logo=assemblyscript&logoColor=white) ![Low-Level](https://img.shields.io/badge/Low--Level_Systems-1A1A1A?style=flat-square)

*Architectural Overview:* A frame-perfect 2D platformer engine written directly against VGA hardware, bypassing the OS I/O stack entirely.

- Achieved real-time frame rendering at consistent throughput by writing directly to VGA video memory (Mode 13h), eliminating rendering latency overhead
- Eliminated collision-detection errors across 100% of game states via a register-allocated bounding-box engine using dedicated CPU registers for position/velocity tracking
- Cut input lag to a single interrupt cycle by hooking hardware keyboard interrupts (INT 09h) directly to game-state handlers

---

**CityMind-AI: City Layout Optimizer** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![Graph Algorithms](https://img.shields.io/badge/Graph_Algorithms-4B0082?style=flat-square)

*Architectural Overview:* A heuristic-search planner that models urban layouts as weighted graphs to optimize infrastructure cost and commute efficiency.

- Reduced infrastructure cost by modeling land-use components as weighted graph nodes and applying spanning-tree heuristics to minimize total road-network edge weight
- Optimized zone placement using shortest-path algorithms, ranking configurations against a composite optimality function
- Produced visual city-map output alongside a scored trade-off report for comparing layout decisions against infrastructure constraints

---

**Mehflix — Event Management Platform** | ![Java](https://img.shields.io/badge/Java_17-ED8B00?style=flat-square&logo=openjdk&logoColor=white) ![JavaFX](https://img.shields.io/badge/JavaFX-EA2D2E?style=flat-square&logo=openjdk&logoColor=white) ![SQL](https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=mysql&logoColor=white)

*Architectural Overview:* A transactional relational-schema platform for managing event bookings across venue categories without collision or corruption.

- Eliminated double-booking across 5 venue categories via database-level conflict detection with composite unique constraints and transactional isolation
- Maintained full referential integrity across a normalized schema using foreign-key constraints and cascading rules, reducing orphan-record anomalies to zero
- Accelerated catalog filtering across 10+ service brands with indexed multi-table joins, delivering sub-second query response

---

**Hospital Management System** | ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white) ![MS SQL Server](https://img.shields.io/badge/MS_SQL_Server-CC2927?style=flat-square&logo=microsoftsqlserver&logoColor=white) ![XAMPP](https://img.shields.io/badge/XAMPP-FB7A24?style=flat-square&logo=xampp&logoColor=white)

*Architectural Overview:* A multi-table hospital records system built around transactional safety and automated reporting.

- Guaranteed zero partial-write data corruption by wrapping all multi-table operations in explicit transactions with rollback-on-error handlers
- Automated treatment-summary and ward-occupancy report generation via stored procedures and AFTER-INSERT triggers, reducing manual query overhead to a single call

---

**Sonic Triple-Player & Buzz Bomber Arcade** | ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![SFML](https://img.shields.io/badge/SFML-8CC445?style=flat-square)

*Architectural Overview:* A multiplayer arcade engine sustaining stable frame timing across concurrent player inputs.

- Sustained stable 60 FPS under three simultaneous player inputs via a fixed-timestep game loop decoupling physics from render calls
- Reduced per-frame memory allocations to zero by architecting an entity hierarchy with C++ inheritance/polymorphism, reusing preallocated objects across state transitions

---

### 📈 GitHub Analytics

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117)
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=tokyonight&hide_border=true&background=0d1117)

</div>

---

### 🌐 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/abdul-moeed-alvi-722467321)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:alvimalick@gmail.com)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-chi-orcin-gmpc77tqdj.vercel.app)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/alvimalick-dot)

</div>
