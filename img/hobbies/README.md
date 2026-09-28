# Hobbies assets

Drop files into the folders below using these **exact filenames**. The site auto-detects them — no HTML edit required.

## 1. Chronicle Doodler → `doodles/`

| File | Notes |
|------|--------|
| `doodles/01.jpg` | Square-ish crop looks best |
| `doodles/02.jpg` | |
| `doodles/03.jpg` | |
| `doodles/04.jpg` | |

Also accepts `.png` / `.jpeg` if you rename the `data-src` in `index.html`, or just use `.jpg`.

## 2. Gymuhhh → `gym/`

| File | Slot |
|------|------|
| `gym/weighted-dips.mp4` | Weighted Dips PR |
| `gym/pull-ups.mp4` | Pull-ups PR |

Keep videos reasonably small (GitHub soft limit ~50–100 MB per file; prefer compressed MP4 / H.264).

## 3. High Saturation Photography → `photos/`

| File | Grid position |
|------|----------------|
| `photos/01.jpg` | top-left |
| `photos/02.jpg` | top-middle |
| `photos/03.jpg` | top-right |
| `photos/04.jpg` | bottom-left |
| `photos/05.jpg` | bottom-middle |
| `photos/06.jpg` | bottom-right |

Square crops (~1:1) match the Instagram-style grid.

## After adding files

```bash
# from repo root
git add img/hobbies/
git commit -m "Add hobbies media"
git push
```

Until a file exists, the matching slot stays as a “coming soon” placeholder.
