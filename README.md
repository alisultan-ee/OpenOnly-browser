# OpenOnly Browser

**OpenOnly Browser is a browser for opening links, not browsing the web.**

It is designed for situations where you need access to web content without also having a general-purpose browser available for searching, discovering, or endlessly moving through content.

The goal is to keep the useful part of a browser: opening a page, using it, and following what is needed from there, while keeping the experience bounded to that purpose.

## Why OpenOnly Browser?

Conventional browsers are designed to make the entire web immediately accessible. That is useful, but it also means opening one page can easily turn into unrelated browsing, searching, feeds, or endless scrolling.

OpenOnly Browser takes a different approach: the browser is something you **open links with**, rather than somewhere you go to browse.

It is intended for people who still need normal web access when a link needs to be opened, but do not want a conventional browser to be a constant entry point to the wider web.

## Design goals

* Open web links normally.
* Keep websites functional once opened.
* Allow useful navigation from opened content.
* Avoid providing a general starting point for browsing the web.
* Keep prolonged or self-perpetuating browsing from defeating the purpose of the app.
* Stay lightweight and independent of website-specific modifications where possible.

## Project status

OpenOnly Browser is currently under active development.

The project is based on the open-source [EinkBro](https://github.com/plateaukao/einkbro) Android browser and uses Android System WebView for web rendering.

The current work focuses on establishing the core OpenOnly browsing model and the infrastructure required to enforce it reliably without unnecessarily interfering with normal web use.

## Building

Requirements include a compatible JDK and Android SDK.

```bash
./gradlew assembleDebug
```

Install a debug build on a connected Android device or emulator:

```bash
./gradlew installDebug
```

## Upstream and license

OpenOnly is derived from EinkBro and retains the applicable GPLv3 licensing requirements and upstream attribution.

See [`LICENSE`](LICENSE) and [`UPSTREAM.md`](UPSTREAM.md) for details.
