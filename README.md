# Tasima Siphosethu Hapazari

Product engineer. I take an underspecified problem, design the system, and ship it — end to end.

BSc Computer Science & Business Computing, University of Cape Town. Graduate trainee (technical) at a Zimbabwean ISP, where I build internal systems — finance automation, security-monitoring dashboards, and customer-service tooling. Outside that I run a small studio building web products for small businesses. [noname-studios.dev]

## Selected work

### Proof-of-payment automation — internal system (in progress)
Customer payments were being matched and receipted into the billing system by hand, causing missed credits and tying up the finance team. I own the project end to end: requirements with finance, design, and build. The billing system has no usable API, so integration runs through browser automation behind a small web app. Bank statements arrive in 29 layouts (14 PDF, 15 Excel); after reviewing 500+ statements I wrote rule-based parsers with format detection, and anything that doesn't parse cleanly goes to an exception queue for a human instead of being guessed. TypeScript / Node. Employer code — not public.

### Cuppa La Var — retail stack for a coffee business
 Built around the spreadsheet workflow the owners already used rather than against it. React storefront with secure onboarding, SvelteKit operations dashboard separating the 2 applications but currently planning a role-based access integration with the dashboard being rebuilt in React, Supabase with row-level security, and a scheduled agent that audits the site's SEO weekly. [cuppalavar.com]

### NEXA — offline-first Android messaging (university capstone)
Peer-to-peer chat for places with unreliable or no internet. Kotlin, Google Nearby Connections, libsodium for end-to-end encryption, and a delay-tolerant routing layer: Spray-and-wait routing for 1:1 messaging and Epidemic routing for group chats.

Measured on 4 physical devices:

| Metric | Result |
|---|---|
| Peer discovery | ~3.8 s |
| Delivery, three hops | 11.2 s |
| Duplicate deliveries | < 2.5% |
| Battery draw while relaying | ~4.7% / hr |

Not done: group channels are partial, media and voice are unverified, and release-build hardening is outstanding (a MobSF scan flagged a debuggable build and `allowBackup` — configuration fixes, not architecture). Apache-2.0. → Repository

## What I work with
**Building with now** — TypeScript · React · Next.js · SvelteKit · Node · PostgreSQL / Supabase · Docker · n8n
**Shipped with before** — Kotlin (Android) · Python · Java
**Systems** — system design · delay-tolerant networking · networking fundamentals · Linux

## How I work
I write the design before the code: options considered, trade-offs, the decision, and what I'd revisit.  I'm explicit about what's verified versus intended — the NEXA section above is what that looks like.

📍 Harare, Zimbabwe · tasima.dev · LinkedIn
