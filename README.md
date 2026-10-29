# Smarthinx — sajt

Landing stranica za Smarthinx naočare za čitanje na privesku.

## Sadržaj

- `index.html` — ceo sajt (HTML, CSS i JavaScript u jednom fajlu)
- `img/` — fotografije i logo

## Kontakt podaci

Viber broj, Instagram profil i podaci o radnji menjaju se na jednom mestu, pri dnu fajla `index.html`, u bloku `CONFIG`:

```js
const CONFIG = {
  viberPhone: "+381655306393",
  instagram: "smarthinx.official",
  legal: ""   // npr. "Naziv radnje PR, Ulica 1, Grad · PIB 000000000 · MB 00000000"
};
```

## Objavljivanje preko GitHub-a i Netlify-ja

1. Na github.com napravite novi repozitorijum (npr. `smarthinx-sajt`).
2. Kliknite **Add file → Upload files** i prevucite sav sadržaj ovog foldera (`index.html`, `img`, `README.md`, `.nojekyll`).
3. Na netlify.com izaberite **Add new site → Import an existing project → GitHub** i izaberite repozitorijum.
4. Build command ostavite prazno, Publish directory: `/`. Kliknite **Deploy**.
5. U Netlify-ju: **Domain management → Add a domain** i upišite svoj domen.

Svaka izmena koja se otpremi na GitHub automatski se objavljuje na sajtu.
