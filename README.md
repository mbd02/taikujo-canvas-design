# tAIkujo · Canvas Design Lab

**[Open the live playground](https://mbd02.github.io/taikujo-canvas-design/)**

A standalone design draft with dummy elements, a separate top-right comment
chat pill on every card, a mirrored top-left preview pill on files/stacks/Tunnels,
and a lower pill for the remaining actions. Task status is a circle only
(outline = open, filled = done). Creator/AI-change, focus and the generic menu
indicators, assets and handlers are removed. Corner controls stay separate at low zoom.
Use the right-side availability controls to simulate an unreachable Tunnel or
Desk target: translucent shape overlay and a centered dark red triangle.
These controls do not check real destinations.
Original app SVG outlines, including the task contour, rounded decision,
capsule event, flat Desk ribbon and square files. Proposed Tunnel shape: a true
semicircular arch over straight walls and a flat base; no fake depth yet. Files/covers are
capped at the base element width. Tunnels use half that width and the provider
icon; account and scope appear in a single draft hover. Double-click a Tunnel
or click its eye for inline Inspector content browsing and scope editing.
The Inspector is a dummy: no provider permissions or real scopes are changed.
Five material themes, light/dark mode, DE/EN, zoom, movable cards and editable
pill spacing/actions. Export/import JSON to share a design configuration.

Reload the same live link after a published change. The revision appears in the
footer. Each new revision starts from the published design; settings saved for
an older revision cannot obscure the updated defaults. Settings remain local
to the browser. Export before switching revisions if you want to keep them.

This repository contains only the dummy page, screenshot and publication metadata.
No real Desks, files, accounts, API/MCP requests or application backend.
Published by GitHub Pages from `main` / root; `.nojekyll` avoids Jekyll processing.

![Design playground](canvas-playground.png)
