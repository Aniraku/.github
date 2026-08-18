# Profile README references

## GitHub platform guidance

- **GitHub Docs — Customizing your organization's profile**: GitHub renders a public organization `README.md` on the organization Overview page and recommends using it for a concise About section and help or engagement guidance. The profile implementation must remain valid GitHub Flavored Markdown.
  - Source: https://docs.github.com/en/organizations/collaborating-with-groups-in-organizations/customizing-your-organizations-profile

## Design constraint

The next Profile README revision will use only existing real Aniraku project assets, GitHub-supported Markdown, and transparent third-party open-source services or patterns. It will not add AI-generated images or invented visual assets.

## Open-source profile patterns reviewed

- **fabrecostudio/awesome-github-organization-profile-readme**: an MIT-licensed curated collection of public organization profile examples. It highlights profile structures ranging from minimalist to detailed and links to established open-source organizations.
  - Source: https://github.com/fabrecostudio/awesome-github-organization-profile-readme
  - Pattern adopted: organize the profile around a short About statement, a compact project ecosystem, and clear participation links instead of decorative generated artwork.

- **Ant Design Team organization profile**: a real public open-source organization profile that makes its ecosystem easy to scan with an About section, grouped project links, design resources, community support, and contribution guidance.
  - Source: https://github.com/ant-design
  - Pattern adopted: use clear hierarchy and real project navigation as the visual anchor; avoid crowded visual widgets and unrelated third-party statistics.

- **GitHub Stats Extended**: a maintained MIT-licensed successor to the deprecated `anuraghazra/github-readme-stats` project. Its predecessor explicitly directs users to this successor for maintained README statistics.
  - Source: https://github.com/stats-organization/github-stats-extended
  - Decision: do not add a dynamic stats card to the Aniraku profile in this revision. The profile will instead use static, verifiable project links and GitHub's own visible organization data to keep the experience lightweight and robust.
