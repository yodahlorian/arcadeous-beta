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



### 0.11.42.1 — 2026-10-30

- **A red pad says why.** Moving or placing a machine on a red pad used to say only "something is in the way", even on
  open floor. It now says the reason: too close to a machine, keep the doorway clear, or customers could not reach a
  machine past it (the aisle in front of a row is where its players stand). (Thanks to the tester who sent this with /bug.)
- **Change machines move again.** The change machine's menu has MOVE THE CHANGE MACHINE, like every cabinet's. Before, the
  one you inherit could only be moved once, and a change machine you bought could never be moved. (Thanks to the tester who
  sent this with /bug.)
- **Android tells the truth about your own music.** The radio told Android players to drop mp3s in an iPhone folder. Android
  has no folder like that yet, so it now says the house stations play; the bug-report button points to /bug in our Discord.
  (Thanks to the tester who sent this with /bug.)

### 0.11.41.3 — 2026-10-30

- **Only Menu pauses.** On the floor, B no longer opens the pause menu — so swapping A with B in Settings › Controller can
  never put Pause on A. The pause menu is on Menu (OPTIONS / + on other pads), which no swap moves. B still cancels moving a
  machine and still closes menus. (Thanks to the tester who sent this with /bug.)
- **Racing cabinets stay solid up close.** Walking up to a cabinet with a steering wheel made its lower half vanish and
  flicker, showing the floor through it. The seat, wheel, pedals and plate now stay drawn at any distance. (Thanks to the
  tester who sent this with /bug.)

### 0.11.40.1 — 2026-10-30

- **Back no longer closes the game on Android.** The system Back swipe or button quit Arcadeous on the spot, mid-shift. It
  now works like the game's own back: it closes the open menu, or pauses on the floor.

### 0.11.39.1 — 2026-10-30

- **Swapping buttons tells you what moved.** Swapping two buttons in Settings › Controller moves BOTH jobs, so swapping A
  with B puts Back (and Pause) on A. The page now says exactly which button does what after a swap; Reset to default puts
  everything back. (Thanks to the tester who sent this with /bug.)
- **A remapped controller names the right buttons.** After you swapped buttons in Settings › Controller, a game's hints
  could still name the old button (and on a Nintendo-style pad, A and B could come out swapped). Every prompt now names the
  button you chose. (Thanks to the tester who sent this with /bug.)
- **Every on-screen button works where it's drawn.** Since full screen, a tap on ☰ (or BUILD, or any on-screen button) on
  a wide phone landed to the left of where you touched, so you had to tap to the right of the icon. Every tap lands
  exactly where you touch now.
- **The opening cards are centred.** The studio logo and the title card sat off to one side on a wide phone or an iPad,
  with the title and its tagline out of line. Both are centred and fill the screen now.
- **Cloud saves show your money right.** The cloud panel showed $72125 where it meant $721.25.

### 0.11.38.1 — 2026-10-30

- **Cloud saves: your arcade on every device.** Main menu › CLOUD SAVES: type your email, then the 6-digit code we send.
  No password, ever. Your saves follow you between PC, iPhone, iPad and Android, and a newer save is never overwritten
  without asking. We never store your email address, and deleting your account is immediate and permanent.
- **Full screen on phones and iPads.** No more black bars: the arcade fills the screen and the menus stay where your thumbs
  can reach them.
- **Cabinet games show the whole screen.** The game was shifted right in the cabinet view and its right edge was cut off
  (scores, the ends of hints). It's centred now.
- **Real racing cabinets.** Pole Run, Chase Car and Coast Run now stand in stand-up racing cabinets, the way their originals
  did: a wheel, a gear stick, pedals on a plate, and nine paint schemes. Customers pay at the coin door, step up and drive,
  both hands on the wheel, shifting now and then.
- **The parts shelf shows what's really on it.** When your technician took a part for a repair, the shelf kept showing it
  until you touched the stock yourself. It updates the moment anyone takes or puts back a part now. (Thanks to the tester who
  sent this with /bug.)

### 0.11.37.1 — 2026-10-30

- **Bluetooth controllers on your phone.** Pick up a pad and every prompt names its buttons instead of the touch controls,
  and the on-screen controls step aside; touch the screen and they come back.
- **Remap your controller.** Settings has a new Controller tab: press Change, then the button you want. The two buttons swap,
  so nothing can ever end up unreachable. Every prompt shows your new layout.

### 0.11.36.1 — 2026-10-29

