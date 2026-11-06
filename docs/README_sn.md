# ChipPeek

Software yakaderera yokutarira hardware yeWindows.

> **Mimwe Mitauro**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | **chiShona** | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Zvinoitwa

- **Kutarira pachena**: Frequency CPU, kudziya CPU, frequency GPU, kudziya GPU, kushandiswa VRAM, kushandiswa ndangariro
- **Mamiriro maviri ekutaridza**: Widget yekona / Bar pamusoro, kushandura nokubaya kamwe
- **Kutaridza kunogadzirwa**: Sarudza zvaunoda kutaridza, shandura pakati pezvigamu/huwandu hw chaihwo
- **Kugara pamusoro**: Chigara pamusoro pemafensteri ose. Kuonekwa pachidzitiro chizere kunoenderana neapp uye maratidzirwo acho
- **Kukura kwoga**: Hupamhi hwefensteri hunoshanduka hwoga hwokwana zvakataridzwa
- **Mamiriro anogadzirwa**: Kuoneka kwefensteri, kujeka kwebackdrop, kukura kwefonti - zvose zinogadzirwa
- **Rutsigiro rwemitauro mizhinji**: Mitauro 103, inotarira mutauro wesystem
- **Kushanda nyore**: Bata kuruboshwe kuti utaure, bayo kurudyo kwemenu yekukurumidza, snapper zvoga kumucheto weskreeni
- **Frequency yosampling inogadzirwa**: 200ms - 3000ms inogadzirwa
- **Kutanga zvoga**: Tangira zvoga paunopinda muWindows
- **Kushandiswa kwakaderera kwesimba**: Hakuna kushandiswa kwakanyanya kumashure

## Kutanga Kukurumidza

### Kushandisa Chikwangwani

Tora [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) uye ubaye kabiri kuti utange (uchangobvunza kodzero dzeadmin nokuda kwekudziya CPU nekufamba kwakati kwete frequency).

### Kumhanya kubva kuSource

```powershell
# Tora repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Isa dependencies
python -m pip install -r requirements.txt pythonnet

# Mhanya
python main.py
```

## Zvinodiwa nesystem

- Windows 10 / Windows 11
- Kodzero dzeadmin (zinokurudzirwa), pasina izvo kudziya CPU nefrequency chaiyo hazvigone kuwanikwa
- .NET Framework 4.7.2 kana kupfuura (inodiwa neLibreHardwareMonitor)
- Python 3 + Tkinter (Kumhanya kubva kuSource)

## Vaka saEXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Mushure mekuvakwa, faira reEXE rinowanikwa ku `dist/ChipPeek.exe`.

## Kushandiswa

### Mabasa Ekutanga

| Chiito | Tsananguro |
|------|------|
| Bata kuruboshwe | Taura fensteri |
| Baya kurudyi | Vhura menu (shandura mamiriro / marongero / buda) |
| Snapper zvoga | Huzviho hoga mukati ma20px kumucheto weskreeni |

### Mamiriro Ekutaridza

- **Widget yekona**: Mitambo yose mitsvi-yotsva, inogona kuiswa kukona kose kweskreeni
- **Bar pamusoro**: Mitambo yose yakati-dzvanya, yaiswa pakati pamusoro peskreeni

### Marongero

- **Mamiriro ekutaridza**: Widget yekona / Bar pamusoro
- **Kwakatariswa widget**: Pasi kurudyi / Pasi kuruboshwe / Pamusoro kurudyi / Pamusoro kuruboshwe
- **Kuoneka kwefensteri**: Slider ye0% - 100% inoenderana nekusajeka kwehwindo kwe100% - 15%
- **Kujeka kwebackdrop**: 0 inoita kuti zvisazoonekwa nepakati pemashure; chero nhamba inopfuura 0 inoita kuti paonekwe nepakati
- **Nharo yosampling**: 200ms - 3000ms kuchingorukwa kwedata
- **Kukura kwefonti**: 8 - 20 pfundo yefonti
- **Mutauro**: Mitauro 103, inotarira mutauro wesystem
- **Mitambo yekutaridza**: Vhura/vala yega yega mitambo
- **Mamiriro ekutaridza**: VRAM / Ndangariro inogona kushandurwa pakati pezvigamu kana huwandu chaihwo
- **Kutanga zvoga**: Tanga zvoga paunopinda muWindows

## Stack yeTechnique

- **GUI**：Tkinter
- **Data yehardware**：LibreHardwareMonitorLib (kuburikidza ne pythonnet), psutil, pynvml (GPU NVIDIA fallback)
- **Kubatanidza kwesystem**：pywin32 (fensteri pamusoro, kutanga zvoga registry)
- **Kuputira**：PyInstaller

## Kuverenga kweProjekiti

```
ChipPeek/
├── main.py                  # Pekutangira
├── monitor_window.py        # UI yefensteri nendima yekubatana
├── hardware_monitor.py      # Kuunganidza data yehardware
├── config.py                # Kugadzirwa kwemarongero
├── i18n.py                  # Kuvandudzwa kwemitauronyina
├── generate_docs.py
├── generate_icon.py         # Script yekugadzira icon
├── admin.manifest           # Manifest yekodzero dzeadmin UAC
├── app.ico                  # Icon yepurogiramu
├── logo.png
├── requirements.txt         # Dependencies dzaPython
├── build.bat
├── docs/                    # Magwaro emitauro mizhinji
│   └── README_*.md
├── i18n/                    # Mafaira ekududzura
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Executable yakavakwa
```

## Faira reConfiguration

Faira `config.json` rinochengetedzwa muchiyenzanita chine `ChipPeek.exe` / `main.py`, rine marongero ose anogadzirwa. Marongero anochengetedzwa zvoga paanoshandurwa.

## Layisensi

[MIT License](../LICENSE)

## Gadziri

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL yeProjekiti: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kutenda

- LibreHardwareMonitor - Laibhurari yekutarira hardware
- psutil - Kutarira kwesystem kunowedzerwa mapuratifomu
- PyInstaller - Fita yekuputira mapeji ePython
