# Mystic-GI v0.3.7 now supports Genshin Impact 7.0

Mystic is a single-player game enhancer for a certain anime game, built around
its own metadata dumper rather than a borrowed offset list.

Most enhancers for this game are a list of addresses copied from someone else's
dump. That list rots the moment the game updates, and when it does there is no
way to tell a stale address from a working one until something misbehaves in a
way that is hard to trace. Mystic takes the other route: it reads the game's own
protected metadata, recovers what every class, method and field actually is, and
generates the addresses it uses from that. Updating for a new game build is a
capture and one command, not an afternoon of re-hunting.

The enhancer half is deliberately narrow. It is aimed at solo play — cutting the
repetition out of exploration and dialogue — not at anything involving other
players.

## Premium Features

- No ads
- Kernel mode injection
- Many more coming soon

## Free Features

### Player

- God mode
- No fall damage
- NoClip, with a speed control and an option to suppress the movement animation

### Combat

- No skill cooldown
- Infinite burst energy
- Multi hit, with a configurable number of hits per attack
- Kill aura, with damage and range controls

### World

- Auto loot, with an adjustable delay and range
- Extended pickup reach, so distant items enter the interaction list
- Vacuum, which draws nearby loot towards you
- Pickup filters for drops, harvestables, wildlife, chests, waypoints and
  statues
- Auto dialogue, with automatic option selection
- Skip and fast-forward for cutscenes, with an adjustable dialogue speed and
  advance delay

### Teleport

- Teleport to the tracked quest marker
- Teleport to a marker placed on the map
- Travel to a point clicked on the map, with an arrival height control and an
  optional server-side travel path

### Map

- Interactive map markers drawn in the world and on the game's own map
- Names, distances, icon size, opacity and a maximum draw distance
- Marker data is fetched and cached by the launcher

### ESP

- Entity boxes with a maximum draw distance
- Tracers, drawn from either the bottom of the screen or its centre
- Distance labels
- Real box sizes taken from the renderer's bounds
- An in-world picker for choosing which kinds of entity to show

### Visuals

- Field of view control
- FPS unlock with a configurable limit
- No fog
- Chest indicator, forced to show around the player

### Interface

- An external overlay for every setting, usable while the game has focus
- An optional in-game panel
- Rebindable hotkeys, including mouse buttons, for the features worth toggling
  mid-fight
- Both interfaces stay hidden until the game has finished loading and a
  character has spawned

## Status

Mystic targets the 7.0 version of the game. The feature list above is what is
implemented and working; anything not listed is not implemented yet rather than
partially done.

## Legal

Mystic is provided for research and single-player use. It is not affiliated with
or endorsed by the game's developer or publisher. Using it may violate the
game's terms of service; that risk is yours to weigh.

Keep feature values within a plausible range. Settings far outside what the game
itself would produce are the fastest way to get an account banned. This project
is new and its detection rate has not been tested, so treat any account you use
it on as one you are prepared to lose.

For anything else, open an issue.
