# Hi, I'm Abhi

Computer Science graduate from CU Boulder. I build full-stack production infrastructure and on-device ML systems, from FERPA-compliant platforms serving 1,000+ students to local-inference tools that run without the cloud.

Open to SWE roles. [LinkedIn](https://www.linkedin.com/in/abhinavchalise/) · [Email](mailto:abhichalise3@gmail.com)

*Currently building NeuroTune and shipping STM32 Battleship firmware.*

## Experience

**Software Engineer, Practicum · University of Colorado Boulder**
- Built and deployed a FERPA-compliant course management platform serving 1,000+ students across 45+ courses, with role-based access controls enforcing federal data privacy requirements at the API layer
- Automated grade verification workflows across four graduate programs, reducing manual processing by 15% per 8-week session
- Containerized with Docker and shipped through a CI/CD pipeline to university infrastructure

## Projects

**[NeuroTune](https://github.com/Abhi6310/NeuroTune)** `Python · TypeScript · FastAPI · Hugging Face · Next.js`

- Building an on-device focus-music platform where a natural-language intent drives a locally-run LLM that composes binaural-beat session schedules, with zero cloud calls or telemetry
- Designed the pipeline so a sentence-transformer classifies intent into a session taxonomy and a constrained-decoding LLM emits a schema-validated JSON schedule, backed by a hardcoded fallback that guarantees valid output on any failure
- Engineered the latency-bound path so every non-LLM stage (classify, retrieve, validate, stream, synthesize) stays under 100ms combined, with a retrieval feedback loop that improves sessions over time

**[AI Mancala](https://github.com/Abhi6310/AI_Mancala)** · [Live Demo](https://abhi6310.github.io/AI_Mancala/) `JavaScript · GitHub Pages`

- Deployed a browser-playable Mancala engine with four AI tiers from random play to alpha-beta pruning at depth 10, reaching a 99% win rate against a random opponent over 100 reproducible games
- Cut node evaluations by 75% at depth 5 with alpha-beta pruning, a 3.8× speedup over plain minimax at identical move quality

**[STM32 Battleship](https://github.com/Abhi6310/STM32_Battleship)** `C · STM32 · LCD · Embedded Firmware`

- Built Battleship in bare-metal C on an STM32F429 board, with touchscreen ship placement, live LCD board rendering, and a hunt-and-target AI opponent
- Ran game logic, rendering, and polled input from one cooperative loop with no OS, driving all timing off a 10ms hardware-timer tick instead of blocking delays

<table>
<tr>
<td valign="top" width="40%">

## Education

**University of Colorado Boulder** `May 2026`\
*B.S. Computer Science · Minor in Computer Engineering*

</td>
<td valign="top" width="60%">

## Skills

- **Languages** Python · TypeScript · JavaScript · C
- **Backend** FastAPI · SQLAlchemy · WebSocket · Docker · CI/CD
- **ML** PyTorch · Hugging Face Transformers
- **Frontend** React · Next.js · Redux Toolkit
- **Embedded** STM32 · bare-metal firmware

</td>
</tr>
</table>
