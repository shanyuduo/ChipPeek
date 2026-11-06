# ChipPeek

Лаки плавајући виџет за надзор хардвера за Windows.

> **Остали језици**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | **Српски** | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Функције

- **Надзор у стварном времену**: фреквенција CPU, температура CPU, фреквенција GPU, температура GPU, коришћење VRAM, коришћење меморије
- **Два начина приказа**: кутни виџет / горња трака, једно кликнуће за пребацивање
- **Прилагодљив приказ**: слободно одаберите које се метрике приказују, пребацивање између процената/стварних вредности
- **Увек на врху**: остаје изнад свих прозора. Видљивост на целом екрану зависи од апликације и режима приказа
- **Аутоматска величина**: ширина прозора се аутоматски прилагођава садржају
- **Подесив стил**: прозирност прозора, прозирност позадине, величина фонта - све је подесиво
- **Вишејезична подршка**: 103 језика, аутоматски препознаје језик система
- **Практично управљање**: померите превлачењем левом тастером, мени десним тастером за брзе поставке, аутоматско лепљење на рубове екрана
- **Подесива фреквенција узорковања**: 200ms - 3000ms подесиво
- **Аутоматско покретање**: покреће се аутоматски при пријави у Windows
- **Ниска потрошња ресурса**: минимално оптерећење у позадини

## Брзи почетак

### Директна употреба

Преузмите [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) и двапут кликните за покретање (аутоматски ће затражити администраторске овлашћења за температуру CPU и тачно читање фреквенције).

### Покретање из изворног кода

```powershell
# Клонирајте репозиторијум
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Инсталирајте зависности
python -m pip install -r requirements.txt pythonnet

# Покрените
python main.py
```

## Системски захтеви

- Windows 10 / Windows 11
- Администраторске овлашћења (препоручује се), иначе температура CPU и тачна фреквенција можда неће бити доступне
- .NET Framework 4.7.2 или новији (потребно за LibreHardwareMonitor)
- Python 3 + Tkinter (Покретање из изворног кода)

## Изградња као EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Након изградње, EXE датотека се налази на `dist/ChipPeek.exe`.

## Употреба

### Основне операције

| Операција | Опис |
|------|------|
| Превлачење левом тастером | Помицање положаја прозора |
| Десна тастер | Отварање менија (промена начина / поставке / излаз) |
| Аутоматско лепљење | Аутоматски се лепљи унутар 20px од рубова екрана |

### Начини приказа

- **Кутни виџет**: све метрике распоређене усправно, могу се поставити у било који кут екрана
- **Горња трака**: све метрике распоређене водоравно, подразумевано центриране на врху екрана

### Поставке

- **Начин приказа**: кутни виџет / горња трака
- **Положај виџета**: десно доле / лево доле / десно горе / лево горе
- **Прозирност прозора**: Клизач 0% - 100% одговара непрозирности прозора 100% - 15%
- **Прозирност позадине**: 0 задржава непрозирну позадину; свака вредност изнад 0 чини је прозирном
- **Интервал узорковања**: 200ms - 3000ms брзина освежавања података
- **Величина фонта**: 8 - 20 тачака
- **Језик**: 103 језика, аутоматски препознаје језик система
- **Метрике приказа**: сваку метрику је могуће независно укључити/искључити
- **Формат приказа**: VRAM / Меморија се могу пребацити између процената или стварних вредности
- **Аутоматско покретање**: аутоматско покретање при пријави у Windows

## Технолошки стек

- **GUI**：Tkinter
- **Подати о хардверу**：LibreHardwareMonitorLib (преко pythonnet), psutil, pynvml (алтернатива за NVIDIA GPU)
- **Интеграција система**：pywin32 (прозор увек на врху, регистар за аутоматско покретање)
- **Паковање**：PyInstaller

## Структура пројекта

```
ChipPeek/
├── main.py                  # Улазна тачка
├── monitor_window.py        # UI прозора и логика интеракције
├── hardware_monitor.py      # Сакупљање података о хардверу
├── config.py                # Управљање конфигурацијом
├── i18n.py                  # Интернационализација
├── generate_docs.py
├── generate_icon.py         # Скрипта за генерисање икона
├── admin.manifest           # Манифест администраторских овлашћења UAC
├── app.ico                  # Икона апликације
├── logo.png
├── requirements.txt         # Python зависности
├── build.bat
├── docs/                    # Вишејезична документација
│   └── README_*.md
├── i18n/                    # Датотеке превода
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Компајлирана извршна датотека
```

## Конфигурациона датотека

Датотека `config.json` се чува у истом директоријуму као `ChipPeek.exe` / `main.py` и садржи све подесиве поставке. Поставке се аутоматски чувају при промени.

## Лиценца

[MIT License](../LICENSE)

## Развојни програмер

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL пројекта: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Захвале

- LibreHardwareMonitor - Библиотека за надзор хардвера
- psutil - Вишеплатформски надзор система
- PyInstaller - Алат за паковање Питона
