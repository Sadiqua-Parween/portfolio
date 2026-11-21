# Sadiqua Parween &bull; Portfolio

> **Systems & Concurrency Software Engineer | seL4 & GNOME Upstream Contributor**
> B.Tech in Computer Science & Artificial Intelligence at Newton School of Technology, S-VYASA University &bull; Bengaluru, India.

A minimalist, warm, and cozy personal portfolio website presenting 100% verified and accurate technical background, upstream open-source contributions, featured engineering projects, and research placement objectives. All frontend, styling, and in-browser message handling are self-contained in `index.html`.

---

## 🏛️ Upstream Open Source Engineering Experience

- **seL4 Foundation / Trustworthy Systems (UNSW)** &bull; *Nov 2026*
  - Engineered official multithreading synchronization architecture for the **seL4 Microkit** framework, reviewed and merged directly into `seL4:main` (**PR #624**, addressing issue #602).
  - Designed cross-Protection Domain (PD) mutual exclusion utilizing standard C11 atomics (`<stdatomic.h>`) with an `atomic_flag` spinlock over a 4KB shared memory region between concurrent processes.
  - Formulated multi-architecture build support and automated verification logic ensuring thread-safe counter increments and race-condition prevention under simulated seL4 execution.

- **GNOME Foundation** &bull; *Sep 2026 – Present*
  - Fixed asynchronous D-Bus IPC race conditions in GNOME Settings by synchronizing AccountsService D-Bus calls in C and GObject (**!3516 merged upstream**).
  - Eliminated multi-second compositor UI freezes during application icon drag-and-drop in GNOME Shell, restoring 60 FPS responsiveness by redesigning asynchronous state synchronization.
  - Modernized display-scale widget constraints using GTK4 and Libadwaita in GNOME Settings (**!3514 merged upstream**), resolving slider responsiveness flaws across variable DPI displays.
  - Resolved state desynchronization in GNOME Shell volume controls, closing 4 upstream bug reports through refactored slider snapping logic in JavaScript/GJS.

---

## 🚀 Featured Engineering & Applied AI Projects

1. **Setu — Bidirectional Real-Time Sign Language & Speech Platform** (*Sep 2026*)
   - *Python, OpenCV, MediaPipe, PyTorch, FastAPI, Web Speech API | Open Source*
   - Real-time assistive translation pipeline translating sign language to speech and vice-versa; achieved 94% recognition accuracy across 30+ dynamic sign gestures using MediaPipe landmarking.
   - Optimized computer vision inference loops using OpenCV multithreading, sustaining smooth 30+ FPS processing on low-power client hardware with <80ms end-to-end latency.

2. **Rentu — High-Concurrency Peer-to-Peer Resource Platform** (*Oct 2026*)
   - *React.js, Node.js, Express.js, MongoDB, Docker | Full-Stack Application*
   - Eliminated concurrent booking race conditions by developing a transactional date-interval collision algorithm preventing double-booking across simultaneous checkout requests.
   - Engineered compound indexing on multi-attribute queries, reducing MongoDB query latency from 380ms to <75ms under simulated concurrent load.

---

## 🛠️ Technical Skills

- **Systems & Low-Level**: C (C11/C99), C11 Atomics (`stdatomic.h`), Spinlocks, GObject, POSIX, D-Bus IPC, Memory Concurrency, Multithreading
- **OS & Microkernels**: seL4 Microkit, Protection Domains, Shared Memory Regions, Linux Internals (Compositor, GTK4, Libadwaita), QEMU
- **Languages & Tools**: Python, JavaScript (GJS / Node.js), C++, SQL, Git & GitHub Actions, Docker, Linux/Unix Shell
- **Applied AI & Backends**: OpenCV (Multithreaded Loops), MediaPipe, PyTorch / TensorFlow, FastAPI, MongoDB, PostgreSQL

---

## 🎓 Education & Work Rights

- **Degree**: Bachelor of Technology in Computer Science & Artificial Intelligence (Expected May 2029, CGPA: 7.57 / 10.0)
- **Institution**: Newton School of Technology, S-VYASA University &mdash; Bengaluru, India
- **Placement & Work Rights**: Seeking an accredited 6-Month Full-Time Research Placement (August 2026 – January 2027) for academic credit. Eligible for the Subclass 408 (Research Stream) Visa, fully supported by Home University No Objection Certificate (NOC) and institutional credit endorsement.

---

## 📬 Contact Links

- **Email**: [falaksadiqua786@gmail.com](mailto:falaksadiqua786@gmail.com)
- **Phone**: +91 9508021556
- **GitHub**: [github.com/Sadiqua-Parween](https://github.com/Sadiqua-Parween)
- **GitLab**: [gitlab.gnome.org/Sadiqua](https://gitlab.gnome.org/Sadiqua)
- **LinkedIn**: [linkedin.com/in/sadiquaparween](https://www.linkedin.com/in/sadiquaparween/)
