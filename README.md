# 72Speculum

The mirror (`speculum`) of [Annulus](https://github.com/KeychainofSolomon/Annulus): the Operator's instrument for looking into Hell without opening it (Annulus `docs/spec/operator.md` §9).

## What is here now

`index.html` is a **design sample**. Open it in a browser. It reads no real files: the records it shows are samples in the shape of `annulus.vas` (the Vessel) and `annulus.proscriptio` (the Index).

- **Scry:** the glass draws you into Hell, a black-and-white place you walk through. W A S D walk, mouse or arrow keys turn, Space leaps, E reads, Esc rises.
  Hell is not laid out beforehand. Each chamber is made when you step into the one before it, and a chamber may or may not be given a way down, so the next circle exists only where one was made. There is no break between circles.
  - **Heights:** floors rise and fall. Ways down are ramps; some drop two circles, some climb one. There are terraces, sunken courts, steps, mounds and tombs.
  - **Pitfalls:** fall into a chasm and you land in another chamber.
  - **The painted passage:** some walls bear a passage painted in perspective. Stand square in front of it, look straight down it, and it becomes a real one.
  - **Hidden ways:** some walls are false. A hairline crack is the tell; face it and press E.
  - **Set plans and parts:** the first chamber of each circle entered by a door or a hidden way has a set plan after Dante's buildings (the noble castle, Minos's seat, the mire, the round of the weights, Styx and its tower, the wall of Dis and its tombs, the broken cliff and the river of blood, the ditches and bridges of Malebolge with their well, the ice of Cocytus). Every other chamber is put together from parts and never the same way as the one before it.
  - **Roofs:** where a chamber has one it is drawn: a built ceiling, a cavern, or rafters. Doorways are low passages through the wall.
  - **Looking up and down:** move the mouse, or press R and F.
  - **Towers and shafts:** stairs wind up above the walls and down into deep shafts; narrow ways cross over drops.
  - **Ledges:** some doors open high over the next circle. You see it from above, step off, and cannot climb back.
  - **Size:** some doors make you larger or smaller, so a wall becomes a step or a step a wall. Some ways are only painted on the wall.
  - **Returning:** ways that lead back prefer the set chambers, so those become the places everything folds back to.
  - **The river:** one water comes down through all of Hell, as Dante has it (XIV), named anew as it goes: Acheron, Styx, Phlegethon, and Cocytus where it can fall no further. It only runs downward: in by the door you came by, out by the ways that descend, over ledges as falls. Its course winds as a sine-generated curve (Langbein and Leopold); width goes as the square root of the flow and depth as its 0.4 power (Leopold and Maddock), so it narrows where it forks. Follow the water and you go down.
  - **Styx and Phlegethon:** the marsh is a scatter of irregular pools; the river of blood bends like a bow and is deep at its ends and shallow at the ford, as in canto XII.
  - **Reading the water:** deep water is a grey body, shallows a darker one with the floor showing through, the shore a bright line, and a dashed line marks where it becomes deep enough to swim.
  - **Banks:** in caverns and open ground the water's edge is a free curve, and ponds have no regular shape; in built chambers it runs in a straight channel with a kerb. A chamber's outer walls rise out of sight, so nothing beyond them is ever seen. Paved floors are large uneven flags laid in rows; cavern floors are bare rock.
  - **Water:** drawn with its surface and its bed, the bed dimmer the deeper it lies. Running water streaks downstream; still water lies in ponds, flooded courts and the marsh of Styx. You wade the shallows and swim, slowly, where it is deep.
  - **Signs:** the walls carry none but the words over the Gate, the stars at the way out, and the numeral of the circle a door leads to.
  - **Stone:** wall patterns are worked out from each point's place and height, so courses run level through a whole chamber, joints break bond, and rock strata follow round corners.
  - **Doorways:** every door is one real arch across its whole width, standing open from the first. Past a door whose far side is not yet made there is only the dark; when it is made, the chamber beyond comes up out of the dark over a few seconds.
  - **The painted passage:** some walls bear a passage painted in perspective. Stand square in front of it, look straight down it, and it becomes a real one.
  - **Hidden ways:** what hides one is a slab of the wall, a case of books or a figure in a niche, which slides aside when you press E; or a wall that is not there at all, which wavers like water as you come near and lets you walk through.
  - **The Gate and the way out:** the Gate stands shut in a deep arch with Dante's words on its leaves; the way out is three open arches onto the stars.
  - **Falls:** where the river goes over a ledge it falls as a waterfall, with mist at its foot. On slopes the river keeps its banks and runs down them.
  - **Pits:** the floor of a pit shows the chamber you will fall into, seen from above, and after a fall the place comes up out of the dark.
  - **Each circle's look:** its own stone, its own kinds of chamber, and its own air: the storm wind of the lustful, the rain on the gluttons, the flakes of fire in the seventh circle, the wind off the ice. The second circle is dressed as a house of ill repute: booths behind hangings, lattice screens, couches, a bath, swags on the walls.
  - **After Escher:** in some chambers a stair climbs round a block and arrives back at its own first step, still climbing; in others a close passage turns you over as you walk it, and you come out with floor and roof changed places until you walk one back.
  - **After Escher's Relativity:** now and then a plain door opens on a tall hall whose one wall carries a drawing of stairs and blocks. Walk along the foot of that wall, keeping it on your right, and the hall turns about you until the wall is the floor: what was drawn is now solid underfoot, and the floor you left is a drawing on the wall at your left. Walk the foot of that wall and it turns back. The way on is in the second holding.
  - **Door frames:** every doorway stands in a frame that comes out into the room, a pier on either hand and an arch between, and the frame at each end of a way is the same frame in the same stone.
  - **The eye:** rides steps and ramps smoothly.
  - **Safeguards:** nothing but a doorway may open a chamber's outer wall; a door the chamber cannot reach is walled up again; the wall over an outer doorway rises out of sight; one arch is measured for a whole doorway so its two halves and its passage always meet.
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

