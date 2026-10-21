# portfolio engineering guidance

<!-- ecc-engineering-defaults:start -->
## Engineering defaults
For coding work, read [.engineering/defaults.md](.engineering/defaults.md).
These are shared fallback conventions; the existing project owner, nested instructions,
skills, model choices, domain contracts and stronger verification/release gates remain authoritative.
No hooks, permissions, MCP services or background automation are installed by this guidance.

### Project adaptation
Static portfolio plus Socket.IO Node server. Preserve package-lock.json; package scripts start persistent servers and no automated suite is declared. Review HTML/CSS and test changed interaction at small/wide viewports; use offline/local fixtures and stop any scoped preview when done. Do not edit tracked node_modules.
<!-- ecc-engineering-defaults:end -->
