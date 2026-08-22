<h1 align="center">
  <a href="https://git.io/typing-svg"><img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=30&pause=1000&color=1FF736&background=000000&center=true&vCenter=true&width=600&lines=Hi%2C+I'm+Duvan+Hernandez;Systems+Engineer+%7C+MSc+in+Intelligent+Applications;Backend+with+Ruby+and+Go%2C+mobile+with+Flutter" alt="Duvan Hernandez" /></a>
</h1>

<p align="center">
  <a href="https://www.linkedin.com/in/duvan-hernandez-figueroa-283011203"><img src="https://img.shields.io/badge/LinkedIn-%230A66C2.svg?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
  <a href="mailto:duvanherfi@gmail.com"><img src="https://img.shields.io/badge/Email-%23EA4335.svg?style=flat-square&logo=gmail&logoColor=white" alt="Email"/></a>
  <a href="https://wa.me/573187670164"><img src="https://img.shields.io/badge/WhatsApp-%2325D366.svg?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp"/></a>
</p>

---

## About me

<img align="right" src="./Images/Right_Side.gif?raw=true" width=28%>

I build backends that have to keep running and mobile apps that have to feel
native. Currently at [@picap-inc](https://github.com/picap-inc), working mostly
in Ruby on Rails and Go.

- Systems Engineer, [Universidad del Valle](https://eisc.univalle.edu.co/) — MSc in intelligent application development
- Day to day: **Ruby on Rails**, **Go**, **Flutter**, **PostgreSQL / MongoDB**, **RabbitMQ**, **Docker**
- I like problems where the interesting part is the constraint: a streaming
  proxy because the server refuses unbounded requests, a cache store because
  the app runs on Mongo and not Active Record
- Based in Cali, Colombia. Open to remote work and freelance projects.

<br clear="right">

---

## Projects

### [Tunebox](https://github.com/duvanherfi/tunebox) · Flutter, Dart
A YouTube Music client for Android, Android Auto and macOS that talks to
InnerTube directly — no microG, no Play Services, no WebView. Playback goes
through a loopback proxy that fetches 1 MiB windows, because googlevideo
refuses unbounded requests. Offline downloads, synced lyrics, Last.fm and
ListenBrainz scrobbling, home-screen widget. Ships as signed releases with a
[Homebrew tap](https://github.com/duvanherfi/homebrew-tunebox) for macOS.

What was measured against YouTube's servers — and what turned out not to work —
is written down in [`docs/streaming-findings.md`](https://github.com/duvanherfi/tunebox/blob/main/docs/streaming-findings.md).

### [solid_cache_mongoid](https://github.com/duvanherfi/solid_cache_mongoid) · Ruby, Rails
Rails' Solid Cache rewritten on top of Mongoid, so applications backed by
MongoDB get a database-backed `ActiveSupport::Cache::Store` instead of being
forced onto Redis. Published as a gem.

### [Smart Tracking](https://github.com/duvanherfi/smart-tracking-docs) · Flutter, Rails, MongoDB
Fleet tracking app that derives geofences from raw location history with
**DBSCAN** clustering, instead of asking the operator to draw them by hand.
Technical, install and user manuals in the repo.

### [Rails microservices over RabbitMQ](https://github.com/duvanherfi/rails-microservices-rabbitmq) · Ruby, Rails
Two services, REST for synchronous queries and RabbitMQ for events, with the
consistency and ordering trade-offs written out rather than assumed.

### [stock-analysis](https://github.com/duvanherfi/stock-analysis) · Go
Market data service on Echo + GORM over CockroachDB: ingests quotes, ranks
them, serves a bundled web UI. `docker compose up` and it runs.

---

## Stack

**Every day**

<p>
  <img src="https://img.shields.io/badge/Ruby%20on%20Rails-D30001?style=flat-square&logo=rubyonrails&logoColor=white" />
  <img src="https://img.shields.io/badge/Go-00ADD8?style=flat-square&logo=go&logoColor=white" />
  <img src="https://img.shields.io/badge/Flutter-02569B?style=flat-square&logo=flutter&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" />
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" />
  <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" />
  <img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" />
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white" />
  <img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" />
  <img src="https://img.shields.io/badge/Hotwire-FF3E00?style=flat-square&logo=hotwire&logoColor=white" />
  <img src="https://img.shields.io/badge/Vue.js-4FC08D?style=flat-square&logo=vuedotjs&logoColor=white" />
</p>

**Also worked with**

<p>
  <img src="https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white" />
  <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" />
  <img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" />
  <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" />
  <img src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" />
  <img src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=amazonwebservices&logoColor=white" />
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=flat-square&logo=googlecloud&logoColor=white" />
  <img src="https://img.shields.io/badge/Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white" />
  <img src="https://img.shields.io/badge/Terraform-7B42BC?style=flat-square&logo=terraform&logoColor=white" />
</p>

---

<details>
  <summary><b>GitHub stats</b></summary>
  <br>
  <p align="center">
    <img src="https://github-readme-stats.vercel.app/api?username=duvanherfi&show_icons=true&count_private=true&locale=en&theme=tokyonight" height="170px"/>
    <img src="https://github-readme-stats.vercel.app/api/top-langs?username=duvanherfi&layout=compact&langs_count=8&locale=en&theme=tokyonight" height="170px"/>
  </p>
  <p align="center"><sub>Top languages only reflects what my public code is written in.</sub></p>
</details>
