<div align="center">

<br/>

```
  ██████╗ ███████╗██████╗  █████╗ ██████╗  ██████╗ ██╗  ██╗ █████╗
  ██╔══██╗██╔════╝██╔══██╗██╔══██╗██╔══██╗██╔════╝ ██║  ██║██╔══██╗
  ██║  ██║█████╗  ██████╔╝███████║██████╔╝██║  ███╗███████║███████║
  ██║  ██║██╔══╝  ██╔══██╗██╔══██║██╔══██╗██║   ██║██╔══██║██╔══██║
  ██████╔╝███████╗██████╔╝██║  ██║██║  ██║╚██████╔╝██║  ██║██║  ██║
  ╚═════╝ ╚══════╝╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Mono&size=16&pause=1400&color=0FF7F7&center=true&vCenter=true&width=640&lines=Building+things+that+have+to+work+in+the+real+world.;AI+systems.+Embedded+hardware.+Full-stack+products.;Freshman+%40+NSEC+%E2%80%94+CSE.+Builder+by+default.;Real-time.+Self-hosted.+On-device.+Always+shipping." alt="Typing SVG" />

<br/>

![Profile Views](https://komarev.com/ghpvc/?username=My-Mation&color=0FF7F7&style=flat-square&label=PROFILE+VIEWS)
&nbsp;
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/debargha-sarkar-72575937a/)
[![Instagram](https://img.shields.io/badge/coded.by.deb-E4405F?style=flat-square&logo=instagram&logoColor=white)](https://www.instagram.com/coded.by.deb/)
[![X](https://img.shields.io/badge/@My__Mation-000000?style=flat-square&logo=x&logoColor=white)](https://x.com/My_Mation)
[![Portfolio](https://img.shields.io/badge/portfolio-22272E?style=flat-square&logo=vercel&logoColor=white)](https://portfolio-hazel-beta-83.vercel.app/)
[![RapidAPI](https://img.shields.io/badge/APIs-005571?style=flat-square&logo=rapidapi&logoColor=white)](https://rapidapi.com/user/MyMation)
[![itch.io](https://img.shields.io/badge/games-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white)](https://my-mation69.itch.io)

</div>

<br/>

---

I build systems that have to work. Not demos, not prototypes that get shelved — things that run, that people depend on, that fail in interesting ways and have to be recovered. I care about understanding the moving parts, debugging what breaks, and designing for what comes after the first version. Mobile, embedded, real-time, backend, game systems — I move across the stack because the problems do too.

Currently a CSE freshman at Netaji Subhash Engineering College, West Bengal. Long-term direction: AI infrastructure, server hosting, and product systems at scale.

---

## 🔴 Currently Building

<div align="center">

![Status](https://img.shields.io/badge/STATUS-BUILDING-0FF7F7?style=for-the-badge&labelColor=0d1117)
&nbsp;
![Focus](https://img.shields.io/badge/FOCUS-Embedded+AI+%2B+Self--Hosted+Infra-FF6B6B?style=for-the-badge&labelColor=0d1117)
&nbsp;
![Open to](https://img.shields.io/badge/OPEN+TO-Collabs+%26+Internships-2EA44F?style=for-the-badge&labelColor=0d1117)

</div>

```python
current_build = {
    "project"   : "AI-Powered Adaptive Testing Station (ESP32 + NotebookLLM)",
    "stack"     : ["C++", "PlatformIO", "Next.js", "NotebookLLM", "ESP32"],
    "status"    : "Firmware stable. Backend sync in progress.",
    "also"      : ["Self-balancing robot (ESP32 + MPU6050)", "Wireless Observatory v3"],
    "learning"  : ["ML systems design", "server infrastructure", "embedded AI"],
}
```

---

## 🏆 GitHub Trophies

<div align="center">

[![trophy](https://github-profile-trophy.vercel.app/?username=My-Mation&theme=darkhub&no-frame=true&no-bg=true&margin-w=6&column=7)](https://github.com/ryo-ma/github-profile-trophy)

</div>

---

## Flagship Projects

<details open>
<summary><b>RepBot — Real-Time AI Fitness Tracking</b> &nbsp;·&nbsp; <code>Flutter</code> <code>On-Device ML</code> <code>Android</code></summary>

<br/>

> On-device pose estimation with automatic rep counting and live visual feedback — zero cloud, zero manual input.

Built on Google's ML Kit pose model, running entirely on-device. The system tracks joint angles frame-by-frame, infers rep boundaries from motion state transitions, and gives audio-visual feedback in real time. No server roundtrip. No latency. No privacy leakage.

![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white)
![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white)
![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white)
![On Device ML](https://img.shields.io/badge/On--Device_ML-FF6B6B?style=flat-square)

[![Play Store](https://img.shields.io/badge/Google_Play-34A853?style=flat-square&logo=google-play&logoColor=white)](https://play.google.com/store/apps/details?id=com.debargha.repbot)

</details>

---

<details open>
<summary><b>AI-Powered Adaptive Testing Station</b> &nbsp;·&nbsp; <code>ESP32</code> <code>C++</code> <code>Next.js</code> <code>NotebookLLM</code></summary>

<br/>

> Hardware + AI test system: teachers upload PDFs, AI generates the quiz, ESP32 administers it, AI evaluates and returns personalized feedback.

A full-loop system. PDF upload → NotebookLLM parses and generates structured JSON quiz → POST to ESP32 → adaptive `TestState` engine runs branching question trees on hardware → student answers via keypad, touch sensor, or voice → responses queued to Next.js backend → AI returns targeted feedback on weak points. Hardware interface: OLED, TM1637 7-seg timer, 4×4 matrix keypad, touch-to-record audio, active buzzer. Audio captured as WebM/Opus, encoded to MP3 (44100Hz mono 128kbps) before backend sync.

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white)
![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white)

[![GitHub](https://img.shields.io/badge/black--current--esp-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/My-Mation/black-current-esp)

</details>

---

<details open>
<summary><b>MindPlay — Multiplayer Quiz & Social Deduction</b> &nbsp;·&nbsp; <code>Node.js</code> <code>Socket.IO</code> <code>MongoDB</code> <code>Firebase</code></summary>

<br/>

> Fault-tolerant real-time multiplayer with live room sync and authoritative server-side state.

The state lives on the server. Clients are thin. Room synchronization handles late joins, disconnects, and reconnects without desync. Built to stay consistent under network noise — not just under ideal conditions.

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white)
![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black)

[![GitHub](https://img.shields.io/badge/RealtimeQuiz-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/My-Mation/RealtimeQuiz)

</details>

---

<details>
<summary><b>Wireless Observatory Node</b> &nbsp;·&nbsp; <code>Python</code> <code>Flask</code> <code>Termux</code> <code>Android</code></summary>

<br/>

> Portable RF and wireless monitoring node running entirely on an Android device via Termux — no dedicated hardware needed.

Real-time radar visualization, WiFi scanning, device presence detection, RF density graphing, and motion detection — all in a dark cyber-console dashboard served locally from the phone. Self-contained. Zero cloud. Useful in the field.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Linux](https://img.shields.io/badge/Termux-2EA44F?style=flat-square&logo=linux&logoColor=white)

[![GitHub](https://img.shields.io/badge/network--scanner-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/My-Mation/network-scanner)
![Stars](https://img.shields.io/github/stars/My-Mation/network-scanner?style=flat-square&label=⭐)

</details>

---

<details>
<summary><b>Live Chat Top-Down Shooter</b> &nbsp;·&nbsp; <code>Unity</code> <code>C#</code> <code>YouTube Live Chat API</code></summary>

<br/>

> YouTube viewers type in chat → their named entity spawns and fights inside a procedurally generated arena.

The game reads live messages, spawns controlled entities per username, and handles concurrent inputs from an audience in real time. An experiment in turning passive viewership into active participation.

![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white)
![YouTube](https://img.shields.io/badge/YouTube_API-FF0000?style=flat-square&logo=youtube&logoColor=white)

[![GitHub](https://img.shields.io/badge/LiveChatShooter-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/My-Mation/LiveChatShooter)

</details>

---

<details>
<summary><b>SpotiRip — Self-Hosted Music Streaming on Android</b> &nbsp;·&nbsp; <code>Navidrome</code> <code>Termux</code> <code>Ubuntu proot</code></summary>

<br/>

> Full private music server running on an Android phone — Subsonic-compatible, zero tracking, full library control.

Ubuntu userspace via proot inside Termux. Navidrome handles indexing and the Subsonic API. Ultrasonic on Android as the client. No subscription, no third-party servers, no data leaving the device.

![Linux](https://img.shields.io/badge/Ubuntu_proot-E95420?style=flat-square&logo=ubuntu&logoColor=white)
![Navidrome](https://img.shields.io/badge/Navidrome-2EA44F?style=flat-square)
![Self Hosted](https://img.shields.io/badge/Self--Hosted-0FF7F7?style=flat-square)

[![GitHub](https://img.shields.io/badge/SpotiRip-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/My-Mation/Spotirip)

</details>

---

<details>
<summary><b>Public Security APIs</b> &nbsp;·&nbsp; <code>REST</code> <code>Node.js</code> <code>Render</code></summary>

<br/>

> Production APIs on RapidAPI — privacy-preserving, deterministic, no ML black boxes.

- **Password Risk Detection** — breach exposure scoring and guessability analysis, privacy-preserving
- **Email Risk & Disposable Domain** — MX validation, typo detection, subdomain and disposable checks
- **CSV Data Cleaning & Normalization** — schema-safe, deterministic pipeline

![REST](https://img.shields.io/badge/REST-005571?style=flat-square)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black)

[![RapidAPI](https://img.shields.io/badge/View_APIs-005571?style=flat-square&logo=rapidapi&logoColor=white)](https://rapidapi.com/user/MyMation)

</details>

---

<details>
<summary><b>Indie Games — Sarbanash & Kisor</b> &nbsp;·&nbsp; <code>Godot</code> <code>GDScript</code> <code>Pixel Art</code></summary>

<br/>

**Sarbanash** — 2D pixel-art survival horror. Classic Pokémon-style exploration meets atmospheric dread. Complete story, event-driven gameplay, state machines throughout.

**Kisor** — A choice-driven psychological mystery. Best experienced blind. You're guiding terminally ill students through their final year. Text-based, branching, heavy.

![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godot-engine&logoColor=white)
![GDScript](https://img.shields.io/badge/GDScript-478CBF?style=flat-square)
![Pixel Art](https://img.shields.io/badge/Pixel_Art-FA5C5C?style=flat-square)

[![Sarbanash](https://img.shields.io/badge/Sarbanash-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white)](https://my-mation69.itch.io/sarbanashgame)
[![Kisor](https://img.shields.io/badge/Kisor-FA5C5C?style=flat-square&logo=itchdotio&logoColor=white)](https://my-mation69.itch.io/kisor)

</details>

---

## Technical Stack

<div align="center">

| Domain | Tools |
|:---:|:---|
| **Languages** | ![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![Dart](https://img.shields.io/badge/Dart-0175C2?style=flat-square&logo=dart&logoColor=white) ![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white) ![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=c-sharp&logoColor=white) ![Java](https://img.shields.io/badge/Java-007396?style=flat-square&logo=java&logoColor=white) |
| **Mobile** | ![Flutter](https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white) ![Android](https://img.shields.io/badge/Android-3DDC84?style=flat-square&logo=android&logoColor=white) ![ML Kit](https://img.shields.io/badge/ML_Kit-FF6B6B?style=flat-square&logo=google&logoColor=white) |
| **Backend** | ![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white) ![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white) ![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white) |
| **Data** | ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?style=flat-square&logo=firebase&logoColor=black) |
| **AI / ML** | ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white) ![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white) |
| **Embedded** | ![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white) ![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white) ![PlatformIO](https://img.shields.io/badge/PlatformIO-F5822A?style=flat-square&logo=platformio&logoColor=white) |
| **Game** | ![Godot](https://img.shields.io/badge/Godot-478CBF?style=flat-square&logo=godot-engine&logoColor=white) ![Unity](https://img.shields.io/badge/Unity-000000?style=flat-square&logo=unity&logoColor=white) |
| **Infra** | ![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black) ![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white) ![Render](https://img.shields.io/badge/Render-46E3B7?style=flat-square&logo=render&logoColor=black) ![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white) |

</div>

---

## Areas of Sustained Interest

```
Real-time systems           ████████████░░░  authoritative state, sync, fault tolerance
Embedded & hardware         ██████████░░░░░  ESP32, sensors, GPIO, actuator control
AI at the edge              █████████░░░░░░  on-device ML, offline inference, no cloud
Self-hosted infrastructure  ████████░░░░░░░  privacy-first, zero dependency stacks
Multiplayer architecture    ███████░░░░░░░░  room systems, reconnection, state machines
Indie game systems          ██████░░░░░░░░░  narrative engines, procedural design
ML & research concepts      █████░░░░░░░░░░  training loops, AGI simulation, system design
```

---

## Builder Timeline

```
2024  ─────────────────────────────────────────────────────────────────►  2025+

 Jun                      Oct                     Dec              Now
  │                       │                       │                │
  ▼                       ▼                       ▼                ▼
