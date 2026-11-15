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
