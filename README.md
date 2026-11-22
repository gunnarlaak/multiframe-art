# Multiframe Art 2.0

Androidi brauseris töötav PWA. Ava HTTPS-iga (näiteks GitHub Pages). Failid jäävad seadmesse.

## Funktsioonid
- getUserMedia kaamera, järjestikused kaadrid ja eelmise kaadri overlay
- Galeriist mitme foto import; süsteemi kaamera varuvariant
- Automaatne **ainult x/y nihke** hindamine väikese pildi pikslivõrdluse põhjal
- Keskmistamine, lighten, screen ja multiply; pehmus, hajutus, värvid
- 2000/3000/4500/6000 px JPG/PNG eksport

## Piirangud
- Ei ole perspektiivi, pöörde, skaala ega objektipõhist semantilist joondamist.
- Keskpunkti puudutamine annab loomingulise nihke, mitte objekti tuvastuse.
- Kaamera vajab HTTPS-i või localhosti ja brauseri kaameraluba.
- Suured ekspordid võivad Androidi brauseris mälupuuduse tõttu ebaõnnestuda.
- Browser camera kvaliteet võib erineda telefoni kaameraäpi kvaliteedist.

## Paigaldamine
Laadi selle kausta failid GitHub Pagesi või mõnele HTTPS-serverile, ava Chrome'is ja vali menüüst Install app / Lisa avakuvale.
