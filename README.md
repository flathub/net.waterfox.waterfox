# net.waterfox.waterfox

Waterfox is a privacy-focused browser built for power users who value customization and control over their online experience.

## Privacy & safety defaults

- Waterfox routes DNS-over-HTTPS through a Fastly-hosted Oblivious HTTP relay, disables DNS prefetching, and blocks 0.0.0.0 lookups so your DNS traffic stays private.
- Cookie-banner automation rejects consent prompts whenever possible, HTTPS-First is enforced, Global Privacy Control is declared, and Google Safe Browsing pings stay off.
- Telemetry, Normandy experiments, analytics, and new tab ad feeds are stripped out - what runs on your machine is the code you installed.

## Private workflows

- Convert any tab into a Private Tab with isolated history, cookies, and default search, then close it to wipe the session in one move.
- Tab context shortcuts let you copy single or full tab lists, unload background tabs, or restart the browser with cache-purge options.
- Everyday ergonomics stay privacy-first: downloads ask before opening new types, scripted pop-ups are forced into tabs, and the classic status bar with link previews is back.

## Customization & layout

- Layout controls move the tab bar, bookmark bar, restart switches, and status bar without touching userChrome.css.
- Switch between Waterfox, Lepton, and Proton presets, then tune icon weight, padding, autohide behaviour, and rounding from the UI.
- Legacy userChrome/userContent loading remains enabled for deep themes when you want to go beyond the built-in presets.

## Modern platform

- WebGPU (including Workers), WebCodecs H.265, Web Share, and other emerging APIs are enabled by default so projects don't need nightly builds.
- JPEG XL, CSS Masonry, scroll-driven animations, and other experimental layout features are ready to test without hidden flags.
- Startpage and Waterfox Private Search ship as defaults, and you can assign a separate private-window engine.

![Welcome to Waterfox!](/images/welcome.png)
![New Tab](/images/newtab_vertical.png)
![Tree Tabs](/images/treetabs.png)
