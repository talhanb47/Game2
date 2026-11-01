# Feelings Game — Your Own Pictures & Audio

A complete, offline-friendly classroom game adapted from your original Feelings Game. You do not need to edit code. Simply add your pictures and recordings with the right filenames.

## How to use

1. Unzip the project folder.
2. Open the `images` folder. Copy your picture files there and rename them after each emotion.
3. Open the `audio` folder. Copy your recorded audio clips there, using the same names.
4. Double-click `index.html` to open the game in Chrome, Edge or another modern browser.
5. Select **My Media Setup** to see which files were found, then use **Learn Feelings** or **Play Game**.

You can add media later; refresh the browser after copying new files.

## File names

| Feeling | Example picture | Example recording |
|---|---|---|
| Happy | `images/Happy.png` | `audio/Happy.mp3` |
| Sad | `images/Sad.png` | `audio/Sad.mp3` |
| Angry | `images/Angry.png` | `audio/Angry.mp3` |
| Scared | `images/Scared.png` | `audio/Scared.mp3` |
| Excited | `images/Excited.png` | `audio/Excited.mp3` |
| Surprised | `images/Surprised.png` | `audio/Surprised.mp3` |
| Shy | `images/Shy.png` | `audio/Shy.mp3` |
| Tired | `images/Tired.png` | `audio/Tired.mp3` |
| Shocked | `images/Shocked.png` | `audio/Shocked.mp3` |

**Important:** Your list included *Scared* twice. The game intentionally has 10 rounds and repeats Scared, but only **one** `Scared` picture and `Scared` audio file are needed. There are 9 different emotions.

The game automatically detects image files ending in `.png`, `.jpg`, `.jpeg`, `.webp`, `.gif`, `.svg`, or audio files ending in `.mp3`, `.wav`, `.m4a`, `.ogg`, `.webm`.

For example, `images/Happy.jpg` and `audio/Happy.wav` work too. Keep capital letters as shown (e.g., `Happy`, not `happy`), especially if hosting on a case-sensitive website.

## What the game does

- **Play Game:** 10 rounds, 4 picture choices per round, one star for each right answer, retry on a wrong answer, optional hidden answer labels, and score screen.
- **Learn Feelings:** Nine clickable feeling cards that play your recordings.
- **My Media Setup:** Displays the file names and whether an image or audio clip was detected.
- **Sound button:** Mutes or unmutes playback.
- **Audio fallback:** If your clip is missing or can't be played, the game attempts to read the English feeling using the browser's built-in voice (if available).
- **Image fallback:** If your picture is missing, an emoji displays instead. The game will still work.
- **Optional feedback clips:** `audio/Correct.mp3` and `audio/TryAgain.mp3` will replace the built-in correct/wrong sound effects. These two files are optional.

## Recommended media

- Pictures: clear square pictures, ideally 600 × 600 px or larger, PNG or JPG.
- Recordings: clear voice saying the English word, e.g. “Happy”, in MP3 or WAV format.
- Avoid placing a different expression under the wrong filename.
- No internet or special software is required when using local media (browser voices may vary by device).

## Folder layout

```text
Feelings_Game_Custom_Media/
├── index.html
├── README.md
├── images/
│   ├── Happy.png      ← you add this
│   ├── Sad.png        ← you add this
│   └── ...
└── audio/
    ├── Happy.mp3     ← you add this
    ├── Sad.mp3       ← you add this
    └── ...
```

**No images or recordings are included yet:** this allows you to use your own pictures and voice clips. You do not need to rename the project folder or change any file paths.
