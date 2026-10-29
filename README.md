<div align="center">

  <img src="assets/header-banner.svg" width="100%" alt="Muhammad Haris — AI Full-Stack Developer & Defensive Cybersecurity Professional" />

  <br />

  <a href="https://readme-typing-svg.demolab.com">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3000&pause=1200&color=00E5FF&center=true&vCenter=true&width=780&height=46&lines=AI+Full-Stack+Developer+%C2%B7+Defensive+Cybersecurity+Specialist;Lead+Full-Stack+Engineer+%C2%B7+BSIT+Premier+Capstone;98.64%25+Holdout+Accuracy+NLP+Threat+Detection+%C2%B7+Mail-Lens+AI;IntruShield+NIDS+%C2%B7+MedicaLink+HMS+%C2%B7+PacketVision;Top+15%25+Nationally+(NSCT)+%C2%B7+96%25+Cybersecurity+Coursework" alt="Typing Subtitle" />
  </a>

  <br />

  <p align="center">
    <a href="https://harisx404.vercel.app"><img src="https://img.shields.io/badge/Portfolio-harisx404.vercel.app-0ea5e9?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" /></a>
    <a href="https://www.linkedin.com/in/harisx404/"><img src="https://img.shields.io/badge/LinkedIn-harisx404-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://tryhackme.com/p/harisx404"><img src="https://img.shields.io/badge/TryHackMe-130%2B_Day_Streak-212C42?style=for-the-badge&logo=tryhackme&logoColor=00FF00" alt="TryHackMe" /></a>
    <a href="https://www.credly.com/users/harisx404"><img src="https://img.shields.io/badge/Credly-Verified_Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" /></a>
    <a href="mailto:itsharis.tech@gmail.com"><img src="https://img.shields.io/badge/Email-itsharis.tech%40gmail.com-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  </p>

  <p align="center">
    <img src="https://komarev.com/ghpvc/?username=harisx404&style=flat-square&color=00e5ff&label=Profile+Views" alt="Profile Views" />
    <img src="https://img.shields.io/github/followers/harisx404?label=Followers&style=flat-square&color=00d4ff&labelColor=0d1117" alt="GitHub Followers" />
    <img src="https://img.shields.io/badge/Status-Open_to_Roles-22c55e?style=flat-square&labelColor=0d1117" alt="Status" />
    <img src="https://img.shields.io/badge/Location-Pakistan_%C2%B7_Remote_Worldwide-6366f1?style=flat-square&labelColor=0d1117" alt="Location" />
    <img src="https://img.shields.io/badge/Degree-BSIT_Graduate_(3.49_CGPA)-38bdf8?style=flat-square&labelColor=0d1117" alt="Degree" />
  </p>

</div>

---

## 👨‍💻 Executive Summary

I am **Muhammad Haris**, a **BS Information Technology graduate (2022–2026, 3.49 / 4.00 CGPA)** from the **University of Malakand**, operating at the intersection of **full-stack software architecture**, **defensive cybersecurity / SOC tooling**, and **applied AI/ML engineering**.

I approach software engineering with an adversary-first mindset: **a developer who knows how systems break is the best architect to build systems that don't.** Whether architecting database-per-tenant hospital platforms, streaming Suricata intrusion telemetry over WebSockets, or building sub-15ms explainable NLP threat classifiers, every system I ship is hardened by design, verified with automated test suites, and documented for zero technical debt.

<br/>

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🏆 National IT Merit (Top 15%)</h4>
      <p>Ranked in the <b>84.6th percentile (Top 15% nationwide)</b> among 33,000+ computing graduates in Pakistan's National Skills Competency Test (NSCT 2026), evaluated across 10 core computer science and engineering disciplines.</p>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Cybersecurity Mastery (96%)</h4>
      <p>Achieved a <b>96% coursework score</b> in Cybersecurity & Defense Operations, paired with hands-on SOC telemetry (Wazuh SIEM), NIDS engineering (Suricata 7, Snort), and an active <b>130+ day streak</b> on TryHackMe defensive labs.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🤖 Applied AI & Explainability (98.64%)</h4>
      <p>Trained and evaluated a 3-class NLP email threat intelligence system achieving <b>98.64% test accuracy</b> across 3,592 holdout samples with custom hyperplane token attribution and <b>&lt;15ms CPU inference</b>.</p>
    </td>
    <td width="50%" valign="top">
      <h4>✍️ Technical Writing & Architecture</h4>
      <p>Authored <b>10 comprehensive technical whitepapers</b> analyzing AI agent security, post-quantum cryptography migration (ML-KEM/ML-DSA), RAG reliability, and cloud Zero Trust architectures.</p>
    </td>
  </tr>
