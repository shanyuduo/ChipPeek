# ChipPeek

'n Liggewig drywende hardeware moniteringsapparaat vir Windows.

> **Ander tale**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | **Afrikaans** | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Kenmerke

- **In-reële-tyd monitering**: CPU frekwensie, CPU temperatuur, GPU frekwensie, GPU temperatuur, VRAM gebruik, geheuegebruik
- **Twee vertoonmodusse**: Hoek-widget / Bokant-balk, skakel met een klik
- **Aangepaste vertoon**: Kies vryelik watter metrika vertoon moet word, skakel tussen persentasie/werklike waardes
- **Altyd bo**: Bly bo alle vensters. Sigbaarheid in volskerm hang af van die toepassing en vertoonmodus
- **Outomatiese grootte**: Vensterwydte word outomaties aangepas volgens inhoud
- **Verstelbare styl**: Vensterdeursigtigheid, agtergronddeursigtigheid, lettergrootte - almal verstelbaar
- **Veeltalige ondersteuning**: 103 tale, outomaties stelseltaal opspoor
- **Maklike bediening**: Sleep met linkerklik om te beweeg, regterklik-kieslys vir vinnige instellings, outomatiese vashegting by skermrante
- **Steekfrekwensie verstelling**: 200ms - 3000ms verstelbaar
- **Outomatiese begin**: Begin outomaties by Windows aanmelding
- **Lae hulpbronverbruik**: Minimale ruimte in agtergrond

## Vinnige begin

### Direkte gebruik

Laai [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) af en dubbelklik om uit te voer (sal outomaties bestuurdersregte aanvra om CPU-temperatuur en akkurate frekwensie te lees).

### Run van bronkode

```powershell
# Klon bewaarplek
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Installeer afhanklikhede
python -m pip install -r requirements.txt pythonnet

# Hardloop
python main.py
```

## Stelselvereistes

- Windows 10 / Windows 11
- Bestuurdersregte (aanbeveel), anders is CPU-temperatuur en akkurate frekwensie miskien nie beskikbaar nie
- .NET Framework 4.7.2 of hoër (nodig vir LibreHardwareMonitor)
- Python 3 + Tkinter (Run van bronkode)

## Bou as EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Na bou is die EXE-lêer in `dist/ChipPeek.exe`.

## Gebruik

### Basiese bedienings

| Bediening | Beskrywing |
|------|------|
| Linkerklik-sleep | Beweeg vensterposisie |
| Regterklik | Maak kieslys oop (skakel modus / instellings / verlaat) |
| Outomatiese vashegting | Hê outomaties vas binne 20px van skermrante |

### Vertoonmodusse

- **Hoek-widget**: Alle metrieke is vertikaal gerangskik, kan in enige hoek van die skerm geplaas word
- **Bokant-balk**: Alle metrieke is horisontaal gerangskik, verstek in die middel van die bokant van die skerm

### Instellings

- **Vertoonmodus**: Hoek-widget / Bokant-balk
- **Widget-posisie**: Onder regs / Onder links / Bo regs / Bo links
- **Vensterdeursigtigheid**: Die skuifbalk 0% - 100% stem ooreen met vensterondeursigtigheid van 100% - 15%
- **Agtergronddeursigtigheid**: 0 hou die agtergrond ondeursigtig; enige waarde bo 0 maak dit deursigtig
- **Steekinterval**: 200ms - 3000ms data verfrissingstempo
- **Lettergrootte**: 8 - 20 punte
- **Taal**: 103 tale, outomaties stelseltaal opspoor
- **Vertoonmetrieke**: Skakel elke metriek onafhanklik aan/uit
- **Vertoonformaat**: VRAM / geheue kan skakel tussen persentasie of werklike waardes
- **Outomatiese begin**: Hardloop outomaties by Windows aanmelding

## Tegnologie stapel

- **GUI**：Tkinter
- **Hardeware data**：LibreHardwareMonitorLib (deur pythonnet), psutil, pynvml (rugsteun vir NVIDIA GPU)
- **Stelselintegrasie**：pywin32 (venster altyd bo, outomatiese begin register)
- **Verpakking**：PyInstaller

## Projek struktuur

```
ChipPeek/
├── main.py                  # Ingangspunt
├── monitor_window.py        # Venster UI en interaksie logika
├── hardware_monitor.py      # Hardeware data versameling
├── config.py                # Konfigurasie bestuur
├── i18n.py                  # Internasionalisering
├── generate_docs.py
├── generate_icon.py         # Ikoon generasie skrip
├── admin.manifest           # UAC bestuurdersregte manifes
├── app.ico                  # Program ikoon
├── logo.png
├── requirements.txt         # Python afhanklikhede
├── build.bat
├── docs/                    # Veeltalige dokumentasie
│   └── README_*.md
├── i18n/                    # Vertaling lêers
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Geboude uitvoerbare lêer
```

## Konfigurasie lêer

`config.json` lêer word in dieselfde gids as `ChipPeek.exe` / `main.py` gestoor en bevat alle verstelbare instellings. Instellings word outomaties gestoor wanneer verander.

## Lisensie

[MIT License](../LICENSE)

## Ontwikkelaar

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projek URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Krediete

- LibreHardwareMonitor - Hardeware monitering biblioteek
- psutil - Kruis-platform stelsel monitering
- PyInstaller - Python verpakkingsgereedskap
