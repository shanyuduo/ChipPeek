# ChipPeek

Windows üçin ýeňil enjamçylyk synlagyň ýüzüp ýören widjeti.

> **Beýleki diller**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | **Türkmen** | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Aýratynlyklar

- **Realtime synlag**: CPU ýygylygy, CPU temperaturasy, GPU ýygylygy, GPU temperaturasy, VRAM ulanylyşy, çeper ulanylyşy
- **Iki görkezme tertibi**: Burç widjeti / Ýokarky panel, bir basmak bilen üýtgetmek
- **Özara görkezme**: Haýsy görkezijileri görkezmeli isigidiň saýlawy, göterim/hakyky bahalar arasynda üýtgetme
- **Hemişe ýokary**: Ähli ainalaryň üstünde galýar. Doly ekranda görünmek programma we görkeziş tertibine baglydyr
- **Awtomatik ululygy**: Ainaýn ini mazmuna laýyk awtomatiki sazlanýar
- **Sazlanýanç stili**: Aina şaffaflygy, arkaýyn şaffaflygy, şrift ululygy hemmesi sazlanýan
- **Köp dilli goldaw**: 103 dil, ulgam dilini awtomatiki anyklaýar
- **Aňsat hereket**: Çep süýşürmek bilen hereket, sag basmak menýu üçin çalt sazlamalar, ekranyň burçlaryna awtomatik ýapyşmak
- **Nemeg sazlamasy**: 200ms - 3000ms sazlanýan
- **Awtomatik başlatmak**: Windows girgende awtomatik başlaýar
- **Az serişde ulanmak**: Yzakynda iň az serişde ulanýar

## Çalt başlangyç

### Doly ulanylyşy

[`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest)-i ýükläň we iki gezek basyň (CPU temperaturasy we takyk ýygylygy okamak üçin awtomatik administrator hukuklaryny sorar).

### Çeşmeden işledip başlamak

```powershell
# Repozitoriýany klonlaň
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Baglylyklary ýerleşdiriň
python -m pip install -r requirements.txt pythonnet

# İşlediň
python main.py
```

## Ulam talaplary

- Windows 10 / Windows 11
- Administrator hukuklary (maslahat berilýär), bolmasa CPU temperaturasy we takyk ýygylygy elmygdama bolmaz
- .NET Framework 4.7.2 ýa-da has ýokary (LibreHardwareMonitor üçin gerekdir)
- Python 3 + Tkinter (Çeşmeden işledip başlamak)

## EXE hökmünde bina etmek

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Bina edilenden soň, EXE faýly `dist/ChipPeek.exe` ýerinde.

## Ulanylyşy

### Esasy hereketler

| Hereket | Düşündiriş |
|------|------|
| Çep süýşürmek | Ainäniň ýerini üýtgetmek |
| Sag basmak | Menýu açmak (tertibi üýtgetmek / sazlamalar / çykmak) |
| Awtomatik ýapyşmak | Ekranyň burçlarynyň 20px içinde awtomatik ýapyşmak |

### Görkezme tertipleri

- **Burç widjeti**: Ähli görkezijiler diklige görä tertiplenýär, ekranyň islendik burçunda ýerleşdirilip bilner
- **Ýokarky panel**: Ähli görkezjiler ýatmaga görä tertiplenýär, deslapky boýunça ekranyň ýokarky ortasynda

### Sazlamalar

- **Görkezme tertibi**: Burç widjeti / Ýokarky panel
- **Widjetiň ýeri**: Aşakda sag / Aşakda çep / Ýokaryda sag / Ýokaryda çep
- **Ainäň şaffaflygy**: 0% - 100% süýşürijisi penjiräniň 100% - 15% dury däldigine gabat gelýär
- **Arkaýyň şaffaflygy**: 0 fonuny dury däl saklaýar; 0-dan uly islendik baha ony dury edýär
- **Nemeg aralygy**: 200ms - 3000ms maglumat täzeleme tizligi
- **Şrift ululygy**: 8 - 20 nokat şrift
- **Dil**: 103 dil, ulgam dilini awtomatiki anyklaýar
- **Görkezme görkezijileri**: Her görkezijini aýratyn açyp/pes edilip bilner
- **Görkezme formaty**: VRAM / Çeper göterim ýa-da hakyky bahalarda üýtgedilip bilner
- **Awtomatik başlatmak**: Windows-a girende awtomatik işlejek

## Tehniki stek

- **GUI**：Tkinter
- **Enjamçylyk maglumat**：LibreHardwareMonitorLib (pythonnet arkaly), psutil, pynvml (NVIDIA GPU üçin)
- **Ulam integrasiýasy**：pywin32 (aina ýokarky, awtomatik başlatmak registri)
- **Paketlemek**：PyInstaller

## Proýekt gurluşy

```
ChipPeek/
├── main.py                  # Giriş nokady
├── monitor_window.py        # Aina UI we täsirleşme logikasy
├── hardware_monitor.py      # Enjamçylyk maglumat ýygnamak
├── config.py                # Sazlama dolandyryşy
├── i18n.py                  # Halkaraçylyk
├── generate_docs.py
├── generate_icon.py         # Nyşan döretmek skripti
├── admin.manifest           # UAC administrator hukuklary manifesti
├── app.ico                  # Proýekt nyşany
├── logo.png
├── requirements.txt         # Python baglylyklary
├── build.bat
├── docs/                    # Köp dilli resminamalar
│   └── README_*.md
├── i18n/                    # Terjime faýllary
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Bina edilen ýerine ýetiriji
```

## Sazlama faýly

`config.json` faýly `ChipPeek.exe` / `main.py` bilen bir katalogda saklanýar, ähli sazlanýan sazlamalary öz içine alýar. Sazlamalar üytgedilende awtomatiki saklanýar.

## Rugsatnama

[MIT License](../LICENSE)

## Önümçilikçi

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Proýekt URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Hormatlar

- LibreHardwareMonitor - Enjamçylyk synlag kitaphanasy
- psutil - Platformalarara ulgam synlagy
- PyInstaller - Python paketleme guraly
