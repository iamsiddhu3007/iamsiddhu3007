<div align="center">

  <h1>Mohana Siddhartha Chivukula</h1>
  <p><b>Software Engineer · AI Infrastructure, Distributed Systems & Multi-Agent Platforms</b></p>

  <a href="https://github.com/iamsiddhu3007">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=18&duration=3000&pause=1000&color=38BDF8&center=true&vCenter=true&width=650&lines=Distributed+Systems+%26+AI+Infrastructure;Autonomous+Multi-Agent+Platforms;Production+Hybrid+RAG+%26+Inference+Meshes;Open+Source+Contributor+%40+LiteLLM" alt="Typing SVG" />
  </a>

  <p>
    <a href="https://github.com/iamsiddhu3007"><img src="https://img.shields.io/badge/GitHub-iamsiddhu3007-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
    <a href="https://www.linkedin.com/in/siddharthachivukula/"><img src="https://img.shields.io/badge/LinkedIn-Siddhartha_Chivukula-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="mailto:mohanasiddhartha.chivukula@gmail.com"><img src="https://img.shields.io/badge/Email-mohanasiddhartha.chivukula%40gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

</div>

---

### 🌐 Open Source Contributions

<table>
  <tr>
    <td>
      <h3>
        <a href="https://github.com/BerriAI/litellm">BerriAI / LiteLLM</a>
        &nbsp;
        <a href="https://github.com/BerriAI/litellm/pull/25610"><img src="https://img.shields.io/badge/PR_%2325610-Merged-8957e5?style=flat-square&logo=git&logoColor=white" alt="PR Merged" /></a>
      </h3>
      <p><b>Added pricing configuration, model specs, and regression tests for Gemini 3.1 Flash Lite Preview</b></p>
      <ul>
        <li>Implemented accurate cost tracking and token rate calculation for Google Gemini 3.1 Flash Lite via OpenRouter.</li>
        <li>Wrote automated unit & regression tests ensuring deterministic pricing evaluations across LLM routing workflows.</li>
      </ul>
      <p>
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white" />
        <img src="https://img.shields.io/badge/LiteLLM_Proxy-0284C7?style=flat-square" />
      </p>
    </td>
  </tr>
</table>

---

