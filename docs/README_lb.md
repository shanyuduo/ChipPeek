# ChipPeek

E liicht schwiewend Widget fir Windows Hardware-Monitoring.

> **Aner Sproochen**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | **Lëtzebuergesch** | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Feature

- **Echtzäit-Monitoring**: CPU-Frequenz, CPU-Temperatur, GPU-Frequenz, GPU-Temperatur, VRAM-Notzung, Späichernotzung
- **Zwei Affichage-Modi**: Eck-Widget / Uewerste Bar, Een-Klick Wiesselung
- **Personaliséierbar Affichage**: Fräi wielen wéi eng Metrike gewise ginn, Wiesselung tëscht Prozenten / reele Wäerter
- **Ëmmer uewen**: Bleift iwwer all Fënster. D’Siichtbarkeet am Vollbild hänkt vun der Applikatioun an dem Uweismodus of
- **Auto-Gréisst**: Fënsterbreet passen sech automatesch un den Inhalt un
- **Upassbar Stil**: Fënster-Opazitéit, Hannergrond-Transparenz, Schrëftgréisst alles upassbar
- **Alemole Sproochën**: 103 Sproochen, erkennt automatesch d'Sprooch vum System
- **Komfortabel Bedienung**: Lénks zéien fir ze réckelen, Riets-Klick-Menü fir séier Astellungen, auto Snap zu Bildschirmkanten
- **Konfiguréierbar Sampling**: 200ms - 3000ms upassbar
- **Auto-Start**: Automatesch Start bei Windows-Umeldung
- **Niddrig Ressourcenverbrauch**: Minimaler Footprint am Hannergrond

## Schnell Start

### Direkt Notzung

Lued [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) erof an duebelklick fir ze starten (frot automatesch no Admin-Rechter fir CPU-Temperatur a genee Frequenzliesung).

### Vun Quelle starten

```powershell
# D'Repository klonen
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Ofhängegkeete installéieren
python -m pip install -r requirements.txt pythonnet

# Starten
python main.py
```

## Systemufuerderungen

- Windows 10 / Windows 11
- Admin-Rechter (empfohlen), soss kann d'CPU-Temperatur an d'genau Frequenz net verfügbar sinn
- .NET Framework 4.7.2 oder méi héich (fuerderlech vu LibreHardwareMonitor)
- Python 3 + Tkinter (Vun Quelle starten)

## Als EXE bauen

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Nom Bau ass d'EXE-Datei ënner `dist/ChipPeek.exe` ze fannen.

## Notzung

### Basis Operatiounen

| Handlung | Beschreiwung |
|------|------|
| Lénks zéien | Fënsterpositioun réckelen |
| Riets klicken | Menü opmaachen (Modus wiesselen / Astellungen / verloossen) |
| Auto Snap | Automatesch binnen 20px vu Bildschirmkanten ugeklemmt |

### Affichage-Modi

- **Eck-Widget**: All Metrike vertikal arrangéiert, kënnen an all Eck vum Bildschirm gesat ginn
- **Uewerste Bar**: All Metrike horizontal arrangéiert, standardméisseg uewen am Bildschirm zentrëiert

### Astellungen

- **Affichage-Modus**: Eck-Widget / Uewerste Bar
- **Widget-Positioun**: Enn riets / Enn lénks / Uewen riets / Uewen lénks
- **Fënster-Opazitéit**: De Schieber 0% - 100% entsprécht enger Fënsterdeckkraaft vun 100% - 15%
- **Hannergrond-Transparenz**: 0 léisst den Hannergrond net transparent; all Wäert iwwer 0 mécht en transparent
- **Sampling-Intervall**: 200ms - 3000ms Datenaktualiséierungsrate
- **Schrëftgréisst**: 8 - 20 Punkt Schrëft
- **Sprooch**: 103 Sproochen, erkennt automatesch d'Sprooch vum System
- **Metrike gewisen**: All Metrik onofhängeg un/auschalten
- **Affichage-Format**: VRAM / Späicher kënnen tëscht Prozenten oder reele Wäerter wiesselen
- **Auto-Start**: Automatesch starten wann Dir Iech bei Windows umellt

## Tech Stack

- **GUI**：Tkinter
- **Hardware-Daten**：LibreHardwareMonitorLib (iwwer pythonnet), psutil, pynvml (NVIDIA GPU Fallback)
- **Systemintegratioun**：pywin32 (Fënster uewen, Auto-Start Registry)
- **Verpakung**：PyInstaller

## Projetstruktur

```
ChipPeek/
├── main.py                  # Ékraaftspunkt
├── monitor_window.py        # Fënster UI a Interaktiounslogik
├── hardware_monitor.py      # Hardware-Daten Sammlung
├── config.py                # Konfiguratiounsverwaltung
├── i18n.py                  # Internationaliséierung
├── generate_docs.py
├── generate_icon.py         # Script fir Icon-Generatioun
├── admin.manifest           # UAC Admin-Recht Manifest
├── app.ico                  # Applikatioun Icon
├── logo.png
├── requirements.txt         # Python Ofhängegkeete
├── build.bat
├── docs/                    # Mëttlesprooch Dokumenten
│   └── README_*.md
├── i18n/                    # Iwwersetzungsdateien
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompiléiert Exécutabel
```

## Konfiguratiounsdatei

D'`config.json` Datei gëtt am selwechte Verzeichnis wéi d'`ChipPeek.exe` / `main.py` gespäichert, mat allen upassbaren Astellungen. Astellungen ginn automatesch gespäichert wa se geännert ginn.

## Lizenz

[MIT License](../LICENSE)

## Entwéckler

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projet URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Merci

- LibreHardwareMonitor - Hardware-Monitoring Bibliothéik
- psutil - Kräizplattform System-Monitoring
- PyInstaller - Python Verpakungstool
