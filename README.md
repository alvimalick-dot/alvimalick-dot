<div align="center">

```
$ file moeed_alvi.elf
moeed_alvi.elf: ELF 64-bit LSB executable, x86-64, statically linked,
                BuildID[human]=a1v1-m0d-2024, not stripped
```

</div>

<br>

```
readelf -h moeed_alvi.elf

ELF Header:
  Magic:    41 42 44 55 4C 20 4D 4F 45 45 44   >ABDUL MOEED<
  Class:                             ELF64 (Systems Engineer)
  Data:                              2's complement, little endian
  Type:                              EXEC (Executable — not a WIP)
  Machine:                           x86-64 native, cross-compiles to Web/Cloud
  Version:                           0x5 (5th Semester)
  Entry point address:               0xFA57NUCE5
  Start of section headers:          Islamabad, Pakistan
  OS/ABI:                            FAST-NUCES/Linux
  Status:                            ACCEPTING INTERNSHIP SYSCALLS
```

<br>

<div align="center">
<img src="https://img.shields.io/badge/-000000?style=flat-square" width="1">

<table>
<tr>
<td>

```c
/*
 * .comment section — human-readable metadata
 * (the compiler usually strips this, I kept it in)
 */

const char* who_am_i =
    "BS Computer Science @ FAST-NUCES Islamabad "
    "(2024 -> 2028, currently linking semester 5)";

const char* what_i_do =
    "I write code close to the metal, then bring "
    "the same discipline up the stack — backend "
    "services, dev infra, and the odd VGA framebuffer.";

const char* currently_building =
    "Project APEX — a multi-agent AI OS. "
    "I own DevOps/infra: Docker mesh, CI, queues, "
    "load tests. Three engineers, one monorepo, "
    "zero patience for silent merge conflicts.";
```

</td>
</tr>
</table>
</div>

---

## `objdump -d --section=.text moeed_alvi.elf`
### disassembly of core competencies

```asm
.text:
  0x0001  mov   eax, [c_cpp]           ; primary weapon of choice
  0x0002  mov   ebx, [x86_asm]         ; COAL — bare-metal, VGA, INT 09h
  0x0003  mov   ecx, [python]          ; heuristics, automation, tooling
  0x0004  mov   edx, [sql]             ; Oracle / MySQL / MSSQL, transactions
  0x0005  mov   esi, [fastapi_react]   ; backend + frontend, glued at the hip
  0x0006  mov   edi, [docker_redis_q]  ; infra: compose, queues, caching

  0x0007  push  discipline
  0x0008  push  low_level_intuition
  0x0009  call  ship_it                ; no floating dependencies, no dead code
  0x000A  test  eax, eax
  0x000B  jnz   fix_before_merge        ; ZF=0, no zero-defect tolerance
```

<sub>Registers actually loaded: C/C++ (advanced) · x86 Assembly · Python · Java · PHP · JavaScript/TypeScript · SQL (Oracle/MySQL/MSSQL) · FastAPI · React/Electron · PostgreSQL · Redis · Celery · Qdrant · Docker · Git</sub>

---

## `readelf -s moeed_alvi.elf`
### symbol table — shipped projects

