# stasis-bot

This azalea-bot can automatically detect thrown pearls and later walk there and pull them for you.

The bot speaks the Minecraft 1.21.11 protocol directly, so ViaProxy is not required for servers on that version. Pass the server address as the first argument. For offline-mode servers, use `--offline-username NAME`; otherwise the bot authenticates with the Microsoft account stored in its auth cache.

## Demonstration

https://github.com/EnderKill98/stasis-bot/assets/117233381/fdf172e7-99f9-4a14-87d1-84ad3dddf496

## Running this bot

 - Install the supported Rust toolchain: `rustup toolchain install nightly-2026-02-04`
 - Build the bot: `cargo +nightly-2026-02-04 build --release`
 - Run it with the server address, for example: `cargo +nightly-2026-02-04 run --release -- play.example.net`