</table>

---

## 🚀 Flagship Engineering Projects

### 🛡️ [IntruShield NIDS](https://github.com/harisx404/intrushield-nids) — Autonomous Network Intrusion Detection & SOC Platform
<p align="center">
  <a href="https://intrushield-nids.vercel.app">
    <img src="assets/intrushield-cover.webp" width="100%" alt="IntruShield NIDS Dashboard" />
  </a>
</p>

> **Autonomous Security Operations Center (SOC) telemetry platform** bridging Suricata 7 deep-packet inspection with an asynchronous FastAPI backend and a Next.js 14 SOC command center over persistent WebSockets.

- **Sub-5ms Telemetry Streaming:** Non-blocking `aiofiles` tailing of Suricata `eve.json` broadcasting structured alert objects directly over WebSockets with zero polling latency.
- **In-Memory Ring Deduplication:** Sliding-window event buffer collapsing repetitive flood alerts (e.g. 250 brute-force attempts into 1 contextual incident) to eliminate analyst alert fatigue.
- **Threat Intelligence Enrichment:** Automatically enriches external threat vectors with MaxMind GeoIP2 country codes, ASN data, and coordinates on ingest.
- **Offensive Attack Validation:** Benchmarked and validated against simulated SYN floods, Nmap sweeps, Hydra SSH brute-force attacks, and Log4j CVE-2021-44228 exploits.
- **Stack:** `Python 3.12` `FastAPI` `Suricata 7.0` `Next.js 14 (App Router)` `WebSockets` `PostgreSQL` `Docker Compose` `Zustand` `Recharts`

<p align="left">
  <a href="https://intrushield-nids.vercel.app"><img src="https://img.shields.io/badge/↗_Live_Platform-intrushield--nids.vercel.app-22c55e?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
  &nbsp;
  <a href="https://github.com/harisx404/intrushield-nids"><img src="https://img.shields.io/badge/🐙_Source_Code-intrushield--nids-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
</p>

---

### 🤖 [Mail-Lens AI (PhishGuard AI)](https://github.com/harisx404/phishguard-ai) — NLP Threat Intelligence & Explainable AI (XAI)
<p align="center">
  <a href="https://maillens-ai.streamlit.app/">
    <img src="assets/maillens-cover.webp" width="100%" alt="Mail-Lens AI Threat Telemetry" />
  </a>
</p>

> **High-accuracy email threat classification and explainability engine** detecting phishing, social engineering lures, and malicious payloads with instant plain-English attribution. Capstone project for the KPITB AI Fellowship.

- **Empirically Evaluated Accuracy:** Achieved **98.64% test accuracy** and **0.9761 Macro F1** across a held-out test partition of 3,592 unseen emails (99.09% precision on legitimate, 97.95% on phishing, 97.06% on malicious).
- **Domain-Specific Feature Fusion:** Combines 10,000 sublinear TF-IDF n-grams with 20 heuristic cybersecurity signals (Levenshtein typosquatting distance against top brand domains, urgency density, attachment risk).
- **Explainable AI (XAI) Attribution:** Projects feature weights directly onto learned SVM hyperplane coefficients to generate keyword threat attribution chips and diagnostic explanations without black-box SHAP/LIME overhead.
- **Ultra-Fast & Offline:** Operates 100% locally with **&lt;15ms CPU inference** per email with zero telemetry leakage; validated across 71 automated Pytest unit and integration tests.
- **Stack:** `Python 3.10+` `Scikit-Learn` `LinearSVC` `Platt Scaling` `TF-IDF` `NLTK` `Streamlit` `Docker` `Pytest`

<p align="left">
  <a href="https://maillens-ai.streamlit.app/"><img src="https://img.shields.io/badge/↗_Live_Demo-maillens--ai.streamlit.app-22c55e?style=for-the-badge&logo=streamlit&logoColor=white" alt="Live Demo" /></a>
  &nbsp;
  <a href="https://github.com/harisx404/phishguard-ai"><img src="https://img.shields.io/badge/🐙_Source_Code-phishguard--ai-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
</p>

---

