<p align="center">
  <img src="./assets/aniraku-banner.svg" alt="Aniraku — a quieter way to watch" width="100%" />
</p>

<p align="center">
  <a href="https://www.aniraku.tech/">Website</a>&nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Aniraku/Aniraku">Frontend</a>&nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://github.com/Aniraku/Aniraku-Backend">Backend</a>&nbsp;&nbsp;·&nbsp;&nbsp;
  <a href="https://discord.gg/aniraku">Community</a>
</p>

## The idea

Aniraku is an open-source anime experience built around **less noise and more continuity**. Find something worth watching, keep your library close, and move from discovery to playback without losing the thread.

## The system

| | Repository | What it owns |
|:--:|:--|:--|
| `01` | [Aniraku](https://github.com/Aniraku/Aniraku) | React/Vite client for discovery, profiles, libraries, and viewing |
| `02` | [Aniraku-Backend](https://github.com/Aniraku/Aniraku-Backend) | Go service for API, authentication, metadata, and provider coordination |
| `03` | [.github](https://github.com/Aniraku/.github) | Organization-wide profile and community configuration |

## Under the hood

```text
React + Vite client
        │
        ▼
Go API service ─── Supabase authentication
        │
        ├── AniList metadata
        ├── Miruro provider
        └── Senshi HLS provider
```

The repositories are intentionally separated by responsibility. The public profile documents the shape of the system, never its secrets or private operational configuration.

## What we care about

**Calm interfaces.** The product should make room for the content rather than compete with it.

**Reliable edges.** Provider fallbacks, explicit errors, and careful boundaries matter more than clever abstractions.

**Open contribution.** Good ideas are welcome when they arrive with context, tests, and respect for the project’s legal and community standards.

## Start here

Read the project-specific [contribution guide](https://github.com/Aniraku/Aniraku/blob/main/CONTRIBUTING.md) before opening a pull request. For security concerns, use a private disclosure channel instead of a public issue.

<p align="center"><sub>Built openly by the Aniraku community. Please respect applicable content rights and service terms.</sub></p>