## Storeys and figures (latest)

- **Rooms above rooms.** A cell can now hold two floors: an undercroft on the ground and a gallery over it, reached by a stair along its side. Bridges are thrown from terraces over the way beside them, so you walk under and over the same spot.
- **Figures built of blocks.** The shapes that stand for records are now small block models with flat grey facets and bright edges, drawn from eight sides so you can walk round them.
  - [S] Where a record names its spirit, the shape is that spirit's as the Goetia gives it (Sloane 3825): Marbas a great lion, Furfur a hart with a fiery tail.
  - [O] Voided work is a soul pushing a weight, an intruder's input a coiled serpent, history a standing stone, and the damned are sunk to the chest in ice.
  - These are effigies standing for a record. The spec's rule that the mirror shows record, never a spirit, is unchanged.

## Dressed walls and floors (latest)

- **Each circle dresses its stone its own way.** The same masonry carries a different surface in each circle, with a few kinds mixed along every wall so no stretch repeats: veined marble and the odd crack in Limbo's castle, runs of filth under the gluttons' rain, the marks the marsh leaves along the walls of Styx, baked and crazed patches by the burning sand, cracks and breaches made good in small brick in Malebolge, fracture lines in the ice.
- **Floors follow the stone.** Lozenge tiles in the second circle, riveted plates on iron, rutted mud for the gluttons and the marsh, crazed ground on the sand, fractured ice at the bottom.
- **Picture textures, in colour.** Walls, floors and ceilings now carry real textures: three or four wall pictures, a floor and a ceiling per kind of place, mixed along the walls. Hangings, lattice screens, door frames, the Gate, the caverns and the ice have their own. The white-line patterns remain only as the fallback while the pictures load, and for rafters and edges.
- **Water that moves, in colour.** Water scrolls with its current, bends in a sine wave, and is lit by a computed ripple, stepped and blocky. Acheron is dark blue-grey, Styx murky green, Phlegethon blood red, Cocytus pale ice-blue. [S] the rivers' natures are Dante's; [O] the exact colours are Annulus's own.

## Credit

The picture textures are from the Daggerfall Unity mod **"Daggerfall Dungeon Variety" by demifiend000**, which re-assigns Daggerfall's own dungeon textures (Bethesda Softworks) by kind of dungeon. They are embedded in `index.html`, brightened where very dark. They are not Annulus's work, and the UNLICENSE in this repo covers the code only, not these pictures.

The moving water follows the method and settings of the Daggerfall Unity mod **"Animated Water" by Excoriated** (scrolling, sine distortion, computed ripple, low frame rate, pixelation). That mod contains no pictures; the water here is computed.
