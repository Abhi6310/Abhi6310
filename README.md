## Hi, I'm Abhi

CS grad from CU Boulder (May 2026). I build full-stack production systems and ML infrastructure, from FERPA-compliant platforms to on-device inference tools.

Open to SWE roles. [LinkedIn](https://www.linkedin.com/in/abhinavchalise/) · [Email](mailto:abhichalise3@gmail.com)

---

**Education**\
**University of Colorado Boulder** `May 2026`\
*B.S. Computer Science · Minor in Computer Engineering*

---

**Experience**

**Software Engineer, Practicum · University of Colorado Boulder**
- Built and deployed a FERPA-compliant course management platform serving 1,000+ students across 45+ courses, with role-based access controls enforcing federal data privacy requirements at the API layer
- Automated grade verification workflows across four graduate programs, reducing manual processing by 15% per 8-week session
- Containerized with Docker and shipped through a CI/CD pipeline to university infrastructure

---

**Projects**

**[NeuroTune](https://github.com/Abhi6310/NeuroTune)** `Python · React · FastAPI · Hugging Face`

- Built a focus-mode audio platform that modulates pitch, BPM, and audio properties in real time based on learned user behavior, with on-device inference via Hugging Face Transformers at zero per-session API cost
- Fine-tuned TinyBERT on user session features to classify cognitive state and drive real-time audio modulation decisions
- Shipped an async FastAPI backend and WebSocket pipeline connecting the React frontend to the inference layer, sustaining sub-100ms end-to-end latency under continuous audio load

**[AI Mancala](https://github.com/Abhi6310/AI_Mancala)** `JavaScript · GitHub Pages`

- Deployed a browser-playable Mancala engine with four AI opponents scaling from random play to minimax with alpha-beta pruning at search depth 10, achieving a 99% win rate against a random opponent
- Reduced node evaluations by 75% at depth 5 via alpha-beta pruning, delivering a 3.8× runtime speedup over pure minimax with sub-80ms move decisions at depth 10 on consumer hardware

**[STM32 Battleship](https://github.com/Abhi6310/STM32_Battleship)** `C · STM32 · LCD · Embedded Firmware`

- Built Battleship in bare-metal C on an STM32 microcontroller with live board rendering on an LCD display and a probabilistic AI opponent
- Coordinated game logic, display rendering, and input handling on a single processor without OS scheduling, using explicit timing budgets to prevent frame drops and input lag
