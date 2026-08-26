## Andrii — Backend Developer

Fifteen years in PHP. I build the parts of a product that have to be right: money, state,
and the rules that decide who is allowed to do what.

Most of my work has been systems where the hard problem isn't the interface — a wallet where
two concurrent charges must not interleave, a legal reference that is wrong if it is a week
stale, a contract that must still mean what it meant on the day it was signed. Deep in Drupal,
currently working in Laravel.

**Open to remote work** · Kyiv, UTC+2 · full-time or contract · English B2

📫 **[dna.ray@gmail.com](mailto:dna.ray@gmail.com)** · Telegram **@ampersand_i**

---

### Selected work

Each links to a write-up of the architecture and the engineering decisions behind it.

#### 🐻 [LittleBearWorks](https://github.com/BaldCatDev/littlebearworks-showcase) — home services marketplace
`Laravel 12` `PHP 8.3` `Vue 3` `Inertia` `Filament` `Docker`

A contract freezes a snapshot of the service as it was agreed, so a provider editing their
price later cannot rewrite past deals. Status changes are append-only events rather than
assignments. Money moves through an immutable ledger, each entry carrying the balance
that followed it, written inside a transaction with the wallet row locked.

#### ⚖️ [zakon.help](https://github.com/BaldCatDev/zakon-showcase) — Ukrainian legislation, kept current
`PHP` `MySQL` `LiqPay` `Monobank` `Telegram API` — [live](https://zakon.help/)

I inherited this one as *"nothing works, please fix it"*: a PHP 5 codebase with logic in flat
scripts and a folder named `___OBSOLETE`. Rather than rewrite a site that could not go down, I
grew a proper object layer inside it — ~105 classes, ~21,500 lines — over a legacy base of
around 79,000. Every act is kept current automatically from the parliament's own sources, past
editions stay addressable, and commentary anchored to a paragraph survives every later edition
of the law it explains.

#### 🛡 [PRO100](https://github.com/BaldCatDev/pro100-showcase) — insurance platform
`Drupal 9` `SOAP` `UPC` `Platon` `GitHub Actions`

Insurance products as discoverable plugins, with coverage tiers and limits declared in YAML so
a new package ships without a deployment. A policyholder cabinet reading contracts and claims
straight from the insurer's internal system over SOAP, self-service registration gated on
matching the insurer's own records, and card payments through two acquirers with PDF receipts
for the finance department. In production 2020–2023 at 1,000–2,000 payments a day.

#### 🛠 [Pomogashka](https://github.com/BaldCatDev/pomogashka-showcase) — services marketplace
`Drupal 9` `Vue` `LiqPay` `NovaPay` — [live](https://pomogashka.com.ua/)

Payment gateways as drop-in plugins, toggled from the admin panel without a deploy. A
hand-written REST layer replacing Views where the generated JSON gave neither the query control
nor the response shape the front end needed. Visibility in search is earned: an incomplete
profile is capped below the listing threshold no matter how many optional fields it fills.

---

### Toolbelt

**Languages** PHP 8, JavaScript, SQL
**Frameworks** Laravel, Drupal 7–10, Vue 3, Inertia, Filament
**Data** MySQL, PostgreSQL
**Ops** Docker, GitHub Actions, nginx, Bash
**Also** Photoshop, Illustrator, Cinema 4D — a designer's eye, occasionally useful

---

### How I work

I like problems where correctness is checkable: a payment that must not be taken twice, a state
machine that must not skip a step, a query that must not quietly return the wrong rows. I would
rather write the boring safeguard than the clever shortcut, and rather ask what happens on the
second webhook than find out in production.

Much of what I have built has been maintained by someone else afterwards, or by me two years
later — so I optimise for the version of this code that gets read, not the one that gets
written.
