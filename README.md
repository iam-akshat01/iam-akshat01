<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1a1f29&height=180&section=header&text=Akshat%20Mani%20Tripathi&fontSize=42&fontColor=58a6ff&fontAlignY=40&desc=Backend%20Engineer%20%7C%20Distributed%20Systems%20%7C%20System%20Design&descAlignY=58&descSize=16&descColor=8b949e&animation=fadeIn" width="100%"/>

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=20&duration=3000&pause=900&color=58A6FF&center=true&vCenter=true&width=640&lines=Building+event-driven+backend+systems;Spring+Boot+%2B+RabbitMQ+%2B+PostgreSQL;CS+undergrad+at+NIT+Hamirpur;Currently+deep+in+Distributed+Systems" alt="Typing SVG" />
</a>

</div>

<br/>

## About

I'm a Computer Science undergraduate at **NIT Hamirpur**, focused on backend engineering — building services that have to actually talk to each other correctly, not just return JSON. Most of my project work centers on **event-driven architecture**, **message queues**, and **distributed systems fundamentals**, backed by active DSA practice and coursework in system design.

I care about understanding *why* a system is built a certain way — consistency models, failure handling, message delivery guarantees — not just shipping a feature that works on the happy path.

```text
Currently building   →  Multi-service video platform (Spring Boot + RabbitMQ + FFmpeg)
Currently learning    →  Distributed consensus, system design at scale
Actively practicing   →  DSA / competitive programming
Open to               →  Backend engineering internships & SDE roles
```

<br/>

## Tech Stack

**Languages**
<br/>
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
<img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
<img src="https://img.shields.io/badge/SQL-4479A1?style=flat-square&logo=postgresql&logoColor=white" />

**Backend & Messaging**
<br/>
<img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white" />
<img src="https://img.shields.io/badge/Spring_Security-6DB33F?style=flat-square&logo=spring&logoColor=white" />
<img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
<img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" />
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" />

**Data & Infra**
<br/>
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
<img src="https://img.shields.io/badge/AWS_S3-569A31?style=flat-square&logo=amazons3&logoColor=white" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
<img src="https://img.shields.io/badge/FFmpeg-007808?style=flat-square&logo=ffmpeg&logoColor=white" />

**Tools**
<br/>
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" />
<img src="https://img.shields.io/badge/Maven-C71A36?style=flat-square&logo=apachemaven&logoColor=white" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" />
<img src="https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black" />

<br/>

## Featured Projects

### [Streaming-Core](https://github.com/iam-akshat01/Streaming-Core) — Event-Driven Video Platform
A multi-service video upload and transcoding system. The API service (`streamingv2`) issues presigned S3 upload URLs, persists video metadata, and publishes a processing job to RabbitMQ. A separate `transcoding-worker` service consumes that job, runs FFmpeg transcoding, uploads the output back to S3, and updates video status — two independently deployable Spring Boot services communicating asynchronously through a shared message contract.

`Spring Boot` `RabbitMQ` `PostgreSQL` `AWS S3` `FFmpeg` `Spring Security`

→ Producer/consumer pair, structured AMQP message DTO, presigned-URL upload flow, video status state machine.

---

### [backend-projs](https://github.com/iam-akshat01/backend-projs) — Auth & File Upload Services
Two standalone REST APIs built to get authentication and authorization right: JWT-based auth with OTP email verification and rate limiting (`auth/`), and a role-based file upload service with Multer, PostgreSQL via Drizzle ORM, and Redis configured for caching (`file_upload_system/`).

`Node.js` `Express` `MongoDB` `PostgreSQL` `Drizzle ORM` `JWT` `Zod`

→ Layered architecture (controller / service / middleware / validator), RBAC middleware, request validation, rate limiting.

---

### AI DSA Interviewer — Multi-Agent Interview Simulator *(local, not yet pushed)*
A backend-driven mock technical interview system built around five chained LLM agents — problem understanding, approach evaluation, coding, code review, and final report generation — each with an externalized prompt file, orchestrated as a sequential pipeline via `llmService.js`. Built on Gemini.

`Node.js` `Express` `Gemini API` `Multi-Agent Orchestration`

→ Currently local-only. Will be pushed and linked here once cleaned up for public review.

---

### [Competitive-Programming](https://github.com/iam-akshat01/Competitive-Programming) — DSA Problem Solving
Ongoing problem-solving practice across data structures and algorithms, including greedy strategies, graph problems, and standard interview-style questions.

`C++` `Data Structures` `Algorithms`

<br/>

## GitHub Stats

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=iam-akshat01&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=iam-akshat01&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=iam-akshat01&theme=tokyonight&hide_border=true&background=0D1117&stroke=58A6FF&ring=58A6FF&fire=58A6FF&currStreakLabel=58A6FF" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=iam-akshat01&theme=tokyo-night&hide_border=true&bg_color=0d1117&color=58a6ff&line=58a6ff&point=c9d1d9" width="100%"/>
</div>

<div align="center">
<img src="https://raw.githubusercontent.com/iam-akshat01/iam-akshat01/output/snake-dark.svg" width="100%" alt="contribution snake animation" />
</div>

<br/>

## Connect

<div align="center">

<a href="mailto:YOUR_EMAIL_HERE"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" /></a>
<a href="https://linkedin.com/in/YOUR_LINKEDIN_HERE"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" /></a>
<a href="https://leetcode.com/YOUR_LEETCODE_HERE"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=flat-square&logo=leetcode&logoColor=white" /></a>

<br/><br/>

![Profile Views](https://komarev.com/ghpvc/?username=iam-akshat01&style=flat-square&color=58a6ff&label=Profile+Views)

</div>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a1f29,100:0d1117&height=80&section=footer" width="100%"/>
