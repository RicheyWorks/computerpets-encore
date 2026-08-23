# Encore

**Pet Karaoke Jam** — Pitch-matching karaoke that sings along with Vox pet voices.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

Vox is the synth. Encore is the game: you match Rui's line. Scoring is pitch + timing, not 'are you a good singer forever'. Babel supplies lyrics.

## Genre & engine

- Genre: **Music pitch-match**
- Engine: **React / Web Audio**
- Stack: TypeScript · React 19 · Web Audio API · Vox reference stems · pitch detector
- Default surface: `8080`

## How you play

1. Pick a Lore lullaby or Cortex-safe line.
2. Pet sings reference (Vox).
3. You match. Score → treat.
4. Twitch later: audience picks the song.

## Talks to

- computerpets-vox
- computerpets-cadence
- computerpets-babel
- computerpets-cortex (optional ad-lib)

## Failure doctrine

Mic permission denied → practice with tap keys. Vox down → MIDI beep reference. Never upload raw mic without opt-in.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Encore must leave Rui walking.

## Layout

```
computerpets-encore/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
cd app; npm install; npm run dev
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