Started         RepBot · MindPlay ·          Email Risk API ·    ESP32 Testing
NSEC          Golden Pledges · Kisor ·       ML Trading ·        Station ·
              Sarbanash ·                    Android Game         Network
              YouTube Chat Shooter           Engine concept       Observatory ·
                                                                  Self-Balancing
                                                                  Robot (WIP)
```

---

## Open Source

Contributions focused on backend APIs, real-time infrastructure, game engine tooling, and embedded firmware. Participated in Hacktoberfest and open experimentation across embedded and full-stack domains.

[![Holopin](https://holopin.me/mymation)](https://holopin.io/@mymation)

---

## GitHub Stats

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=My-Mation&show_icons=true&theme=github_dark&hide_border=true&bg_color=00000000&title_color=0FF7F7&icon_color=0FF7F7&text_color=FFFFFF" height="165"/>

<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=My-Mation&layout=compact&theme=github_dark&hide_border=true&bg_color=00000000&title_color=0FF7F7&text_color=FFFFFF" height="165"/>

<br/><br/>

<img src="https://streak-stats.demolab.com?user=My-Mation&theme=github-dark&hide_border=true&mode=weekly&card_width=500" height="160"/>

<br/><br/>

<img src="https://github-readme-activity-graph.vercel.app/graph?username=My-Mation&theme=github-compact&hide_border=true&area=true&color=0FF7F7&line=0FF7F7&point=FFFFFF" width="92%"/>

</div>

---

## Milestones

<div align="center">

<table>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/01-0FF7F7?style=for-the-badge&labelColor=0d1117&color=0FF7F7" height="28"/>
    </td>
    <td>
      <b>RepBot</b> — shipped a production Android app with on-device ML for real-time pose estimation and rep counting, no cloud required
    </td>
  </tr>
  <tr><td colspan="2"><img src="https://img.shields.io/badge/─────────────────────────────────────────────────────────-0d1117?style=flat-square&labelColor=0d1117" width="100%"/></td></tr>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/02-FF6B6B?style=for-the-badge&labelColor=0d1117&color=FF6B6B" height="28"/>
    </td>
    <td>
      <b>RapidAPI</b> — designed and deployed privacy-focused production APIs: password risk detection, email risk & disposable domain, and CSV normalization
    </td>
  </tr>
  <tr><td colspan="2"><img src="https://img.shields.io/badge/─────────────────────────────────────────────────────────-0d1117?style=flat-square&labelColor=0d1117" width="100%"/></td></tr>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/03-2EA44F?style=for-the-badge&labelColor=0d1117&color=2EA44F" height="28"/>
    </td>
    <td>
      <b>MindPlay</b> — built real-time multiplayer and live-chat–driven game systems with authoritative server-side state handling
    </td>
  </tr>
  <tr><td colspan="2"><img src="https://img.shields.io/badge/─────────────────────────────────────────────────────────-0d1117?style=flat-square&labelColor=0d1117" width="100%"/></td></tr>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/04-F5822A?style=for-the-badge&labelColor=0d1117&color=F5822A" height="28"/>
    </td>
    <td>
      <b>ESP32</b> — implemented embedded systems with direct sensor input, actuator control, adaptive state machines, and AI feedback loops
    </td>
  </tr>
  <tr><td colspan="2"><img src="https://img.shields.io/badge/─────────────────────────────────────────────────────────-0d1117?style=flat-square&labelColor=0d1117" width="100%"/></td></tr>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/05-0175C2?style=for-the-badge&labelColor=0d1117&color=0175C2" height="28"/>
    </td>
    <td>
      <b>SpotiRip</b> — deployed a full self-hosted music streaming stack on Android using Termux, Ubuntu (proot), and Navidrome — zero cloud, full control
    </td>
  </tr>
  <tr><td colspan="2"><img src="https://img.shields.io/badge/─────────────────────────────────────────────────────────-0d1117?style=flat-square&labelColor=0d1117" width="100%"/></td></tr>
  <tr>
    <td align="center" width="60">
      <img src="https://img.shields.io/badge/06-FFCA28?style=for-the-badge&labelColor=0d1117&color=FFCA28" height="28"/>
    </td>
    <td>
      <b>Consistency</b> — maintained long-term output across mobile, backend, real-time, embedded, and game systems through Year 1 of college
    </td>
  </tr>
</table>

</div>

---

<div align="center">
<sub>
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Mono&size=12&pause=9999&color=555555&center=true&vCenter=true&width=520&repeat=false&lines=Thanks+for+reading.+A+follow+would+mean+a+lot+%E2%86%92+github.com%2FMy-Mation" alt="Thanks" />
</sub>
</div>

---

## Random Dev Thought

<div align="center">

[![readme-quotes](https://quotes-github-readme.vercel.app/api?type=horizontal&theme=dark)](https://github.com/piyushsuthar/github-readme-quotes)

</div>

---

<div align="center">

<img src="https://readme-typing-svg.demolab.com?font=Fira+Mono&size=13&pause=3000&color=0FF7F7&center=true&vCenter=true&width=520&lines=Ships+things.+Debugs+things.+Reads+error+logs+until+2am.+Repeat." alt="Footer" />

</div>
