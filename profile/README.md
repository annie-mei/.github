<div align="center">

# Annie Mei

Open source tools for anime and manga discovery in Discord.

[Main bot](https://github.com/annie-mei/annie-mei) · [Auth service](https://github.com/annie-mei/auth) · [Live docs](https://anniemei.app/) · [Docs source](https://github.com/annie-mei/docs)

![Rust](https://img.shields.io/badge/Rust-2024-orange?logo=rust&logoColor=white)
![Discord bot](https://img.shields.io/badge/Discord-bot-5865F2?logo=discord&logoColor=white)
![AniList](https://img.shields.io/badge/AniList-powered-02A9FF)
![Docs](https://img.shields.io/badge/Docs-Mintlify-16BDCA)

</div>

Annie Mei is a Rust Discord bot that helps your server look up anime and manga details from AniList, discover opening and ending themes, and connect AniList accounts for richer shared context.

## What we maintain

| Repository | Purpose |
| --- | --- |
| [`annie-mei`](https://github.com/annie-mei/annie-mei) | Main Discord bot built with Rust, Serenity, and Axum |
| [`auth`](https://github.com/annie-mei/auth) | AniList OAuth service used for account linking |
| [`docs`](https://github.com/annie-mei/docs) | Mintlify documentation site and setup guides |

## Highlights

- Anime and manga lookups powered by AniList
- Theme song discovery backed by MyAnimeList and Spotify
- AniList account linking for member score context
- Japanese kana-friendly search support
- Observability with Sentry and lightweight health endpoints

## Tech stack

- Rust for the bot and auth services
- Serenity for Discord interactions
- Axum and Rocket for HTTP services
- PostgreSQL and Redis for persistence and caching
- Mintlify for public docs

## Explore Annie Mei

- Read the [live documentation site](https://anniemei.app/)
- Browse the [docs source repository](https://github.com/annie-mei/docs)
- Browse the [main bot source](https://github.com/annie-mei/annie-mei)
- Inspect the [AniList auth service](https://github.com/annie-mei/auth)

## Contributing

Issues and pull requests are welcome. If you want to improve the bot, auth flow, or docs, start in the repository closest to the change and include enough context for reproduction or review.
