# Strings and Things 🧶

View the live game here: [Strings and Things](https://gorbnw.github.io/headsup/home.html)

---

## About the Game

Strings and Things is a fun, twisted guessing game:  
- One player sees the clue and tries to **describe it to others without saying the actual answer**.  
- The other players try to guess what it is.  
- Clues can be a single word, a phrase, or even a full sentence — the more creative, the better!  
- Play is fast-paced and meant for laughs.

---

## How to Add a New List of Clues

1. Create a new `.txt` file with your clues.  
   - Each clue should be on its own line.  
   - For example:

```
flying spaghetti monster
the last slice of pizza
your secret talent
```

2. Place the `.txt` file in the `lists/` folder.

3. Open the `index.json` file (in the same folder as `home.html`) and add the filename to the array.  
   - Example `index.json`:

```json
[
  "fruits.txt",
  "90s.txt",
  "party_clues.txt"
]
```

4. Save the files and reload the game. The new list will automatically appear in the dropdown.

---

## Notes

- Make sure there are **no trailing commas** in `index.json`.  
- Audio files (`start.wav`, `countdown.wav`, `end.wav`) must be in the same folder as `home.html` (or adjust paths in the HTML if stored elsewhere).  
- Have fun! Be creative with your clues and descriptions — the more twisted, the better.
