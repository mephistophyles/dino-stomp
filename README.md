# Dino Stomp

A third-person T-rex romp in the browser. Single file, no build step.

## Play

Open `index.html` in a browser (or serve the folder with any static server).
Needs internet access on first load to fetch Three.js from cdnjs.

## Controls

| Key | Action |
| --- | --- |
| W / S | Walk forward / back |
| A / D | Turn |
| Space | Lunge forward and chomp |
| Q / Esc | Quit (shows final stats) |

## Rules

- 5 health bars. Game ends at 0 health or when you quit.
- Small dinos: crush by walking over them (1 pt) or eat them (5 pts, +1 health).
- Stegosaurus: cannot be crushed. Takes 3 bites to kill. Every bite (or loitering near it)
  triggers a tail swing that does 1 damage unless you get out of range or stand in front of it.
  Once dead, chomp the carcass for +3 health.
- Raptors: packs of 3 to 5 that hunt you and attack from your sides and rear.
  1 health each, 1 damage per hit. Stomp them or bite them. Eating them gives no health.
- Trees fall over when you walk into them. Footprints are left in grass and sand.

Tracked stats: trees crushed, small animals crushed, things eaten, kills by type,
damage dealt and damage taken.
