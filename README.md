# Shipcast's state

This branch is written by Shipcast's GitHub Action mode, never by hand: `registry.json` is the
launch registry (which releases were launched, their pieces and where they went), `lock.json`
says which run is using it. It holds no secret. See docs/decisions/action-mode.md in Shipcast.
