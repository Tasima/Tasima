# Tasima Siphosethu Hapazari

**Aspiring Product engineer.** I take an underspecified idea, design the system, and ship it
to production — end to end.

BSc Computer Science & Business Computing, University of Cape Town.
Currently on the technical graduate programme at a Zimbabwean ISP (deployment
automation, monitoring, internal tooling). Outside that I build web products for
small businesses — storefronts, operations dashboards, and customer-service
automation.

---

## Selected work

### NEXA — offline-first Android messaging
Peer-to-peer chat for environments with unreliable or absent internet. Kotlin,
Google Nearby Connections, libsodium for end-to-end encryption, and a
delay-tolerant routing layer that selects its forwarding strategy by network
density — Spray-and-Wait for one-to-one, Epidemic for groups.

Field-measured across multiple physical devices:

| Metric | Result |
|---|---|
| Peer discovery | ~3.8 s |
| Delivery, three hops | 11.2 s |
| Duplicate deliveries | < 2.5% |
| Battery draw while relaying | ~4.7% / hr |

Apache-2.0. → [Repository](https://github.com/Tasima/NEXA)

### Cuppa La Var — retail launch stack
A full commercial build for a coffee retailer, designed around the spreadsheet
workflow they already used rather than against it. React storefront with secure
onboarding, SvelteKit operations dashboard, Supabase with row-level security,
Gemini-backed sales insights, and a scheduled agent that audits the site's SEO
weekly and reports back.

---

## What I work with

**Building with now** — TypeScript · React · Next.js · SvelteKit · Node ·
PostgreSQL / Supabase · Docker

**Shipped with before** — Kotlin (Android) · Python · Java

**Systems** — system design · distributed systems · delay-tolerant networking ·
applied cryptography · networking fundamentals · Linux · CI/CD

---

## How I work

I write the design before I write the code: options considered, trade-offs,
decision, and what I'd revisit. I'm explicit about what's verified versus what's
intended — including when the verification contradicts me.

---

📍 Harare, Zimbabwe · [tasima.dev](https://tasima.dev) · [LinkedIn](https://www.linkedin.com/in/tasimahapazari) · [email](tasimahapaz@gmail.com)
