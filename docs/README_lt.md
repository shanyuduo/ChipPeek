# ChipPeek

Lengvas plaukiojantis aparatinės įrangos stebėjimo valdiklis Windows operacinei sistemai.

> **Kitos kalbos**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | **Lietuvių** | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funkcijos

- **Stebėjimas realiuoju laiku**: CPU dažnis, CPU temperatūra, GPU dažnis, GPU temperatūra, VRAM naudojimas, atminties naudojimas
- **Du rodinimo režimai**: kampinis valdiklis / viršutinė juosta, perjungimas vienu paspaudimu
- **Tinkinamas rodinys**: laisvai pasirinkite, kuriuos rodiklius rodyti, perjungkite tarp procentų / tikrųjų verčių
- **Visada priekyje**: išlieka virš visų langų. Matomumas visame ekrane priklauso nuo programos ir rodymo režimo
- **Automatinis dydis**: lango plotis automatiškai prisitaiko prie turinio
- **Reguliuojamas stilius**: lango permatomumas, fono permatomumas, šrifto dydis - viską galima reguliuoti
- **Daugiakalbi palaikymas**: 103 kalbos, automatiškai nustato sistemos kalbą
- **Patogu valdymas**: perkelkite tempdami kairiuoju mygtuku, dešiniojo mygtuko meniu greitiems nustatymams, automatinis pritvirtinimas prie ekrano kraštų
- **Konfigūruojama imties dažnis**: 200ms - 3000ms reguliuojama
- **Automatinis paleidimas**: paleidžiamas automatiškai prisijungus prie Windows
- **Mažas išteklių sunaudojimas**: minimali atminties pėdsake fone

## Greitas pradžia

### Tiesioginis naudojimas

Atsisiųskite [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) ir dukart spustelėkite, kad paleistumėte (automatiškai paprašys administratoriaus teisių CPU temperatūrai ir tiksliai dažnio skaitymui).

### Paleisti iš pirminio kodo

```powershell
# Nuklonuokite saugyklą
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Įdiekite priklausomybes
python -m pip install -r requirements.txt pythonnet

# Paleiskite
python main.py
```

## Sistemos reikalavimai

- Windows 10 / Windows 11
- Administratoriaus teisės (rekomenduojama), kitaip CPU temperatūra ir tikslus dažnis gali būti nepasiekiami
- .NET Framework 4.7.2 arba naujesnė (reikalinga LibreHardwareMonitor)
- Python 3 + Tkinter (Paleisti iš pirminio kodo)

## Sukurti kaip EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Sukūrus EXE failas yra `dist/ChipPeek.exe` vietoje.

## Naudojimas

### Pagrindinės operacijos

| Operacija | Aprašymas |
|------|------|
| Tempimas kairiuoju | Lango padėties perkėlimas |
| Dešinysis mygtukas | Meniu atidarymas (režimo keitimas / nustatymai / išeiti) |
| Automatinis pritvirtinimas | Automati pritvirtinamas 20px atstumu nuo ekrano kraštų |

### Rodinimo režimai

- **Kampinis valdiklis**: visi rodikliai išdėstyti vertikaliai, galima patalpinti bet kuriame ekrano kampe
- **Viršutinė juosta**: visi rodikliai išdėstyti horizontaliai, pagal nutylėjimą išcentruoti ekrano viršuje

### Nustatymai

- **Rodinimo režimas**: kampinis valdiklis / viršutinė juosta
- **Valdiklio padėtis**: dešinėje apačioje / kairėje apačioje / dešinėje viršuje / kairėje viršuje
- **Lango permatomumas**: Slankiklis 0% - 100% atitinka lango nepermatomumą 100% - 15%
- **Fono permatomumas**: 0 palieka foną nepermatomą; bet kuri reikšmė virš 0 padaro jį skaidrų
- **Imties intervalas**: 200ms - 3000ms duomenų atnaujinimo dažnis
- **Šrifto dydis**: 8 - 20 taškai
- **Kalba**: 103 kalbos, automatiškai nustato sistemos kalbą
- **Rodomieji rodikliai**: kiekvieną rodiklį galima nepriklausomai įjungti / išjungti
- **Rodinimo formatas**: VRAM / Atmintis gali būti perjungta tarp procentų arba tikrųjų verčių
- **Automatinis paleidimas**: automatiškai paleisti prisijungus prie Windows

## Technologijų dėžė

- **GUI**：Tkinter
- **Aparatinės įrangos duomenys**：LibreHardwareMonitorLib (per pythonnet), psutil, pynvml (NVIDIA GPU atsarginis variantas)
- **Sistemos integracija**：pywin32 (langas visada priekyje, automatinio paleidimo registras)
- **Pakuojimas**：PyInstaller

## Projekto struktūra

```
ChipPeek/
├── main.py                  # Įėjimo taškas
├── monitor_window.py        # Lango UI ir sąveikos logika
├── hardware_monitor.py      # Aparatinės įrangos duomenų rinkimas
├── config.py                # Konfigūracijos valdymas
├── i18n.py                  # Internacionalizacija
├── generate_docs.py
├── generate_icon.py         # Piktogramų generavimo scenarijus
├── admin.manifest           # UAC administratoriaus teisių manifestas
├── app.ico                  # Programos piktograma
├── logo.png
├── requirements.txt         # Python priklausomybės
├── build.bat
├── docs/                    # Daugiakalbė dokumentacija
│   └── README_*.md
├── i18n/                    # Vertimo failai
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Sukompiliuotas vykdomasis failas
```

## Konfigūracijos failas

Failas `config.json` išsaugomas toje pačioje direktorijoje kaip `ChipPeek.exe` / `main.py` ir turi visus reguliuojamus nustatymus. Nustatymai išsaugomi automatiškai juos pakeitus.

## Licencija

[MIT License](../LICENSE)

## Kūrėjas

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekto URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Padėkos

- LibreHardwareMonitor - Aparatinės įrangos stebėjimo biblioteka
- psutil - Tarp-platformų sistemos stebėjimas
- PyInstaller - Python pakavimo įrankis
