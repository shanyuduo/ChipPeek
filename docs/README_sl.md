# ChipPeek

Lahek plavajoči pripomoček za nadzor strojne opreme za Windows.

> **Drugi jeziki**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | **Slovenščina** | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funkcije

- **Nadzor v realnem času**: frekvenca CPU, temperatura CPU, frekvenca GPU, temperatura GPU, poraba VRAM, poraba pomnilnika
- **Dva načina prikaza**: kotni pripomoček / vršna vrstica, preklop z enim klikom
- **Prilagodljiv prikaz**: prosto izberite, katere metrike želite prikazati, preklop med odstotki/dejanskimi vrednostmi
- **Vedno na vrhu**: ostaja nad vsemi okni. Vidnost v celozaslonskem načinu je odvisna od aplikacije in načina prikaza
- **Samodejna velikost**: širina okna se samodejno prilagodi vsebini
- **Prilagodljiv slog**: prosojnost okna, prosojnost ozadja, velikost pisave - vse je prilagodljivo
- **Večjezična podpora**: 103 jezikov, samodejno zazna jezik sistema
- **Priročno upravljanje**: premaknite s povlekom z levim gumbom, meni z desnim gumbom za hitre nastavitve, samodejno prileganje robovom zaslona
- **Prilagodljiva frekvenca vzorčenja**: 200ms - 3000ms prilagodljivo
- **Samodejni zagon**: zažene se samodejno ob prijavi v Windows
- **Nizka poraba virov**: minimalno breme v ozadju

## Hiter začetek

### Neposredna uporaba

Prenesite [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) in dvakrat kliknite za zagon (samodejno bo zahteval skrbniške dovoljenja za temperaturo CPU in točno branje frekvence).

### Zagon iz izvorne kode

```powershell
# Klonirajte repozitorij
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Namestite odvisnosti
python -m pip install -r requirements.txt pythonnet

# Zaženite
python main.py
```

## Sistemski zahtevi

- Windows 10 / Windows 11
- Skrbniška dovoljenja (priporočljivo), sicer temperatura CPU in točna frekvenca morda ne bosta na voljo
- .NET Framework 4.7.2 ali novejša (zahteva LibreHardwareMonitor)
- Python 3 + Tkinter (Zagon iz izvorne kode)

## Izgradnja kot EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Po izgradnji je EXE datoteka na lokaciji `dist/ChipPeek.exe`.

## Uporaba

### Osnovne operacije

| Operacija | Opis |
|------|------|
| Povlek z levim gumbom | Premik položaja okna |
| Desni gumb | Odpiranje menija (sprememba načina / nastavitve / izhod) |
| Samodejno prileganje | Samodejno se prileže znotraj 20px od robov zaslona |

### Načini prikaza

- **Kotni pripomoček**: vse metrike razporejene navpično, jih je možno postaviti v katerikoli kot zaslona
- **Vršna vrstica**: vse metrike razporejene vodoravno, privzeto sredinsko poravnane na vrhu zaslona

### Nastavitve

- **Način prikaza**: kotni pripomoček / vršna vrstica
- **Položaj pripomočka**: desno spodaj / levo spodaj / desno zgoraj / levo zgoraj
- **Prosojnost okna**: Drsnik 0% - 100% ustreza neprosojnosti okna 100% - 15%
- **Prosojnost ozadja**: 0 ohrani ozadje neprosojno; vsaka vrednost nad 0 ga naredi prosojnega
- **Interval vzorčenja**: 200ms - 3000ms frekvenca osveževanja podatkov
- **Velikost pisave**: 8 - 20 točk
- **Jezik**: 103 jezikov, samodejno zazna jezik sistema
- **Metrike prikaza**: vsako metriko je mogoče neodvisno vklopiti/izklopiti
- **Oblika prikaza**: VRAM / Pomnilnik se lahko preklopijo med odstotki ali dejanskimi vrednostmi
- **Samodejni zagon**: samodejni zagon ob prijavi v Windows

## Tehnološki sklad

- **GUI**：Tkinter
- **Podatki o strojni opremi**：LibreHardwareMonitorLib (preko pythonnet), psutil, pynvml (nadomestni način za NVIDIA GPU)
- **Sistemska integracija**：pywin32 (okno vedno na vrhu, register za samodejni zagon)
- **Pakiranje**：PyInstaller

## Struktura projekta

```
ChipPeek/
├── main.py                  # Vhodna točka
├── monitor_window.py        # UI okna in logika interakcije
├── hardware_monitor.py      # Zbiranje podatkov o strojni opremi
├── config.py                # Upravljanje konfiguracije
├── i18n.py                  # Mednarodna podpora
├── generate_docs.py
├── generate_icon.py         # Skripta za generiranje ikon
├── admin.manifest           # Manifest skrbniških dovoljenj UAC
├── app.ico                  # Ikona aplikacije
├── logo.png
├── requirements.txt         # Python odvisnosti
├── build.bat
├── docs/                    # Večjezična dokumentacija
│   └── README_*.md
├── i18n/                    # Prevodne datoteke
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Prevedena izvršljiva datoteka
```

## Konfiguracijska datoteka

Datoteka `config.json` se shrani v istem imeniku kot `ChipPeek.exe` / `main.py` in vsebuje vse prilagodljive nastavitve. Nastavitve se samodejno shranijo ob spremembi.

## Licenca

[MIT License](../LICENSE)

## Razvijalec

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL projekta: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Zahvale

- LibreHardwareMonitor - Knjižnica za nadzor strojne opreme
- psutil - Večplatformski nadzor sistema
- PyInstaller - Orodje za pakiranje Pythona