### 🏥 [MedicaLink HMS](https://github.com/harisx404/MedicaLink-HMS) — Enterprise Multi-Tenant Hospital Management SaaS
<p align="center">
  <a href="https://github.com/harisx404/MedicaLink-HMS">
    <img src="assets/medicalink-cover.webp" width="100%" alt="MedicaLink HMS Clinical Command" />
  </a>
</p>

> **Enterprise-grade healthcare management SaaS** engineered with strict database-per-tenant isolation, real-time clinical synchronization, and a Google Gemini AI clinical documentation copilot.

- **Tenant Isolation:** Enforces physical and logical database-per-tenant separation through dynamic Mongoose connection multiplexing resolved from tenant subdomain headers.
- **Granular Access Control:** Implements 15 distinct hospital roles (Doctors, Nurses, Pharmacists, Lab Techs, Billing, CMOs) across 25+ clinical modules with zero cross-tenant data leakage.
- **Real-Time Clinical Telemetry:** Powers emergency department bed allocation and ICU patient triage queues via Socket.io backed by Redis pub/sub.
- **Clinical AI Copilot:** Embedded Google Gemini 1.5 Flash assistant transforming unstructured doctor consultation notes into formatted SOAP (Subjective, Objective, Assessment, Plan) records.
- **Encrypted Telemedicine:** Built-in WebRTC browser-to-browser encrypted video consultations with virtual waiting rooms.
- **Stack:** `TypeScript Strict` `Turborepo` `React 18` `Vite` `Node.js 20 LTS` `Express 4` `MongoDB Atlas` `Redis` `Socket.io` `Gemini 1.5 Flash` `Tailwind CSS` `shadcn/ui`

<p align="left">
  <a href="https://github.com/harisx404/MedicaLink-HMS"><img src="https://img.shields.io/badge/🐙_Source_Code-MedicaLink--HMS-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Demo-Available_Privately_on_Request-64748b?style=for-the-badge" alt="Private Demo" />
</p>

---

### 📡 [PacketVision](https://github.com/harisx404/packet-vision-network-sniffer) — Multithreaded Network Packet Sniffer & Protocol Analyzer
<p align="center">
  <a href="https://github.com/harisx404/packet-vision-network-sniffer">
    <img src="assets/packetvision-cover.webp" width="100%" alt="PacketVision Network Telemetry" />
  </a>
</p>

> **High-performance terminal-based network packet inspection and protocol telemetry engine** built with a decoupled Producer-Consumer multithreaded architecture.

- **Zero-Drop Concurrency:** Decouples raw socket wire capture from console parsing using Python's synchronized `queue.Queue`, preventing socket buffer overflows under heavy bursts.
- **RAM Exhaustion Protection:** Employs `store=False` in Scapy with a bounded FIFO queue, maintaining a flat ~45MB RSS memory profile across 500,000+ continuous packets.
- **Anti-ANSI Injection Defense:** Sanitizes raw network payloads by stripping unprintable ASCII characters and terminal escape codes (`\x1b[...]`), mitigating terminal spoofing vulnerabilities.
- **Multi-Layer Dissection & Forensics:** Deep protocol dissection across Layer 2 through Layer 7 (Ethernet, ARP, IPv4/v6, TCP flag matrix, UDP, ICMP, DNS, HTTP, TLS SNI) with Wireshark `.pcap`, structured JSON, and CSV export.
- **Stack:** `Python 3.12+` `Scapy 2.5+` `Raw Sockets` `Multithreading` `Berkeley Packet Filters (BPF)` `Npcap/libpcap` `Colorama` `Pytest`

<p align="left">
  <a href="https://github.com/harisx404/packet-vision-network-sniffer"><img src="https://img.shields.io/badge/🐙_Source_Code-packet--vision--network--sniffer-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
  &nbsp;
  <img src="https://img.shields.io/badge/Platform-CLI_Tool_(Win%20%2F%20Linux)-0284c7?style=for-the-badge" alt="Platform" />
</p>

---

### 🗺️ [TourMate Malakand](https://tourmate-malakand.vercel.app/) — Regional Tourism & Geospatial Platform
<p align="center">
  <a href="https://tourmate-malakand.vercel.app/">
    <img src="assets/tourmate-cover.webp" width="100%" alt="TourMate Malakand Platform" />
  </a>
</p>

> **Premier BSIT Capstone Project at University of Malakand**, defended with highest departmental honors. Solves travel information bottlenecks across the Malakand division with interactive vector mapping and safety telemetry.

