# Mystic-GI v0.3.14 — Genshin Impact 7.0

Mystic is a single-player game enhancer focused on reducing repetitive
exploration, combat and dialogue tasks.

Unlike tools that depend entirely on manually maintained address lists, Mystic
derives the information it needs from the game's runtime metadata. This makes
updating for new game versions faster and reduces the chance of silently using
outdated addresses.

Mystic is designed for solo play. It does not provide features intended for
competitive or cooperative advantages.

## Installation

1. Download the latest installer from the GitHub Releases page.
2. Run `Mystic Launcher_0.3.8_x64-setup.exe`.
3. Open Mystic Launcher and configure the game path if it is not detected
   automatically.
4. Start the game through the launcher.

Mystic currently supports 64-bit Windows.

## Access

The free version uses an ad-supported daily pass. Premium access removes the
daily ad requirement and enables kernel-mode injection.

### Sponsor features

- No daily advertisement
- Kernel-mode injection
- More robust against anti cheat

### Free features

#### Player

- God mode
- No fall damage
- NoClip
  - Adjustable movement speed
  - Option to suppress the movement animation

#### Combat

- No skill cooldown
- Infinite burst energy
- Multiple hits, with a configurable number of hits per attack
- Kill aura, with configurable damage and range

#### World

- Auto loot, with adjustable delay and range
- Extended pickup reach, allowing distant items to enter the interaction list
- Loot vacuum, which draws nearby loot towards the player
- Pickup filters for:
  - Drops
  - Harvestables
  - Wildlife
  - Chests
  - Waypoints
  - Statues
- Automatic dialogue advancement
- Optional automatic dialogue-choice selection
- Option to leave important dialogue choices to the player
- Cutscene skipping and fast-forward controls
- Adjustable dialogue speed and advancement delay

#### Teleport

- Teleport to the currently tracked quest marker
- Teleport to a marker placed on the in-game map
- Travel to a point selected on the map
- Adjustable arrival height
- Optional server-synchronized travel path

#### Map

- Interactive markers displayed in the world and on the game's map
- Configurable marker names, distances, icon size and opacity
- Configurable maximum drawing distance
- Marker data downloaded and cached by the launcher

#### ESP

- Entity boxes with a configurable maximum drawing distance
- Tracers drawn from the bottom or centre of the screen
- Distance labels
- Box dimensions derived from renderer bounds
- In-world entity-type picker

#### Visuals

- Field-of-view control
- FPS unlock with a configurable limit
- Fog removal
- Forced nearby chest indicators

#### Interface

- External overlay that remains usable while the game has focus
- Optional in-game control panel
- Rebindable keyboard and mouse hotkeys
- Automatic interface hiding while the game is still loading
- Settings shared between Standard and Kernel injection modes

## Security and updates

Mystic v0.3.8 introduces several launcher and update-security improvements:

- The launcher downloads a mod built specifically for its current version.
- Downloaded mod files are verified against a fresh, cryptographically signed
  hash before being loaded.
- Damaged, replaced or outdated files are downloaded again automatically.
- Protected downloads use a device identity in addition to the machine ID.
- Premium sessions periodically renew a signed access lease.
- Revoked premium access stops working during an active session.
- Free daily-pass sessions are allowed to finish normally after midnight. A new
  pass is required the next time the game starts.

Premium users upgrading from v0.3.7 must enter their existing premium key once
more. This enrolls the new device identity and does not consume or reset the
key.

## Current compatibility

Mystic v0.3.8 targets Genshin Impact 7.0.

The features listed above are implemented for the supported game version.
Updates to the game may temporarily disable individual features until Mystic
has been updated and compatibility has been verified.

Features that are not listed should be considered unavailable rather than
partially implemented.

## Important notice

Mystic is an independent project and is not affiliated with, authorized by or
endorsed by HoYoverse or Cognosphere.

Using third-party software with the game may violate its terms of service and
may result in account restrictions or permanent account loss. No configuration,
feature or injection mode can be guaranteed safe or undetectable.

Use Mystic entirely at your own risk, preferably only with an account you are
prepared to lose.

## Support

If you encounter a reproducible problem:

1. Confirm that you are using the latest Mystic release.
2. Confirm that the installed game version is supported.
3. Check existing GitHub issues for the same problem.
4. Open a new issue with the launcher version, game version and steps needed to
   reproduce the problem.

Do not include premium keys, device files, account credentials or other private
information in issue reports.
