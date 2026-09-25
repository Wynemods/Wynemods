<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0E27,25:0F2C4C,60:0E5C6E,100:00F7FF&height=280&section=header&text=ALEX%20%E2%80%94%20THE%20CODE%20WARDEN&fontSize=46&fontColor=ffffff&animation=fadeIn&fontAlignY=34&desc=Senior%20Software%20Engineer%20%E2%97%86%20Systems%20Architect%20%E2%97%86%20Production-Grade%20Builder&descAlignY=52&descSize=17&descColor=8FE9FF" width="100%"/>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:00F7FF,100:0A0E27&height=3&width=100%" width="100%"/>

<br/>

<img src="https://readme-typing-svg.demolab.com?font=Poppins&weight=600&size=24&duration=2600&pause=900&color=6EE7F9&center=true&vCenter=true&width=780&separator=%3B&lines=Designing+systems+that+survive+contact+with+reality%3BArchitecting+MOTO+RIDES+%E2%80%94+live+geospatial+mobility+at+scale%3BREST+%C2%B7+GraphQL+%C2%B7+WebSockets+%C2%B7+Distributed+Systems%3BI+don't+ship+features.+I+ship+architecture." alt="Typing SVG" />

<br/><br/>

<!-- self-contained animated orbit mark -->
<svg width="92" height="92" viewBox="0 0 92 92">
  <circle cx="46" cy="46" r="5" fill="#00F7FF"/>
  <circle cx="46" cy="46" r="26" fill="none" stroke="#00F7FF" stroke-width="1" opacity="0.3"/>
  <circle cx="46" cy="46" r="38" fill="none" stroke="#6EE7F9" stroke-width="1" opacity="0.15"/>
  <g>
    <circle cx="46" cy="8" r="4" fill="#6EE7F9"/>
    <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0 46 46" to="360 46 46" dur="3.5s" repeatCount="indefinite"/>
  </g>
  <g>
    <circle cx="46" cy="84" r="3" fill="#00A8E8"/>
    <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="360 46 46" to="0 46 46" dur="5s" repeatCount="indefinite"/>
  </g>
</svg>

<br/><br/>

<!-- status pulse -->
<svg width="230" height="34" viewBox="0 0 230 34">
  <rect x="0" y="0" width="230" height="34" rx="17" fill="#0d1117" stroke="#1f6feb" stroke-width="1"/>
  <circle cx="22" cy="17" r="5" fill="#3fb950">
    <animate attributeName="opacity" values="1;0.25;1" dur="1.6s" repeatCount="indefinite"/>
  </circle>
  <text x="40" y="22" fill="#c9d1d9" font-family="Verdana, sans-serif" font-size="12" font-weight="bold">Open to ambitious builds</text>
</svg>

<br/><br/>

