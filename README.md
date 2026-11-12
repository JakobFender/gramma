# Gramma

A small game for memorizing the Greek alphabet: match each letter's capital, small form and name.

Open `index.html` in a browser. There's no build step and nothing to install. Progress is saved in `localStorage`.

- **Triple match**: find the three tiles that belong together. Missed letters come back more often (spaced repetition).
- **Trouble letters**: puts look-alikes such as ν/υ, ζ/ξ and Σ/σ/ς, plus your own frequent mix-ups, in the same round.
- **Progress**: mastery for all 24 letters, your mix-ups, and a reset.

Letter data lives in the `LETTERS` array at the top of the script. To add a game mode, call `registerMode({...})`; the contract is documented above `MODES` in `index.html`.
