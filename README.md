<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:00F7FF&height=240&section=header&text=Alex%20%E2%80%94%20The%20Code%20Warden&fontSize=40&fontColor=ffffff&animation=fadeIn&fontAlignY=36&desc=Senior%20Software%20Engineer%20%E2%80%A2%20Systems%20Architect%20%E2%80%A2%20Builder%20of%20Production%20Systems&descAlignY=56&descSize=16" width="100%"/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=2800&pause=900&color=00F7FF&center=true&vCenter=true&width=760&lines=Designing+systems+that+survive+contact+with+reality;Architecting+MOTO+RIDES+%E2%80%94+live+geospatial+mobility+at+scale;REST+%C2%B7+GraphQL+%C2%B7+WebSockets+%C2%B7+Distributed+Systems;I+don't+just+ship+features.+I+ship+architecture." alt="Typing SVG" />

<br/>

<!-- inline spinning orbit — self-contained SVG, no external dependency -->
<svg width="120" height="120" viewBox="0 0 120 120">
  <circle cx="60" cy="60" r="6" fill="#00F7FF"/>
  <g>
    <circle cx="60" cy="14" r="5" fill="#7CFFCB"/>
    <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="0 60 60" to="360 60 60" dur="4s" repeatCount="indefinite"/>
  </g>
  <g>
    <circle cx="60" cy="106" r="4" fill="#00A8E8"/>
    <animateTransform attributeName="transform" attributeType="XML" type="rotate" from="360 60 60" to="0 60 60" dur="6s" repeatCount="indefinite"/>
  </g>
  <circle cx="60" cy="60" r="34" fill="none" stroke="#00F7FF" stroke-width="1" opacity="0.35"/>
  <circle cx="60" cy="60" r="48" fill="none" stroke="#00A8E8" stroke-width="1" opacity="0.2"/>
</svg>

<br/><br/>

