# ChipPeek

Windows hardware monitor widget arin bat.

> **Beste Hizkuntza**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | **Euskara** | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Eginbideak

- **Denbora errealeko monitoringa**: CPU maiztasuna, CPU tenperatura, GPU maiztasuna, GPU tenperatura, VRAM erabilera, memoria erabilera
- **Bi pantaila modu**: Ertzeko widget-a / Goiko barra, klik bakarrez aldatu
- **Pantaila pertsonalizatua**: Aukeratu nahi dituzun neurriak, ehuneko/balio errealen artean aldatu
- **Beti goaldean**: Leiho guztien gainean gelditzen da. Pantaila osoko ikusgarritasuna aplikazioaren eta bistaratze moduaren araberakoa da
- **Tamaina automatikoa**: Leihoaren zabalera automatikoki egokitzen da edukiarekin
- **Estiloa aldagarria**: Leihoaren opakotasuna, atzeko planoko gardentasuna, letra-tamaina guztiak aldagarriak
- **Hizkuntza anitzeko euskarrria**: 103 hizkuntza, sistemaren hizkuntza automatikoki detektatzen du
- **Erosketa erraza**: Ezkerreko arrastoa mugitzeko, eskuineko klik menua ezarpen azkarretarako, pantailaren ertzetara automatikoki atxikitzea
- **Laginaketa tartea aldagarria**: 200ms - 3000ms aldagarria
- **Automatikoki hasi**: Windows saioa hastean automatikoki abiatu
- **Baliabide erabilera txikia**: Atzeko planorean oso gutxitsuten den eragina

## Hasi Azkar

### Zuzenean Erabili

Deskargatu [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) eta klik bikoitza egin exekutatzeko (kudeatzaile baimenak eskatuko ditu automatikoki CPU tenperatura eta maiztasun zehatza irakurtzeko).

### Iturburutik Exekutatu

```powershell
# Biltegia klonatu
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Menpekotasunak instalatu
python -m pip install -r requirements.txt pythonnet

# Exekutatu
python main.py
```

## Sistemaren Eskaerak

- Windows 10 / Windows 11
- Kudeatzaile baimenak (gomendatua), bestela CPU tenperatura eta maiztasun zehatza agian ez da erabilgarri
- .NET Framework 4.7.2 edo goiagoa (LibreHardwareMonitor-k behar du)
- Python 3 + Tkinter (Iturburutik Exekutatu)

## EXE gisa Bildu

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Eraiki ondoren, EXE fitxategia `dist/ChipPeek.exe` kokapen dago.

## Erabilera

### Oinarrizko Eragiketak

| Ekintza | Deskribapena |
|------|------|
| Ezkerreko arrastoa | Leihoaren posizioa mugitu |
| Eskuineko klik | Menua ireki (modua aldatu / ezarpenak / irten) |
| Atxiki automatikoa | Pantailaren 20px ertzetara automatikoki atxitzen da |

### Pantaila Moduak

- **Ertzeko Widget-a**: Neurri guztiak bertikalki antolatuta, pantailaren edozein ertzetan ipini daiteke
- **Goiko Barra**: Neurri guztiak horizontalki antolatuta, pantailaren goialdean centered modu lehenetsian

### Ezarpenak

- **Pantaila modua**: Ertzeko widget-a / Goiko barra
- **Widget-aren posizioa**: Beheko eskuin / Beheko ezker / Goiko eskuin / Goiko ezker
- **Leihoaren opakotasuna**: 0% - 100% graduatzailea leihoaren 100% - 15% opakutasunari dagokio
- **Atzeko planoko gardentasuna**: 0 balioak atzeko planoa opaku mantentzen du; 0 baino handiagoak garden bihurtzen du
- **Laginaketa tartea**: 200ms - 3000ms datuak freskatzeko abiadura
- **Letra-tamaina**: 8 - 20 puntu letra-tamaina
- **Hizkuntza**: 103 hizkuntza, sistemaren hizkuntza automatikoki detektatzen du
- **Pantaila neurriak**: Neurri bakoitza independenteekin txandakatu
- **Pantaila formatua**: VRAM / Memoria ehuneko edo balio errealen artean aldatu daiteke
- **Automatikoki hasi**: Windows saioa hastean automatikoki exekutatu

## Tech Stack

- **GUI**：Tkinter
- **Hardware datuak**：LibreHardwareMonitorLib (pythonnet bidez), psutil, pynvml (NVIDIA GPU alternatiboa)
- **Sistemaren integrazioa**：pywin32 (leihoa goaldean, auto-start erregistroa)
- **Paketea**：PyInstaller

## Proiektuaren Egitura

```
ChipPeek/
├── main.py                  # Sarrera puntua
├── monitor_window.py        # Leihoaren UI eta elkarreragin logika
├── hardware_monitor.py      # Hardware datuen bilketa
├── config.py                # Konfigurazio kudeaketa
├── i18n.py                  # Nazioartekoa
├── generate_docs.py
├── generate_icon.py         # Ikonoen sorpen scripta
├── admin.manifest           # UAC admin baimen manifiesto
├── app.ico                  # Aplikazioaren ikonoa
├── logo.png
├── requirements.txt         # Python menpekotasunak
├── build.bat
├── docs/                    # Hizkuntza anitzeko dokumentuak
│   └── README_*.md
├── i18n/                    # Itzulpen fitxategiak
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Konpilatutako exekutagarria
```

## Konfigurazio Fitxategia

`config.json` fitxategia `ChipPeek.exe` / `main.py`-rekin direkotorio berean gordetzen da, ezarpen guztiak aldagarriak barne. Ezarpenak automatikoki gordetzen dira aldatzen direnean.

## Lizentzia

[MIT License](../LICENSE)

## Garatzailea

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Proiektuaren URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Eskerrak

- LibreHardwareMonitor - Hardware monitoring liburutegia
- psutil - Plataforma gurutzatuko sistema monitora
- PyInstaller - Python paketeaketa tresna
