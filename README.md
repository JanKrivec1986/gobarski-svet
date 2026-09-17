# Gobarski svet — GitHub Pages starter

## Objava
1. Ustvari nov GitHub repository in vanj naloži **vsebino te mape** (ne nujno ZIP datoteke).
2. GitHub → Settings → Pages → Build and deployment → Source: **Deploy from a branch**.
3. Izberi branch `main` in mapo `/ (root)`.
4. Počakaj na build. Projekt uporablja Jekyll, ki ga GitHub Pages podpira.

## Če objavljaš kot project site
Če bo naslov `uporabnik.github.io/ime-repoja`, v `_config.yml` nastavi:
`baseurl: "/ime-repoja"`

Če uporabljaš lastno domeno ali user/organization site, pusti `baseurl: ""`.

## Urejanje sveže ponudbe
Odpri `data/ponudba.json`. Za vsak izdelek lahko spremeniš `cena`, `pakiranja`, `na_voljo`, `zaloga`, `sezona`, `datum_pobiranja`, `lokacija`, `opis` in `kontakt`.

Možne vrednosti `zaloga`: `na_voljo`, `omejena`, `ni_na_voljo`. Prikaz primarno upošteva `na_voljo`.

## Affiliate povezave
V `seti/index.md` zamenjaj `href="#"` z dejanskimi affiliate URL-ji. Ohranjen je `rel="sponsored nofollow"`. Dodaj tudi pogoje/razkritja, ki jih zahteva posamezen affiliate program in veljavna zakonodaja.

## Pred objavo
- zamenjaj ime znamke in e-pošto,
- vnesi pravo domeno,
- dodaj svoje fotografije,
- odstrani vzorčne ponudbe,
- pripravi potrebne informacije o upravljavcu strani, zasebnosti/piškotkih, če jih uporabljaš, in pogojih prodaje,
- pred prodajo svežih gob preveri veljavne zahteve za živilsko dejavnost.

## Lokalni razvoj (neobvezno)
Če imaš Ruby/Bundler:
`bundle install`
`bundle exec jekyll serve`
