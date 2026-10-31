# Refract Browser

This repository contains the compiled static app bundle from
[qsnt/swiftthunder99](https://github.com/qsnt/swiftthunder99), pinned at commit
`8e1d14bb29c346b7e506183e857cfc4ce9b92915`. It is served from `index.html`.

The upstream repository contains a production bundle rather than editable
application source or build configuration. The browser UI is bundled with
other dashboard pages. The separate click-triggered popup script and embedded
Google Analytics code were not copied.

The browser's proxy transport is configured to connect to the same-origin
WebSocket path `/vu3hctgo/`. A static file server can serve the interface, but
browser requests require a compatible WebSocket backend at that path.