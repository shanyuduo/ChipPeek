# ChipPeek

Eitt lætt Windows tól til vélbúnaðareftirlit.

> **Onnur mál**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | **Føroyskt** | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Eginleikar

- **Skjótt eftirlit**: CPU tíðni, CPU hiti, GPU tíðni, GPU hiti, VRAM nýtsla, minnisnýtsla
- **Tveir vísingarhættir**: Hornisforrit / Toppstong, við einum klikki skift
- **Tillagað sýn**: Vel frítt hvørjar mátar vísast, skift millum prosent/tilverðingar virði
- **Altíð omaná**: Ver omaná øllum gluggum. Sýnileiki á fullum skíggja er treytaður av forritinum og vísingarháttinum
- **Sjálvbæri stødd**: Gluggabreidd stillar sjálv til at mát innihald
- **Tillagað útsjónd**: Gluggaógjøgnsægd, bakgrunnsgjøgnsægd, stavastødd øll tillægjing
- **Fleirmála stuðul**: 103 mál, finur sjálv verkætlanarmál
- **Nýtilig handil**: Vinstra drag at flyta, høgra klikk valmynd fyri skjótar stillingar, sjálvfest at skíggjabrúnunum
- **Tilligibar sýnishorn**: 200ms - 3000ms stillibar
- **Sjálvbyrjan**: Byrja sjálv tá Windows innritar
- **Lítil tilfeingi nýtsla**: Lætt í bakgrunninum

## Skjótt at byrja

### Beinir nýtsla

Tak niður [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) og tvíklikk fyri at koyra (krevur sjálvbyrjan fyri CPU hita og neyvar tíðni lesing).

### Koyr frá keldu

```powershell
# Clone the repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Install dependencies
python -m pip install -r requirements.txt pythonnet

# Run
python main.py
```

## Skipanarkrav

- Windows 10 / Windows 11
- Fyrisitararættindi (viðmælt), annars kunnu CPU hiti og neyvar tíðni ikki verða tøk
- .NET Framework 4.7.2 ella hægri (krevst av LibreHardwareMonitor)
- Python 3 + Tkinter (Koyr frá keldu)

## Bygg sum EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Eftir bygging er EXE fílan í `dist/ChipPeek.exe`.

## Nýtsla

### Grundleggjandi gerðir

| Gerð | Frágreiðing |
|------|------|
| Vinstra drag | Flyt gluggastað |
| Høgra klikk | Opna valmynd (skift hátt / stillingar / lat aftur) |
| Sjálvfest | Festist sjálvt innan 20px av skíggjabrúnum |

### Vísingarhættir

- **Hornisforrit**: Øll mátir í loddrøtt, kann setast í nøkrum hvørjum skíggjahorni
- **Toppstong**: Øll mátir í vørrøtt, miðað í toppinum av skíggjanum sjálvsagt

### Stillingar

- **Vísingarháttur**: Hornisforrit / Toppstong
- **Forritastaður**: Niðri til høgru / Niðri til vinstru / Uppi til høgru / Uppi til vinstru
- **Gluggaógjøgnsægd**: Rennarin 0% - 100% svarar til ógjøgnumskygni í vindeyganum á 100% - 15%
- **Bakgrunnsgjøgnsægd**: 0 heldur bakgrundina ógjøgnumskygda; øll virði oman fyri 0 gera hana gjøgnumskygda
- **Sýnishornabil**: 200ms - 3000ms dátuendurnýggjanartíðni
- **Stavastødd**: 8 - 20 punkts stavar
- **Mál**: 103 mál, finur sjálv verkætlanarmál
- **Vísingarmátar**: Kvik hvønn mát sjálvstætt
- **Vísingarformat**: VRAM / Minni kann skiftast millum prosent ella tilverðingar virði
- **Sjálvbyrjan**: Koyr sjálv tá í Windows verður innritað

## Tøkni

- **GUI**：Tkinter
- **Vélbúnaðardáta**：LibreHardwareMonitorLib (við pythonnet), psutil, pynvml (NVIDIA GPU fallback)
- **Skipanarsambling**：pywin32 (glugga_ovast, sjálvbyrjan skráseting)
- **Pakking**：PyInstaller

## Verkætlanaruppbygging

```
ChipPeek/
├── main.py                  # Innleiðingarpunktur
├── monitor_window.py        # Glugga UI og samhandlingarlogikkur
├── hardware_monitor.py      # Vélbúnaðardátuinsavning
├── config.py                # Samansetingarfyrisiting
├── i18n.py                  # Altjóðagerð
├── generate_docs.py
├── generate_icon.py         # Íkonagerðarskripta
├── admin.manifest           # UAC fyrisitararættindislisti
├── app.ico                  # Forritsíkon
├── logo.png
├── requirements.txt         # Python tilfeingi
├── build.bat
├── docs/                    # Fleirmáladokumentir
│   └── README_*.md
├── i18n/                    # Þýðingarfílur
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Bygd koyrifíla
```

## Samansetingarfíla

`config.json` fílan er goymd í somu skjátt sum `ChipPeek.exe` / `main.py`, innihaldandi allar stillibar stillingar. Stillingar verða goymdar sjálvar tá ið tær verða broyttar.

## Loyvi

[MIT License](../LICENSE)

## Mennari

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Verkætlanar URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Takk til

- LibreHardwareMonitor - Vélbúnaðareftirlitsbókasavn
- psutil - Tvørskipanareftirlit
- PyInstaller - Python pakkingsamboð
