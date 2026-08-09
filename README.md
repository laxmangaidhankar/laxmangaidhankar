<div align="center">

# Laxman Gaidhankar

**Full-Stack Developer · Google Student Ambassador · Hackathon Finalist**

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&pause=1000&color=1A56DB&center=true&width=650&lines=Building+fintech%2C+privacy%2C+and+platform+engineering+projects;Top+12+%2F+163+%E2%80%A2+Top+100+%2F+900%2B+%E2%80%A2+Top+33+%E2%80%A2+Hack4Delhi+Shortlisted;Google+Student+Ambassador+%7C+Pune%2C+India;DSA+%7C+System+Design+%7C+Scalable+Solutions)](https://github.com/laxmangaidhankar)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-laxmangaidhankar-0A66C2?style=flat-square&logo=linkedin)](https://linkedin.com/in/laxmangaidhankar)
[![Twitter](https://img.shields.io/badge/Twitter-@lgaidhankar-1DA1F2?style=flat-square&logo=twitter)](https://twitter.com/lgaidhankar)
[![LeetCode](https://img.shields.io/badge/LeetCode-laxmangaidhankar-FFA116?style=flat-square&logo=leetcode&logoColor=white)](https://leetcode.com/laxmangaidhankar)
[![HackerRank](https://img.shields.io/badge/HackerRank-laxmangaidhankar-2EC866?style=flat-square&logo=hackerrank&logoColor=white)](https://hackerrank.com/laxmangaidhankar)
[![GFG](https://img.shields.io/badge/GeeksForGeeks-laxmangaidhankar-2F8D46?style=flat-square&logo=geeksforgeeks&logoColor=white)](https://auth.geeksforgeeks.org/user/laxmangaidhankar)
[![CodeChef](https://img.shields.io/badge/CodeChef-dev__laxman-5B4638?style=flat-square&logo=codechef)](https://codechef.com/users/dev_laxman)

</div>

---

## About Me

I'm a B.Tech student at SCTR's Pune Institute of Computer Technology, building full-stack products across fintech, privacy engineering, and platform security. I believe in shipping fast, iterating constantly, and learning in public.

- 🔭 Currently building **RelayPay** (fintech failover payments), **CipherVault** (PII tokenization engine), and **HeartBench** (privacy-first peer support platform)
- 🤝 Google Student Ambassador — bridging campus and the developer ecosystem
- 🏆 Competed in 4 national hackathons, shortlisted/awarded in all four
- 🎯 Working toward FAANG-level DSA & System Design proficiency
- 💡 Open to internships, open-source collaboration, and startup ideas

---

## 🚀 Featured Projects

<table>
<tr>
<td width="50%" valign="top">

### 💳 RelayPay — Real-Time Payment Failover System &nbsp;![Ongoing](https://img.shields.io/badge/status-ongoing-yellow?style=flat-square)

Fault-tolerant UPI-style payment system that reroutes failed transactions to a pre-approved backup contact instead of leaving them stuck.

**Stack:** MERN (MongoDB, Express, React, Node.js) · Socket.io · JWT

**Highlights:**
- Reroutes failed transactions to a pre-approved backup contact, recovering an estimated ~90-95% of simulated failed payments without manual retry
- Atomic transaction ledger (MongoDB sessions) preventing partial-transfer states across concurrent wallet operations — tested with 10+ concurrent simulated transactions, zero balance inconsistencies
- Real-time failover notifications via Socket.io, cutting failure-to-resolution time to under 3-5 seconds by replacing polling with push-based delivery
- Models realistic failure conditions (network timeout, insufficient balance) affecting ~15% of transactions, with automated failover triggering for each

</td>
<td width="50%" valign="top">

### 🔐 CipherVault — PII Tokenization & Multi-Tenant Data Isolation Engine &nbsp;![Ongoing](https://img.shields.io/badge/status-ongoing-yellow?style=flat-square)

Tokenization engine that replaces sensitive PII fields with secure tokens before data enters downstream systems and reporting pipelines.

**Stack:** Java · Spring Boot · Spring Security · PostgreSQL · JPA

**Highlights:**
- Tokenizes sensitive fields (account numbers, customer identity) so downstream services only ever operate on tokens, not raw PII
- Tenant-aware data access enforcing logical isolation between multiple institutional clients in a shared multi-tenant architecture
- Role-based detokenization workflow requiring reason codes and comprehensive audit logging for every sensitive data access
- Secure token vault architecture designed to minimize PII exposure
- Unit-tested (JUnit + Mockito) across tokenization, authorization, and access-control services

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 💙 HeartBench — Privacy-First Peer Support & Study Matching Platform &nbsp;![Ongoing](https://img.shields.io/badge/status-ongoing-yellow?style=flat-square)

Mobile-first platform connecting students by need category and location zone in real time, built around privacy rather than public broadcast.

**Stack:** React (PWA) · Node.js · Express.js · Socket.io · MongoDB (Geospatial)

**Highlights:**
- MongoDB 2dsphere geospatial proximity matching to connect students by need category and location zone
- Privacy-first matching engine using pseudonymized identities and location fuzzing, replacing public broadcast matching with secure server-side pairing
- Real-time request-response matching via Socket.io, targeting sub-3-second match notification delivery
- Category-based escalation logic to route high-sensitivity requests toward campus counseling resources rather than peer-only matching
- Architected for scale via MongoDB geospatial indexing, with Redis-backed Socket.io scaling identified as the production next step

</td>
<td width="50%" valign="top">

</td>
</tr>
</table>

---

## 🏆 Hackathons & Competitions

| Competition | Result | Focus |
|---|---|---|
| 🥇 **Startup Smackdown Hackathon** | **Top 12 / 163 teams** | Real-world startup problem · Rapid prototyping |
| 🥈 **AWS IIT Bombay ImpactX Challenge** | **Top 100 / 900+ teams** | Innovation · Social & economic impact |
| 🥉 **Dimension X 2026** *(Team: MarathaMinds)* | **Top 33** | Sustainability · Google technologies integration |
| 🏅 **Hack4Delhi** | **Shortlisted** | Civic tech · Pitching to government stakeholders |

> Competed in **4 national hackathons** — shortlisted or awarded in every single one.

---

## 🛠️ Tech Stack

**Languages**

![Java](https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)

**Backend & Frameworks**

![Spring Boot](https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Express](https://img.shields.io/badge/Express.js-000000?style=flat-square&logo=express&logoColor=white)
![Socket.io](https://img.shields.io/badge/Socket.io-010101?style=flat-square&logo=socketdotio&logoColor=white)

**Web**

![React](https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![Tailwind](https://img.shields.io/badge/TailwindCSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)

**Databases & Security**

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=flat-square&logo=mongodb&logoColor=white)
![JWT](https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white)

**Tools**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)


---

## 📊 GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=laxmangaidhankar&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" height="160"/>
&nbsp;&nbsp;
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=laxmangaidhankar&layout=compact&theme=tokyonight&hide_border=true" height="160"/>

<img src="https://github-readme-streak-stats.herokuapp.com/?user=laxmangaidhankar&theme=tokyonight&hide_border=true" height="160"/>

</div>

---

## 🎯 2025–26 Roadmap

- [ ] Ship **RelayPay** end-to-end (send money / relay status FSM screen, Android app)
- [ ] Take **CipherVault** and **HeartBench** to a demoable state
- [ ] Deep-dive into **System Design** (HLD + LLD)
- [ ] Win (not just compete) in a national hackathon

---

<div align="center">

*"Ideas are easy. Implementation is hard. Build fast, fail fast, learn faster."*

![Profile Views](https://komarev.com/ghpvc/?username=laxmangaidhankar&color=1A56DB&style=flat-square)

</div>
