# ChipPeek

Igikoresho cyoroshye cyo kugenzura hardware ya Windows kigarambuje.

> **Indimi Zindi**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | **Kinyarwanda** | [Soomaali](README_so.md)

## Ibiranga

- **Kugenzura mu gihe nyacyo**: Ubwisubire bwa CPU, ubushyuhe bwa CPU, ubwisubire bwa GPU, ubushyuhe bwa GPU, imikoreshereze VRAM, imikoreshereze y'umwanya w'ibyibutsa
- **Imiterere ibiri yo kugaragaza**: Widget y'ifuruka / Bar yo hejuru, hindura nk'ukanda kimwe
- **Kugaragaza byihariye**: Hitamo uko ushaka ibimenyetso byo kugaragaza, hindura hagati y'imijana/indangagaciro nyayo
- **Kuma hejuru buri gihe**: Kuma hejuru y'udirishya hose. Kugaragara kuri ekara yose biterwa na porogaramu n’uburyo bwo kwerekana
- **Ingano ihita ihinduka**: Ubugari bwa window bwihita bumikana n'ibikubiyemo
- **Imisusire ishobora guhindurwa**: Ubumukye bwa window, ubumukye bwa mbuganyuma, ingano y'umwandiko - byose byahindurwa
- **Gufasha indimi nyinshi**: Indimi 103, ifata ururimi rwa sistemu mu buryo bwikora
- **Imikorerere myiza**: Kurura ibumoso himura window, kanda iburyo ku menu y'igenamiterere ihuta, afata ku mpera z'ekrani
- **Intera yo gusampura ishobora guhindurwa**: 200ms - 3000ms ishobora guhindurwa
- **Gutangira byikora**: Tangira byikora ugize winjira muri Windows
- **Imikoreshereze y'ibikorwa mike**: Imyanda muto mu mbuganyuma

## Gutangira Vuba

### Gukoresha Mvugo

Kura [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) ukande kabiri kugira ngo utangire (bizasaba uburenganzira bwa admin ku bushyuhe bwa CPU no gusoma ubwisubire bw'icyo aricyo).

### Gukoresha Uhereye ku Source

```powershell
# Fata repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Shyira dependencies
python -m pip install -r requirements.txt pythonnet

# Tangira
python main.py
```

## Ibisabwa bya Sisitemu

- Windows 10 / Windows 11
- Uburenganzira bwa admin (byifuzwa), bitabaye ibyo ubushyuhe bwa CPU n'ubwisubire bw'icyo aricyo bishobora kubura
- .NET Framework 4.7.2 cyangwa hejuru (bisabwa na LibreHardwareMonitor)
- Python 3 + Tkinter (Gukoresha Uhereye ku Source)

## Vaka nka EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Nyuma yo kuvuka, dosiye EXE iri kuri `dist/ChipPeek.exe`.

## Ikoreshwa

### Ibikorwa By'ibanze

| Igikorwa | Ubusobanuro |
|------|------|
| Kurura ibumoso | Himura window |
| Kanda iburyo | Fungura menu (hindura uburyo / igenamiterere / sohoka) |
| Afata byikora | Afata byikora mu mpeshyi 20px ku mpera z'ekrani |

### Uburyo bwo Kugaragaza

- **Widget y'ifuruka**: Ibyerekana byose bibe ahagana-y'umutambike, bishobora gushyirwa ku nkokora zose z'ekrani
- **Bar yo hejuru**: Ibyerekana byose bibe ahagana-y'umutambanyatso, bisanzwe bibe hagati hejuru y'ekrani

### Igenamiterere

- **Uburyo bwo kugaragaza**: Widget y'ifuruka / Bar yo hejuru
- **Ahari widget**: Hasi iburyo / Hasi ibumoso / Hejuru iburyo / Hejuru ibumoso
- **Ubumukye bwa window**: Agakoresho ko kunyerera ka 0% - 100% gahura no kutabonerana kw’idirishya bwa 100% - 15%
- **Ubumukye bwa mbuganyuma**: 0 ituma inyuma hatabonerana; agaciro kose karenze 0 gatuma habonerana
- **Intera yo gusampura**: 200ms - 3000ms vuba yo kugenzura amakuru
- **Ingano y'umwandiko**: 8 - 20 inota y'umwandiko
- **Ururimi**: Indimi 103, ifata ururimi rwa sistemu mu buryo bwikora
- **Ibimenyetso byo kugaragaza**: Fungura/Sara bimenyetso buri kimwe
- **Imiterere yo kugaragaza**: VRAM / Umwanya w'ibyibutsa bishobora guhindurwa hagati y'imijana cyangwa indangagaciro nyayo
- **Gutangira byikora**: Tangira byikora winjira muri Windows

## Stack ya Tekinike

- **GUI**：Tkinter
- **Ibyatanzwe bya hardware**：LibreHardwareMonitorLib (biturutse kuri pythonnet), psutil, pynvml (GPU NVIDIA fallback)
- **Kuvanga sisitemu**：pywin32 (window hejuru, gutangira byikora registry)
- **Gufata mu gisubizo**：PyInstaller

## Imiterere ya Proje

```
ChipPeek/
├── main.py                  # Ahantu hatangirira
├── monitor_window.py        # UI ya window n'umvikano
├── hardware_monitor.py      # Gufata ibyatanzwe bya hardware
├── config.py                # Gucunga ibonezwa
├── i18n.py                  # Kwimurura indimi
├── generate_docs.py
├── generate_icon.py         # Inyandiko nkoranyambuso yo kurema icon
├── admin.manifest           # Manifest y'uburenganzira admin UAC
├── app.ico                  # Icon ya porogaramu
├── logo.png
├── requirements.txt         # Dependencies ya Python
├── build.bat
├── docs/                    # Inyandiko z'indimi nyinshi
│   └── README_*.md
├── i18n/                    # Dosiye zo guhindura indimi
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Executable yubatswe
```

## Dosiye ya Configuration

Dosiye `config.json` irabibitswe mu bubiko bumwe na `ChipPeek.exe` / `main.py`, ifite ibonezwa byose bishobora guhindurwa. Ibonezwa birabibitswa byikora byahinduwe.

## Lisini

[MIT License](../LICENSE)

## Umuhanzi

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL ya Proje: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Amashimwe

- LibreHardwareMonitor - Isomero ryo kugenzura hardware
- psutil - Kugenzura sisitemu kuri puratifomu zose
- PyInstaller - Igikoresho cyo gufata Python mu gisubizo
