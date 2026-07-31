# Faqja e Dashurisë 🐾❤️

## Si ta hedhësh në GitHub (GitHub Pages)

1. Krijo një repository të ri në GitHub, p.sh. `per-dashurine-time`.
2. Ngarko **të gjithë skedarët dhe folderin `media/`** (me foto+video brenda), plus `index.html` dhe `love-song.mp3`, duke ruajtur të njëjtën strukturë foldersh (drag & drop në GitHub, ose `git add . && git commit -m "love page" && git push`).
3. Shko te **Settings → Pages** te repository.
4. Te "Branch", zgjidh `main` dhe folderin `/ (root)`, pastaj **Save**.
5. Pas ~1 minute, faqja do të jetë live te:
   `https://<username-yt>.github.io/per-dashurine-time/`

## Si të shtosh foto/video shtesë

Në seksionin "Momente Tona" të `index.html`, mund të shtosh një kartelë të re si:

```html
<div class="photo reveal"><img src="media/photo7.jpg" alt="Momenti ynë"></div>
```

Vendos skedarin e ri brenda folderit `media/`.

## Si të ndryshosh emrin

Në krye të faqes, `<h1>Për <em>Dashurinë</em> Time</h1>` — mund ta zëvendësosh "Dashurinë" me emrin e saj nëse do.
