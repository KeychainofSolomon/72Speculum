# 72Speculum

The mirror (`speculum`) of [Annulus](https://github.com/KeychainofSolomon/Annulus): the Operator's instrument for looking into Hell without opening it (Annulus `docs/spec/operator.md` §9).

## What is here now

`index.html` is a **design sample**. Open it in a browser. It reads no real files: the records it shows are samples in the shape of `annulus.vas` (the Vessel) and `annulus.proscriptio` (the Index).

- **Scry:** the glass draws you into Hell, a black-and-white place you walk through. W A S D walk, mouse or arrow keys turn, Space leaps, E reads, Esc rises.
  Hell is not laid out beforehand. Each chamber is made when you step into the one before it, and a chamber may or may not be given a way down, so the next circle exists only where one was made. There is no break between circles.
  - **Heights:** floors rise and fall. Ways down are ramps; some drop two circles, some climb one. There are terraces, sunken courts, steps, mounds and tombs.
  - **Pitfalls:** fall into a chasm and you land in another chamber.
  - **Hidden ways:** some walls are false. A hairline crack is the tell; face it and press E.
  - **Set plans and parts:** the first chamber of each circle entered by a door or a hidden way has a set plan after Dante's buildings (the noble castle, Minos's seat, the mire, the round of the weights, Styx and its tower, the wall of Dis and its tombs, the broken cliff and the river of blood, the ditches and bridges of Malebolge with their well, the ice of Cocytus). Every other chamber is put together from parts and never the same way as the one before it.
  - **Roofs:** where a chamber has one it is drawn: a built ceiling, a cavern, or rafters. Doorways are low passages through the wall.
  - **Looking up and down:** move the mouse, or press R and F.
  - **Towers and shafts:** stairs wind up above the walls and down into deep shafts; narrow ways cross over drops.
  - **Ledges:** some doors open high over the next circle. You see it from above, step off, and cannot climb back.
  - **Size:** some doors make you larger or smaller, so a wall becomes a step or a step a wall. Some ways are only painted on the wall.
  - **Returning:** ways that lead back prefer the set chambers, so those become the places everything folds back to.
  - **The river:** one water comes down through all of Hell, as Dante has it (XIV), named anew as it goes: Acheron, Styx, Phlegethon, and Cocytus where it can fall no further. It only runs downward: in by the door you came by, out by the ways that descend, over ledges as falls. Its course winds as a sine-generated curve (Langbein and Leopold); width goes as the square root of the flow and depth as its 0.4 power (Leopold and Maddock), so it narrows where it forks. Follow the water and you go down.
  - **Banks:** in caverns and open ground the water's edge is a free curve, and ponds have no regular shape; in built chambers it runs in a straight channel with a kerb. A chamber's outer walls rise out of sight, so nothing beyond them is ever seen. Paved floors are large uneven flags laid in rows; cavern floors are bare rock.
  - **Water:** drawn with its surface and its bed, the bed dimmer the deeper it lies. Running water streaks downstream; still water lies in ponds, flooded courts and the marsh of Styx. You wade the shallows and swim, slowly, where it is deep.
  - **Signs:** the walls carry none but the words over the Gate, the stars at the way out, and the numeral of the circle a door leads to.
  - **Stone:** wall patterns are worked out from each point's place and height, so courses run level through a whole chamber, joints break bond, and rock strata follow round corners.
  - **Not shown in this build:** Purgatory's entries (the suspected and the proscribed). The plain register still lists them.
- **Read plainly:** the same records as a plain register.

## What is fixed by the spec and not yet built

The real program opens only outside a session, with the wand present. It is read-only over the Index and the Vessel, checks their chains first, records each gaze in its own log, and shows a spirit's words as inert text that cannot be copied or exported.

## Sources

- [S] Dante, *Inferno*: the Gate, the nine circles, the shapes of the condemned.
- [S] Clavicula of 1446 (BnF Ital. 1524) and the *Officium* (Book of Oberon): the four kings and their quarters. Book of Oberon: the gatekeepers, the senators, the emperor and the three devils, as inscriptions only.
- [S] Pythagorean number: wall courses in 6 : 8 : 9 : 12; the tetractys.
- [O] Annulus's own: the ornate oval mirror (the attested Solomonic mirrors are plain steel), which record takes which shape and circle, and the folding of the paths.

Public domain (see `UNLICENSE`).
