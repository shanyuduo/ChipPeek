# ChipPeek

En lettvekts flytende maskinvareovervåkingswidget for Windows.

> **Andre språk**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | **Norsk** | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funksjoner

- **Realtimeovervåking**: CPU-frekvens, CPU-temperatur, GPU-frekvens, GPU-temperatur, VRAM-bruk, minnebruk
- **To visningsmoduser**: Hjørnewidget / Toppliste, ett-klikk bytte
- **Tilpassbar visning**: Velg fritt hvilke måleverdier som skal vises, bytt mellom prosent/faktiske verdier
- **Alltid øverst**: Forblir over alle vinduer. Synlighet i fullskjerm avhenger av programmet og visningsmodusen
- **Automatisk størrelse**: Vindusbredden justeres automatisk etter innholdet
- **Justerbar stil**: Vindusopasitet, bakgrunnsgjennomsiktighet, skriftstørrelse - alt kan justeres
- **Flerspråklig støtte**: 103 språk, oppdager automatisk systemspråket
- **Enkel håndtering**: Venstreklikk og dra for å flytte, høyreklikkmeny for raske innstillinger, automatisk feste til skjermkantene
- **Konfigurerbar samplingsfrekvens**: 200ms - 3000ms justerbar
- **Autostart**: Starter automatisk ved Windows-pålogging
- **Lav resursbruk**: Minimal fotavtrykk i bakgrunnen

## Hurtigstart

### Direkte bruk

Last ned [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) og dobbeltklikk for å kjøre (behov automatisk administratorrettigheter for CPU-temperatur og nøyaktig frekvensavlesning).

### Kjør fra kildekode

```powershell
# Klon depotet
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Installer avhengigheter
python -m pip install -r requirements.txt pythonnet

# Kjør
python main.py
```

## Systemkrav

- Windows 10 / Windows 11
- Administratorrettigheter (anbefalt), ellers kan CPU-temperatur og nøyaktig frekvens ikke være tilgjengelig
- .NET Framework 4.7.2 eller høyere (kreves av LibreHardwareMonitor)
- Python 3 + Tkinter (Kjør fra kildekode)

## Bygg som EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Etter bygging finnes EXE-filen på `dist/ChipPeek.exe`.

## Bruk

### Grunnleggende operasjoner

| Handling | Beskrivelse |
|------|------|
| Venstreklikk og dra | Flytt vindusposisjon |
| Høyreklikk | Åpne meny (bytt modus / innstillinger / avslutt) |
| Automatisk festing | Fester automatisk innen 20px fra skjermkantene |

### Visningsmoduser

- **Hjørnewidget**: Alle måleverdier ordnet vertikalt, kan plasseres i ethvert hjørne av skjermen
- **Toppliste**: Alle måleverdier ordnet horisontalt, sentrert øverst på skjermen som standard

### Innstillinger

- **Visningsmodus**: Hjørnewidget / Toppliste
- **Widgetposisjon**: Nederst til høyre / Nederst til venstre / Øverst til høyre / Øverst til venstre
- **Vindusopasitet**: Glidebryteren 0% - 100% tilsvarer en vindusopasitet på 100% - 15%
- **Bakgrunnsgjennomsiktighet**: 0 holder bakgrunnen ugjennomsiktig; alle verdier over 0 gjør den gjennomsiktig
- **Samplingsintervall**: 200ms - 3000ms dataoppdateringshastighet
- **Skriftstørrelse**: 8 - 20 punkter
- **Språk**: 103 språk, oppdager automatisk systemspråket
- **Visningsverdier**: Slå av/på hver måleverdi uavhengig
- **Visningsformat**: VRAM / Minne kan bytte mellom prosent eller faktiske verdier
- **Autostart**: Kjør automatisk når du logger på Windows

## Teknistabel

- **GUI**：Tkinter
- **Maskinvare-data**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (alternativ for NVIDIA GPU)
- **Systemintegrasjon**：pywin32 (vindu alltid øverst, autostartregister)
- **Pakking**：PyInstaller

## Prosjektstruktur

```
ChipPeek/
├── main.py                  # Startpunkt
├── monitor_window.py        # Vindu-UI og interaksjonslogikk
├── hardware_monitor.py      # Innhenting av maskinvare-data
├── config.py                # Konfigurasjonsstyring
├── i18n.py                  # Internasjonalisering
├── generate_docs.py
├── generate_icon.py         # Ikon-genereringsskript
├── admin.manifest           # UAC-adminrettighetsmanifest
├── app.ico                  # Applikasjonsikon
├── logo.png
├── requirements.txt         # Python-avhengigheter
├── build.bat
├── docs/                    # Flerspråklig dokumentasjon
│   └── README_*.md
├── i18n/                    # Oversettelsesfiler
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompilert kjørbar fil
```

## Konfigurasjonsfil

`config.json`-filen lagres i samme mappe som `ChipPeek.exe` / `main.py`-filen og inneholder alle justerbare innstillinger. Innstillingene lagres automatisk når de endres.

## Lisens

[MIT License](../LICENSE)

## Utvikler

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Prosjekt-URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kreditter

- LibreHardwareMonitor - Maskinvareovervåkingsbibliotek
- psutil - Plattformuavhengig systemovervåking
- PyInstaller - Python-pakkingsverktøy
