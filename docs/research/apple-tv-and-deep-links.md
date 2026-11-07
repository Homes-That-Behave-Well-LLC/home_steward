# Apple TV and deep links

> RESEARCH INCOMPLETE. Public-source bootstrap reviewed 2026-11-07; no playback integration.

## Official technical sources

[Universal Links](https://developer.apple.com/documentation/xcode/allowing-apps-and-websites-to-link-to-your-content),
[NSUserActivity](https://developer.apple.com/documentation/foundation/nsuseractivity) and
[Deep Linking on tvOS, WWDC 2017](https://developer.apple.com/videos/play/wwdc2017/246/).

The first two are current platform-general documentation; the tvOS session is historical, not a
current per-app playback API specification. Do not infer universal tvOS support from broader Apple
platform behavior. Exact OS/app handling and link scheme must be researched.

## Claims / unknowns

Deep links/app-domain association and activity/Top Shelf handoff can route a supported app/content
request. They do not guarantee provider availability, licensing, account entitlement, exact episode,
resumption, autoplay, physical playback or availability on every installed app.

App/provider-specific links, native HA entity capabilities, household account privacy, confirmation,
observability and unavailable behavior remain open. No blanket Apple TV capability is asserted.

Home Steward may identify/propose content; HTBW governs the request and authorized handoff;
native device/media capabilities remain executors. A link or successful API request is not Truth
that playback began. No Apple TV command, service integration or link test performed.
