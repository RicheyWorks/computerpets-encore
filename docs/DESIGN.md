# Encore design

Implement against this file, not folklore.

## Identity

- Product: **Encore**
- Repo: `computerpets-encore`
- Idea: Pet Karaoke Jam
- Genre: Music pitch-match
- Engine: React / Web Audio
- Surface: `8080`

## Loop

Vox is the synth. Encore is the game: you match Rui's line. Scoring is pitch + timing, not 'are you a good singer forever'. Babel supplies lyrics.

## Play beats

- Pick a Lore lullaby or Cortex-safe line.
- Pet sings reference (Vox).
- You match. Score → treat.
- Twitch later: audience picks the song.

## Neighbors

- computerpets-vox
- computerpets-cadence
- computerpets-babel
- computerpets-cortex (optional ad-lib)

## Failure doctrine

Mic permission denied → practice with tap keys. Vox down → MIDI beep reference. Never upload raw mic without opt-in.

## Hard rules

1. Minigames cannot mint or burn NFTs by themselves (Minter is the write path).
2. Stats come from lived overlay care + Dojo caps, not cash shop.
3. Species kits stay inside Lore. Illegal hybrids never spawn.
4. Fail soft: the desktop overlay process is not this process.
