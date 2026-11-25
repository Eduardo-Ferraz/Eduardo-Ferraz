# Hi, I'm Eduardo Ferraz 👋

**Software engineer building LLM applications (RAG, model serving and coding agents) on a backend foundation in
Java, Node.js and Python.**
Full stack engineer at Gama Ensino · Computer Science student at the Federal University of Espírito Santo (UFES), Brazil.

## Impact so far

| | |
|---:|---|
| **Thousands** | of students use the education platform I work on at Gama Ensino |
| **7,900+** | commits in **73** company repositories since September 2024, 25 of them with 100+ (counted from git history) |
| **12** | Java/Spring Boot microservices I have contributed to, with 10+ commits each |
| **72%** | of the commits behind the essay-grading product: the AI service, the backend, the student app and the admin |
| **2** | native student apps: Android (Kotlin, Jetpack Compose), published on Google Play in November 2026, and iOS (Swift, SwiftUI) |
| **Hundreds** | of iFood delivery couriers covered by the engagement dashboards I built on Discola for the iFood partnership |
| **~60%** | less query code after replacing hand-written queries with dynamic JPA Specification filters |
| **0** | critical vulnerabilities left after penetration-test-driven security hardening |
| **12** | developers led as Technology Director at CT Junior, a junior enterprise at UFES, with **100%** of deliveries on time |

## What I build

**LLM features in production.** At Gama Ensino, an education company, I build the platform's AI features:

- an essay-grading microservice that evaluates student essays against the ENEM rubric with the Gemini and ChatGPT APIs;
- question generation with a locally hosted Qwen model and RAG (Qdrant + BAAI/bge-m3 embeddings), with no per-call API cost.

**Serving open-weight models.** In a team project we built a gateway (Python, FastAPI, asyncio) in front of llama.cpp
inference nodes: per-node queues, load balancing, failover, token streaming over SSE, and output constrained by a JSON
Schema and validated again before it is released.

**Measuring before trusting the model.** Structured output, validation in code and a human fallback. In my n8n triage
demo all 8 answers were valid JSON, and a manual check still found 2 of them wrong; the README says so and names the next
step, a labeled evaluation set.

**Orchestrating coding agents.** I run Claude Code as a small team instead of a single assistant: one model plans the task
and writes the guide, another model executes it, and a reviewer agent checks the result before anything is published.

**Backend foundation.** Java/Spring Boot, Node.js/TypeScript and Python on PostgreSQL and AWS (Lambda, EventBridge): a
monolith-to-microservices migration, dynamic JPA Specification filters, and security hardening after penetration tests
(rate limiting, CSP, reCAPTCHA, JWT refresh tokens).

## Skills

- **LLM engineering:** LLM APIs (Gemini, OpenAI), open-weight models (Qwen on LM Studio and Ollama), RAG and embeddings
  (Qdrant, BAAI/bge-m3), structured output with JSON Schema, prompt engineering, n8n
- **AI-assisted development:** Claude Code with planner, executor and reviewer agents
- **Backend:** Java, Spring Boot, JPA, Node.js, TypeScript, Python, FastAPI, REST APIs
- **Mobile:** Kotlin with Jetpack Compose, Swift with SwiftUI
- **Data and cloud:** PostgreSQL, AWS (Lambda, EventBridge), Docker, Terraform, CI/CD
- **Quality and security:** JUnit, Mockito, Cypress, penetration-test-driven hardening

## Projects

| Project | What it is | Stack |
|---|---|---|
| [fhir-llm-gateway](https://github.com/Eduardo-Ferraz/fhir-llm-gateway) | **Implemented; real-model measurements pending.** Distributed gateway that serves open-weight LLMs on local infrastructure, with per-node queues, three balancing policies, failover, token streaming (SSE) and JSON-Schema-validated output, to turn clinical notes into structured records without sending health data to a cloud API. Team of three, Computer Networks course. The code is in private team repositories; this one holds the design record. | Python, FastAPI, asyncio, llama.cpp |
| [n8n-local-llm-support-triage](https://github.com/Eduardo-Ferraz/n8n-local-llm-support-triage) | Triage of food-delivery support messages with a local LLM: JSON-schema output, team and SLA from a routing table, human review when the answer does not validate. Includes a measured run and the 2 wrong answers a manual check found. | n8n, LM Studio, Qwen |
| [pagerank-search-engine](https://github.com/Eduardo-Ferraz/pagerank-search-engine) | The retrieval fundamentals behind RAG: an inverted index on a symbol table, PageRank with the power method and ranked queries. Team project. | C |
| [multithreaded-mini-kernel](https://github.com/Eduardo-Ferraz/multithreaded-mini-kernel) | Mini-kernel that schedules processes with pthreads: FCFS, Round Robin and preemptive priority, on one or two CPUs. Pair project. | C, pthreads |
| [happy-paws-go](https://github.com/Eduardo-Ferraz/happy-paws-go) | Clickable prototype of a dog-walking marketplace, generated with Lovable from Software Engineering requirements and refined by the team. **[Live demo](https://happypawss.lovable.app)** | React, Vite, TypeScript |

## 💻 My Tech Stack

<table>
  <tr>
    <!-- Backend -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring" title="Spring" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" title="Python" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/fastapi/fastapi-original.svg" alt="FastAPI" title="FastAPI" /></td>
    <!-- Database -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" /></td>
    <!-- Cloud -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/amazonwebservices/amazonwebservices-original.svg" alt="AWS" title="AWS" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" alt="Docker" title="Docker" /></td>
    <!-- APIs, DevOps & Tools -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postman/postman-original.svg" alt="Postman" title="Postman" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" alt="Git" title="Git" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original-wordmark.svg" alt="GitHub" title="GitHub" /></td>
    <!-- Core Languages -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/typescript/typescript-original.svg" alt="TypeScript" title="TypeScript" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-plain.svg" alt="JavaScript" title="JavaScript" /></td>
    <!-- Frontend -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/react/react-original.svg" alt="React" title="React" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nextjs/nextjs-original.svg" alt="Next.js" title="Next.js" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/angularjs/angularjs-original.svg" alt="Angular" title="Angular" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ionic/ionic-original.svg" alt="Ionic" title="Ionic" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg" alt="HTML5" title="HTML5" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg" alt="CSS3" title="CSS3" /></td>
    <!-- Testing -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cypressio/cypressio-original.svg" alt="Cypress" title="Cypress" /></td>
  </tr>
</table>

## Contact

[LinkedIn](https://www.linkedin.com/in/eduardo-ferraz1)
