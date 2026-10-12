# Mobile-first – Péče v detailu

Jednostránkový web v češtině na téma péče o automobil a základů autodetailingu. Projekt vznikl jako školní úkol k tématům responzivní design, SEO základy a SEO obsah.

## Soubory

- `index.html` – sémantická struktura stránky, metadata a přirozeně napsaný obsah.
- `style.css` – mobile-first stylování, Flexbox/Grid a responzivní úpravy pro větší obrazovky.
- `images/hero.svg` – vlastní vektorová ilustrace optimalizovaná pro web.

## Spuštění

Otevřete `index.html` v prohlížeči. Web nepoužívá JavaScript, externí knihovny ani vzdálené obrázky. Vlastní SVG ilustrace je uložena v repozitáři, takže se načítá i bez připojení k internetu.

## Použité SEO fráze

- péče o auto
- ruční mytí auta
- čištění interiéru auta
- ochrana laku
- autodetailing

Fráze jsou vloženy do titulku, meta description, nadpisů a odstavců přirozeně, bez zbytečného opakování.

## Responzivita a přístupnost

- Výchozí CSS je navržené pro mobilní zařízení.
- Media queries od `768px` a `1100px` rozšiřují rozvržení na tabletu a desktopu.
- Stránka používá `header`, `nav`, `main`, `section`, `article`, `figure` a `footer`.
- Obrázky mají smysluplný `alt`, fluidní rozměry a nastavené atributy `width` a `height`.
- Navigace odkazuje na sekce stránky; nechybí přeskočení přímo na hlavní obsah.

## Ilustrace

Úvodní ilustrace je vlastní SVG soubor v `images/hero.svg`. Zůstává ostrá při různých velikostech a nevyžaduje další síťový požadavek.
