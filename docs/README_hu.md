# ChipPeek

Egy könnyű súlyú lebegő hardvermonitorozó widget Windowshez.

> **Egyéb nyelvek**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | **Magyar** | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Jellemzők

- **Valós idejű monitorozás**: CPU frekvencia, CPU hőmérséklet, GPU frekvencia, GPU hőmérséklet, VRAM használat, memória használat
- **Két megjelenítési mód**: sarok widget / felső sáv, egy kattintással váltás
- **Testreszabható megjelenítés**: szabadon választhatja, melyik metrikát jelenítse meg, százalék/tényleges értékek közötti váltás
- **Mindig felül**: minden ablak felett marad. A teljes képernyős láthatóság az alkalmazástól és a megjelenítési módtól függ
- **Automatikus méret**: az ablak szélessége automatikusan igazodik a tartalomhoz
- **Beállítható stílus**: ablak átlátszóság, háttér átlátszóság, betűméret - mind beállítható
- **Többnyelvű támogatás**: 103 nyelv, automatikusan felismeri a rendszer nyelvét
- **Kényelmes kezelés**: bal gombbal húzva mozgatás, jobb klikk menü gyors beállításokhoz, automatikus rögzítés a képernyő szélére
- **Beállítható mintavételi gyakoriság**: 200ms - 3000ms beállítható
- **Automatikus indítás**: automatikusan elindul a Windows bejelentkezéskor
- **Alacsony erőforrás-használat**: minimális terhelés a háttérben

## Gyors kezdés

### Közvetlen használat

Töltse le a [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) fájlt, és kattintson duplán a futtatáshoz (automatikusan rendszergazdai engedélyt kér a CPU hőmérséklethez és a pontos frekvenciaolvasáshoz).

### Futtatás forráskódból

```powershell
# Tároló klónozása
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Függőségek telepítése
python -m pip install -r requirements.txt pythonnet

# Futtatás
python main.py
```

## Rendszerkövetelmények

- Windows 10 / Windows 11
- Rendszergazdai engedélyek (ajánlott), egyébként a CPU hőmérséklet és a pontos frekvencia nem lehet elérhető
- .NET Framework 4.7.2 vagy magasabb (a LibreHardwareMonitor igényli)
- Python 3 + Tkinter (Futtatás forráskódból)

## Összeállítás EXE-ként

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Az összeállítás után az EXE fájl a `dist/ChipPeek.exe` helyen található.

## Használat

### Alapvető műveletek

| Művelet | Leírás |
|------|------|
| Bal klikk húzás | Ablak helyzetének mozgatása |
| Jobb klikk | Menü megnyitása (mód váltás / beállítások / kilépés) |
| Automatikus rögzítés | Automatikusan rögzül a képernyő szélétől 20px távolságon belül |

### Megjelenítési módok

- **Sarok widget**: összes metrika függőlegesen rendezve, elhelyezhető a képernyő bármelyik sarkában
- **Felső sáv**: összes metrika vízszintesen rendezve, alapértelmezésben középen a képernyő tetején

### Beállítások

- **Megjelenítési mód**: sarok widget / felső sáv
- **Widget helye**: jobb alsó / bal alsó / jobb felső / bal felső
- **Ablak átlátszóság**: A 0% - 100% csúszka az ablak 100% - 15% fedettségének felel meg
- **Háttér átlátszóság**: 0 esetén a háttér átlátszatlan; minden 0 feletti érték átlátszóvá teszi
- **Mintavételi intervallum**: 200ms - 3000ms adatfrissítési gyakoriság
- **Betűméret**: 8 - 20 pont
- **Nyelv**: 103 nyelv, automatikusan felismeri a rendszer nyelvét
- **Megjelenítendő metrikák**: minden metrika külön kapcsolható be/ki
- **Megjelenítési formátum**: VRAM / Memória váltás százalék vagy tényleges értékek között
- **Automatikus indítás**: automatikus futtatás Windows bejelentkezéskor

## Technológiai verem

- **GUI**：Tkinter
- **Hardver adatok**：LibreHardwareMonitorLib (pythonnet segítségével), psutil, pynvml (NVIDIA GPU tartalék)
- **Rendszerintegráció**：pywin32 (ablak mindig felül, automatikus indítási beállításjegyzék)
- **Csomagolás**：PyInstaller

## Projekt szerkezete

```
ChipPeek/
├── main.py                  # Belépési pont
├── monitor_window.py        # Ablak UI és interakciós logika
├── hardware_monitor.py      # Hardver adatgyűjtés
├── config.py                # Konfiguráció kezelése
├── i18n.py                  # Nemzetközivé tétel
├── generate_docs.py
├── generate_icon.py         # Ikon generáló szkript
├── admin.manifest           # UAC rendszergazdai engedély manifest
├── app.ico                  # Alkalmazás ikon
├── logo.png
├── requirements.txt         # Python függőségek
├── build.bat
├── docs/                    # Többnyelvű dokumentáció
│   └── README_*.md
├── i18n/                    # Fordítási fájlok
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Összeállított futtatható fájl
```

## Konfigurációs fájl

A `config.json` fájl az `ChipPeek.exe` / `main.py`-hez hasonló mappában kerül mentésre, és tartalmazza az összes beállítható beállítást. A beállítások automatikusan mentésre kerülnek módosításkor.

## Licenc

[MIT License](../LICENSE)

## Fejlesztő

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekt URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Köszönet

- LibreHardwareMonitor - Hardver monitorozó könyvtár
- psutil - Platformfüggetlen rendszer monitorozás
- PyInstaller - Python csomagoló eszköz
