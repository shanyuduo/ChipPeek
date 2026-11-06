# ChipPeek

Lagani plutajući widget za nadzor hardvera za Windows.

> **Ostali jezici**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | **Hrvatski** | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Značajke

- **Nadzor u stvarnom vremenu**: frekvencija CPU, temperatura CPU, frekvencija GPU, temperatura GPU, korištenje VRAM, korištenje memorije
- **Dva načina prikaza**: kutni widget / gornja traka, jedno kliktanje za prebacivanje
- **Prilagodljivi prikaz**: slobodno odaberite koje će se metrike prikazivati, prebacivanje između postotka/stvarnih vrijednosti
- **Uvijek na vrhu**: ostaje iznad svih prozora. Vidljivost na cijelom zaslonu ovisi o aplikaciji i načinu prikaza
- **Automatska veličina**: širina prozora se automatski prilagođava sadržaju
- **Podesivi stil**: prozirnost prozora, prozirnost pozadine, veličina fonta - sve je podesivo
- **Višejezična podrška**: 103 jezika, automatski prepoznaje jezik sustava
- **Praktično upravljanje**: pomaknite povlačenjem lijevom tipkom, izbornik desnom tipkom za brze postavke, automatsko lijepljenje na rubove zaslona
- **Podesiva frekvencija uzorkovanja**: 200ms - 3000ms podesivo
- **Automatsko pokretanje**: pokreće se automatski pri prijavi u Windows
- **Niska potrošnja resursa**: minimalno opterećenje u pozadini

## Brzi početak

### Izravna upotreba

Preuzmite [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) i dvaput kliknite za pokretanje (automatski će zatražiti administratorske ovlasti za temperaturu CPU i točno čitanje frekvencije).

### Pokretanje iz izvornog koda

```powershell
# Klonirajte repozitorij
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instalirajte ovisnosti
python -m pip install -r requirements.txt pythonnet

# Pokrenite
python main.py
```

## Sustavski zahtjevi

- Windows 10 / Windows 11
- Administratorske ovlasti (preporučuje se), inače temperatura CPU i točna frekvencija možda neće biti dostupne
- .NET Framework 4.7.2 ili noviji (potrebno za LibreHardwareMonitor)
- Python 3 + Tkinter (Pokretanje iz izvornog koda)

## Izgradnja kao EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Nakon izgradnje, EXE datoteka se nalazi na `dist/ChipPeek.exe`.

## Upotreba

### Osnovne operacije

| Operacija | Opis |
|------|------|
| Povlačenje lijevom tipkom | Pomicanje položaja prozora |
| Desna tipka | Otvaranje izbornika (promjena načina / postavke / izlaz) |
| Automatsko lijepljenje | Automatski se lijepi unutar 20px od rubova zaslona |

### Načini prikaza

- **Kutni widget**: sve metrike raspoređene okomito, mogu se postaviti u bilo koji kut zaslona
- **Gornja traka**: sve metrike raspoređene vodoravno, zadano centrirane na vrhu zaslona

### Postavke

- **Način prikaza**: kutni widget / gornja traka
- **Položaj widgeta**: desno dolje / lijevo dolje / desno gore / lijevo gore
- **Prozirnost prozora**: Klizač 0% - 100% odgovara neprozirnosti prozora 100% - 15%
- **Prozirnost pozadine**: 0 zadržava neprozirnu pozadinu; svaka vrijednost iznad 0 čini je prozirnom
- **Interval uzorkovanja**: 200ms - 3000ms brzina osvježavanja podataka
- **Veličina fonta**: 8 - 20 točaka
- **Jezik**: 103 jezika, automatski prepoznaje jezik sustava
- **Metrike prikaza**: svaku metriku je moguće neovisno uključiti/isključiti
- **Format prikaza**: VRAM / Memorija se mogu prebaciti između postotka ili stvarnih vrijednosti
- **Automatsko pokretanje**: automatsko pokretanje pri prijavi u Windows

## Tehnološki stek

- **GUI**：Tkinter
- **Podaci o hardveru**：LibreHardwareMonitorLib (preko pythonnet), psutil, pynvml (alternativa za NVIDIA GPU)
- **Integracija sustava**：pywin32 (prozor uvijek na vrhu, registar za automatsko pokretanje)
- **Pakiranje**：PyInstaller

## Struktura projekta

```
ChipPeek/
├── main.py                  # Ulazna točka
├── monitor_window.py        # UI prozora i logika interakcije
├── hardware_monitor.py      # Sakupljanje podataka o hardveru
├── config.py                # Upravljanje konfiguracijom
├── i18n.py                  # Internacionalizacija
├── generate_docs.py
├── generate_icon.py         # Skripta za generiranje ikona
├── admin.manifest           # Manifest administratorskih ovlasti UAC
├── app.ico                  # Ikona aplikacije
├── logo.png
├── requirements.txt         # Python ovisnosti
├── build.bat
├── docs/                    # Višejezična dokumentacija
│   └── README_*.md
├── i18n/                    # Datoteke prijevoda
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompajlirana izvršna datoteka
```

## Konfiguracijska datoteka

Datoteka `config.json` sprema se u istom direktoriju kao `ChipPeek.exe` / `main.py` i sadrži sve podesive postavke. Postavke se automatski spremaju prilikom promjene.

## Licenca

[MIT License](../LICENSE)

## Razvojni programer

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL projekta: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Zahvale

- LibreHardwareMonitor - Knjižnica za nadzor hardvera
- psutil - Višeplatformski nadzor sustava
- PyInstaller - Alat za pakiranje Pythona