- **Geospatial Mapping & Routing:** Interactive Mapbox GL JS vector tile maps featuring GPS spot clusters, driving distance calculations, and turn-by-turn routing with MongoDB `2dsphere` spatial indexing.
- **Emergency Telemetry & Safety:** Direct-dial emergency SOS directory (Rescue 1122, hospitals, tourist police) paired with live destination OpenWeatherMap forecasts.
- **Bandwidth Optimization:** Client-side HTML5 canvas image pre-compression downscaling photo uploads to &lt;400KB WebP payloads, reducing 3G mobile data consumption by **78%**.
- **Defense-in-Depth:** Hardened with Helmet HTTP Content Security Policy, `express-mongo-sanitize` stripping NoSQL injection vectors, XSS filtering, and tiered auth rate limiting.
- **Stack:** `React 18` `Vite` `Node.js 20 LTS` `Express 5` `MongoDB Atlas` `Mongoose` `Mapbox GL JS` `Cloudinary` `Tailwind CSS`

<p align="left">
  <a href="https://tourmate-malakand.vercel.app/"><img src="https://img.shields.io/badge/↗_Live_Platform-tourmate--malakand.vercel.app-22c55e?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
  &nbsp;
  <a href="https://github.com/harisx404/tourmate_malakand_frontend"><img src="https://img.shields.io/badge/🐙_Frontend_Repo-tourmate_frontend-181717?style=for-the-badge&logo=github&logoColor=white" alt="Frontend Repo" /></a>
  &nbsp;
  <a href="https://github.com/harisx404/tourmate_malakand_backend"><img src="https://img.shields.io/badge/🐙_Backend_Repo-tourmate_backend-181717?style=for-the-badge&logo=github&logoColor=white" alt="Backend Repo" /></a>
</p>

---

### 🌐 [Harisx404 Engineering Platform (v3.0)](https://harisx404.vercel.app) — Production Portfolio & AI Assistant
<p align="center">
  <a href="https://harisx404.vercel.app">
    <img src="assets/portfolio-cover.png" width="100%" alt="Harisx404 Engineering Platform" />
  </a>
</p>

> **Production engineering and technical publication platform** combining 127 compiled routes, 168 passing automated test suites, a Supabase PostgreSQL backend with 50 migrations, and a streaming RAG AI assistant.

- **Dual-Provider Resilient AI:** Low-latency Server-Sent Events (SSE) chat API running Groq Cloud Qwen 3.8-27b with automatic failover to Google Gemini 2.5 Flash within 4.5 seconds if zero tokens emit.
- **Zero-Trust Edge Security:** Fail-closed edge middleware enforcing RBAC, 50 PostgreSQL Row Level Security (RLS) migrations, and SHA-256 hashed distributed rate limiting.
- **Automated Testing Suite:** 168 automated test specifications covering unit logic, Supabase RLS contracts, and Playwright headless browser E2E test suites with 100% Lighthouse audit scores.
- **Stack:** `Next.js 15 (App Router)` `React 19` `TypeScript Strict` `Supabase PostgreSQL` `Tailwind CSS` `Framer Motion` `TipTap MDX` `Playwright`

<p align="left">
  <a href="https://harisx404.vercel.app"><img src="https://img.shields.io/badge/↗_Live_Portfolio-harisx404.vercel.app-22c55e?style=for-the-badge&logo=vercel&logoColor=white" alt="Live Demo" /></a>
  &nbsp;
  <a href="https://github.com/harisx404/harisx404-portfolio"><img src="https://img.shields.io/badge/🐙_Source_Code-harisx404--portfolio-181717?style=for-the-badge&logo=github&logoColor=white" alt="Source Code" /></a>
</p>

---

## 🧰 Technical Arsenal & Skills Matrix

