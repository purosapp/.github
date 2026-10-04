# Puros

Puros is a small team building a music player for people who care about sound, focus, and owning their library.

We are starting simple: a macOS player that brings together local playback, streaming, and a cleaner listening experience without the usual clutter. CoreAudio exclusive mode, per-device audio setup, high-quality resampling, EQ and VST effects, and format badges that show exactly what is playing.

**[⬇ Download Puros (alpha)](https://github.com/purosapp/purosapp/releases)** · [Website](https://getpuros.app) · [Discord](https://discord.gg/AauwQm2fKe)

## Public repositories

Puros is not a fully open source project. The main app is closed source; the parts others build on are public here.

| Repository | What it is |
| --- | --- |
| [purosapp](https://github.com/purosapp/purosapp) | About Puros, and compiled releases to download |
| [puros-provider-sdk](https://github.com/purosapp/puros-provider-sdk) | Provider API, packer and build tools for streaming integrations ([npm](https://www.npmjs.com/package/puros-provider-sdk), MIT) |
| [providers-list](https://github.com/purosapp/providers-list) | Every known provider, with download links |

## Streaming integrations

Streaming services connect to Puros through **providers**, separate packages you install from **Settings → Accounts → Install provider…**. Puros keeps your library, queue, decoding, DSP and output; a provider handles sign-in, the service's catalog and preparing audio files.

Community providers for SoundCloud, Spotify, TIDAL and YouTube Music are listed in [providers-list](https://github.com/purosapp/providers-list). They are unofficial, third-party software: Puros does not develop, review or support them and is not responsible for them. Want to build one? Start with the [Provider SDK](https://github.com/purosapp/puros-provider-sdk).

## What We Are Building

- A music player with a strong local library foundation
- High-quality playback for macOS
- Thoughtful streaming integrations, open to anyone through the provider SDK
- A product shaped carefully, one solid release at a time

## Follow Along

This organization is where we share the public side of Puros: the SDK, the provider list and releases, and more open components as the project grows. Come talk to us on [Discord](https://discord.gg/AauwQm2fKe).
