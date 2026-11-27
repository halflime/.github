# HalfLime

[HalfLime](https://halflime.dev/) counts app events and website pageviews in your own Cloudflare account. A Worker writes the events to D1. You can ask an MCP client how many PDF exports finished this week, or get the same counts through the HTTP API.

For self-hosted error tracking, see our sibling project [Bicho FYI](https://github.com/bicho-fyi/bicho).

## SDKs

| SDK | Use it for |
| --- | --- |
| [JavaScript / TypeScript](https://github.com/halflime/halflime-javascript) | Track events in browsers and Node.js, or count website pageviews. |
| [Rust](https://github.com/halflime/halflime-rust) | Send events from a Rust app, including a Tauri backend. |

## Support HalfLime

Found a bug? Open an issue in the SDK repository above. To support development, you can [sponsor Alex Zappa](https://github.com/sponsors/reatlat).

Both SDKs use the Apache-2.0 license. Made by [Alex Zappa](https://alex.zappa.dev/) ([FreshJuice](https://freshjuice.dev/)).