[![Live Product](https://img.shields.io/badge/🛰️_IN_PRODUCTION-motorides.app-00F7FF?style=for-the-badge&labelColor=0A0E27)](https://motorides.app)
[![WhatsApp](https://img.shields.io/badge/💬_WHATSAPP-25D366?style=for-the-badge&labelColor=0A0E27&color=25D366)](https://wa.me/YOUR_NUMBER_HERE)
[![Email](https://img.shields.io/badge/✉️_EMAIL-D14836?style=for-the-badge&labelColor=0A0E27&color=D14836)](mailto:Kingstonmuhoro@gmail.com)
[![X](https://img.shields.io/badge/𝕏_FOLLOW-000000?style=for-the-badge&labelColor=0A0E27)](https://x.com/manman)
[![Instagram](https://img.shields.io/badge/📸_INSTAGRAM-E4405F?style=for-the-badge&labelColor=0A0E27&color=E4405F)](https://instagram.com/_alexmods)

</div>

<br/>

<!-- terminal-style whoami block -->
<div align="center">

```bash
root@codewarden:~$ whoami
> Alex — Senior Software Engineer / Systems Architect
> Uptime: production-grade since day one
> Trust level: root
root@codewarden:~$ cat /var/log/status
> ARCHITECTING  : MOTO RIDES — real-time geospatial mobility
> SLA TARGET    : 99.9% — latency budgets measured in milliseconds, not vibes
> STATUS        : compiling ambition into infrastructure
```

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🧭&nbsp; Who I Am

> Engineers I've worked with tend to call me **The Code Warden** — and the name stuck for a reason. I treat architecture the way a warden treats a perimeter: not precious, not decorative — *defended*. Clean boundaries between layers, contracts that don't leak, systems that fail loudly in staging instead of silently in production.

I'm a senior full-stack engineer and systems architect specializing in **real-time, geospatially-aware platforms** — the unglamorous, deeply technical discipline of reconciling location, timing, and distributed state at scale, under unreliable networks, on unreliable hardware, in markets that don't forgive a slow app.

I don't optimize for résumés. I optimize for systems still legible — and still standing — eighteen months after I wrote them. Ask anyone who's had to read my postmortems: they're short, because there isn't much left to explain once the boundaries are drawn correctly the first time.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🛰️&nbsp; Flagship Build — MOTO RIDES

<table>
<tr><td width="100%">

**[motorides.app](https://motorides.app)** — live, in production, moving real riders across **Chuka, Embu, and Meru**.

MOTO RIDES is a technology-driven mobility platform built for East African markets — a domain where the interesting engineering problems aren't theoretical. Connectivity drops mid-trip. GPS drift is real. Riders and drivers need to converge on a shared, trustworthy version of "where," propagated in near real time, on hardware that might be three network generations behind flagship.

I own this system end-to-end — not just the feature surface, but the architecture underneath it:

- 🗺️ **Real-time mapping & geolocation** — designed and built the core `MapView` layer: live position tracking, route rendering, and the state-reconciliation logic that keeps rider and driver clients eventually consistent without drowning either one in redundant payloads.
- ⚙️ **Matching & dispatch logic** — the systems-level work of resolving "who's nearby" against "who's actually reachable," under latency jitter and positional uncertainty that a naive haversine calculation won't survive.
- 📡 **Fault-tolerant delivery** — built for degraded connectivity: retry semantics, idempotent writes, and graceful degradation instead of a spinner and a prayer.
- 📱 **Product-grade mobile UX** — an interface engineered for low-bandwidth, high-urgency use: someone on a roadside who needs a ride *now*, not a beautifully animated loading state.
- 🧱 **End-to-end ownership** — from data model to CI/CD pipeline, accountable for the whole system, not a ticket queue.

> *"Tap. Ride. Arrive."* — MOTO RIDES, by Zylos

`Real-Time Systems` `Geospatial Engineering` `Distributed State` `Fault Tolerance` `Mobile-First Architecture` `Production at Scale`

</td></tr>
</table>

<br/>

<!-- HUD-style access panel — self-made, no third-party IP -->
<div align="center">

<svg width="620" height="150" viewBox="0 0 620 150">
  <rect x="1" y="1" width="618" height="148" rx="10" fill="#05070f" stroke="#00F7FF" stroke-width="1" opacity="0.9"/>
  <line x1="20" y1="34" x2="600" y2="34" stroke="#1f6feb" stroke-width="1" opacity="0.5"/>
  <text x="20" y="24" fill="#6EE7F9" font-family="Consolas, monospace" font-size="13" font-weight="bold">SYSTEM ACCESS PANEL</text>
  <text x="20" y="58" fill="#c9d1d9" font-family="Consolas, monospace" font-size="12">ACCESS_LEVEL  ::  ROOT</text>
  <text x="20" y="80" fill="#c9d1d9" font-family="Consolas, monospace" font-size="12">ENCRYPTION    ::  AES-256 / TLS 1.3</text>
  <text x="20" y="102" fill="#c9d1d9" font-family="Consolas, monospace" font-size="12">FOOTPRINT     ::  MINIMAL — logs rotate, code stays</text>
  <text x="20" y="124" fill="#3fb950" font-family="Consolas, monospace" font-size="12">STATUS        ::  ONLINE — building, not bragging</text>
  <circle cx="590" cy="18" r="5" fill="#3fb950">
    <animate attributeName="opacity" values="1;0.2;1" dur="1.4s" repeatCount="indefinite"/>
  </circle>
</svg>

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## ⚙️&nbsp; Engineering Philosophy

I think about software the way a structural engineer thinks about a building — the parts nobody sees are the parts that determine whether it stands.

- **Boundaries over cleverness.** A clean interface between two services is worth more than an elegant hack inside one of them.
- **Design for the failure case first.** The happy path is easy. I want to know what the system does under partition, under malformed payloads, under 3x load at 6pm on a Friday.
- **Observability isn't optional.** If a system can't tell me *why* it failed, I haven't finished building it — I've just finished hiding the problem.
- **Legibility is a feature.** Code a teammate — or future-me — can read at 2am during an incident beats code that's merely clever.
- **Ship, then harden.** Production feedback beats theoretical completeness. A working system under iteration beats a perfect one stuck in design review.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🧬&nbsp; Core Domains

<div align="center">

| Domain | What I Actually Do Here |
|---|---|
| 🛰️ **Real-Time & Geospatial Systems** | Live location tracking, mapping layers, matching engines, event-driven pipelines |
| 🔌 **APIs & Backend Architecture** | REST, GraphQL, WebSockets, service boundaries, microservices |
| 🗄️ **Data & Persistence** | Schema design, ORMs, consistency models for systems that can't afford to be "eventually" right |
| 🎛️ **Frontend Engineering** | React, Vue, Angular — component systems built to survive product change, not just ship it |
| ☁️ **Cloud & DevOps** | Docker, CI/CD, zero-downtime deploys, infrastructure that stays boring on purpose |
| 🧩 **Product Engineering** | Concept → architecture → production, owning outcomes, not just output |

</div>

<br/>

## 🧪&nbsp; Tech Stack

<div align="center">

![JavaScript](https://img.shields.io/badge/javascript-323330?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![TypeScript](https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![NodeJS](https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white)
![React](https://img.shields.io/badge/react-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Vue.js](https://img.shields.io/badge/vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D)
![PHP](https://img.shields.io/badge/php-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Java](https://img.shields.io/badge/java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![C++](https://img.shields.io/badge/c++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Docker](https://img.shields.io/badge/docker-0db7ed?style=for-the-badge&logo=docker&logoColor=white)
![Google Maps](https://img.shields.io/badge/Geo%20%26%20Maps-4285F4?style=for-the-badge&logo=googlemaps&logoColor=white)

</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🕶️&nbsp; Off Duty

<!-- Drop your own art here once it's committed to /assets in this repo, e.g.: -->
<!-- <img src="assets/hacker-glitch.png" width="260" align="right"/> -->

- 🎧 Debug faster with music running — most of the hard bugs get solved after everyone else has logged off
- 🎮 When not shipping code, reverse-engineering game architectures and system design out of pure habit
- 🤖 Deep interest in AI & automation — but still hand-craft the solutions that matter
- 🧩 Treat side projects like production systems: version-controlled, documented, no exceptions

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 📊&nbsp; Activity & Metrics

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=wynemods&show_icons=true&theme=radical&hide_border=true&bg_color=0A0E27&title_color=6EE7F9&icon_color=00F7FF&text_color=c9d1d9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wynemods&layout=compact&theme=radical&hide_border=true&bg_color=0A0E27&title_color=6EE7F9&text_color=c9d1d9" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=wynemods&theme=radical&hide_border=true&background=0A0E27&ring=00F7FF&fire=00F7FF&currStreakLabel=6EE7F9" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=wynemods&theme=react-dark&hide_border=true&bg_color=0A0E27&color=00F7FF&line=00F7FF&point=ffffff" width="95%"/>
</div>

<br/>

## 🏆&nbsp; Trophy Case

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=wynemods&theme=radical&no-frame=true&no-bg=true&margin-w=8&row=1" />
</div>

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 📡&nbsp; Connect With Me

<div align="center">

[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/YOUR_NUMBER_HERE)
[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:Kingstonmuhoro@gmail.com)
[![X](https://img.shields.io/badge/X-000000?style=for-the-badge&logo=x&logoColor=white)](https://x.com/manman)
[![Instagram](https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white)](https://instagram.com/_alexmods)

*Reach out through whichever channel — response time is fast, filler talk is not included.*

</div>

<br/>

### 🔭&nbsp; Currently

<div align="center">

Hardening MOTO RIDES' real-time matching layer for scale beyond three cities — and always reachable for conversations about systems worth building well.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0A0E27,100:00F7FF&height=140&section=footer&width=100%"/>

</div>
