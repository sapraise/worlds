# World as workspace UI

## Application shell

Use white/light neutral surfaces, charcoal typography, generous spacing, selective colour, crisp icons, and compact controls. The top-down world is the largest area. The shell stays calm while the world carries expressive art. Avoid dashboard tiles surrounding a tiny decorative map.

Top bar: world name, source/last-sync status, world/list switch, invite or local-session control. A compact roster/room rail can collapse. Selecting a character, room, or object opens one inspector on the right. On narrow screens, use a full-width detail sheet and keep direct list access.

## Main interactions

| Element | Meaning and action |
|---|---|
| Human avatar | Presence and name; select to locate or inspect permitted shared context |
| Agent character | Stable connected identity; inspect status, current task, provenance, output and supported continuation |
| Proposed character | A visibly unconnected recommendation; never animate as a live worker |
| Workstation | Opens the relevant project/task context, not an unrelated generic dialog |
| Project board | Tasks, blockers, review queue and run history |
| Archive/library | Approved output references with source and date |
| Shared table/café | Meeting/presence space; voice/video is future scope unless implemented |
| Door/path | Navigation; no permission is granted by proximity |

Useful tasks must be accessible by direct click and a list. Do not force the user to walk across a map to answer a blocker. Keyboard movement is an optional delight; focus, typing, and form controls must not trigger movement.

## Onboarding

1. Choose a supported connection or a clearly labelled sample.
2. Select source scope and inspect discovered entities.
3. Review existing agents and separately proposed additions.
4. Choose purpose, solo/shared use, theme, and world size.
5. Edit area assignments and review a schematic plan with reasons.
6. Approve the exact revision and build.
7. Enter, inspect one real or explicitly sample workflow, and optionally join a second local client.

Show empty, loading, partial source, disconnected, stale, failed, needs-input, and large-roster states. Imported content is untrusted data. Keep the plan editable rather than disguising a fixed team behind a form.

## Spatial design

Gather references establish overview, neighbourhoods, presence labels, and recognisable stations. Translate those ideas into original art. Use near-top-down framing, clear ground planes, well-separated districts, short paths, and sparse status labels that do not cover characters. Scale detail to zoom level.

Users can keep actual source names while choosing display aliases, character appearance, and area names. A newsroom may become a press pavilion, a research area an observatory, or a creative team an atelier. These are editable suggestions based on discovered work, never required roles.

## Truthful status

Display task state and connection freshness separately. Labels distinguish human, connected agent, proposed agent, and ambient NPC. Sample state is labelled throughout. “Completed” and “accepted by a human” are separate. Do not animate an agent as actively working when its connection is stale.

## Local prototype

A local visual concept may switch between sample rosters and themes, inspect sample work, and step through plans. This is a UI study, not proof of live integration. Real multiplayer requires two clients and a running room server; two dots in one browser are not sufficient evidence.
