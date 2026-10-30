# Hi, I'm Eduardo Ferraz 👋

Full stack developer building with generative AI: LLMs in production, RAG and coding agents.
Computer Science student at the Federal University of Espírito Santo (UFES), Brazil.

## What I work on

**LLMs in production.** At Gama Ensino, an education company, I build the AI features of the platform:

- an essay-grading microservice that evaluates student essays against the ENEM rubric with the Gemini and ChatGPT APIs;
- question generation with a locally hosted Qwen model and RAG (Qdrant + BAAI/bge-m3 embeddings), with no per-call API cost.

**Orchestrating coding agents.** I run Claude Code as a small team instead of a single assistant: one model plans the task
and writes the guide, another model executes it, and a reviewer agent checks the result before anything is published.

**Automation with local LLMs.** Workflows in which the model runs next to the data, behind an OpenAI-compatible API
(LM Studio, Ollama), with structured JSON output and a human fallback when the answer cannot be trusted. See the n8n
demo below.

**Full stack.** TypeScript, Node.js, React/Next.js, Java/Spring Boot and Python on PostgreSQL and AWS (Lambda, EventBridge),
including a monolith-to-microservices migration and security hardening after penetration tests.

## Projects

| Project | What it is | Stack |
|---|---|---|
| [n8n-local-llm-support-triage](https://github.com/Eduardo-Ferraz/n8n-local-llm-support-triage) | Triage of food-delivery support messages with a local LLM: JSON-schema output, team and SLA from a routing table, human review when the answer does not validate. Measured run included. | n8n, LM Studio, Qwen |
| [fhir-llm-gateway](https://github.com/Eduardo-Ferraz/fhir-llm-gateway) | **Design phase.** Gateway that turns free-text clinical notes into validated HL7 FHIR R4 records with open-weight LLMs on local infrastructure, so health data never leaves the institution. Team of three, Computer Networks course. | WebSocket, Ollama, Qwen |
| [happy-paws-go](https://github.com/Eduardo-Ferraz/happy-paws-go) | Clickable prototype of a dog-walking marketplace, generated with Lovable from Software Engineering requirements and refined by the team. **[Live demo](https://happypawss.lovable.app)** | React, Vite, TypeScript |
| [pagerank-search-engine](https://github.com/Eduardo-Ferraz/pagerank-search-engine) | Mini search engine: inverted index on a symbol table, PageRank with the power method and ranked queries. Team project. | C |
| [multithreaded-mini-kernel](https://github.com/Eduardo-Ferraz/multithreaded-mini-kernel) | Mini-kernel that schedules processes with pthreads: FCFS, Round Robin and preemptive priority, on one or two CPUs. Pair project. | C, pthreads |

## 💻 My Tech Stack

<table>
  <tr>
    <!-- Backend -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/java/java-original.svg" alt="Java" title="Java" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/spring/spring-original.svg" alt="Spring" title="Spring" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/nodejs/nodejs-original.svg" alt="Node.js" title="Node.js" /></td>
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/python/python-original.svg" alt="Python" title="Python" /></td>
    <!-- Database -->
    <td><img width="40" src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/postgresql/postgresql-original.svg" alt="PostgreSQL" title="PostgreSQL" /></td>
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
