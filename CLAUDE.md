# CLAUDE.md

Notes for working on this repo with Claude.

## What this is

A landing page for Mike's three Logitech M185 mouse conversions (repo wottle/vintage-apple-mice-logitech-m185,
local folder `~/Documents/3d Prints/Models/vintage-apple-mice-logitech-m185`). No models or scripts live here: each
mouse is its own repo, and this one only shows them together and links to them.

| Mouse | Repo | Local folder (Mike's Mac, `~/Documents/3d Prints/Models/`) |
|-------|------|------|
| Lisa | wottle/lisa-mouse-logitech-m185 | `LisaMouseLogitechM185` |
| Macintosh M0100 | wottle/mac-mouse-logitech-m185 | `AppleMouseLogitechM185` |
| ADB G5431 | wottle/adb-mouse-logitech-m185 | `ADBMouseLogitechM185` |

Facts on this page (status, parts, screws, credits) come from those repos' READMEs. When one of them
changes, check the comparison table here.

## Photos

`images/<mouse>_<fdm|resin>.jpg`, with `<mouse>` one of `lisa`, `mac`, `adb`. Extra views add a suffix
(`lisa_fdm_apple_logo.jpg`). Resize to at most 1400 px on the long side, JPEG quality about 85, with
EXIF rotation applied. To add a photo, put it in `images/` and replace that cell's *Photo to come*
in the README's variants table with an `<img ... width="300">` like its neighbours.

Missing photos as of 2026-11-20: Lisa resin, Macintosh resin, ADB resin, ADB FDM (a render stands in:
`adb_render.jpg`, from the ADB repo's `images/preview.png`). The Lisa and Macintosh FDM photos are older PLA
prints with the original sloping sides (the note under the table says so); replace them with prints of the
flat-sided FDM shells when there are some, and drop the note.

Keep the Apple logo out of ADB pictures: its upper shell has the logo moulded in, from the source
model, and the ADB repo's renders hide it.

## Working conventions

- **Mike runs git himself.** Leave changes uncommitted; give him the commands.
- Don't draw Apple logos.
