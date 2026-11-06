# ChipPeek

Viegli peldošs aparatūras monitoringa logrīks Windows operētājsistēmai.

> **Citas valodas**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | **Latviešu** | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Iespējas

- **Monitorings reālajā laikā**: CPU frekvence, CPU temperatūra, GPU frekvence, GPU temperatūra, VRAM izmantošana, atmiņas izmantošana
- **Divu attēlošanas režīmi**: stūra logrīks / augšējā josla, pārslēgšana ar vienu klikšķi
- **Pielāgojama attēlošana**: brīvi izvēlieties, kurus rādītājus rādīt, pārslēdziet starp procentiem/reāliem vērtībām
- **Vienmēr priekšplānā**: paliek virs visām logiem. Redzamība pilnekrāna režīmā ir atkarīga no lietotnes un attēlošanas režīma
- **Automātiska izmērs**: loga platums automātiski pielāgojas saturam
- **Regulējams stils**: loga caurspīdīgums, fona caurspīdīgums, fonta lielums - viss ir regulējams
- **Daudzvalodu atbalsts**: 103 valodas, automātiski noteik sistēmas valodu
- **Ērti darbība**: pārvietojiet, velkot ar kreiso pogu, labās pogas izvēlne ātrai iestatīšanai, automātiskā pieķeršanās ekrāna malām
- **Konfigurējama izlases frekvence**: 200ms - 3000ms regulējama
- **Automātiska palaišana**: palaižas automātiski, pieslēdzoties Windows
- **Zems resursu patēriņš**: minimāls atmiņas apjoms fona režīmā

## Ātrais sākums

### Tieša lietošana

Lejupielādējiet [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) un veiciet dubultklikšķi, lai palaistu (automātiski pieprasīs administratora tiesības CPU temperatūrai un precīzai frekvences nolasīšanai).

### Palaist no pirmkoda

```powershell
# Klonējiet repozitoriju
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instalējiet atkarības
python -m pip install -r requirements.txt pythonnet

# Palaidiet
python main.py
```

## Sistēmas prasības

- Windows 10 / Windows 11
- Administratora tiesības (ieteicams), pretējā gadījumā CPU temperatūra un precīza frekvence var nebūt pieejamas
- .NET Framework 4.7.2 vai jaunāks (nepieciešams LibreHardwareMonitor)
- Python 3 + Tkinter (Palaist no pirmkoda)

## Sastādīt kā EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Pēc sastādīšanas EXE fails atrodas `dist/ChipPeek.exe`.

## Lietošana

### Pamata darbības

| Darbība | Apraksts |
|------|------|
| Velkšana ar kreiso pogu | Loga pozīcijas pārvietošana |
| Labā poga | Izvēlnes atvēršana (režīma maiņa / iestatījumi / iziet) |
| Automātiskā pieķeršanās | Automātiski pieķeras 20px attālumā no ekrāna malām |

### Attēlošanas režīmi

- **Stūra logrīks**: visi rādītāji izkārtoti vertikāli, var izvietot jebkurā ekrāna stūrī
- **Augšējā josla**: visi rādītāji izkārtoti horizontāli, pēc noklusējuma centrēti ekrāna augšdaļā

### Iestatījumi

- **Attēlošanas režīms**: stūra logrīks / augšējā josla
- **Logrīka pozīcija**: pa labi apakšā / pa kreisi apakšā / pa labi augšā / pa kreisi augšā
- **Loga caurspīdīgums**: Slīdnis 0% - 100% atbilst loga necaurspīdīgumam 100% - 15%
- **Fona caurspīdīgums**: 0 saglabā fonu necaurspīdīgu; jebkura vērtība virs 0 padara to caurspīdīgu
- **Izlases intervāls**: 200ms - 3000ms datu atjaunināšanas ātrums
- **Fonta lielums**: 8 - 20 punkti
- **Valoda**: 103 valodas, automātiski noteik sistēmas valodu
- **Attēlojāmie rādītāji**: katru rādītāju var neatkarīgi ieslēgt/izslēgt
- **Attēlošanas formāts**: VRAM / Atmiņa var pārslēgties starp procentiem vai reāliem vērtībām
- **Automātiska palaišana**: automātiski palaist, pieslēdzoties Windows

## Tehnoloģiju steka

- **GUI**：Tkinter
- **Aparatūras dati**：LibreHardwareMonitorLib (izmantojot pythonnet), psutil, pynvml (NVIDIA GPU rezerves variants)
- **Sistēmas integrācija**：pywin32 (logs vienmēr priekšplānā, automātiskās palaišanas reģistrs)
- **Iepakošana**：PyInstaller

## Projekta struktūra

```
ChipPeek/
├── main.py                  # Ieejas punkts
├── monitor_window.py        # Loga UI un mijiedarbības loģika
├── hardware_monitor.py      # Aparatūras datu vākšana
├── config.py                # Konfigurācijas pārvaldība
├── i18n.py                  # Internacionalizācija
├── generate_docs.py
├── generate_icon.py         # Ikonu ģenerēšanas skripts
├── admin.manifest           # UAC administratora tiesību manifests
├── app.ico                  # Lietotnes ikona
├── logo.png
├── requirements.txt         # Python atkarības
├── build.bat
├── docs/                    # Daudzvalodu dokumentācija
│   └── README_*.md
├── i18n/                    # Tulkošanas faili
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompilēts izpildāmais fails
```

## Konfigurācijas fails

Fails `config.json` tiek saglabātā tajā pašā mapē kā `ChipPeek.exe` / `main.py` un satur visus regulējamos iestatījumus. Iestatījumi tiek saglabāti automātiski, tie tiek mainīti.

## Licence

[MIT License](../LICENSE)

## Izstrādātājs

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekta URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Pateicības

- LibreHardwareMonitor - Aparatūras monitoringa bibliotēka
- psutil - Starpplatformu sistēmas monitorings
- PyInstaller - Python iepakšanas rīks
