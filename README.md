# Derek Liu

<div align="center">

**CS Student @ University of Washington** · Solving complex problems in tech & finance

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/derek-l/)
[![Resume](https://img.shields.io/badge/Resume-4285F4?style=for-the-badge&logo=googledocs&logoColor=white)](https://www.overleaf.com/read/qwjcxbcmzjvr#9df549)
[![LeetCode](https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=white)](https://leetcode.com/u/Neighbor1/)
[![Email](https://img.shields.io/badge/deliu@uw.edu-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:deliu@uw.edu)

</div>

---

### About Me

I'm a student at the University of Washington passionate about building things at the intersection of **systems, security, and software engineering**.

### Skills & Tools

**Languages:** Java · C++ · Python · Rust · SQL · Golang · C · JavaScript · R · LaTeX · x86 Assembly
**Tools & Frameworks:** PyTorch · PySpark · React · Next.js · Docker · Git · JUnit · GHAS · Jira · Vim · VSCode
**Practices:** Agile · CI/CD · Network Security · Data Analysis

---

### Capstone — Obby: Semantic Video Search Tool

> Informatics Capstone · University of Washington · Sponsored by **Microsoft Product Innovation**
>
> 🔗 [Project Repository](https://github.com/cleoreyes/semantic-video-search)

**Obby** is a semantic video search platform that lets users query their video libraries using natural language — no manual scrubbing or tagging required. The tool ingests raw footage, processes it through AI-powered scene segmentation and transcription, and returns timestamped results that jump you straight to the relevant moment.

#### Goals

The team set out to answer: *How might content creators efficiently search and retrieve specific moments within their video libraries so they can reduce time spent managing assets and accelerate content production?* Content creators spend disproportionate amounts of time scrubbing through footage and manually tagging clips, leading to wasted production time, missed creative opportunities, and inefficient workflows. We aimed to build a tool that replaces this manual review with semantic discovery — allowing search by meaning rather than metadata.

#### Process

**Team & Roles:** Our five-person team consisted of Kathryn Rochleau-Rice (Project Manager), Keira Wong (Front-End Engineer), Cleo Reyes (Front-End Engineer), Chelsea Li (Back-End Engineer), and myself as **Back-End Engineer**.

**Research & Validation:** We conducted user research with content creators, identifying key personas such as long-form travel vloggers struggling to sort through B-roll and short-form lifestyle influencers overwhelmed by similar-looking takes. We validated six key concepts — concept clarity, query accuracy, time savings, result trust, web preference, and manual upload willingness — through prototype testing. Users responded positively to the clean interface and the core library-session-search flow, though we identified areas needing refinement such as confusing "Sessions" terminology, redundant upload flows, and cumbersome slider-based clip trimming.

**Solution Architecture:** The pipeline is built on three Azure services:
- **Azure Video Indexer** — Ingests video and performs scene segmentation, speech transcription, and visual metadata extraction
- **Azure OpenAI** — Generates scene summaries and produces vector embeddings, stored in Azure AI Search
- **Semantic Search & Retrieval** — Natural language queries return timestamped scenes with confidence filtering and thumbnail previews

The frontend is built with **Next.js** (App Router), and the codebase follows a modular structure for scalability.

#### My Individual Contributions

As a back-end engineer, I focused on the data ingestion and processing pipeline — connecting Azure Video Indexer to our backend, building out the API layer that serves search results to the frontend, and helping design the indexing workflow that turns raw video into searchable embeddings. I also contributed to the market and user research phase, presenting findings on the current state of video search and the opportunity for semantic approaches. Working on this project deepened my experience with cloud-based AI services, vector search, and building production-grade APIs in a team setting.

#### Takeaways

From a **team perspective**, we learned the importance of early user validation — our concept testing surfaced critical usability issues (like confusing terminology and redundant flows) before we invested heavily in building them out. Structured decision-making with domain leads and a consensus-based approach to architectural changes kept the team aligned throughout.

From an **individual perspective**, this project pushed me to work across the full stack of an AI-powered application, from cloud infrastructure to API design. I gained hands-on experience with Azure's AI ecosystem and learned how to integrate multiple services into a cohesive pipeline. It also strengthened my ability to translate research insights into technical requirements.

#### Next Steps

The project is still in progress. Remaining work includes optimizing the search strategy for better result relevance and tuning the processing pipeline for cost efficiency. We are also addressing ethical considerations around privacy (video libraries may contain sensitive content), bias in semantic understanding, and ensuring equitable access so the tool doesn't only benefit well-resourced creators.

---

### 🌟 Featured Projects

| Project | Description | Tech |
|---------|-------------|------|
| [Cisco Networking Portfolio](https://github.com/Deleted-0970/Cisco-Networking-Portfolio) | Hands-on documentation for configuring Cisco routers, switches, and network topologies from scratch | Cisco IOS · CLI · VLANs · OSPF |
| [Firewall & VPN Portfolio](https://github.com/Deleted-0970/Cybersecurity-Networking-Portfolio) | End-to-end guides for setting up site-to-site VPNs, ACLs, and firewall rule sets | pfSense · IPsec · ACLs |
| [Wordplay](https://github.com/wordplaydev/wordplay) | Research project on interactive typography — making text come alive through code | TypeScript · Web APIs |
| [3ps](https://github.com/srihariKrishnaswamy/3ps) | Computer vision pipeline for an underwater remotely operated vehicle — detecting and tracking objects beneath the surface | Python · OpenCV · CV |
| [Eterna](https://github.com/cleoreyes/eterna) | DubHacks '24 hackathon project — built in 24 hours with a team of four! | Hackathon · Collaborative Dev |
| [The State of Our Climate](https://deleted0970.shinyapps.io/final-deliverable-p03-andrewpking/) | Interactive data visualization and analysis of climate trends using real-world Kaggle datasets | R · Shiny · Data Cleaning |

---

### 💫 Just for Fun

| Project | Description | Tech |
|---------|-------------|------|
| [Ground Roll Calculator](https://github.com/Deleted-0970/Ground-Roll-Calculator) | Calculates the takeoff ground roll distance for RC aircraft — born from a love of flying things | Python · Physics |
| [Kappa Calculator](https://github.com/Deleted-0970/Kappa-Calculator) | Calculates kappa. That's it. That's the project. | Math · Vibes |
| [ConnectX](https://github.com/Deleted-0970/ConnectX) | A fully customizable Connect 4 — play on any grid size with any win condition | Java · Game Logic |
| [Roblox Sims](https://github.com/Deleted-0970/Roblox-Sims) | A terminal-based Kaiju Cats game inspired by Roblox — because why not? | Python · Terminal UI |

---
