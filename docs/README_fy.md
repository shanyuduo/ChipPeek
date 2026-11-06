# ChipPeek

In lichtgewicht sweevjend widget foar hardwaremonitoring op Windows.

> **Oare talen**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | **Frysk** | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funksjes

- **Echt-tids monitoring**: CPU-frekwinsje, CPU-temperatuer, GPU-frekwinsje, GPU-temperatuer, VRAM-gebrûk, ûnthâldgebrûk
- **Twa werjeftemodi**: Hoek-widget / Boppeste balke, ien-klik wikselje
- **Oanpasbere werjefte**: frij kieze hokker metiken toand wurde, wikselje tusken persintaazje/werklike wearde
- **Altyd boppe-oan**: bliuwt boppe alle finsters. Sichtberens op folslein skerm hinget ôf fan de tapassing en de werjeftemodus
- **Auto-oanpassing**: finsterbreedte past automatysk oan ynhâld oan
- **Oanpasbere styl**: finstertrochsichtichheid, eftergrûntrochsichtichheid, lettergrutte oanpasber
- **Meartalige stipe**: 103 talen, detektearret automatysk systeemtaal
- **Handige betsjinning**: lofts slepe om te ferpleatsen, rjochts-klik menu foar flugge ynstellings, automatysk fêstsjen oan skermrânen
- **Konfigurearbere samplearring**: 200ms - 3000ms ynstelber
- **Automatysk starte**: start automatysk by Windows-oanmelding
- **Leech boarnnebrûk**: minimale fuotôfdrukt yn eftergrûn

## Flugge start

### Direkt gebrûk

Download [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) en dûbelklik om út te fieren (sil automatysk behearderrjochten freegje foar CPU-temperatuer en krekte frekwinsje-lêzing).

### Fanút boarne útfiere

```powershell
# De opslach klonje
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Ofhinklikheden ynstallearje
python -m pip install -r requirements.txt pythonnet

# Útfiere
python main.py
```

## Systeemeasken

- Windows 10 / Windows 11
- Behearderrjochten (oanrekommandearre), oars CPU-temperatuer en krekte frekwinsje net beskikber wêze kinne
- .NET Framework 4.7.2 of heger (fereaske troch LibreHardwareMonitor)
- Python 3 + Tkinter (Fanút boarne útfiere)

## As EXE bouwe

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Nei it bouwen is it EXE-bestân te finen op `dist/ChipPeek.exe`.

## Gebrûk

### Basisbewurkingen

| Aksje | Beskriuwing |
|------|------|
| Lofts slepe | Finster ferpleatse |
| Rjochts klikke | Menu iepenje (modus wikselje / ynstellings / slute) |
| Automatysk fêstsjen | Hâldt automatysk fêst binnen 20px fan skermrânen |

### Werjeftemodi

- **Hoek-widget**: alle metiken fertikaal oardere, op eltse skermhoeke te pleatsen
- **Boppeste balke**: alle metiken horizontaal oardere, standert sintral op it boppeste part fan it skerm

### Ynstellings

- **Werjeftemodus**: Hoek-widget / Boppeste balke
- **Widget-posysje**: Rjochts ûnder / Lofts ûnder / Rjochts boppe / Lofts boppe
- **Finstertrochsichtichheid**: De skúfbalke 0% - 100% komt oerien mei in finsterdekking fan 100% - 15%
- **Eftergrûntrochsichtichheid**: 0 hâldt de eftergrûn net-trochsichtich; elke wearde boppe 0 makket dy trochsichtich
- **Sammelynterval**: 200ms - 3000ms fernijingssnelheid
- **Lettergrutte**: 8 - 20 punts lettertype
- **Taal**: 103 talen, detektearret automatysk systeemtaal
- **Toande metiken**: elke metyk ûnôfhinklik wikselje
- **Werjefteformaat**: VRAM / Unthâld kinne wikselje tusken persintaazje of werklike wearde
- **Automatysk starte**: automatysk útfiere by oanmelden by Windows

## Technology-stack

- **Grafyske ynterface**：Tkinter
- **Hardware-gegevens**：LibreHardwareMonitorLib (fia pythonnet), psutil, pynvml (NVIDIA GPU-fallbackoplossing)
- **Systeem-yntegraasje**：pywin32 (finster boppe-oan, autostart-register)
- **Ynpakken**：PyInstaller

## Projektstruktuer

```
ChipPeek/
├── main.py                  # Yngongspunt
├── monitor_window.py        # Finster-UI en ynteraktielogika
├── hardware_monitor.py      # Hardware-gegevenssamling
├── config.py                # Konfiguraasjebehear
├── i18n.py                  # Ynternasjonalisearring
├── generate_docs.py
├── generate_icon.py         # Ikoangeneraasjeskript
├── admin.manifest           # UAC-beheardermanifest
├── app.ico                  # Applikaasje-ikoan
├── logo.png
├── requirements.txt         # Python-ôfhinklikheden
├── build.bat
├── docs/                    # Meartalige dokumintaasje
│   └── README_*.md
├── i18n/                    # Oersetbestannen
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompilearre útfierber bestân
```

## Konfiguraasjebestân

It `config.json`-bestân wurdt bewarre yn itselde map as de `ChipPeek.exe` / `main.py`, en befettet alle oanpasbere ynstellings. Ynstellings wurde automatysk bewarre by wiziging.

## Lisinsje

[MIT License](../LICENSE)

## Untwikkeler

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekt URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Tank

- LibreHardwareMonitor - Hardware-monitoring bibleteek
- psutil - Cross-platform systeemmonitoring
- PyInstaller - Python-ynpaktasje-ark
