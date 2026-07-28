## Hi, I'm Andrii

I am a professional Backend (mostly) Developer and Graphic Designer with over 15 years of experience in web development. Over the years, my focus has shifted from simply writing code to architecting highly reliable, evolutionary modular systems.


I specialize in building modular extensions, custom core components, and high-performance server-side architecture. As an advocate for the **"Belt and Suspenders" approach**, I prioritize absolute reliability, predictable execution, and exhaustive automated verification over quick, fragile workarounds.

### Navigate
[Core](Core Technical Experitse) | [Featured Projects](Featured Projects) | [Tech Stack](Tech Stack and Toolbelt) | [Phylosophy](https://pages.github.com/) 

### Contact

✉️ dna.ray@gmail.com | tg: @amersand_i


---

### 🚀 Core Technical Expertise

*   **Backend Architecture & Paradigms:** Clean Architecture, Domain-Driven Design (DDD), strict SOLID compliance, Dependency Injection (DI), Data Transfer Objects (DTOs), and paranoid programming patterns.
*   **Performance & Optimization:** Comprehensive refactoring, query optimization, caching strategies, and bottleneck elimination.
*   **Infrastructure & Environments:** Containerized sandboxes (Docker), robust local DNS infrastructure configurations, automated workflows, and complex multi-environment management.
*   -------
*   **Visual & Interface Design:** Professional asset creation, UI/UX optimization, motion design, and industrial aesthetics (Photoshop, Cinema 4D).

### ⚙️ Featured Projects

#### 🔹 PRO100: Payment Core for Insurance company
*A modular payment processing module integrated with internal accounting software.*

*   **The Task:** Designing a scalable system to support multiple, fluctuating payment gateways while ensuring strict transaction data consistency across external financial platforms and internal accounting software.
*   **The Solution:** Developed an API-driven abstraction layer that isolates gateway-specific logic into individual modules managed via an administrative UI. Integrated a dedicated interface for accountants to track logs and generate receipts manually when automated flows required verification.
*   **Key Highlights & Challenges:**
    *   **Idempotency & Webhook Protection:** Solved the problem of duplicate external webhooks by implementing a "payment intents" ledger. Incoming events are strictly validated against intermediate states before marking a transaction as completed.
    *   **Stuck Transactions Handling:** Designed a fallback cron routine to automatically query gateway APIs for pending or unconfirmed transactions, resolving state mismatches without manual intervention.
    *   **Accounting Integration:** Provided a direct data pipeline to corporate accounting software, processing a stable load of 1,000–2,000 daily transactions within predictable execution limits.
*   *Tech Stack:* Drupal 8, PHP, MySQL, REST API.

#### 🔹 PRO100: Payment Core for Insurance company
*Modular payment processing engine integrated with the company's internal accounting system.*

- **Architecture:** a single internal API that payment gateways connect to as separate modules. Integrated LiqPay, Mono, and UPC — enabling/disabling gateways, API keys, and receipt text are configured through the admin panel without code changes.
- **Duplicate protection:** every webhook was cross-checked against a "payment intent" table before processing, preventing the same payment from being processed twice.
- **Stuck transactions:** a separate mechanism periodically polled the gateway for status updates on transactions that didn't receive a final response immediately.
- **Accounting:** synced payments with the company's internal accounting system; a dedicated accountant interface for reviewing payments and generating receipts (receipts were also sent to the customer immediately — electronic receipts weren't yet standard in Ukraine at the time).
- **Load:** 1,000–2,000 payments processed daily in production.

*Stack:* Drupal 8, PHP, MySQL, REST API

#### [Pro100: online insurance creation]
*A resilient asynchronous automation service built for real-time data parsing and structured forwarding.*
*   **The Challenge:** Processing high-velocity data feeds efficiently while maintaining strict filtering templates and low-latency dispatch.
*   **The Solution:** Implemented a lightweight, event-driven network service utilizing robust message-filtering abstraction layers.
*   **Key Highlights:** Implemented clean architectural decoupling, allowing templates to be modified without altering the underlying core network routine.
*   *Tech Stack:* [e.g., Python/FastAPI/Node.js], Asyncio, Docker.

#### [Drupal Commerce Universal XML parser:]

#### [Pomogashka: Ukrainian handy-man seek online platform]

#### [::::::::::.com: Canada-wide online handyman search platform] (WIP)

#### [zakon.help: laws and official documents user-friendly database (Ukraine)]

*A website intended to be a handy tool for those who use state laws on daily basis*

Site has a tons of different features to be implemented. Some prominent ones:

- all state laws are kept in actual state *automatically* by utilising all possible sources (APIs, parsing print versions, parsing HTML versions etc)
- user can switch document versions (editions) in one click
- user can comment any law published. Such comments are saved across all later versions
- user can view a professional lawyers / official comments for each document
- user can create a bookmarks and have an easy access to them from their Cabinet
- site Content Managers have a flexible yet powerful taxonomy tools to keep all content in order
- site Content Managers have a tool to make changes to documents while keeping the original content untouched
- third party authors can publish their own laws-related books/articles and provide either paid or free access to read them
*   *Tech Stack:* ![PHP](https://shields.io), ![VUE](https://shields.io)

---

### 🛠️ Tech Stack & Toolbelt

*   **Languages:** PHP, Python, modern JavaScript / TypeScript.
*   **Frameworks & Ecosystems:** Advanced Drupal 7+, Laravel, FastAPI, Vue.js.
*   **Databases & Caching:** MySQL, SQL, PostgreSQL.
*   **Tools & DevOps:** Docker, Webpack, Git, Bash automation, CI/CD pipelines.
*   **Design & 3D:** Adobe Photoshop / Illustrator, Cinema 4D.

---

### 🧠 Engineering Philosophy

> *"If it isn't explicitly validated, it is broken."*

I treat software development as an exact craft. Whether I am architecting a sandbox environment, refactoring a legacy module, or designing complex visual assets, I focus on the underlying logic and system behavior. I don't just write code that works; I build systems that are bulletproof against failure, transparent to profile, and clean to maintain.

---

📫 **How to reach me:** [dna.ray@gmail.com](mailto:dna.ray@gmail.com) / @ampersand_i [TG]
