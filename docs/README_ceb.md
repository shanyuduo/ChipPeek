# ChipPeek

Usa ka gamay nga himo sa pagbantay sa hardware sa Windows.

> **Ubang mga Pinulongan**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | **Cebuano** | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Mga Bahandi

- **Real-time nga pagbantay**: Frequency sa CPU, temperatura sa CPU, frequency sa GPU, temperatura sa GPU, pag-gamit sa VRAM, pag-gamit sa memory
- **Duha ka mode sa pagpakita**: Widget sa suuk / Bar sa taas, usa ka klik ibalhin
- **Pagpakita nga mahimo masal-an**: Mahimo pilion unsa nga metrik ang ipakita, ibalhin ang persentase/aktwal nga bili
- **Kanunay sa ibabaw**: Magpabilin sa ibabaw sa tanan nga window. Ang pagkakita sa tibuok screen nagdepende sa app ug display mode
- **Auto-sukod**: Ang gilapdon sa window awtomatik nga mosukod sumala sa sulod
- **Estilo nga mahimo masal-an**: Opacity sa window, transparency sa background, gidak-on sa font tanan mahimo masal-an
- **Suporta sa daghang pinulongan**: 103 nga pinulongan, awtomatik nga pangitaon ang pinulongan sa sistema
- **Sayon nga operasyon**: Biraha sa wala aron ibalhin, right-click alang sa menu, auto snap sa kilid sa screen
- **Sampling nga mahimo masal-an**: 200ms - 3000ms
- **Auto start**: Awtomatik nga magsugod kung mo-login sa Windows
- **Gamay nga pag-gamit sa recurso**: Minimal nga footprint sa background

## Dali nga Pagsugod

### Direkta nga Paggamit

I-download ang [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) ug double-click aron modagan (awtomatik nga mangayo sa admin privileges alang sa pagbasa sa temperatura sa CPU ug tukma nga frequency).

### Modagan gikan sa Tinubdan

```powershell
# I-clone ang repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# I-install ang mga dependensi
python -m pip install -r requirements.txt pythonnet

# Modagan
python main.py
```

## Mga Kinahanglan sa Sistema

- Windows 10 / Windows 11
- Admin privileges (girekomendar), kon dili temperatura sa CPU ug tukma nga frequency mahimo dili magamit
- .NET Framework 4.7.2 o mas taas (gikinahanglan sa LibreHardwareMonitor)
- Python 3 + Tkinter (Modagan gikan sa Tinubdan)

## Himoon nga EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Human sa paghimo, ang EXE file makita sa `dist/ChipPeek.exe`.

## Pag-gamit

### Mga Basic nga Operasyon

| Aksyon | Deskripsyon |
|------|------|
| Bira sa wala | Ibalhin ang posisyon sa window |
| Right click | Ablihi ang menu (usba ang mode / settings / gikan) |
| Auto snap | Awtomatik nga snap sulod sa 20px gikan sa kilid sa screen |

### Mga Mode sa Pagpakita

- **Widget sa suuk**: Tanan metrik gihanay nga patindog, mahimo butangi sa bisan asa nga suuk sa screen
- **Bar sa taas**: Tanan metrik gihanay nga pahigda, default sa tunga sa ibabaw sa screen

### Mga Setting

- **Mode sa pagpakita**: Widget sa suuk / Bar sa taas
- **Posisyon sa widget**: Ubos too / Ubos wala / Taas too / Taas wala
- **Opacity sa window**: Ang slider nga 0% - 100% katumbas sa opacity sa bintana nga 100% - 15%
- **Transparency sa background**: Ang 0 magpabiling dili transparent ang background; bisan unsang labaw sa 0 maghimo niini nga transparent
- **Interval sa sampling**: 200ms - 3000ms pagsapang sa datos
- **Gidak-on sa font**: 8 - 20 ka puntos nga font
- **Pinulongan**: 103 nga pinulongan, awtomatik nga pangitaon ang pinulongan sa sistema
- **Metrik sa pagpakita**: Mahimo i-on/off ang matag metrik
- **Format sa pagpakita**: VRAM / Memory mahimo ibalhin tali sa persentase o aktwal nga bili
- **Auto start**: Awtomatik nga modagan kung mo-login sa Windows

## Stack sa Teknolohiya

- **GUI**：Tkinter
- **Data sa hardware**：LibreHardwareMonitorLib (pinaagi sa pythonnet), psutil, pynvml (backup alang sa NVIDIA GPU)
- **Integrasyon sa sistema**：pywin32 (window topmost, auto-start registry)
- **Packaging**：PyInstaller

## Istruktura sa Proyekto

```
ChipPeek/
├── main.py                  # Entry point
├── monitor_window.py        # UI sa window ug logika sa interaksyon
├── hardware_monitor.py      # Koleksyon sa datos sa hardware
├── config.py                # Maneho sa konfigurasyon
├── i18n.py                  # Internasyonalisasyon
├── generate_docs.py
├── generate_icon.py         # Skrip sa paghimo sa icon
├── admin.manifest           # Manifest sa UAC admin privilege
├── app.ico                  # Icon sa aplikasyon
├── logo.png
├── requirements.txt         # Mga dependensi sa Python
├── build.bat
├── docs/                    # Mga dokumento sa daghang pinulongan
│   └── README_*.md
├── i18n/                    # Mga file sa hubad
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Gikompila nga executable
```

## File sa Konfigurasyon

Ang file nga `config.json` gitago sa parehas nga direktoriya sa `ChipPeek.exe` / `main.py`, naglakip sa tanan nga masal-ang setting. Ang setting awtomatik nga gitago kung usbon.

## Lisensya

[MIT License](../LICENSE)

## Developer

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL sa Proyekto: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Mga Kredit

- LibreHardwareMonitor - Library sa pagbantay sa hardware
- psutil - Cross-platform nga pagbantay sa sistema
- PyInstaller - Himo sa packaging sa Python
