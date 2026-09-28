# g0kul6.github.io

Personal academic site for **Gokul Kannan** — single-page GitHub Pages site (`index.html` + `img/`).

## Structure

```
g0kul6.github.io/
├── index.html              # entire site (CSS + JS inline)
├── img/
│   ├── hero_robot.jpeg     # hero background
│   ├── profile1.jpeg       # about photo (hover alt)
│   ├── profile2.jpeg       # about photo (primary)
│   ├── favicon.png
│   └── hobbies/
│       ├── doodles/        # Chronicle Doodler images
│       ├── gym/            # Gymuhhh PR videos
│       └── photos/         # Instagram teaser thumbnails
├── LICENSE
└── README.md
```

## Local preview

Open `index.html` in a browser, or from this folder:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000`.

## Deploy

Push to the `main` branch of `g0kul6/g0kul6.github.io`. GitHub Pages serves the root automatically.

## Still to fill in

- **X (Twitter) URL** — replace `href="#"` on the X icon in `index.html` (hero + footers)
- **Hobbies media** — see [img/hobbies/README.md](img/hobbies/README.md)
