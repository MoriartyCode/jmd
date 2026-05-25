# JMD Travel — Image Assets

## Folder structure

```
your-repo/
├── index.html
└── images/
    ├── logo-teal.png       ← provided (extracted from your upload)
    ├── logo-white.png      ← provided (recolored variant)
    ├── hero-clouds.jpg     ← you upload
    ├── bali.jpg            ← you upload
    ├── kyoto.jpg           ← you upload
    ├── lisbon.jpg          ← you upload
    ├── marrakech.jpg       ← you upload
    └── iceland.jpg         ← you upload
```

## Image specs

| Filename | Used for | Recommended size | Suggested source |
|---|---|---|---|
| `logo-teal.png` | Nav + footer logo | already optimized (300×96) | ✅ provided |
| `logo-white.png` | About section dark bg | already optimized (300×96) | ✅ provided |
| `hero-clouds.jpg` | Hero right column, portrait | 1200×1500 (4:5 ratio) | airplane window / clouds / sky |
| `bali.jpg` | Largest destination card | 1400×1050 (4:3 landscape, displays large) | Bali rice terraces / Uluwatu |
| `kyoto.jpg` | Destination card portrait | 1000×1250 (4:5) | Kyoto temple / bamboo grove |
| `lisbon.jpg` | Destination card portrait | 900×1125 (4:5) | Lisbon tram / azulejo tiles |
| `marrakech.jpg` | Destination card portrait | 900×1125 (4:5) | Marrakech souk / riad |
| `iceland.jpg` | Destination card portrait | 900×1125 (4:5) | Iceland landscape / aurora |

## Optimization tips before upload

- Compress JPGs to ~80% quality (use [tinypng.com](https://tinypng.com) or `squoosh.app`)
- Target: each photo under 200KB for fast loading
- Format: `.jpg` for photos, `.png` only if transparency needed

## Original Unsplash sources (if you want exact same photos)

These were the placeholder URLs — download from Unsplash directly, rename to match filenames above:

- hero-clouds: https://unsplash.com/photos/photo-1488085061387-422e29b40080
- bali: https://unsplash.com/photos/photo-1537996194471-e657df975ab4
- kyoto: https://unsplash.com/photos/photo-1493976040374-85c8e12f0c0e
- lisbon: https://unsplash.com/photos/photo-1469854523086-cc02fe5d8800
- marrakech: https://unsplash.com/photos/photo-1539635278303-d4002c07eae3
- iceland: https://unsplash.com/photos/photo-1500382017468-9049fed747ef

## GitHub Pages deploy

1. Create repo, push `index.html` + `images/` folder
2. Settings → Pages → deploy from `main` branch / root
3. Site live at `https://<username>.github.io/<repo>/`

Image paths in `index.html` are relative (`images/bali.jpg`) so they work both locally and on GitHub Pages with no changes.