<table>
  <tr>
    <td width="24%"><b>💻 Languages & Core</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=ts,js,py,cpp,bash,html,css" alt="TypeScript, JavaScript, Python, C++, Bash, HTML, CSS" /></a>
      <br/>
      <sub>TypeScript 5 (Strict), JavaScript (ES6+), Python 3.12, C++, SQL, Bash Scripting, HTML5, CSS3</sub>
    </td>
  </tr>
  <tr>
    <td><b>🌐 Frontend Architecture</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind" alt="React, Next.js, Vite, Tailwind" /></a>
      <br/>
      <sub>Next.js 15 (App Router, RSC, SSR), React 18/19, Vite, Tailwind CSS 3, Framer Motion, shadcn/ui, Radix UI, Zustand, TipTap MDX, Mapbox GL JS, Recharts</sub>
    </td>
  </tr>
  <tr>
    <td><b>⚙️ Backend & Real-Time</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=nodejs,express,fastapi" alt="Node.js, Express, FastAPI" /></a>
      <br/>
      <sub>Node.js 20 LTS, Express 4/5, FastAPI (Async Python), WebSockets, Socket.io, WebRTC (P2P), RESTful APIs, Turborepo Monorepos</sub>
    </td>
  </tr>
  <tr>
    <td><b>🗄️ Databases & Storage</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=postgres,supabase,mongodb,redis,sqlite" alt="PostgreSQL, Supabase, MongoDB, Redis, SQLite" /></a>
      <br/>
      <sub>PostgreSQL (50+ migrations), Supabase (Row Level Security), MongoDB Atlas, Mongoose, Redis (Pub/Sub & Caching), SQLite, Cloudinary CDN</sub>
    </td>
  </tr>
  <tr>
    <td><b>🛡️ Defensive Security & SOC</b></td>
    <td>
      <img src="https://img.shields.io/badge/Suricata_7-EF3B2D?style=flat-square&logo=suricata&logoColor=white" />
      <img src="https://img.shields.io/badge/Snort_NIDS-CC0000?style=flat-square" />
      <img src="https://img.shields.io/badge/Wazuh_SIEM-3A7D44?style=flat-square" />
      <img src="https://img.shields.io/badge/Scapy_Sockets-334155?style=flat-square" />
      <img src="https://img.shields.io/badge/Wireshark-1679A7?style=flat-square&logo=wireshark&logoColor=white" />
      <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kalilinux&logoColor=white" />
      <img src="https://img.shields.io/badge/OWASP_Top_10-000000?style=flat-square&logo=owasp&logoColor=white" />
      <img src="https://img.shields.io/badge/Zero_Trust-0F172A?style=flat-square" />
      <img src="https://img.shields.io/badge/Cisco_Packet_Tracer-049FD9?style=flat-square&logo=cisco&logoColor=white" />
      <br/>
      <sub>Deep Packet Inspection (DPI), Network Telemetry & Log Correlation, Berkeley Packet Filters (BPF), Packet Dissection, Anti-ANSI Injection, Helmet CSP, RBAC/ABAC, JWT Auth</sub>
    </td>
  </tr>
  <tr>
    <td><b>🤖 Applied AI & ML</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=sklearn" alt="Scikit-Learn" /></a>
      <img src="https://img.shields.io/badge/Google_Gemini-4285F4?style=flat-square&logo=googlegemini&logoColor=white" />
      <img src="https://img.shields.io/badge/Groq_Cloud-F55036?style=flat-square" />
      <img src="https://img.shields.io/badge/NLP_TF--IDF-7C3AED?style=flat-square" />
      <img src="https://img.shields.io/badge/Explainable_AI_(XAI)-6D28D9?style=flat-square" />
      <img src="https://img.shields.io/badge/RAG_Pipelines-0EA5E9?style=flat-square" />
      <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=flat-square" />
      <br/>
      <sub>Scikit-Learn, LinearSVC, Platt Scaling, TF-IDF Vectorization, NLTK Lemmatization, Hyperplane Attribution, Retrieval-Augmented Generation, Prompt Hardening</sub>
    </td>
  </tr>
  <tr>
    <td><b>🚀 DevOps, Cloud & QA</b></td>
    <td>
      <a href="https://skillicons.dev"><img src="https://skillicons.dev/icons?i=docker,git,githubactions,vercel,linux,vitest" alt="Docker, Git, GitHub Actions, Vercel, Linux, Vitest" /></a>
      <br/>
      <sub>Docker & Docker Compose, GitHub Actions CI/CD, Vercel Edge Deployments, Playwright E2E Browser Testing, Pytest, Node.js Test Runner, Zod, Pydantic</sub>
    </td>
  </tr>
</table>

---

## 💼 Professional Experience

