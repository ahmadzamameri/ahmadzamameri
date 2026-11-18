<!--
  ===========================================================================
  ملفّ التعريف — ضعه في مستودع اسمه بالضبط مثل اسم مستخدمك على GitHub.
  مثال: اسم المستخدم ahmad-zamameri  ⇐  مستودع اسمه ahmad-zamameri
  وقتها يظهر هذا النصّ تلقائيًّا في أعلى صفحة حسابك.

  قبل الرفع: راجع كلّ سطر واحذف ما لا تريد قوله. الأرقام والروابط صحيحة
  بحسب ما تحقّقتُ منه، لكنّ الصياغة صياغتي — اجعلها صياغتك أنت.
  ===========================================================================
-->

# Ahmad Zamameri

I build and run web and mobile products end to end — from the database schema to the nginx
config to the app in the user's hand. Most of what I ship is in Arabic, for Arabic users, and
most of it is in production right now.

---

## Things I built that are live

**[mojtamatech.com](https://mojtamatech.com)** — an Arabic technology community platform:
accounts, posts, moderation, a workshops system, and a separate admin console. Built on a
reusable full-stack core of my own, deployed with Docker behind nginx, with database migrations,
automated backups and health monitoring.

**[almugamirtours.com](https://almugamirtours.com)** — a travel company's public site, plus the
admin dashboard behind it: content management for destinations and city guides, offers,
notifications, analytics and client agreements.

**A travel mobile app** (React Native / Expo) — the consumer side of the same platform:
destination guides, services, travel tools, eSIM purchase, and a day-planning engine that builds
a realistic daily itinerary from routing data rather than a fixed list.

**[chess.agrtravel.com](https://chess.agrtravel.com)** — real-time multiplayer chess with
accounts, Elo and an admin panel. **The source is public:** [github.com/ahmadzamameri/chess](https://github.com/ahmadzamameri/chess)

---

## Repositories here

| Repository | What it shows |
|---|---|
| **chess** | Full-stack TypeScript: authoritative game server over Socket.IO, JWT auth, bcrypt, per-IP throttling, privilege separation, MySQL, React front end — and it is deployed |
| **chess-lab** | Stockfish compiled to WebAssembly running in the browser, with the COOP/COEP headers and Web Worker setup that `SharedArrayBuffer` requires |
| **sql-injection-lab** | A teaching lab that executes a concatenated query and a parameterised one side by side, with tests |

My client and production work stays in private repositories.

---

## What I work with

**Languages** — TypeScript, JavaScript, SQL, Python, Bash
**Back end** — Node.js, Express, Socket.IO, MySQL, REST APIs, JWT, database migrations
**Front end** — React, Vite, React Router, React Native (Expo), RTL/Arabic interfaces
**Operations** — Linux servers, nginx, PM2, Docker, deployment pipelines, backups, uptime
monitoring and alerting
**Integrations** — Stripe, Google OAuth, Google Places, OSRM routing, push notifications

---

## What I am after

I want to move from building products that *use* APIs to building the intelligent parts myself.
The itinerary engine I wrote is the closest I have come — a real optimisation problem solved with
heuristics — and it is what convinced me that I want to study this properly rather than keep
reaching for someone else's endpoint.
