# Mamince

Klid na dobrou noc. Jednoduchá webová aplikace pro chvíle, kdy nejde usnout, kdy je člověk ve stresu nebo je toho na něj prostě moc.

## Co umí

- **Domů – Jak se teď cítíš?** Pět voleb: *Nemůžu spát*, *Jsem ve stresu*, *Je toho na mě moc*, *Neklidná hlava*, *Návaly a přechod*. Každá nabídne krátký plán, kde se každý krok spustí jedním klepnutím.
- **Dýchání** – kruh vede nádech a výdech. Techniky: krabicové 4·4·4·4, na usnutí 4·7·8, rovnoměrné 5,5 a povzdech.
- **Zvuky** – hnědý, růžový a bílý šum, déšť, moře, ventilátor. Vlastní mix i hotové předvolby. Všechno se generuje v prohlížeči.
- **Hry** – bez bodů a bez prohry: bublinková fólie, spojování hvězd, zen zahrádka, světlušky.
- **Usínání** – vedené uvolnění těla (čte se nahlas česky), míchání myšlenek, odložení starostí, zhasnutí obrazovky.
- **Hormony** – pro období přechodu: vedené zklidnění, když přijde nával (s představou chladu), tipy při nočním pocení, cviky na pánevní dno s počítáním (3 úrovně) a 8 cviků u židle na kosti a rovnováhu s časovačem a předčítáním.
- **Nahoře** – velké tlačítko pro vypnutí veškerého zvuku, usínací časovač (zvuk na konci pomalu zeslábne), výběr jazyka, **Aa** pro větší písmo a tlačítko pro sdílení.
- **Jazyky** – čeština, angličtina, slovinština a chorvatština (včetně předčítání). Jazyk se vybere sám podle telefonu, přepnout jde nahoře.
- **Pozdrav** – podle denní doby: dobrou noc, dobré ráno, dobré dopoledne, dobré odpoledne, dobrý večer.

## Soubory

- `index.html` – celá aplikace
- `manifest.webmanifest`, `icon-192.png`, `icon-512.png` – aby šla aplikace přidat na plochu telefonu
- `sw.js` – aby aplikace fungovala i bez internetu
- `README.md` – tento popis

## Zveřejnění na GitHub Pages

1. Na GitHubu vytvoř nový repozitář (např. `mamince`).
2. Nahraj do něj všechny soubory (**Add file → Upload files**).
3. **Settings → Pages** → *Source*: **Deploy from a branch**, větev `main`, složka `/ (root)` → **Save**.
4. Za chvíli bude aplikace na `https://<tvoje-jmeno>.github.io/mamince/`.

## Na Androidu

1. Otevři odkaz v Chromu.
2. Na úvodní obrazovce dole klepni na **Přidat** (nebo v Chromu **⋮** vpravo nahoře → **Přidat na plochu** / **Instalovat aplikaci**).
3. Na ploše se objeví ikona s měsíčkem a aplikace se otevírá jako normální aplikace.

Tipy:
- Při **Zhasnout obrazovku** zůstane telefon černý, ale nezamkne se, takže zvuk hraje dál. Když se telefon zamkne tlačítkem, Chrome může zvuk po chvíli zastavit.
- Předčítání používá hlas Google v telefonu pro zvolený jazyk. Když chybí, dá se doinstalovat v *Nastavení → Systém → Jazyky → Převod textu na řeč*.
- Písmo se načítá z Google Fonts. Bez internetu se použije náhradní písmo, vše ostatní funguje.

---

Tahle aplikace není zdravotnická pomůcka. Pokud nespavost nebo úzkost trápí dlouhodobě, je dobré poradit se s lékařem.
