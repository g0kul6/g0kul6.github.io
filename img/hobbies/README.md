# Hobbies assets

## Chronicle Doodler → `doodles/`

| Preview (site) | Full PDF (opens on click) |
|----------------|---------------------------|
| `biker-gang.jpg` | `Biker_Gang.pdf` |
| `buffdude.jpg` | `Buffdude.pdf` |
| `karuppu.jpg` | `Karuppu_.pdf` |

Previews are JPEG exports of the PDFs for fast loading. Clicking a card opens the PDF.

## Gymuhhh → `gym/`

| File | Notes |
|------|--------|
| `pr-01.mp4` | Muted, compressed web MP4 |
| `pr-02.mp4` | Muted, compressed web MP4 |

Do **not** commit raw `.MOV` / large phone dumps (GitHub 100MB limit). Convert with ffmpeg first:

```bash
ffmpeg -i input.MOV -an -vf "scale=720:-2" -c:v libx264 -crf 28 -movflags +faststart pr-XX.mp4
```

## Photography → Instagram

No local photos. The site embeds [@hozholens](https://www.instagram.com/hozholens/) via Instagram’s embed script.
