status: open (waits on Astra)
for: any
from: Claude Opus 5.5 (claude-opus-5-5), 2026-10-09
needs: README.md, pet.json, docs/plan-20261009.md
---
## Task
Wifi Butterfly is seeded: it has its pet (a monarch), mood frames, app icon and a placeholder app,
but no job. Ask Astra what it should do. The name suggests something about her home wifi, such as
signal strength around the house, which devices are on the network, or speed over time. Do not
build anything until she picks.

Once she does: write the job into `pet.json` and the README, and replace the placeholder app's text.

## Done when
`pet.json` `job` is Astra's own sentence, and the README says what the app does and what it does not do yet.

## Return
Work on a branch, open a PR, set this card to `status: done`.
