# ChipPeek

Erfaun monitro caledn Windows ysgafn.

> **Ieithoedd Eraill**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | **Cymraeg** | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Nodweddion

- **Monitro real-amser**: Amlder CPU, tymheredd CPU, amlder GPU, tymheredd GPU, defnydd VRAM, defnydd cof
- **Dau fodddangos**: Widget cornel / Bar brig, newid gydag un cliciad
- **Dangos addasadwy**: Dewiswch yn rhydd pa fesurau i'w dangos, newid rhwng canran/gwerthoedd gwirioneddol
- **Ar bob tro ar frig**: Yn aros uwchben pob ffenestr. Mae gwelededd sgrin lawn yn dibynnu ar yr ap a’r modd arddangos
- **Maint awtomatig**: Lled y ffenestr yn addasu'n awtomatig i gyd-fynd â'r cynnwys
- **Arddull addasadwy**: Tryloywder ffenestr, tryloywder cefndir, maint ffont i gyd yn addasadwy
- **Cefnogaeth amlieithog**: 103 iaith, yn canfod iaith y system yn awtomatig
- **Gweithred hudol**: Llusgo chwith i symud, dewislen clic dde ar gyfer gosodiadau cyflym, cysgodi'n awtomatig i gyrion y sgrin
- **Samplu addasadwy**: 200ms - 3000ms yn addasadwy
- **Cychwyn gyda'r system**: Cychwyn'n awtomatig wrth fewngofnodi i Windows
- **Defnydd adnoddau isaf**: Troedfedd lleiaf yn y cefndir

## Cychwyn Cyflym

### Defnyddio'n Uniongyrchol

Lawrlwythwch [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) a chlicio dwbl i'w redeg (bydd yn gofyn am hawliau gweinyddol yn awtomatig ar gyfer darllen tymheredd CPU ac amlder gywir).

### Redeg o'r Ffynhonnell

```powershell
# Clonio'r storfa
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Gosod dibenniadau
python -m pip install -r requirements.txt pythonnet

# Rhedeg
python main.py
```

## Gofynion System

- Windows 10 / Windows 11
- Hawliau gweinyddol (argymhorol), fel arall gall tymheredd CPU ac amlder gywir ddim bod ar gael
- .NET Framework 4.7.2 neu uwch (angen gan LibreHardwareMonitor)
- Python 3 + Tkinter (Redeg o'r Ffynhonnell)

## Begu'n EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Ar ôl i'r adeilad gwblhau, mae'r ffeil EXE yn `dist/ChipPeek.exe`.

## Defnydd

### Gweithrediadau Sylfaenol

| Gweithred | Disgrifiad |
|------|------|
| Llusgo chwith | Symud safle'r ffenestr |
| Clic dde | Agor dewislen (newid modd / gosodiadau / gadael) |
| Cysgodi awtomatig | Yn cysgodi'n awtomatig o fewn 20px o gyrion y sgrin |

### Moddau Dangos

- **Widget Cornel**: Pob mesur wedi'i threfnu'n fertigol, gellir ei roi mewn unrhyw gornel o'r sgrin
- **Bar Brig**: Pob mesur wedi'i threfnu'n lorweddol, wedi'i ganolbrychu ar frig y sgrin yn ddiofyn

### Gosodiadau

- **Modd dangos**: Widget cornel / Bar brig
- **Lleoliad y widget**: Dde'r gwaelod / Chwith y gwaelod / Dde'r brig / Chwith y brig
- **Tryloywder y ffenestr**: Mae’r llithrydd 0% - 100% yn cyfateb i ddidreiddedd ffenestr o 100% - 15%
- **Tryloywder y cefndir**: Mae 0 yn cadw’r cefndir yn afloyw; mae unrhyw werth dros 0 yn ei wneud yn dryloyw
- **Ymweliad samplu**: 200ms - 3000ms cyflymder adnewyddu data
- **Maint y ffont**: 8 - 20 pwynt ffont
- **Iaith**: 103 iaith, yn canfod iaith y system yn awtomatig
- **Mesurau dangos**: Toglo pob mesur yn annibynnol
- **Fformat dangos**: VRAM / Cof gall newid rhwng canran neu werthoedd gwirioneddol
- **Cychwyn gyda'r system**: Rhedeg yn awtomatig wrth fewngofnodi i Windows

## Tech Stack

- **GUI**：Tkinter
- **Data caledn**：LibreHardwareMonitorLib (trwy pythonnet), psutil, pynvml (GPU NVIDIA wrth gefn)
- **Integreiddio system**：pywin32 (ffenestr ar frig, cofrestriad cychwyn awtomatig)
- **Pecynnu**：PyInstaller

## Strwythur y Prosiect

```
ChipPeek/
├── main.py                  # Pwynt mynediad
├── monitor_window.py        # UI ffenestr a rhesymeg rhyngweithio
├── hardware_monitor.py      # Casglu data caledn
├── config.py                # Rheoli gosodiadau
├── i18n.py                  # Rhyngwladoli
├── generate_docs.py
├── generate_icon.py         # Sgript cynhyrchu eicon
├── admin.manifest           # Maniffest hawliau gweinyddol UAC
├── app.ico                  # Eicon y rhaglen
├── logo.png
├── requirements.txt         # Dibenniadau Python
├── build.bat
├── docs/                    # Dogfennau amlieithog
│   └── README_*.md
├── i18n/                    # Ffeiliau cyfieithu
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # DLL LibreHardwareMonitorLib
└── dist/
    └── ChipPeek.exe         # Gweithrediad wedi'i grynhoi
```

## Ffeil Ffurfwedd

Mae'r ffeil `config.json` wedi'i chadw yn yr un cyfeiriadur â'r `ChipPeek.exe` / `main.py`, gan gynnwys pob gosodiad addasadwy. Mae gosodiadau'n cael eu cadw'n awtomatig pan fyddant yn cael eu newid.

## Trwydded

[MIT License](../LICENSE)

## Datblygydd

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL y Prosiect: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Diolchiadau

- LibreHardwareMonitor - Llyfrgell monitro caledn
- psutil - Monitro system draws-ffurflen
- PyInstaller - Erfyn pecynnu Python
