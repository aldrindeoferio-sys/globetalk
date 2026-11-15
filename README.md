# GlobeTalk — Global Translator

Web-first prototype (Build 0.2), with a planned Capacitor iPhone/TestFlight release.

## Features
- Text translation using the public MyMemory API (prototype only)
- Language selection, swap, copy, speech playback
- Browser-dependent speech input
- Two-person turn-taking conversation mode
- Local favorites and translation history

## Run
Open index.html in a browser or serve it with any static web server.
For local development: `python3 -m http.server 8080` then open http://localhost:8080

## Deploy
This repository includes a GitHub Pages workflow. In repository Settings → Pages,
set Source to **GitHub Actions**. The site will be published at
https://aldrindeoferio-sys.github.io/globetalk/

## iPhone roadmap
1. Validate web translation and accessibility.
2. Introduce a production backend (do not expose paid API keys in client code).
3. Add Capacitor and an iOS Xcode project.
4. Configure Apple Developer certificates, App Store Connect, and TestFlight.
5. Test on physical iPhones before release.

**Limitations:** Translation service rate limits and accuracy vary. No native iOS build,
Apple signing, or TestFlight upload is configured yet. Do not submit sensitive content.
