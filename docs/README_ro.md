# ChipPeek

Un widget ușor de monitorizare hardware plutitor pentru Windows.

> **Alte limbi**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | **Română** | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Caracteristici

- **Monitorizare în timp real**: frecvență CPU, temperatură CPU, frecvență GPU, temperatură GPU, utilizare VRAM, utilizare memorie
- **Două moduri de afișare**: widget colț / bară superioară, comutare cu un singur clic
- **Afișare personalizabilă**: alegeți liber ce metrici să afișați, comutați între procentaj/valori reale
- **Întotdeauna deasupra**: rămâne deasupra tuturor ferestrelor. Vizibilitatea pe tot ecranul depinde de aplicație și de modul de afișare
- **Dimensiune automată**: lățimea ferestrei se ajustează automat la conținut
- **Stil reglabil**: opacitate fereastră, transparență fundal, dimensiune font - toate reglabile
- **Suport pentru mai multe limbi**: 103 limbi, detectează automat limba sistemului
- **Operare convenabilă**: trageți cu clic stânga pentru a muta, meniu clic dreapta pentru setări rapide, aliniere automată la marginile ecranului
- **Frecvență de eșantionare configurabilă**: 200ms - 3000ms reglabilă
- **Pornire automată**: pornește automat la conectarea în Windows
- **Utilizare scăzută a resurselor**: amprentă minimă în fundal

## Început rapid

### Utilizare directă

Descărcați [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) și faceți dublu clic pentru a rula (va solicita automat privilegii de administrator pentru temperatura CPU și citirea precisă a frecvenței).

### Rulare din codul sursă

```powershell
# Clonați depozitul
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instalați dependențele
python -m pip install -r requirements.txt pythonnet

# Rulați
python main.py
```

## Cerințe de sistem

- Windows 10 / Windows 11
- Privilegii de administrator (recomandat), altfel temperatura CPU și frecvența precisă ar putea să nu fie disponibile
- .NET Framework 4.7.2 sau mai mare (necesar de către LibreHardwareMonitor)
- Python 3 + Tkinter (Rulare din codul sursă)

## Compilare ca EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

După compilare, fișierul EXE se află la `dist/ChipPeek.exe`.

## Utilizare

### Operații de bază

| Operație | Descriere |
|------|------|
| Tragere clic stânga | Mutarea poziției ferestrei |
| Clic dreapta | Deschidere meniu (schimbare mod / setări / ieșire) |
| Aliniere automată | Se aliniază automat în intervalul de 20px de la marginile ecranului |

### Moduri de afișare

- **Widget colț**: toate metricile aranjate vertical, pot fi plasate în orice colț al ecranului
- **Bară superioară**: toate metricile aranjate orizontal, în mod implicit centrate în partea superioară a ecranului

### Setări

- **Mod de afișare**: widget colț / bară superioară
- **Poziție widget**: dreapta jos / stânga jos / dreapta sus / stânga sus
- **Opacitate fereastră**: Glisorul 0% - 100% corespunde unei opacități a ferestrei de 100% - 15%
- **Transparență fundal**: 0 păstrează fundalul opac; orice valoare peste 0 îl face transparent
- **Interval de eșantionare**: 200ms - 3000ms rată de reîmprospătare a datelor
- **Dimensiune font**: 8 - 20 puncte
- **Limbă**: 103 limbi, detectează automat limba sistemului
- **Metrici de afișare**: activați/dezactivați fiecare metrică independent
- **Format de afișare**: VRAM / Memorie pot comuta între procentaj sau valori reale
- **Pornire automată**: rulare automată la conectarea în Windows

## Stivă tehnologică

- **GUI**：Tkinter
- **Date hardware**：LibreHardwareMonitorLib (prin pythonnet), psutil, pynvml (alternativă pentru GPU NVIDIA)
- **Integrare sistem**：pywin32 (fereastră întotdeauna deasupra, registru de pornire automată)
- **Ambalare**：PyInstaller

## Structura proiectului

```
ChipPeek/
├── main.py                  # Punct de intrare
├── monitor_window.py        # UI fereastră și logică de interacțiune
├── hardware_monitor.py      # Colectare date hardware
├── config.py                # Gestionare configurație
├── i18n.py                  # Internaționalizare
├── generate_docs.py
├── generate_icon.py         # Script de generare pictograme
├── admin.manifest           # Manifest privilegii administrator UAC
├── app.ico                  # Pictogramă aplicație
├── logo.png
├── requirements.txt         # Dependențe Python
├── build.bat
├── docs/                    # Documentare multilingvă
│   └── README_*.md
├── i18n/                    # Fișiere traducere
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Fișier executabil compilat
```

## Fișier de configurație

Fișierul `config.json` este salvat în același director cu `ChipPeek.exe` / `main.py` și conține toate setările reglabile. Setările sunt salvate automat atunci când sunt modificate.

## Licență

[MIT License](../LICENSE)

## Dezvoltator

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL proiect: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Mulțumiri

- LibreHardwareMonitor - Bibliotecă de monitorizare hardware
- psutil - Monitorizare sistem între platforme
- PyInstaller - Unelte de ambalare Python