[![Live Product](https://img.shields.io/badge/🛰️_In_Production-motorides.app-00F7FF?style=for-the-badge&labelColor=0d1117)](https://motorides.app)
[![Email](https://img.shields.io/badge/✉️_Email-D14836?style=for-the-badge&labelColor=0d1117&color=D14836)](mailto:Kingstonmuhoro@gmail.com)
[![X](https://img.shields.io/badge/𝕏-000000?style=for-the-badge&labelColor=0d1117)](https://x.com/manman)
[![Instagram](https://img.shields.io/badge/📸_Instagram-E4405F?style=for-the-badge&labelColor=0d1117&color=E4405F)](https://instagram.com/_alexmods)

</div>

<br/>

## 🧭 Who I Am

I'm Alex — engineers who've worked with me tend to call me **The Code Warden**, and the name stuck for a reason: I treat architecture the way a warden treats a perimeter. Not precious, not decorative — *defended*. Clean boundaries between layers, contracts that don't leak, and systems that fail loudly in staging instead of silently in production.

I'm a senior full-stack engineer and systems architect with a specialization in **real-time, geospatially-aware platforms** — the unglamorous, deeply technical work of making location, timing, and state agree with each other at scale, under unreliable networks, on unreliable hardware, in markets that don't forgive a slow app.

I don't optimize for résumés. I optimize for systems that are still legible — and still standing — eighteen months after I wrote them.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🛰️ Flagship Build — MOTO RIDES

<table>
<tr><td width="100%">

**[motorides.app](https://motorides.app)** — live, in production, moving real riders across **Chuka, Embu, and Meru**.

MOTO RIDES is a technology-driven mobility platform built for East African markets — a domain where the interesting engineering problems aren't theoretical. Connectivity drops mid-trip. GPS drift is real. Riders and drivers need to converge on a shared, trustworthy version of "where," updated in near real time, on a phone that might be three network generations behind flagship hardware.

I own this system end-to-end — not just the feature surface, but the architecture underneath it:

- 🗺️ **Real-time mapping & geolocation** — designed and built the core `MapView` layer: live position tracking, route rendering, and the state management that keeps rider and driver views synchronized without drowning the client in redundant updates.
- ⚙️ **Matching & dispatch logic** — the systems-level work of reconciling "who's nearby" with "who's actually reachable," under latency and location uncertainty that a naive haversine calculation won't survive.
- 📱 **Product-grade mobile UX** — an interface built for low-bandwidth, high-urgency use: someone standing on a roadside who needs a ride *now*, not a beautiful loading skeleton.
- 🧱 **End-to-end ownership** — from data model to deployment pipeline, I'm accountable for the whole system, not a ticket queue.

> **"Tap. Ride. Arrive."** — MOTO RIDES, by Zylos

`Real-Time Systems` `Geospatial Engineering` `Mobile-First Architecture` `Distributed State` `Production at Scale`

</td></tr>
</table>

<br/>

## ⚙️ Engineering Philosophy

I think about software the way a structural engineer thinks about a building — the parts nobody sees are the parts that determine whether it stands.

- **Boundaries over cleverness.** A clean interface between two systems is worth more than an elegant hack inside one of them.
- **Design for the failure case first.** The happy path is easy. I want to know what the system does when the network drops, the payload is malformed, or the load triples at 6pm on a Friday.
- **Legibility is a feature.** Code that a teammate — or future-me — can read at 2am during an incident is worth more than code that's merely clever.
- **Ship, then harden.** Production feedback beats theoretical completeness. I'd rather have a working system I iterate on than a perfect one still in design review.

<br/>

<div align="center">
<img src="https://capsule-render.vercel.app/api?type=transparent&color=00F7FF&height=2&section=header&width=100%" width="100%"/>
</div>

## 🧬 Core Domains

<div align="center">

| Domain | What I Actually Do Here |
|---|---|
| 🛰️ **Real-Time & Geospatial Systems** | Live location tracking, mapping layers, matching engines, event-driven pipelines |
| 🔌 **APIs & Backend Architecture** | REST, GraphQL, WebSockets, service boundaries, microservices |
| 🗄️ **Data & Persistence** | Schema design, ORMs, consistency models for systems that can't afford to be "eventually" right |
| 🎛️ **Frontend Engineering** | React, Vue, Angular — component systems built to survive product change, not just ship it |
| ☁️ **Cloud & DevOps** | Docker, CI/CD, deployment pipelines that make shipping boring on purpose |
| 🧩 **Product Engineering** | Concept → architecture → production, owning outcomes, not just output |

</div>

<br/>

## 🧪 Tech Stack

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

## 📊 Activity & Metrics

<div align="center">
<img height="165" src="https://github-readme-stats.vercel.app/api?username=wynemods&show_icons=true&theme=radical&hide_border=true&bg_color=0d1117&title_color=00F7FF&icon_color=00F7FF&text_color=c9d1d9" />
<img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=wynemods&layout=compact&theme=radical&hide_border=true&bg_color=0d1117&title_color=00F7FF&text_color=c9d1d9" />
</div>

<div align="center">
<img src="https://github-readme-streak-stats.herokuapp.com/?user=wynemods&theme=radical&hide_border=true&background=0d1117&ring=00F7FF&fire=00F7FF&currStreakLabel=00F7FF" />
</div>

<div align="center">
<img src="https://github-readme-activity-graph.vercel.app/graph?username=wynemods&theme=react-dark&hide_border=true&bg_color=0d1117&color=00F7FF&line=00F7FF&point=ffffff" width="95%"/>
</div>

<br/>

## 🏆 Trophy Case

<div align="center">
<img src="https://github-profile-trophy.vercel.app/?username=wynemods&theme=radical&no-frame=true&no-bg=true&margin-w=8&row=1" />
</div>

<br/>

<div align="center">

### 🔭 Currently

Hardening MOTO RIDES' real-time matching layer for scale beyond three cities — and always open to conversations about systems worth building well.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:00F7FF,100:0F2027&height=120&section=footer&width=100%"/>

</div>
