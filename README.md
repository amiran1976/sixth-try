# Sixth Try

A Wordle-style word game where the twist is scoring, not speed. You have 6 guesses
at a 5-letter word, but you only score points if you eventually land the correct
word — and turns 5 and 6 carry Scrabble-style double/triple word multipliers.
The longer you can stall on real near-miss words, the more you can potentially
score, but if you never land the word, you score zero.

Live word validation and target words are drawn from the original Wordle word lists.
Max possible score is calculated per-word and shown at the top of each round.

## Run locally

Just open `index.html` in a browser. No build step, no dependencies.

## Deploy

This is a single static HTML file, so any static host works. For Vercel:

```bash
npm i -g vercel   # if you don't have it already
vercel             # from inside this folder, follow the prompts
vercel --prod      # promote to production once you're happy
```

Or connect this repo to Vercel via the dashboard (vercel.com/new) for
auto-deploys on every push to main.
