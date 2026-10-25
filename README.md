# Arcadeous — iPhone beta

**Own an arcade. Play every machine.**

[![This beta](https://img.shields.io/github/downloads/yodahlorian/arcadeous-beta/latest/total?label=this%20beta&color=38c8ff)](../../releases/latest)
[![Earlier betas](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Fyodahlorian%2Farcadeous-beta%2Fmain%2Fdownloads.json&query=%24.retired&label=earlier%20betas&color=6a7f99)](downloads.json)

Downloads count AltStore / SideStore installs and direct downloads together.

Run your own arcade: build the floor, buy cabinets, keep them working, empty the coin boxes — and play every machine yourself,
from the fighter dojo to the claw. Beta by **Devious Developments**.

**Play on PC:** [github.com/yodahlorian/arcadeous](https://github.com/yodahlorian/arcadeous/releases/latest)

## Install with AltStore (updates itself)

1. In **AltStore** → **Sources** → **+**, add this source:
   `https://raw.githubusercontent.com/yodahlorian/deviousdevelopments/main/source.json`
2. Open **Devious Developments** → **Arcadeous** → **Free / Get**. New betas show up as updates.

## Or SideStore (refreshes anywhere, no computer after setup)

Add the same source in **[SideStore](https://sidestore.io)** → Sources → +. It works exactly like AltStore.

## Or Sideloadly (Windows / macOS)

1. Install **[Sideloadly](https://sideloadly.io)** on your computer (Windows also needs iTunes from apple.com, not the Microsoft Store).
2. Download the newest `Arcadeous-<version>.ipa` from **[Releases → Latest](../../releases/latest)**.
3. Plug your iPhone in with a cable, unlock it and tap **Trust** if it asks.
4. Open Sideloadly, drag the `.ipa` onto it, enter your Apple ID and press **Start**.
5. On the phone: **Settings → General → VPN & Device Management** → tap your Apple ID → **Trust**.
6. iOS 16 and newer: **Settings → Privacy & Security → Developer Mode** → on (the phone restarts).
7. Open Arcadeous and play in landscape. To update, repeat steps 2–4 with the new `.ipa`.

A free Apple ID signs apps for 7 days; re-sideload to refresh. Each new beta replaces the file (one release, one file).

## Touch controls

Left thumb moves (or steers the joystick in a cabinet), drag on the right to look, tap on the right to use. The on-screen
buttons are the cabinet's own buttons. Menus are plain taps; ✕ BACK is bottom-right.

## Changelog



### 0.11.26.10 — 2026-10-25

- **The pause menu stays open.** Tapping ☰ opened it and closed it again straight away — the menu read your finger, still
  on the button, as a second press. A button you are holding when the screen changes now counts only once you let go.

### 0.11.26.9 — 2026-10-24

- **Delivery boxes pick up in one click.** One tap used to pick the box up and put it straight back down, so it crept a little each time.

### 0.11.26.8 — 2026-10-24

- **When the change machine runs dry, the day pauses for a lesson:** customers and the clock stop, you empty a coin box and refill
  the changer (open → click → shut, both), and the day carries on — with a card on how the coin loop works. Once, the first time.
- **Change machines from day one:** the licence is included — it is first in the build menu before you own any game, and the
  licences page shows it. $250 each, charged when you place it (it was charging $2.50), refunded if you cancel.
- **The prize shelf is unreleased again:** it is no longer sold (new or used), and as furniture it has no parts that can break.
- **The bill stacker fills up:** it holds 150% of a full hopper's value ($750). A full stacker takes no more notes — empty the
  bill mech to bank them.

### 0.11.26.7 — 2026-10-24

- **Every door works the same way: open it → click to do the job → click to shut it.** Cabinet coin doors, monitors and the
  change machine. The menu only opens the door; emptying the coins, pulling a dead part and fitting a new one are clicks on
  the open machine, one job per click. The tutorial cards say it the same way.
- **Cash boxes hold $625** — more than a full change machine can hand out, so the changer runs dry (and is refilled from the boxes) before a box can fill and stop its machine. A busy first day no longer stops the whole floor.
- **A cash box pays out the right number of quarters** — $1.00 in the box is 4 quarters in your pocket (it was paying 100).
- "Diagnose a fault" no longer claims a machine is dead before one is: it tells you to open for the day and find it.

### 0.11.26.6 — 2026-10-24

- **New icon:** a neon quarter with the Arcadeous A stamped in it.
- **The pause menu pauses the game**, says PAUSED, and sits centred under it; ✕ BACK closes it.
- **Report a bug** no longer pushes the menu off the bottom of the screen — its message shows below the menu.
- The build menu can no longer be shut by a stray back press while it is still opening.
- **Settings → Display & Touch scrolls** — every setting can be reached.
- The money / day / time bar is centred on its text, and it no longer follows you back to the main menu.
- No Quit button on the phone's main menu (iOS apps leave with the home gesture — the button did nothing).

### 0.11.26.5 — 2026-10-23

- **Coin collection works on the phone.** A quick tap on the right is USE even when the frame rate dips in a full arcade — it
  used to read as a look, so the coin door never opened.
- **Menus:** the tap after a menu pick is no longer swallowed (it was eating the coin door and the change drawer on every second visit).
- **Back room rearranged:** the four supply shelves, then the workbench, in one line on the side wall; the bin across the aisle;
  the ordering computer on the back wall. Every shelf can be reached now.
- **Whatever you stand nearest is what a tap uses** — computer, bench, bin or shelf. No more pinpointing.

### 0.11.26.4 — 2026-10-23

- SideStore now sees every phone build as an update (the version carries the build number).

### 0.11.26.3 — 2026-10-23

- **The Claw and the Coin Pusher:** an on-screen stick and a DROP button; their prompts speak touch ("tap DROP").
- **Money shows once**, in the top bar — a faint second copy behind it is gone (on PC too). Ticket and prize counts sit under the bar.
- Every bespoke machine has touch labels (stick, d-pad, its own button words); the prize shelf has PULL and BENCH SLOT.
- Placing a machine: PLACE · TURN · ◀ ▶ colour · ✕, with icons; no colour change while moving one.
- Settings → **Display & Touch:** button size, transparency, left-handed layout, look sensitivity.
- HUD centred on the phone; ✕ BACK on every menu, bottom-right; the build menu no longer flashes shut.
- "BUILDING YOUR ARCADE…" while the world loads; the pause menu shows money properly; bug reports save to the Files app.

### 0.11.26.1 – 0.11.26.2 — 2026-10-23

- **First iPhone builds.** An on-screen controller: left thumb moves (rim = sprint), drag right to look, tap right to use,
  BUILD, DUCK, ☰. Cabinets get their own buttons; menus are plain taps, swipe to scroll.
- Text fields lift above the keyboard; the arcade letter grid types on a tap.
