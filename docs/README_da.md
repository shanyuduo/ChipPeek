# ChipPeek

En letvægts flydende hardware-overvågningswidget til Windows.

> **Andre sprog**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | **Dansk** | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funktioner

- **Realtidsovervågning**: CPU-frekvens, CPU-temperatur, GPU-frekvens, GPU-temperatur, VRAM-forbrug, hukommelsesforbrug
- **To visningstilstande**: Hjørne widget / Topbjælke, et-klik skift
- **Tilpasselig visning**: Vælg frit, hvilke målværdier der skal vises, skift mellem procent/faktiske værdier
- **Altid øverst**: Forbliver over alle vinduer. Synlighed i fuld skærm afhænger af programmet og visningstilstanden
- **Automatisk størrelse**: Vinduesbredden justeres automatisk efter indholdet
- **Justerbar stil**: Vinduesugennemsigtighed, baggrundsgennemsigtighed, skriftstørrelse - alt kan justeres
- **Flersproget understøttelse**: 103 sprog, registrerer automatisk systemsproget
- **Bekvem betjening**: Venstreklik og træk for at flytte, højreklikmenu for hurtige indstillinger, automatisk snap til skærmkanter
- **Konfigurerbar samplingsfrekvens**: 200ms - 3000ms justerbar
- **Autostart**: Starter automatisk ved Windows-logon
- **Lav ressourceforbrug**: Minimal fodaftryk i baggrunden

## Hurtig start

### Direkte brug

Download [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) og dobbeltklik for at køre (anmoder automatisk om administratorrettigheder for CPU-temperatur og nøjagtig frekvens aflæsning).

### Kør fra kildekode

```powershell
# Klon repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Installer afhængigheder
python -m pip install -r requirements.txt pythonnet

# Kør
python main.py
```

## Systemkrav

- Windows 10 / Windows 11
- Administratorrettigheder (anbefalet), ellers kan CPU-temperatur og nøjagtig frekvens muligvis ikke være tilgængelig
- .NET Framework 4.7.2 eller højere (krævet af LibreHardwareMonitor)
- Python 3 + Tkinter (Kør fra kildekode)

## Byg som EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Efter bygning er EXE-filen placeret på `dist/ChipPeek.exe`.

## Brug

### Grundlæggende operationer

| Handling | Beskrivelse |
|------|------|
| Venstreklik og træk | Flyt vinduesposition |
| Højreklik | Åbn menu (skift tilstand / indstillinger / afslut) |
| Automatisk snap | Snapper automatisk inden for 20px af skærmkanterne |

### Visningstilstande

- **Hjørne widget**: Alle målværdier arrangeret vertikalt, kan placeres i hvert skærmhjørne
- **Topbjælke**: Alle målværdier arrangeret horisontelt, centreret øverst på skærmen som standard

### Indstillinger

- **Visningstilstand**: Hjørne widget / Topbjælke
- **Widget position**: Nederst til højre / Nederst til venstre / Øverst til højre / Øverst til venstre
- **Vinduesugennemsigtighed**: Skyderen 0% - 100% svarer til en vinduesopacitet på 100% - 15%
- **Baggrundsgennemsigtighed**: 0 holder baggrunden uigennemsigtig; alle værdier over 0 gør den gennemsigtig
- **Samplingsinterval**: 200ms - 3000ms data opdateringshastighed
- **Skriftstørrelse**: 8 - 20 punkter skrift
- **Sprog**: 103 sprog, registrerer automatisk systemsproget
- **Visningsværdier**: Slå hver målværdi til/fra uafhængigt
- **Visningsformat**: VRAM / Hukommelse kan skifte mellem procent eller faktiske værdier
- **Autostart**: Kør automatisk, når du logger på Windows

## Teknologi stak

- **GUI**：Tkinter
- **Hardware data**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (reserve for NVIDIA GPU)
- **Systemintegration**：pywin32 (vindue altid øverst, autostart registreringsdatabase)
- **Pakning**：PyInstaller

## Projektstruktur

```
ChipPeek/
├── main.py                  # Startpunkt
├── monitor_window.py        # Vindues-UI og interaktionslogik
├── hardware_monitor.py      # Hardware dataindsamling
├── config.py                # Konfigurationsstyring
├── i18n.py                  # Internationalisering
├── generate_docs.py
├── generate_icon.py         # Ikon genereringsscript
├── admin.manifest           # UAC adminrettighedsmanifest
├── app.ico                  # Applikationsikon
├── logo.png
├── requirements.txt         # Python afhængigheder
├── build.bat
├── docs/                    # Flersproget dokumentation
│   └── README_*.md
├── i18n/                    # Oversættelsesfiler
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompileret eksekverbar fil
```

## Konfigurationsfil

`config.json`-filen gemmes i samme mappe som `ChipPeek.exe` / `main.py`-filen og indeholder alle justerbare indstillinger. Indstillinger gemmes automatisk, når de ændres.

## Licens

[MIT License](../LICENSE)

## Udvikler

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekt URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Tak

- LibreHardwareMonitor - Hardware overvågningsbibliotek
- psutil - På tværs af platforme systemovervågning
- PyInstaller - Python pakningsværktøj
