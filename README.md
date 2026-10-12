# 💣 Word Bomb

A fast-paced browser word game. Each round shows a 2–3 letter combo. Type a word that contains it before the fuse burns out.

## How to play

1. Open `index.html` in any modern browser. There's nothing to install or build.
2. Wait for the dictionary to load, then press **Start**.
3. Type a word containing the shown letters and press **Enter**.

## Rules

- Words must be at least 3 letters, in the dictionary, and not already used this game.
- If the fuse runs out you lose a life ❤️. You start with 3.
- The fuse gets shorter each round, and the letter combos get harder.
- **Scoring:** 1 point per letter, plus a 5-point bonus for words of 8+ letters.
- **Alphabet bonus:** use every letter A–Z across your words to earn an extra life (up to 3).
- Your best score is saved in your browser.

## Dictionary

The game loads [`word-list`](https://www.npmjs.com/package/word-list) (about 274,000 English words) from the jsDelivr CDN. If you're offline, it falls back to a small built-in word list.
