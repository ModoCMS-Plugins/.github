# Modo CMS — wtyczki / plugins

[Polska wersja](#polska-wersja) · [English version](#english-version)

---

## Polska wersja

Darmowe wtyczki do [Modo CMS](https://modocms.top/), rozwijane w tej organizacji. Każda wtyczka ma **własne repozytorium**, więc pobierasz tylko tę, której naprawdę potrzebujesz — bez klonowania całości i bez szukania plików w archiwum zbiorczym.

**Zasady organizacji**

- **Jedna wtyczka = jedno repozytorium**, nazwane `plugin-<id>` (np. `plugin-modo-watermark`).
- Nazwa repozytorium = nazwa katalogu wtyczki = nazwa pliku głównego (`plugin-modo-watermark` → `modo-watermark/modo-watermark.php`).
- **Zero zależności zewnętrznych** — bez CDN, bez Composera. Wgranie katalogu wystarcza.
- Licencja **MIT**, interfejs po polsku i angielsku (słownik `assets/lang/`).
- Kod jest tym samym kodem, który działa na stronie — bez ukrytego zdalnego wywołania.

**Instalacja wtyczki**

1. Wejdź w repozytorium wtyczki i kliknij **Code → Download ZIP**.
2. Skopiuj **zawartość** archiwum do `plugins/<id>/` w instalacji Modo.
3. Panel → **Wtyczki** → włącz wtyczkę.
4. Wyczyść cache (Panel → Cache), jeśli jest włączony.

**Dostępne wtyczki**

| Wtyczka | Co robi | Wersja | PHP |
| --- | --- | --- | --- |
| [Modo Watermark](https://github.com/ModoCMS-Plugins/plugin-modo-watermark) | Znak wodny na zdjęciach nakładany **w przeglądarce** — pliki obrazów pozostają nietknięte. Obejmuje treści stron i wpisów, Modo Gallery, meta-galerie z pól niestandardowych, Modo Carousel / slider, lightbox oraz zwykłe obrazy w motywie (pola niestandardowe typu obraz lub galeria). Automatycznie pomija logo, nagłówek, stopkę, nawigację i awatary; każde zdjęcie można też wykluczyć klasą `mwm-skip`, atrybutem `data-no-watermark` lub własnym selektorem CSS. | 1.1.0 | 8.0+ |

**Zgłaszanie błędów i nowe wtyczki**

Błąd, brakującą funkcję albo propozycję nowej wtyczki zgłoś w **issue** repozytorium, którego to dotyczy — pełna dokumentacja każdej wtyczki (instalacja, wszystkie opcje, lista zmian) jest w jej README. Nowa wtyczka powstaje jako osobne repozytorium `plugin-<id>` w tej organizacji, zgodne z zasadami powyżej.

**Wsparcie:** ☕ [ko-fi.com/multicolorplugins](https://ko-fi.com/multicolorplugins) — jeśli wtyczka się przydała, postaw kawę.

---

## English version

Free plugins for [Modo CMS](https://modocms.top/), developed in this organization. Every plugin lives in **its own repository**, so you download only the one you need — no cloning everything, no digging through a bundle archive.

**Organization rules**

- **One plugin = one repository**, named `plugin-<id>` (e.g. `plugin-modo-watermark`).
- Repository name = plugin folder name = main file name (`plugin-modo-watermark` → `modo-watermark/modo-watermark.php`).
- **No external dependencies** — no CDN, no Composer. Dropping the folder in is enough.
- **MIT** license, admin interface in Polish and English (dictionary in `assets/lang/`).
- The code is exactly what runs on your site — no hidden remote calls.

**Installing a plugin**

1. Open the plugin's repository and click **Code → Download ZIP**.
2. Copy the **contents** of the archive into `plugins/<id>/` of your Modo installation.
3. In the admin open **Plugins** and enable the plugin.
4. Clear the cache (Admin → Cache) if caching is enabled.

**Available plugins**

| Plugin | What it does | Version | PHP |
| --- | --- | --- | --- |
| [Modo Watermark](https://github.com/ModoCMS-Plugins/plugin-modo-watermark) | Watermark on images drawn **in the browser** — image files stay untouched. Covers page and post content, Modo Gallery, custom-field meta galleries, Modo Carousel / slider, the lightbox and plain images anywhere in the theme (image or gallery custom fields). It skips logos, header, footer, navigation and avatars automatically; any image can also be excluded with the `mwm-skip` class, a `data-no-watermark` attribute or a custom CSS selector. | 1.1.0 | 8.0+ |

**Bug reports and new plugins**

Report bugs, missing features or ideas for a new plugin in the **issue tracker** of the repository they concern — each plugin's README holds its full documentation (installation, every option, changelog). A new plugin becomes its own `plugin-<id>` repository in this organization, following the rules above.

**Support:** ☕ [ko-fi.com/multicolorplugins](https://ko-fi.com/multicolorplugins) — if a plugin helped you, buy me a coffee.

---

Licencja / License: MIT
