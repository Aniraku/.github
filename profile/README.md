<p align="center">
  <img src="./assets/aniraku-banner.svg" alt="Aniraku — a quieter way to watch" width="100%" />
</p>

<p align="center">
  <a href="https://www.aniraku.tech/"><img src="https://img.shields.io/badge/Web%20Experience-111827?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Open Aniraku on the web" /></a>
  <a href="https://aniraku.github.io/Aniraku-App/"><img src="https://img.shields.io/badge/Native%20Android-111827?style=for-the-badge&logo=android&logoColor=96D37B" alt="Open the Aniraku Android app site" /></a>
  <a href="https://github.com/Aniraku"><img src="https://img.shields.io/badge/Open%20Source-111827?style=for-the-badge&logo=github&logoColor=white" alt="Browse Aniraku on GitHub" /></a>
</p>

## About Aniraku

Aniraku is an open-source anime experience for discovering titles, keeping a personal library, following episode context, and watching through the interfaces that fit each device. The web, backend, and Android projects share one goal: make the route from *finding something good* to *continuing the story* feel clear and respectful of the viewer’s time.

> **Open by default.** The profile uses the real Aniraku banner already maintained in this repository, GitHub Flavored Markdown, standard Shields.io badges, and public open-source profile patterns. It does not rely on generated artwork or invented visual assets.

## Explore the projects

| Project | Purpose | Start here |
| --- | --- | --- |
| **Aniraku Web** | React and Vite for discovery, schedules, profiles, libraries, watch history, and browser playback. | [Repository](https://github.com/Aniraku/Aniraku) · [Live site](https://www.aniraku.tech/) |
| **Aniraku Backend** | Go services for API access, Supabase authentication, AniList metadata, provider coordination, and normalized data. | [Repository](https://github.com/Aniraku/Aniraku-Backend) |
| **Aniraku Native Android** | Expo and React Native client for direct Android distribution, native playback context, and supported offline downloads. | [Repository](https://github.com/Aniraku/Aniraku-App) · [App site](https://aniraku.github.io/Aniraku-App/) |

<p align="center">
  <a href="https://github.com/Aniraku/Aniraku"><img src="https://img.shields.io/github/stars/Aniraku/Aniraku?style=flat-square&label=Aniraku%20stars&color=5B8DEF&labelColor=111827&logo=github" alt="Aniraku frontend stars" /></a>
  <a href="https://github.com/Aniraku/Aniraku/network/members"><img src="https://img.shields.io/github/forks/Aniraku/Aniraku?style=flat-square&label=forks&color=7CC4A6&labelColor=111827&logo=github" alt="Aniraku frontend forks" /></a>
  <a href="https://github.com/Aniraku/Aniraku-App/releases/latest"><img src="https://img.shields.io/github/v/release/Aniraku/Aniraku-App?display_name=tag&style=flat-square&label=Android%20release&color=E66A6A&labelColor=111827&logo=github" alt="Latest Aniraku Android release" /></a>
</p>

## Native Android / v4.2

The current stable Android release is **v4.2** for `aniraku.anime.app`. It retains the native Anime Detail relationships, provider-aware playback recovery, quality selection, AniSkip, fullscreen, direct downloads where eligible, and protected list synchronization. v4.2 also prevents a routine Watch-history refresh from applying an old resume point after a rebuffer, so the active forward buffer can continue without an application-driven backward seek.

| Package | Device support | Official routes |
| --- | --- | --- |
| `aniraku.anime.app` | Android 9+ · ARM32 + ARM64 | [App site](https://aniraku.github.io/Aniraku-App/) · [v4.2 release](https://github.com/Aniraku/Aniraku-App/releases/tag/v4.2) · [Orion Store](https://rookieenough.github.io/Orion-Data/redirect.html?id=aniraku) |

<p align="center">
  <a href="https://github.com/Aniraku/Aniraku-App/releases/tag/v4.2"><img src="https://img.shields.io/badge/Download%20v4.2-E66A6A?style=for-the-badge&logo=android&logoColor=111827" alt="Download Aniraku v4.2" /></a>
  <a href="https://aniraku.github.io/Aniraku-App/"><img src="https://img.shields.io/badge/Installation%20Guide-111827?style=for-the-badge&logo=readme&logoColor=white" alt="Open the Aniraku Android installation guide" /></a>
  <a href="https://rookieenough.github.io/Orion-Data/redirect.html?id=aniraku"><img src="https://img.shields.io/badge/Orion%20Store-111827?style=for-the-badge&logo=android&logoColor=96D37B" alt="Get Aniraku from Orion Store" /></a>
</p>

## How to participate

| If you want to… | The best path |
| --- | --- |
| Report a reproducible issue | [Open an issue in the web repository](https://github.com/Aniraku/Aniraku/issues) or use the relevant project repository. |
| Improve code or documentation | Read the repository-specific contribution guidance, keep scope clear, and use a focused pull request. |
| Discuss a security concern | Use the published [security policy](https://github.com/Aniraku/Aniraku-App/blob/main/SECURITY.md) instead of posting sensitive details publicly. |
| Follow development | Browse the [organization repositories](https://github.com/Aniraku) and the latest [Android release](https://github.com/Aniraku/Aniraku-App/releases/latest). |

## Profile sources

This public profile follows the documented GitHub organization README convention and draws its information hierarchy from real open-source organization profiles and curated examples. The implementation intentionally favors stable Markdown, project links, and existing assets over generated visuals.

- [GitHub Docs: Customizing an organization profile](https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile)
- [Awesome GitHub Organization Profile READMEs](https://github.com/fabrecostudio/awesome-github-organization-profile-readme)
- [Ant Design Team organization profile](https://github.com/ant-design)
- [Shields.io](https://shields.io/)

<p align="center"><sub>Built openly by the Aniraku community. Please respect applicable content rights, upstream services, and each other.</sub></p>
