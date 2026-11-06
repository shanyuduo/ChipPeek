# ChipPeek

Kayan aiki mai sauqi na Windows don kula da kayan aikin lissafi ta hanyar wijet mai tunawa.

> **Sauran Harsuna**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | **Hausa** | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Fasaloli

- **Kula a lokaci guda**: Mitar CPU, zafin CPU, mitar GPU, zafin GPU, amfani da VRAM, amfani da tunani
- **Yanayin nuni biyu**: Wijet na kusurwa / Layin sama, canzawa da danna sau daya
- **Nuni da za'a iya gyara**: Zaɓi wanda za'a nuna, canzawa tsakanin kashi/ahirin daraja
- **Kasancewa a saman koyaushe**: Yana kasancewa a kowane taga. Ganuwa a cikakken allo ya danganta da manhaja da yanayin nuni
- **Girma kansa**: Faɗin taga yana daidaitawa da kansa don dacewa da abun ciki
- **Salon da za'a iya daidaitawa**: Gaskiyar taga, gaskiyar bayani, girman fonti duk za'a iya daidaita
- **Goyon bayan harsuna da yawa**: Harsuna 103, yana gano harshen tsari da kansa
- **Aiki mai sauqi**: Ja da hagu don motsa, danna dama don menu na saurin saitoci, kashe kansa zuwa gefen allon
- **Saitin samfuri da za'a iya daidaita**: 200ms - 3000ms za'a iya daidaita
- **Fara kansa**: Kunshewa aiki lokacin shiga Windows
- **Amfani da ƙarancin albarkatu**: Ƙaramin sawa a bango

## Fara Cikin Gaggawa

### Amfani Kai Tsaye

Sauke [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) kuma danna sau biyu don gudanarwa (zai nemi haƙƙin mai gudanarwa don karanta zafin CPU da ainihin mitar).

### Gudanar Daga Tushen Code

```powershell
# Kwafa mashigar
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Sanya dogaro
python -m pip install -r requirements.txt pythonnet

# Gudanar
python main.py
```

## Bukatun Tsarin

- Windows 10 / Windows 11
- Haƙƙin mai gudanarwa (ana bada shawara), in ba haka ba zafin CPU da ainihin mitar ba za su kasance ba
- .NET Framework 4.7.2 ko mafi girma (LibreHardwareMonitor yana buƙatar shi)
- Python 3 + Tkinter (Gudanar Daga Tushen Code)

## Gina A Matsayin EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Bayan ginawa, fayil ɗin EXE yana cikin `dist/ChipPeek.exe`.

## Yadda Ake Amfani

### Ayyukan Tushen

| Aiki | Bayani |
|------|------|
| Ja da hagu | Motsa wurin taga |
| Danna dama | Bude menu (canza yanayi / saitoci / fita) |
| Kashe kansa | Yana kashe kansa cikin 20px na gefen allon |

### Yanayin Nuni

- **Wijet na kusurwa**: Duk ma'auni an tsara su a tsaye, za'a iya sanya su a kowane kusurwar allon
- **Layin sama**: Duk ma'auni an tsara su a kwance, tsakiya a saman allon da tsoho

### Saitoci

- **Yanayin nuni**: Wijet na kusurwa / Layin sama
- **Wurin wijet**: Kasa dama / Kasa hagu / Sama dama / Sama hagu
- **Gaskiyar taga**: Zamewar 0% - 100% tana daidai da rashin ganin ta cikin taga na 100% - 15%
- **Gaskiyar bayani**: 0 yana sa bango ya kasance marar ganin ta ciki; duk ƙima fiye da 0 tana sa ya zama mai ganin ta ciki
- **Tazarar samfuri**: 200ms - 3000ms saurin sabunta bayanai
- **Girman fonti**: 8 - 20 batu fonti
- **Yare**: Harsuna 103, yana gano harshen tsari da kansa
- **Nuna ma'auni**: Kowane ma'auni za'a iya canzawa kansa
- **Tsarin nuni**: VRAM / Tunani za'a iya canzawa tsakanin kashi ko ainihin daraja
- **Fara kansa**: Gudanar da kansa lokacin shiga Windows

## Tarihin Fasaha

- **GUI**：Tkinter
- **Bayanan kayan aiki**：LibreHardwareMonitorLib (ta pythonnet), psutil, pynvml (madadin NVIDIA GPU)
- **Hadewar tsari**：pywin32 (taga a saman, rijista ta fara kansa)
- **Kunshewa**：PyInstaller

## Tsarin Aikin

```
ChipPeek/
├── main.py                  # Mashigar shiga
├── monitor_window.py        # UI na taga da kula da hira
├── hardware_monitor.py      # Tattara bayanan kayan aiki
├── config.py                # Kula da saitoci
├── i18n.py                  # Yafi ƙasashe da yawa
├── generate_docs.py
├── generate_icon.py         # Rubutun ƙirƙirar alama
├── admin.manifest           # Bayanin haƙƙin UAC mai gudanarwa
├── app.ico                  # Alamar aikace-aikace
├── logo.png
├── requirements.txt         # Dogaro da Python
├── build.bat
├── docs/                    # Takardun harsuna da yawa
│   └── README_*.md
├── i18n/                    # Fayilolin fassara
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Fayil ɗin da za'a iya aiwatarwa bayan tarawa
```

## Fayil ɗin Saitoci

Fayil ɗin `config.json` yana adanawa a cikin wannan fayil ɗin da `ChipPeek.exe` / `main.py`, yana ɗauke da duk saitocin da za'a iya daidaitawa. Saitoci ana adana su ne da kansu lokacin da aka canza su.

## Lasisi

[MIT License](../LICENSE)

## Mai Habaka

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL ɗin Aikin: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Godiya

- LibreHardwareMonitor - Laburaren kula da kayan aiki
- psutil - Kula da tsarin ƙasashe da yawa
- PyInstaller - Kayan aikin kunshewar Python