### 🛠️ Featured Repositories

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/ForgeAI">🤖 ForgeAI</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
      </p>
      <p><b>Autonomous multi-agent software engineering platform.</b> Moves beyond naive single-prompt code generation into an observable, verified distributed system.</p>
      <ul>
        <li><b>LangGraph Orchestration:</b> Multi-agent state graph with durable checkpointing, retry loops, and human-in-the-loop pause/resume hooks.</li>
        <li><b>Hybrid Repo Retrieval:</b> Dense semantic embeddings + BM25 sparse keyword search combined via Reciprocal Rank Fusion (RRF) and cross-encoder reranking.</li>
        <li><b>Tool Sandbox & Queues:</b> Real MCP (Model Context Protocol) client/server execution sandbox with asynchronous task queues via RabbitMQ.</li>
        <li><b>Observability:</b> End-to-end tracing and metrics instrumentation with OpenTelemetry, Prometheus, and Grafana.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/InferenceMesh">⚡ InferenceMesh</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/Elasticsearch-005571?style=flat-square&logo=elasticsearch&logoColor=white" />
        <img src="https://img.shields.io/badge/Qdrant-DC2626?style=flat-square" />
        <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
      </p>
      <p><b>Distributed LLM serving & inference routing mesh</b> demonstrating the real architectural mechanics behind production AI infrastructure.</p>
      <ul>
        <li><b>Dynamic Inference Router:</b> Policy-based model routing with adaptive circuit breakers to prevent cascading service degradation.</li>
        <li><b>Hybrid RAG Pipeline:</b> Dual retrieval from Elasticsearch (BM25) and Qdrant (dense vectors) fused through score-agnostic RRF.</li>
        <li><b>Tiered Caching:</b> Exact and semantic caching layer in Redis to eliminate redundant LLM calls under repeated traffic.</li>
        <li><b>Streaming & Ingestion:</b> Non-blocking async document ingestion with real-time Server-Sent Events (SSE) token streaming.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/SemanticRAG">🔍 SemanticRAG</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
        <img src="https://img.shields.io/badge/BM25_+_Dense-38BDF8?style=flat-square" />
        <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" />
      </p>
      <p><b>Production-style hybrid RAG platform</b> engineered to benchmark and evaluate retrieval decisions separating toy demos from robust deployments.</p>
      <ul>
        <li><b>Dual-Channel Retrieval:</b> Solves vocabulary mismatch by combining lexical exact matching (BM25) with semantic paraphrase vectors (pgvector).</li>
        <li><b>Rank Fusion & Reranking:</b> Fuses disparate ranking distributions via RRF and refines top contexts using a cross-encoder model.</li>
        <li><b>Redis Query Caching:</b> Sub-millisecond latency on cache hits with automated invalidation.</li>
        <li><b>IR Evaluation Harness:</b> Automated evaluation measuring Recall@K, MRR, and NDCG alongside Prometheus performance metrics.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/TokenPilot">🪄 TokenPilot</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
        <img src="https://img.shields.io/badge/Claude-D97706?style=flat-square&logo=anthropic&logoColor=white" />
        <img src="https://img.shields.io/badge/Butterbase_MCP-10B981?style=flat-square" />
        <img src="https://img.shields.io/badge/XTrace-8B5CF6?style=flat-square" />
      </p>
      <p><b>Autonomous cost-and-priority brain for engineering backlogs.</b> Reads your codebase and tickets to make intelligent routing decisions inside budget.</p>
      <ul>
        <li><b>Multi-Agent Runtime:</b> RocketRide pipeline coordinates estimation, budget allocation, model selection, context compilation, and monitoring.</li>
        <li><b>Dynamic Claude Routing:</b> Directs complex architectures to Claude Opus and routine patches to Haiku, maximizing throughput per dollar.</li>
        <li><b>Butterbase MCP Server:</b> Integrated Model Context Protocol backend handling ticketing state, authentication, and gateway switching.</li>
        <li><b>Memory & Proactive Alerts:</b> XTrace episodic memory resolves ticket contradictions; Photon pushes proactive iMessage notifications.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/JobTracker">💼 JobTracker</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Swift_5-FA7343?style=flat-square&logo=swift&logoColor=white" />
        <img src="https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white" />
        <img src="https://img.shields.io/badge/SwiftData-5856D6?style=flat-square" />
        <img src="https://img.shields.io/badge/OAuth_2.0_PKCE-232F3E?style=flat-square" />
      </p>
      <p><b>Native macOS application</b> turning incoming emails into an intelligent, automatically maintained job-application pipeline.</p>
      <ul>
        <li><b>Mail Ingestion:</b> OAuth 2.0 PKCE Gmail sync and streaming parser capable of processing multi-GB Google Takeout <code>.mbox</code> archives.</li>
        <li><b>Batch LLM Classification:</b> Multi-provider inference (NVIDIA NIM, OpenAI, Groq) with ATS heuristic prefilters to avoid API waste.</li>
        <li><b>Smart Thread Matching:</b> Correlates companies, roles, and recruiters into structured timelines with duplicate deduplication.</li>
        <li><b>Local-First Privacy:</b> Zero external tracking databases; all records stay on device in SwiftData and Apple Keychain.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/job-search-agent">🎯 job-search-agent</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/AsyncIO-3776AB?style=flat-square" />
        <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" />
        <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
      </p>
      <p><b>Autonomous job aggregator</b> orchestrated with 3 parallel LLM agents running on scheduled serverless workflows.</p>
      <ul>
        <li><b>Parallel LLM Workers:</b> Concurrent Python/asyncio agents (Claude, Gemini, OpenAI) query distinct portals every 6 hours.</li>
        <li><b>Visa & Resume Matcher:</b> Automatic F1/OPT visa sponsorship filtering and semantic resume matching against live Google Drive documents.</li>
        <li><b>Automated Pipeline:</b> Results are deduplicated, stored in PostgreSQL, compiled into Gmail digests, and displayed on a React dashboard.</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/STREAM-DPS-Project">🚇 STREAM-DPS-Project</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" />
        <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
        <img src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" />
        <img src="https://img.shields.io/badge/Helm-0F1689?style=flat-square&logo=helm&logoColor=white" />
      </p>
      <p><b>Scalable Real-Time Event and Analytics Machine</b> for distributed high-throughput transportation network analysis.</p>
      <ul>
        <li><b>Streaming Ingestion:</b> High-velocity Kafka producer and Kafka Connect pipeline streaming data into Neo4j graph nodes.</li>
        <li><b>Graph Analytics:</b> Runs PageRank and Breadth-First Search (BFS) algorithms using Neo4j Graph Data Science to identify traffic hubs.</li>
        <li><b>Cluster Deployment:</b> Fully containerized microservices managed on Kubernetes with custom Helm charts and Zookeeper coordination.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3 align="center"><a href="https://github.com/iamsiddhu3007/Optimizers-in-deep-models">📊 Optimizers-in-deep-models</a></h3>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
        <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" />
        <img src="https://img.shields.io/badge/Vision_Transformers-38BDF8?style=flat-square" />
      </p>
      <p><b>Empirical research benchmark</b> investigating optimizer convergence on Vision Transformer (ViT) architectures.</p>
      <ul>
        <li><b>7-Optimizer Evaluation:</b> Systematic comparative study of Adam, AdamW, AdaBelief, RAdam, AdaGrad, AdaDelta, and SGD on CIFAR-10/100.</li>
        <li><b>Performance Benchmarks:</b> AdamW with decoupled weight decay reached 92.96% accuracy on CIFAR-10; AdaBelief with decoupled decay achieved 74.85% on CIFAR-100.</li>
        <li><b>Data Augmentations:</b> Explored rotation and contrast shifts, boosting model generalization and stability.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 💻 Technologies Across Repositories

