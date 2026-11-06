# ChipPeek

Ľahký plávajúci widget na monitorovanie hardvéru pre Windows.

> **Iné jazyky**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | **Slovenčina** | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funkcie

- **Monitorovanie v reálnom čase**: frekvencia CPU, teplota CPU, frekvencia GPU, teplota GPU, využitie VRAM, využitie pamäte
- **Dva režimy zobrazenia**: widget v rohu / horná lišta, prepnutie jedným kliknutím
- **Prispôsobiteľné zobrazenie**: slobodne si vyberte, ktoré metriky zobrazovať, prepínač medzi percentuálnymi/skutočnými hodnotami
- **Vždy navrchu**: zostáva nad všetkými oknami. Viditeľnosť na celej obrazovke závisí od aplikácie a režimu zobrazenia
- **Automatická veľkosť**: šírka okna sa automaticky prispôsobí obsahu
- **Nastaviteľný štýl**: priehľadnosť okna, priehľadnosť pozadia, veľkosť písma - všetko sa dá nastaviť
- **Podpora viacerých jazykov**: 103 jazykov, automaticky rozpozná jazyk systému
- **Pohodlné ovládanie**: presúvajte ťahaním ľavým tlačidlom, menu pravým tlačidlom pre rýchle nastavenia, automatické priľnavanie k okrajom obrazovky
- **Nastaviteľná vzorkovacia frekvencia**: 200ms - 3000ms nastaviteľná
- **Automatické spustenie**: spúšťa sa automaticky pri prihlásení do Windows
- **Nízka spotreba zdrojov**: minimálna záťaž v pozadí

## Rýchly štart

### Priame použitie

Stiahnite si [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) a dvakrát kliknite pre spustenie (automaticky požiada o oprávnenia správcu pre teplotu CPU a presné čítanie frekvencie).

### Spustenie zo zdrojového kódu

```powershell
# Naklonujte repozitár
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Nainštalujte závislosti
python -m pip install -r requirements.txt pythonnet

# Spustite
python main.py
```

## Systémové požiadavky

- Windows 10 / Windows 11
- Oprávnenia správcu (odporúča sa), inak teplota CPU a presná frekvencia nemusia byť dostupné
- .NET Framework 4.7.2 alebo vyšší (vyžaduje LibreHardwareMonitor)
- Python 3 + Tkinter (Spustenie zo zdrojového kódu)

## Zostavenie ako EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Po zostavení sa EXE súbor nachádza v `dist/ChipPeek.exe`.

## Použitie

### Základné operácie

| Operácia | Popis |
|------|------|
| Ťahanie ľavým tlačidlom | Presunutie pozície okna |
| Pravé tlačidlo | Otvorenie menu (zmena režimu / nastavenia / ukončenie) |
| Automatické priľnavanie | Automaticky sa prilne do 20px od okrajov obrazovky |

### Režimy zobrazenia

- **Widget v rohu**: všetky metriky usporiadané zvisle, dá sa umiestniť do ktoréhokoľvek rohu obrazovky
- **Horná lišta**: všetky metriky usporiadané vodorovne, predvolene zarovnané stredne v hornej časti obrazovky

### Nastavenia

- **Režim zobrazenia**: widget v rohu / horná lišta
- **Pozícia widgetu**: vpravo dole / vľavo dole / vpravo hore / vľavo hore
- **Priehľadnosť okna**: Posuvník 0% - 100% zodpovedá nepriehľadnosti okna 100% - 15%
- **Priehľadnosť pozadia**: 0 ponechá pozadie nepriehľadné; každá hodnota nad 0 ho spriehľadní
- **Vzorkovací interval**: 200ms - 3000ms rýchlosť obnovy dát
- **Veľkosť písma**: 8 - 20 bodov
- **Jazyk**: 103 jazykov, automaticky rozpozná jazyk systému
- **Zobrazované metriky**: každú metriku je možné nezávisle zapnúť/vypnúť
- **Formát zobrazenia**: VRAM / Pamäť sa dajú prepnúť na percentá alebo skutočné hodnoty
- **Automatické spustenie**: spúšťať automaticky pri prihlásení do Windows

## Technologický zásobník

- **GUI**：Tkinter
- **Hardvérové dáta**：LibreHardwareMonitorLib (cez pythonnet), psutil, pynvml (záložné riešenie pre NVIDIA GPU)
- **Systémová integrácia**：pywin32 (okno vždy navrchu, registr automatického spustenia)
- **Zabalovanie**：PyInstaller

## Štruktúra projektu

```
ChipPeek/
├── main.py                  # Vstupný bod
├── monitor_window.py        # UI okna a logika interakcie
├── hardware_monitor.py      # Zber hardvérových dát
├── config.py                # Správa konfigurácie
├── i18n.py                  # Internacionalizácia
├── generate_docs.py
├── generate_icon.py         # Skript na generovanie ikon
├── admin.manifest           # Manifest oprávnení správcu UAC
├── app.ico                  # Ikona aplikácie
├── logo.png
├── requirements.txt         # Python závislosti
├── build.bat
├── docs/                    # Jazykovo rozmanitá dokumentácia
│   └── README_*.md
├── i18n/                    # Prekladové súbory
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Skompilovaný spustiteľný súbor
```

## Konfiguračný súbor

Súbor `config.json` sa ukladá v rovnakom adresári ako `ChipPeek.exe` / `main.py` a obsahuje všetky nastaviteľné nastavenia. Nastavenia sa automaticky ukladajú pri zmene.

## Licencia

[MIT License](../LICENSE)

## Vývojár

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL projektu: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Poďakovanie

- LibreHardwareMonitor - Knižnica na monitorovanie hardvéru
- psutil - Naprieč platformami sledovanie systému
- PyInstaller - Nástroj na balenie Python programov