```
Num:    Size   Type      Bind    Vis      Name
  0)  0x2A00   FUNC      GLOBAL  DEFAULT  project_apex
                  → multi-agent AI OS. FastAPI + Electron/React/TS + Qdrant +
                    Redis + PostgreSQL + Celery. I own the DevOps/infra layer:
                    service mesh, Alembic migrations, WS connection pooling,
                    tiktoken history trimmer, load-test suite.

  1)  0x1F40   FUNC      GLOBAL  DEFAULT  secure_ecommerce_engine
                  → FastAPI + PostgreSQL + Redis + Stripe. JWT auth with
                    refresh-token rotation. 46/46 pytest green.

  2)  0x1900   FUNC      GLOBAL  DEFAULT  taskboard
                  → FastAPI + React, full-stack kanban, dark terminal UI,
                    phosphor-green accent (obviously).

  3)  0x0C10   FUNC      LOCAL   DEFAULT  super_mario_clone.asm
                  → x86 Assembly platformer. Writes straight to VGA Mode 13h.
                    Keyboard handled via raw INT 09h hook. No OS middleman.

  4)  0x0B30   FUNC      LOCAL   DEFAULT  chrono_rift
                  → OS semester project. POSIX shared memory, pthreads,
                    signal handling, SFML front-end.

  5)  0x0A80   FUNC      LOCAL   DEFAULT  citymind_ai
                  → Python graph-search city-layout optimizer. Spanning-tree
                    heuristics over weighted infrastructure nodes.

  6)  0x0900   FUNC      LOCAL   DEFAULT  mehflix
                  → JavaFX event-management platform. Transactional booking,
                    zero double-bookings, zero orphan records.

  7)  0x0870   FUNC      WEAK    DEFAULT  sonic_multiplayer
                  → C++/SFML, 3-player local, fixed-timestep loop, 60 FPS,
                    zero per-frame heap allocations.
```

<details>
<summary><code>readelf --debug-dump=frames</code> — full backtrace, expand if you're not in a hurry</summary>

<br>

```
Stack trace (most recent frame first):
#0  0x555a  in build_project_apex ()        at semester-5/2026
#1  0x4a2c  in ship_secure_ecommerce ()     at internship-track/2026
#2  0x3f10  in complete_deloitte_forage ()  at internship-track/2026
#3  0x2ee8  in build_hunarmand_python ()    at internship-track/2025
#4  0x21a0  in build_taskboard ()           at internship-track/2025
#5  0x1620  in write_chrono_rift_os ()      at fast-nuces/os-course/2025
#6  0x0f00  in build_citymind_ai ()         at fast-nuces/coursework/2024
#7  0x0740  in build_mehflix ()             at fast-nuces/coursework/2024
#8  0x0300  in build_sonic_arcade ()        at self-directed/c++/2024
#9  0x0080  in write_super_mario_asm ()     at fast-nuces/coal-course/2024
#10 0x0000  in _start ()                    at fast-nuces/islamabad/2024
```

</details>

---

## `nm --dynamic moeed_alvi.elf`
### dynamic symbols — resolved at link time (contact)

```
U  GMAIL_HANDLE          0x67 6d 61 69 6c  ->  alvimalick@gmail.com
U  GITHUB_UPLINK         0x67 69 74 68 75  ->  github.com/alvimalick-dot
U  LINKEDIN_SOCKET       0x6c 69 6e 6b 65  ->  linkedin.com/in/abdul-moeed-alvi-722467321
U  PORTFOLIO_ENTRYPOINT  0x76 65 72 63 65  ->  portfolio-chi-orcin-gmpc77tqdj.vercel.app
```

<div align="center">

[![gmail](https://img.shields.io/badge/gmail-1a1a1a?style=flat-square&logo=gmail&logoColor=E8A33D)](mailto:alvimalick@gmail.com)
[![github](https://img.shields.io/badge/github-1a1a1a?style=flat-square&logo=github&logoColor=E8A33D)](https://github.com/alvimalick-dot)
[![linkedin](https://img.shields.io/badge/linkedin-1a1a1a?style=flat-square&logo=linkedin&logoColor=E8A33D)](https://linkedin.com/in/abdul-moeed-alvi-722467321)
[![portfolio](https://img.shields.io/badge/portfolio-1a1a1a?style=flat-square&logo=vercel&logoColor=E8A33D)](https://portfolio-chi-orcin-gmpc77tqdj.vercel.app)

</div>

---

<div align="center">

```
$ echo $?
0

Process finished, no core dumped.
Segments loaded. Waiting on next syscall: internship_offer()
```

</div>