<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h4>🌐 Full-Stack Engineer (Freelance)</h4>
      <p><b>Self-Employed · Remote Worldwide</b> &nbsp;|&nbsp; <i>2024 — Present</i></p>
      <ul>
        <li>Architects and ships production web applications using Next.js, TypeScript, Node.js, and Supabase.</li>
        <li>Enforces zero-trust security defaults, OWASP Top 10 mitigations, and role-based access control (RBAC).</li>
        <li>Re-engineered legacy query and caching layers, cutting API response times by 99% for client applications.</li>
        <li>Delivers transparent milestone scoping, weekly velocity reports, and documented handovers.</li>
      </ul>
      <p>🏷️ <code>Next.js</code> <code>TypeScript</code> <code>Supabase</code> <code>OWASP</code></p>
    </td>
    <td width="50%" valign="top">
      <h4>🛡️ Open-Source Systems & Security Engineer</h4>
      <p><b>GitHub Community · Remote</b> &nbsp;|&nbsp; <i>2026 — Present</i></p>
      <ul>
        <li>Designs, tests, and publishes open-source defensive security tools and full-stack software platforms.</li>
        <li>Created <b>IntruShield NIDS</b> (real-time Suricata WebSocket platform) and <b>PacketVision</b> (multithreaded sniffer).</li>
        <li>Architected <b>MedicaLink HMS</b> (multi-tenant hospital SaaS) and <b>TourMate Malakand</b>.</li>
        <li>Releases complete architectural diagrams, threat models, and reproducible Docker environments.</li>
      </ul>
      <p>🏷️ <code>Python</code> <code>FastAPI</code> <code>Suricata</code> <code>Security Tooling</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h4>🔒 Cyber Security Intern</h4>
      <p><b>CodeAlpha · Remote</b> &nbsp;|&nbsp; <i>Jun 2026 — Jul 2026</i></p>
      <ul>
        <li>Configured and tuned Network Intrusion Detection Systems using Snort and Suricata for continuous traffic analysis.</li>
        <li>Engineered a custom Python packet sniffer utilizing Scapy and raw sockets for Layer 2–7 payload inspection.</li>
        <li>Conducted manual code audits and automated static code analysis to remediate application vulnerabilities.</li>
        <li>Authored security awareness training modules on social engineering tactics and phishing defense.</li>
      </ul>
      <p>🏷️ <code>Suricata</code> <code>Snort</code> <code>Scapy</code> <code>AppSec</code></p>
    </td>
    <td width="50%" valign="top">
      <h4>🖥️ SOC Analyst Intern</h4>
      <p><b>Tech Hierarchy · Remote</b> &nbsp;|&nbsp; <i>Mar 2026 — Mar 2026</i></p>
      <ul>
        <li>Utilized Wazuh SIEM to aggregate logs, monitor endpoints, and correlate events to detect network anomalies.</li>
        <li>Simulated virtual network segmentation architectures in Cisco Packet Tracer with strict subnet isolation.</li>
        <li>Executed hands-on defensive simulations in TryHackMe labs covering traffic forensics and incident triage.</li>
        <li>Practiced active defense strategies, vulnerability identification, and endpoint protection workflows.</li>
      </ul>
      <p>🏷️ <code>Wazuh SIEM</code> <code>Log Analysis</code> <code>Network Defense</code></p>
    </td>
  </tr>
</table>

---

## 🎓 Education & Verified Certifications

### 🏛️ Formal Education
**Bachelor of Science in Information Technology (BSIT)** — **University of Malakand (UoM)**, Pakistan  
*Academic Session: 2022 — 2026* &nbsp;|&nbsp; **CGPA: 3.49 / 4.00**  
- **Capstone Honors:** Lead Full-Stack Developer for *TourMate Malakand*, defended with highest department honors.
- **Cybersecurity Excellence:** Scored **96% in Cybersecurity & Defense Operations** coursework.
- **Core Coursework:** Software Engineering, Data Structures & Algorithms, Object-Oriented Programming (C++, Python), Database Systems, Computer Networks & Protocols, Operating Systems, Web Technologies, Artificial Intelligence, and IoT.

<br/>

### 📜 Verified Credentials & Certifications

