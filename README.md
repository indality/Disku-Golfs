# Riekstukalns — rezultātu karte

Disku golfa rezultātu karte, vēsture un statistika. Darbojas kā aplikācija tavā iPhone.

## Faili
Ievieto GitHub repo šos failus **vienā mapē** (piemēram, repo saknē):
- `index.html`
- `manifest.json`
- `sw.js`
- `hero.jpg`
- `icon-192.png`, `icon-512.png`, `apple-touch-icon.png`, `favicon-32.png`

## 1. Publicē ar GitHub Pages
1. Izveido jaunu repo (piem. `riekstukalns-scorecard`) un ielādē visus failus.
2. **Settings → Pages → Build and deployment → Source**: izvēlies `Deploy from a branch`, branch `main`, mape `/ (root)`.
3. Pēc pāris minūtēm lapa būs pieejama `https://tavsvards.github.io/riekstukalns-scorecard/`.

## 2. Pievieno kā aplikāciju iPhone
1. Atver saiti Safari (svarīgi — ne Chrome).
2. Spied **Share** ikonu (kvadrāts ar bultu uz augšu).
3. Izvēlies **Add to Home Screen**.
4. Apstiprini — ikona parādīsies tavā sākuma ekrānā un atvērsies pilnekrāna režīmā, bez pārlūka joslas.

## Kā darbojas
- **Spēlēt** — ievadi lokāciju, datumu, spēlētāju vārdus un rezultātus pa bedrītēm.
- **Saglabāt raundu** — pievieno pašreizējo raundu vēsturei un notīra rezultātus nākamajai spēlei (vārdi un lokācija paliek).
- **Vēsture** — visi saglabātie raundi, uzvarētājs katrā raundā iezīmēts.
- **Statistika** — līderu tabula (uzvaras, vidējie metieni, vidējā starpība pret paru) un statistika pa lokācijām (var salīdzināt, kurā parkā spēlē labāk).

Visi dati glabājas tikai tavā ierīcē (localStorage) — nekas netiek sūtīts uz serveri.
