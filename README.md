# marcramiro-comments

**Public** repository that hosts the **blog comments** for [marcramiro.com](https://marcramiro.com) using **Giscus** (GitHub Discussions).

## How it works
- The site embeds the Giscus widget and maps each article to a *Discussion* (via `pathname`).
- The first time someone comments, Giscus creates the thread if it doesn’t exist.
- All comment content lives here, not in the site’s code repository.

## Moderation & guidelines
- Be civil. No spam, no offensive/illegal content.
- I may edit/hide comments or block users when necessary.
- Questions or reports: open a *Discussion* in the **Meta** category.

## Privacy
- You need a GitHub account to comment. Your comments are public.
- No ads or extra trackers: backend is GitHub Discussions.

## Configuration (summary)
- Primary category: **Comments** (search only within this category).
- `mapping`: `pathname` with `strict: true` to avoid duplicates.
- Allowed origins (optional): `giscus.json` restricting to `https://marcramiro.com`.

## Not for code issues
- This repo **does not** accept Issues/PRs for the website code. Use it only for blog comments.

## Licensing

- **Code & configuration:** [MIT](./LICENSE)
- **User-generated comments:** [CC BY 4.0](./COMMENTS-LICENSE.md)

Comments live in **GitHub Discussions** and are embedded on https://marcramiro.com via Giscus.