| Certification / Credential | Issuing Organization | Issued | Credential Verification |
|---|---|:---:|---|
| **CS50's Introduction to Programming with Python** | **Harvard University** | Aug 2026 | [Verify Certificate (09de786b...)](https://cs50.harvard.edu/certificates/09de786b-0b5e-445b-a3bb-e672b623b3ea) |
| **Introduction to Cybersecurity** | **Cisco Networking Academy** | Jun 2026 | [Verify Credly Badge (660327f0...)](https://www.credly.com/badges/660327f0-5dc5-48d1-95e7-e4375d1d3f14/linked_in_profile) |
| **AI Skills Fest 2026** | **Microsoft** | Jun 2026 | [Verify Credly Badge (b21bab8d...)](https://www.credly.com/badges/b21bab8d-85e4-4363-b176-74d4330992e3/linked_in_profile) |
| **AI & Machine Learning (144-Hour Fellowship)** | **KPITB & UET Mardan** | Oct 2026 | [Verify Official Certificate (AI-043)](https://uetmardan.edu.pk/kpitb-certificates/verify.php?token=887cd553618276835b5348b8df6a767e344231d7c27e85ed033f134a5ea4dfd6) |
| **Master Computer Networking** | **Scaler** | Sep 2025 | [Verify Certificate (Scaler Moonshot)](https://moonshot.scaler.com/s/li/Q8CqwmLi0Q) |
| **Hacker Holidays 2026** | **TryHackMe** | 2026 | [View Certificate (THM-T8MNSZKCNH)](https://tryhackme-certificates.s3-eu-west-1.amazonaws.com/THM-T8MNSZKCNH.pdf) |
| **1 Million Prompters** | **Dubai Future Foundation** | 2025 | [View Certificate (v0vHXvZ3ubeN)](https://omp.dub.ai/certificate/v0vHXvZ3ubeN) |
| **Delta 2.0: Full Stack Web Development (MERN)** | **Apna College** | Nov 2023 | *Full-stack engineering & modern web technologies* |

---

## ✍️ Published Technical Whitepapers & Engineering Articles

I author in-depth technical analyses on systems architecture, defensive security, and applied AI. Read all articles on **[harisx404.vercel.app/blog](https://harisx404.vercel.app/blog)**:

- 🛡️ **[Securing AI Agents: Prompt Injection, Tool Abuse, and Least Privilege](https://harisx404.vercel.app/blog/securing-ai-agents)** — 5 practical defense controls: narrow tool definitions, scoped identity tokens, human approval gates, egress control, and audit logging.
- 🔐 **[Post-Quantum Cryptography: What Developers Need to Know Before Migrating](https://harisx404.vercel.app/blog/post-quantum-cryptography-migration)** — Developer guide on NIST standards (ML-KEM, ML-DSA), hybrid classical/PQC key exchanges in TLS, and cryptographic agility.
- 🤖 **[How AI Is Changing the Security Operations Center (SOC)](https://harisx404.vercel.app/blog/ai-security-operations-center)** — Separating AI marketing hype from engineering reality; human-in-the-loop automation during alert triage and correlation.
- 🧠 **[RAG in 2026: What Actually Makes a Retrieval System Reliable?](https://harisx404.vercel.app/blog/reliable-rag)** — Moving beyond naive vector search with structure-aware chunking, dense/sparse hybrid search, and cross-encoder reranking.
- ⚡ **[Small Language Models vs. Large Language Models: When Smaller Makes Sense](https://harisx404.vercel.app/blog/small-vs-large-language-models)** — Latency, cost, and privacy trade-offs with the "route-and-escalate" architectural pattern.
- 🧪 **[How to Evaluate an AI Application Before Calling It Production Ready](https://harisx404.vercel.app/blog/ai-application-evaluation)** — Building evaluation datasets, automated graders, factual grounding vs. hallucination metrics, and CI regression suites.
- 🌐 **[Zero Trust Networking for Modern Cloud Applications](https://harisx404.vercel.app/blog/zero-trust-networking-cloud)** — Architectural implementation of Policy Decision Points (PDP), SPIFFE/SPIRE workload identities, and Kubernetes default-deny rules.
- 📡 **[How AI Workloads Are Changing Modern Network Architecture](https://harisx404.vercel.app/blog/ai-workloads-network-architecture)** — Distributed GPU cluster communications, synchronized all-reduce collectives, tail latency, RoCEv2, and Ultra Ethernet.
- ⚡ **[Next.js 16 in Practice: Cache Components, Instant Navigations, and Modern App Architecture](https://harisx404.vercel.app/blog/nextjs-16-cache-components)** — Deep dive into cache components, the `use cache` directive, Partial Prerendering, and Turbopack production builds.
- 🔒 **[End-to-End Type Safety: Building a Type-Safe MERN Application](https://harisx404.vercel.app/blog/type-safe-mern-typescript)** — Sharing Zod validation schemas between TypeScript React clients and Express 5 backends without redundant interfaces.

---

## 📊 GitHub Telemetry & Activity Stats

<div align="center">

  <table border="0" cellspacing="0" cellpadding="0">
    <tr>
      <td align="center" valign="middle">
        <a href="https://github.com/harisx404">
          <img src="https://github-readme-stats.vercel.app/api?username=harisx404&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0B0F19&title_color=00E5FF&text_color=E2E8F0&icon_color=00E5FF&count_private=true" alt="Haris's GitHub Stats" />
        </a>
      </td>
      <td align="center" valign="middle">
        <a href="https://github.com/harisx404">
          <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=harisx404&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B0F19&title_color=00E5FF&text_color=E2E8F0&langs_count=8" alt="Top Languages" />
        </a>
      </td>
    </tr>
  </table>

  <br/>

  <a href="https://github.com/harisx404">
    <img src="https://streak-stats.demolab.com?user=harisx404&theme=tokyonight&hide_border=true&background=0B0F19&ring=00E5FF&fire=00E5FF&currStreakLabel=00E5FF&sideNums=E2E8F0&sideLabels=94A3B8" alt="GitHub Streak" />
  </a>

  <br/><br/>

  <a href="https://github.com/harisx404">
    <img width="98%" src="https://github-readme-activity-graph.vercel.app/graph?username=harisx404&bg_color=0B0F19&color=00E5FF&line=00E5FF&point=E2E8F0&area=true&hide_border=true" alt="Contribution Graph" />
  </a>

  <br/><br/>

  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/harisx404/harisx404/output/github-contribution-grid-snake-dark.svg">
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/harisx404/harisx404/output/github-contribution-grid-snake.svg">
    <img alt="GitHub Contribution Snake Animation" src="https://raw.githubusercontent.com/harisx404/harisx404/output/github-contribution-grid-snake.svg" width="100%" />
  </picture>

</div>

---

## 🤝 Let's Connect & Build Together

I am actively open to **full-time software engineering roles**, **defensive cybersecurity / SOC positions**, **applied AI engineering**, and **high-impact technical contract projects**.

<br/>

<table width="100%">
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="https://www.linkedin.com/in/harisx404/" target="_blank">
        <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
      </a>
      <br/><br/>
      <b>💼 Professional Network</b>
      <p align="center">Connect for career opportunities, engineering discussions & industry updates.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="https://harisx404.vercel.app/" target="_blank">
        <img src="https://img.shields.io/badge/Portfolio-Visit%20Platform-0EA5E9?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
      </a>
      <br/><br/>
      <b>🌐 Interactive Showcase</b>
      <p align="center">Explore live project demos, interactive AI assistant & technical blog.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="mailto:itsharis.tech@gmail.com">
        <img src="https://img.shields.io/badge/Email-Direct%20Inquiry-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
      </a>
      <br/><br/>
      <b>📧 Direct Inquiries</b>
      <p align="center">Fast response for full-time offers, technical consulting & collaborations.</p>
    </td>
  </tr>
  <tr>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="https://tryhackme.com/p/harisx404" target="_blank">
        <img src="https://img.shields.io/badge/TryHackMe-Profile-212C42?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe" />
      </a>
      <br/><br/>
      <b>🛡️ Hands-on Defense</b>
      <p align="center">Check out 130+ day streak, rooms completed & defensive lab writeups.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="https://www.credly.com/users/harisx404" target="_blank">
        <img src="https://img.shields.io/badge/Credly-Badges-FF6B00?style=for-the-badge&logo=credly&logoColor=white" alt="Credly" />
      </a>
      <br/><br/>
      <b>🏅 Verified Credentials</b>
      <p align="center">Explore verified badges from Cisco, Microsoft, and global institutions.</p>
    </td>
    <td width="33.3%" align="center" valign="top">
      <br/>
      <a href="https://wa.me/923485058727" target="_blank">
        <img src="https://img.shields.io/badge/WhatsApp-Chat-25D366?style=for-the-badge&logo=whatsapp&logoColor=white" alt="WhatsApp" />
      </a>
      <br/><br/>
      <b>💬 Direct Message</b>
      <p align="center">Reach out directly on WhatsApp for prompt project communications.</p>
    </td>
  </tr>
</table>

<br/>

<div align="center">

  <p><i>"A developer who understands how systems break is the strongest person to build systems that don't."</i></p>
  <sub>— Muhammad Haris (harisx404)</sub>

  <br/><br/>

  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B0F19,50:0EA5E9,100:6366F1&height=100&section=footer" width="100%" alt="Footer Wave" />

</div>