<p align="center">
  <b>Programming Languages</b><br>
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
  <img src="https://img.shields.io/badge/Swift-FA7343?style=flat-square&logo=swift&logoColor=white" alt="Swift" />
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" alt="Kotlin" />
  <img src="https://img.shields.io/badge/Java-007396?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
  <img src="https://img.shields.io/badge/SQL-CC292B?style=flat-square&logo=mysql&logoColor=white" alt="SQL" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=c%2B%2B&logoColor=white" alt="C++" />
</p>

<p align="center">
  <b>AI, Agent Frameworks & Vector Retrieval</b><br>
  <img src="https://img.shields.io/badge/LangGraph-FF6F00?style=flat-square&logo=python&logoColor=white" alt="LangGraph" />
  <img src="https://img.shields.io/badge/Multi--Agent_Systems-8B5CF6?style=flat-square" alt="Multi-Agent Systems" />
  <img src="https://img.shields.io/badge/Hybrid_RAG_(BM25_+_Dense_+_RRF)-06B6D4?style=flat-square" alt="Hybrid RAG" />
  <img src="https://img.shields.io/badge/Model_Context_Protocol_(MCP)-10B981?style=flat-square&logo=anthropic&logoColor=white" alt="MCP" />
  <img src="https://img.shields.io/badge/LiteLLM-0284C7?style=flat-square" alt="LiteLLM" />
  <img src="https://img.shields.io/badge/pgvector-336791?style=flat-square&logo=postgresql&logoColor=white" alt="pgvector" />
  <img src="https://img.shields.io/badge/Qdrant-DC2626?style=flat-square" alt="Qdrant" />
</p>

<p align="center">
  <b>Backend, Distributed Systems & Storage</b><br>
  <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white" alt="Node.js" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
  <img src="https://img.shields.io/badge/Apache_Kafka-231F20?style=flat-square&logo=apache-kafka&logoColor=white" alt="Kafka" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" alt="RabbitMQ" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=flat-square&logo=neo4j&logoColor=white" alt="Neo4j" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" alt="Kubernetes" />
</p>

<p align="center">
  <b>Observability, Testing & Platforms</b><br>
  <img src="https://img.shields.io/badge/OpenTelemetry-000000?style=flat-square&logo=opentelemetry&logoColor=white" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/Prometheus-E6522C?style=flat-square&logo=prometheus&logoColor=white" alt="Prometheus" />
  <img src="https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white" alt="Grafana" />
  <img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=github-actions&logoColor=white" alt="GitHub Actions" />
  <img src="https://img.shields.io/badge/SwiftUI-007AFF?style=flat-square&logo=swift&logoColor=white" alt="SwiftUI" />
</p>

---

### 📊 Repository & Activity Metrics

<div align="center">
  <table border="0">
    <tr>
      <td align="center" width="50%">
        <img src="https://github-readme-stats-fast.vercel.app/api?username=iamsiddhu3007&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&icon_color=38bdf8&text_color=c9d1d9" alt="GitHub Stats" />
      </td>
      <td align="center" width="50%">
        <img src="https://streak-stats.demolab.com?user=iamsiddhu3007&theme=tokyonight&hide_border=true&background=0D1117&stroke=38BDF8&ring=38BDF8&fire=FF7B72&currStreakLabel=38BDF8" alt="GitHub Streak" />
      </td>
    </tr>
    <tr>
      <td colspan="2" align="center">
        <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=iamsiddhu3007&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38bdf8&text_color=c9d1d9" alt="Top Languages" />
      </td>
    </tr>
  </table>
</div>
