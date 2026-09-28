# Her Photos

Drop her photos into this folder to make every letter personal.

## Naming (required)

Name each photo to match the letter it appears on:

```
photos/photo-01.jpg   ← appears on Letter 01
photos/photo-02.jpg   ← appears on Letter 02
...
photos/photo-20.jpg   ← appears on Letter 20
```

- Use exactly two digits: `photo-01.jpg` … `photo-20.jpg`.
- `.jpg`, `.jpeg`, `.png` and `.webp` all work — if you use another extension,
  change the filename in `index.html` (search for `photo-`).
- Photos are lazy-loaded, so only the ones being viewed are fetched.
- Original aspect ratios are preserved everywhere except the small circular
  frames, which are gently cropped to a circle (no stretching).

## If you have fewer than 20 photos

The letters already share photos intelligently — letter 1 uses `photo-01`,
letter 2 uses `photo-04`, letter 3 uses `photo-07`, and so on (see the
`P2P` list in `index.html`). Just copy your favourite photo to several
filenames, e.g. the same picture as `photo-01.jpg`, `photo-04.jpg` and
`photo-07.jpg`. Each letter gives it a different treatment (Polaroid,
round frame, taped, clipped…), so repeats still feel handmade.

## Missing photos are fine

Until a photo file exists, that letter simply shows a slightly empty-handed
frame with a tiny handwritten "photo coming soon ♡" — nothing breaks.

## Tips

- Phone photos are usually fine as-is; something around 1200–2000 px wide
  keeps the site fast.
- Faces usually sit best near the centre since some frames crop slightly.
