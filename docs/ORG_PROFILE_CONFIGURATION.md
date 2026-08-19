# Organization profile configuration findings

## 2026-08-19

- `Aniraku/Aniraku` public repository Discussions are enabled. Its public community route is `https://github.com/Aniraku/Aniraku/discussions`.
- The public Aniraku organization currently has no configured repository pins according to the GitHub GraphQL profile query.
- GitHub's official documentation states that only organization owners can pin repositories. The supported operation is performed in the organization Overview page: select the public view, then use **pin repositories** in the sidebar or **Customize pins** in the Pinned section, choose the repositories, and save.
- The public Overview should pin only `Aniraku/Aniraku` and `Aniraku/Aniraku-App`. The `.github` repository must remain unpinned.
- Direct API mutation attempts did not expose an organization repository-pinning mutation or REST endpoint. The owner-only browser interface is therefore required for the final pin action.