- **Every game tells you the touch controls.** Some games, Sky Lance among them, still gave PC instructions on the phone ("Press
  SPACE …"). Every game's hints and messages now name the controls in your hand: the on-screen stick and buttons on the phone,
  the buttons on a controller. (Thanks to the tester who sent this with /bug.)
- **Your wall design is on every wall.** Some walls kept the old colour when you picked a new wall design: the street wall, the
  back room's walls, and the strip over its door. And a saved shop came back with the design on none of them until you changed
  it again. Every wall now takes the design, and a loaded shop shows it straight away. (Thanks to the tester who sent this with
  /bug.)

### 0.11.35.1 — 2026-10-29

- **A cabinet stuck in a wall is moved out.** Shops saved before 0.11.34 could still hold a used cabinet set into the back-room
  wall, where nobody could reach it. Load your game and it's moved to the nearest free spot on the floor, ready to use. Nothing
  else moves. (Thanks to the tester who sent this with /bug.)

### 0.11.34.1 — 2026-10-29

- **Used cabinets never land inside a wall.** Once the walls filled up, a used cabinet could be set down in the corner by the
  back room, half inside the wall, where nobody could reach it. Every used cabinet now goes to a spot with room for it and room
  to stand at it. If there's no such spot left, the ArcadeList won't sell it, and nothing is charged. (Thanks to the tester who
  sent this with /bug.)

### 0.11.33.1 — 2026-10-29

- **Your technician gets in through the front door.** Before you open for the day, the doors only swung for you, so a hired
  technician walked into a shut door, and if you came up behind them it swung into them. The doors now open for anyone
  walking through and stay open until they are clear. (Thanks to the tester who sent this with /bug.)

### 0.11.32.1 — 2026-10-29

- **The ticket machines are really here now.** 0.11.29 to 0.11.31 opened the redemption booth at level 10 but left every
  ticket machine saying "COMING SOON!" on the licence page. They now unlock from level 10 (Drop Zone) to 18 (Coin Pusher), at
  the new lower prices. (Thanks to the tester who sent this with /bug.)

### 0.11.31.1 — 2026-10-29

- **Ticket machines are priced to earn their keep.** They used to cost nearly three times a video cabinet and earn about the
  same, so one took about 55 days to pay for itself. Every ticket machine and The Claw now costs about half, and pays back in
  about a month. At default prices and payout a ticket machine earns what a video cabinet does.
- **A toy at the booth costs 150 tickets** (was 130), so the prizes your customers take home stay a fair share of what they spent.

### 0.11.30.1 — 2026-10-29

- **The redemption booth opens with the ticket machines, at level 10.** It used to open a level later, so the first tickets your
  customers won had nowhere to go.

### 0.11.29.1 — 2026-10-29

**The ticket tier opens.** From level 10 your arcade gets ticket machines, a redemption booth and the prize shelf.

- **Ticket machines, one a level from 10 to 18.** Drop Zone comes first at level 10, then Tumbler, High Rise, High Striker and
  The Claw, Gopher Bash, Buzzer Beater, Alley Roller and Coin Pusher. They're on the licence page now.
- **Tickets come off a roll.** Every ticket a customer wins is torn off that machine's roll. When the lamp on the ticket door
  turns amber, open the ticket door from the machine's menu and click to put a new roll on. An empty roll pays nobody, and
  customers notice.
- **Set each ticket machine's payout** from its menu. A stingy machine earns the same and puts people off.
- **The redemption booth (level 10, with the first ticket machine).** Customers who leave happy trade their tickets at the counter for a toy. Keep its
  shelves stocked from the counter's menu: an empty booth sends people home disappointed.
- **The prize shelf (level 15).** Pull a guaranteed new piece for your collection with tickets or cash, choose six for the
  display case, and see what your toys are doing for the shop. Every piece you own gives a bonus: cheaper rent and power,
  cheaper licences, more customers, fuller wallets, happier crowds, more celebrity visits and more used cabinets for sale.
- **The Claw is stocked with the collection's toys.** When you win one yourself, it joins your collection.
- **Your stockhand** now changes ticket rolls and restocks the booth and the claw.
- **Pinball, the puck table, the rhythm pad and every ticket machine can be repaired by hand.** Their board is behind the
  service panel, which now opens from the machine's menu. They no longer carry a picture tube they don't have.

### 0.11.28.6 — 2026-10-27

- **Your own music on the radio, on the phone.** The radio said to drop songs into an "Arcadeous" folder that an iPhone doesn't
  have. Put them in the Files app under On My iPhone › Arcadeous › music, and the radio says so. (Thanks to the tester who sent
  this with /bug.)

### 0.11.28.5 — 2026-10-27

- **Cabinets keep their art.** After you left a game or bought from the ArcadeList, every machine on the floor turned white:
  the shop rebuilt itself, and the new cabinets were copied from ones whose artwork had just been thrown away. Each rebuild now
  paints its own. (Thanks to the tester who sent this with /bug.)
- **Typing never hides behind the keyboard.** Some text boxes didn't move up when the phone's keyboard opened, so you typed
  into a box you couldn't see. Every one lifts above it now.

### 0.11.28.4 — 2026-10-27

- **The ArcadeList says when a licence is included.** A used cabinet for a game you haven't licensed yet costs the cabinet plus
  that game's licence, and the button showed that total with no word about the licence, so it looked like the wrong price.
  Each row now reads "+ $180.00 licence" and the button "buy + licence — $293.26". (Thanks to the tester who sent this with /bug.)

### 0.11.28.3 — 2026-10-27

- **A cabinet's cash box counts quarters.** Standing at a machine showed its takings in cents ("100 coins" for $1.00). It now
  reads "4 quarters ($1.00)", which is what you get when you empty it. (Thanks to the tester who sent this with /bug.)
- **▶ starts every game.** On the 3D machines (the ones with rounds) the ▶ button in the corner did nothing — only their main
  button started a round. It starts all of them now.
- **✕ BACK in the shop console goes back a page.** It used to throw you out of the console altogether.

### 0.11.28.2 — 2026-10-27

- **The whole shop speaks phone, not just the games.** Your task card, the out-of-quarters lesson, the pop-up notices and the
  celebration screen still said "click" and "Esc". They now say tap, USE, BACK and the other words on your buttons.
- **Swiping long menus works in a busy arcade.** With a full floor the game can slow down, and a quick swipe on a long list
  (like the build menu) was read as too slow, so the page didn't turn. A quick swipe turns the page however busy it gets.

### 0.11.28.1 — 2026-10-26

- **Every game speaks phone.** The cabinets' button legend, "PRESS ENTER TO PLAY" and How to Play named keyboard keys
  (SPACE, ENTER, arrows, the mouse). They now name the buttons on your screen — STICK, GO, DROP, ✕ and the rest — the same
  words the buttons wear. (Thanks to the tester who sent this with /bug.)

### 0.11.27.2 — 2026-10-26

- **CANCEL cancels.** Moving a cabinet and tapping CANCEL opened the pause menu and left the cabinet in your hands. Now it puts
  the cabinet back where it was and the game carries on. (Thanks to the tester who sent this with /bug.)

### 0.11.27.1 — 2026-10-26

- **Used cabinets get their own spot.** Every used machine was set down on the same spot, so a second one landed on top of
  the first and looked like it had replaced it. Each one now goes to the next free space on your floor, like a new machine.
  If there is no free space, the sale doesn't go through and nothing is charged.
- **Used cabinets can be moved.** MOVE THIS CABINET was greyed out on them ("part of the fittings"). It works now, including on
  one you already bought — so two that ended up on one spot can be pulled apart.
- The PC and iPhone builds share one version again: this is the game at 0.11.27.

### 0.11.26.13 — 2026-10-26

- **A change machine in a corner works again.** You could only use it from its side, so tucked into a corner with that side
  against a wall it couldn't be reached at all. Now you stand at its front, like every other machine.
- **The price list shows the new price straight away.** After you picked a price, the list still marked the old one as current.

### 0.11.26.12 — 2026-10-26

- **You can charge a real price for a game.** The price list stopped at 5 cents. It now runs from FREE up to $2.50 in
  quarters, and every machine's normal price is on it. A game you set to a few cents in an older build is moved up to the
  matching quarter price when you load.
- **Swiping a menu no longer picks the row under your finger.** A row is chosen when you tap it and let go. A swipe turns the
  page, one page per swipe, on long lists like the build menu.

### 0.11.26.11 — 2026-10-25

- **Quarters no longer run out.** Customers used to change their whole wallet into quarters at the door and walk out with whatever
  they didn't spend — about a third of your change machine's float, every day, until it ran dry by day four. Now they only take
  the quarters they actually play, so the store's quarters stay in the store.
- **Some customers bring their own quarters** and spend those first, so your float slowly grows instead of shrinking.

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
