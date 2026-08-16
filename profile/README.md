<p align="center">
  <img src="./assets/aniraku-banner.svg" alt="Aniraku — a quieter way to watch" width="100%" />
</p>

<p align="center">
  <a href="https://www.aniraku.tech/"><img src="https://img.shields.io/badge/Live%20experience-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Live experience" /></a>
  <a href="https://github.com/Aniraku/Aniraku"><img src="https://img.shields.io/badge/Frontend-111827?style=for-the-badge&logo=react&logoColor=61DAFB" alt="Frontend repository" /></a>
  <a href="https://aniraku.github.io/Aniraku-App/"><img src="https://img.shields.io/badge/Native%20Android-111827?style=for-the-badge&logo=android&logoColor=96D37B" alt="Aniraku Native Android" /></a>
  <a href="https://discord.gg/aniraku"><img src="https://img.shields.io/badge/Community-111827?style=for-the-badge&logo=discord&logoColor=5865F2" alt="Discord community" /></a>
</p>

<img src="./assets/profile-divider.svg" alt="Gradient divider" width="100%" />

## The idea

Aniraku is an open-source anime experience built around **less noise and more continuity**. Find something worth watching, keep your library close, and move from discovery to playback without losing the thread.

```text
one product
 two repositories
  a calmer path from search to screen
```

## The showcase

### Aniraku / Frontend

<p><strong>The visible surface.</strong><br/>A React and Vite experience for discovery, schedules, profiles, libraries, watch history, and focused playback.</p>

<p>
  <a href="https://github.com/Aniraku/Aniraku"><img src="https://img.shields.io/github/stars/Aniraku/Aniraku?style=flat-square&label=stars&color=818CF8&labelColor=111827&logo=github" alt="Aniraku frontend stars" /></a>
  <a href="https://github.com/Aniraku/Aniraku/network/members"><img src="https://img.shields.io/github/forks/Aniraku/Aniraku?style=flat-square&label=forks&color=22D3EE&labelColor=111827&logo=github" alt="Aniraku frontend forks" /></a>
  <img src="https://img.shields.io/badge/React%20%2B%20Vite-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React and Vite" />
</p>

### Aniraku / Backend

<p><strong>The quiet engine.</strong><br/>A Go service for API access, Supabase authentication, AniList metadata, provider coordination, network safety, and normalized edges.</p>

<p>
  <a href="https://github.com/Aniraku/Aniraku-Backend"><img src="https://img.shields.io/badge/Go%201.24-111827?style=flat-square&logo=go&logoColor=00ADD8" alt="Go 1.24" /></a>
  <a href="https://github.com/Aniraku/Aniraku-Backend/blob/main/CONTRIBUTING.md"><img src="https://img.shields.io/badge/Contribute-111827?style=flat-square&logo=gitbook&logoColor=F8FAFC" alt="Backend contribution guide" /></a>
</p>

### Aniraku / Native Android

<p><strong>v2.6 is the current stable direct-distribution release.</strong><br/>The Expo and React Native client brings Aniraku discovery, source-aware native playback, website-provider parity, replay-safe rebuffer recovery, resilient public Downloads-folder saves for eligible direct sources, guarded embedded-player navigation, and the same protected AniList/MyAnimeList library-sync route used by aniraku.tech to Android 9+ devices.</p>

<p>
  <a href="https://aniraku.github.io/Aniraku-App/"><img src="https://img.shields.io/badge/App%20site-111827?style=flat-square&logo=android&logoColor=96D37B" alt="Aniraku Android app site" /></a>
  <a href="https://github.com/Aniraku/Aniraku-App/releases/tag/v2.6"><img src="https://img.shields.io/badge/v2.6-FF4D4D?style=flat-square&logo=github&logoColor=111827" alt="Aniraku v2.6 stable release" /></a>
  <a href="https://rookieenough.github.io/Orion-Data/redirect.html?id=aniraku"><img src="https://img.shields.io/badge/Orion%20Store-111827?style=flat-square&logo=android&logoColor=96D37B" alt="Get Aniraku on Orion Store" /></a>
</p>

> **Package:** `aniraku.anime.app` · **Compatibility:** Android 9+ (API 28+) · ARM32 + ARM64 · **Install:** direct APK, without Google Play.

<p><a href="https://github.com/Aniraku/Aniraku-App"><strong>Explore the Android source and downloads →</strong></a></p>

<img src="./assets/profile-divider.svg" alt="Gradient divider" width="100%" />

## Architecture

```text
┌────────────────────────────┐
│ React + Vite · Native App  │
│   discover · save · watch  │
└──────────────┬─────────────┘
               │
┌──────────────▼─────────────┐
│        Go API service      │
│ auth · metadata · routing  │
└───────┬─────────┬──────────┘
        │         │
   AniList    providers
              Miruro · Senshi
```

## Stack constellation

<p>
  <img src="https://img.shields.io/badge/React-111827?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
  <img src="https://img.shields.io/badge/Vite-111827?style=flat-square&logo=vite&logoColor=646CFF" alt="Vite" />
  <img src="https://img.shields.io/badge/Go-111827?style=flat-square&logo=go&logoColor=00ADD8" alt="Go" />
  <img src="https://img.shields.io/badge/Supabase-111827?style=flat-square&logo=supabase&logoColor=3ECF8E" alt="Supabase" />
  <img src="https://img.shields.io/badge/AniList-111827?style=flat-square&logo=anilist&logoColor=02A9FF" alt="AniList" />
  <img src="https://img.shields.io/badge/Docker-111827?style=flat-square&logo=docker&logoColor=2496ED" alt="Docker" />
</p>

## Organization pulse

<p align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=Aniraku&theme=github_dark&show_icons=true&hide_border=true&bg_color=00000000&title_color=A78BFA&text_color=94A3B8&icon_color=60A5FA&rank_icon=github&include_all_commits=true" alt="Aniraku GitHub statistics" height="180" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Aniraku&bg_color=00000000&color=94A3B8&line=A78BFA&point=60A5FA&area=true&hide_border=true" alt="Aniraku activity graph" width="96%" />
</p>

## Contribute to the atmosphere

Good contributions arrive with context, clear boundaries, and respect for the project’s users and upstream services. Start with the repository-specific contribution guide, keep secrets out of commits, and use private disclosure for security concerns.

<p>
  <a href="https://github.com/Aniraku/Aniraku/issues"><img src="https://img.shields.io/badge/Issues-111827?style=for-the-badge&logo=github&logoColor=F8FAFC" alt="Aniraku issues" /></a>
  <a href="https://github.com/Aniraku"><img src="https://img.shields.io/badge/All%20repositories-111827?style=for-the-badge&logo=github&logoColor=F8FAFC" alt="All Aniraku repositories" /></a>
</p>

<p align="center"><sub>Built openly by the Aniraku community. Please respect applicable content rights and service terms.</sub></p>
