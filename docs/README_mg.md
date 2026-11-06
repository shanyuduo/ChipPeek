# ChipPeek

Fitaovana maivana fanaraha-maso hardware Windows mivelatra.

> **Fiteny Hafa**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | **Malagasy** | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Toetra

- **Fanaraha-maso tena izy**: Hatingan'ny CPU, hafanana CPU, hatingan'ny GPU, hafanana GPU, fampiasana VRAM, fampiasana fitadidiana
- **Fomba fampisehoana roa**: Widget eny zoro / Bar ambony, ovaina amin'ny tsindry iray
- **Fampisehoana azo ovaina**: Mifidy malalaka izay tondro aseho, mifanakalo isan-jato/sanda tena izy
- **Mijanona ambony indrindra**: Mijanona ambonin'ny window rehetra. Ny fahitana amin’ny efijery feno dia miankina amin’ny rindranasa sy ny fomba fampisehoana
- **Haben'ny mifanaraka**: Ny haben'ny window dia mifanaraka ho azy amin'ny atiny
- **Endrika azo ovaina**: Tsy fahavitrehana'ny window, fahavitrehana afara, haben'ny soratra rehetra azo ovaina
- **Fanohanana fiteny maro**: Fiteny 103, mamonjy ho azy ny fitenin'ny system
- **Asa mora**: Tsindrio havia finday, tsindrio havanana ho an'ny menu haingana, mihodina ho azy eo amin'ny sisin'ny efijery
- **Sampling azo ovaina**: 200ms - 3000ms azo ovaina
- **Fanombohana ho azy**: Atombohy ho azy rehefa miditra amin'ny Windows
- **Fampiasana loharano ambany**: Tsy mavesatra eo amin'ny background

## Fiantombohana Haingana

### Fampiasana Mivantana

Alao [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) ary tsindrio indroa hijerena (hangataka ho azy alalana'ny admin ho an'ny hafanana CPU sy famakiana hatingana marina).

### Mandeha avy amin'ny Source

```powershell
# Makà ilay repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Ampidiro ny dependencies
python -m pip install -r requirements.txt pythonnet

# Mihazà
python main.py
```

## Fepetra System

- Windows 10 / Windows 11
- Alalana'ny admin (atoro), raha tsia izany dia mety tsy ho azo ny hafanana CPU sy hatingana marina
- .NET Framework 4.7.2 na ambony (ilain'ny LibreHardwareMonitor)
- Python 3 + Tkinter (Mandeha avy amin'ny Source)

## Manangà EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Rehefa vita ny fananganana, ny rakitra EXE dia ao amin'ny `dist/ChipPeek.exe`.

## Fampiasana

### Asa Fototra

| Asa | Famaritana |
|------|------|
| Tsindrio havia finday | Finday toeran'ny window |
| Tsindrio havanana | Sokafy menu (ovay fomba / fitantanana / hiala) |
| Hodina ho azy | Mihodina ho azy ao anatin'ny 20px amin'ny sisin'ny efijery |

### Fomba Fampisehoana

- **Widget eny zoro**: Tondro rehetra mitsangana, azo apetraka amin'ny zoro rehetra'ny efijery
- **Bar ambony**: Tondro rehetra mivelatra, apetraka afovoany ambonin'ny efijery

### Fitantanana

- **Fomba fampisehoana**: Widget eny zoro / Bar ambony
- **Toerana widget**: Ambany havanana / Ambany havia / Ambony havanana / Ambony havia
- **Tsy fahavitrehana window**: Ny slider 0% - 100% dia mifanaraka amin’ny tsy fahatanterahan’ny hazavana amin’ny varavarankely 100% - 15%
- **Fahavitrehana afara**: 0 mitazona ny lafika tsy mangarahara; ny sanda mihoatra ny 0 dia mahatonga azy ho mangarahara
- **Elanelam-potoana sampling**: 200ms - 3000ms hafainganam-pamahana data
- **Haben'ny soratra**: 8 - 20 teboka soratra
- **Fiteny**: Fiteny 103, mamonjy ho azy ny fitenin'ny system
- **Tondro aseho**: Afindra tsirairay ny tondro tsirairay
- **Endrika fampisehoana**: VRAM / Fitadidiana dia azo ovaina amin'ny isan-jato na sanda tena izy
- **Fanombohana ho azy**: Mihazà ho azy rehefa miditra amin'ny Windows

## Stack Technique

- **GUI**：Tkinter
- **Data hardware**：LibreHardwareMonitorLib (amin'ny pythonnet), psutil, pynvml (GPU NVIDIA fallback)
- **Fampivondronana system**：pywin32 (window ambony indrindra, fanombohana ho azy registry)
- **Fonosana**：PyInstaller

## Lafin'ny Tetikasa

```
ChipPeek/
├── main.py                  # Tobim-pidirana
├── monitor_window.py        # UI window sy logika fifandraisana
├── hardware_monitor.py      # Fanangona data hardware
├── config.py                # Fitantanana configuration
├── i18n.py                  # I18n
├── generate_docs.py
├── generate_icon.py         # Script famoronana icon
├── admin.manifest           # Manifest alalana admin UAC
├── app.ico                  # Icon application
├── logo.png
├── requirements.txt         # Dependencies Python
├── build.bat
├── docs/                    # Tatitra fiteny maro
│   └── README_*.md
├── i18n/                    # Rakitra fandikana
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Executable voaangona
```

## Rakitra Configuration

Ny rakitra `config.json` dia voatahiry ao amin'ny lahatahiry mitovy amin'ny `ChipPeek.exe` / `main.py`, misy ny fitantanana rehetra azo ovaina. Voatahiry ho azy ny fitantanana rehefa ovaina.

## Lisansa

[MIT License](../LICENSE)

## Mpamorona

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL Tetikasa: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Misaotra

- LibreHardwareMonitor - Rian-trano fanaraha-maso hardware
- psutil - Fanaraha-maso system amin'ny plateformes rehetra
- PyInstaller - Fitaovana fonosana Python
