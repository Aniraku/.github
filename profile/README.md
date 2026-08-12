# Aniraku

<p align="center"><strong>Open-source tools for anime discovery and viewing.</strong></p>

<p align="center">
  <img src="https://img.shields.io/badge/Open%20source-161B22?style=for-the-badge&logo=github&logoColor=white" alt="Open source"/>
  <img src="https://img.shields.io/badge/React%20%2B%20Vite-06B6D4?style=for-the-badge&logo=react&logoColor=white" alt="React and Vite"/>
  <img src="https://img.shields.io/badge/Go%20backend-8B5CF6?style=for-the-badge&logo=go&logoColor=white" alt="Go backend"/>
</p>

Aniraku builds a focused anime experience around discovery, metadata, personal libraries, and adaptable playback. The organization separates the browser client from the service layer so each repository can evolve with a clear technical boundary.

## Repositories

| Repository | Role | Primary verified stack |
|---|---|---|
| [Aniraku](https://github.com/Aniraku/Aniraku) | React-based discovery and viewing frontend | React, JSX, Vite, CSS, AniList, Supabase client |
| [Aniraku-Backend](https://github.com/Aniraku/Aniraku-Backend) | API, authentication, metadata, and provider coordination | Go 1.24, Chi, Zerolog, Supabase JWT/JWKS |
| [.github](https://github.com/Aniraku/.github) | Organization-wide community configuration | GitHub profile and repository governance |

## Architecture at a Glance

```text
React/Vite client
       |
       v
Go API service ── Supabase authentication
       |
       +── AniList metadata
       +── Miruro provider
       +── Senshi HLS provider
```

The architecture diagram reflects repository evidence and is intentionally high-level. Configuration values, credentials, private operational details, and upstream secrets do not belong in this profile.

## Community Standards

We value focused product design, accessible interfaces, maintainable code, responsible upstream usage, and respectful collaboration. Read each repository’s contribution guide before opening a pull request, and report security concerns through the appropriate private channel rather than a public issue.

## Links

Visit the [Aniraku website](https://www.aniraku.tech/), browse the [organization repositories](https://github.com/Aniraku), or join the [community Discord](https://discord.gg/aniraku).

---

<p align="center"><sub>Built openly by the Aniraku community. Please respect applicable content rights and service terms.</sub></p>
