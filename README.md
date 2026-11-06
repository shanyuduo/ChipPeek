<div align="center">

# ChipPeek

### Lightweight Windows Hardware Monitoring Floating Widget

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Platform: Windows](https://img.shields.io/badge/Platform-Windows-10%2F11-0078D4.svg)](https://github.com/shanyuduo/ChipPeek)
[![Languages: 103](https://img.shields.io/badge/Languages-103-green.svg)](#languages)
[![Python: 3.x](https://img.shields.io/badge/Python-3.x-3776AB.svg)](https://www.python.org/)
[![Stars](https://img.shields.io/github/stars/shanyuduo/ChipPeek?style=social)](https://github.com/shanyuduo/ChipPeek)
[![Releases](https://img.shields.io/github/v/release/shanyuduo/ChipPeek)](https://github.com/shanyuduo/ChipPeek/releases)

A lightweight, open-source **CPU / GPU temperature and frequency monitor** for Windows. \
Real-time hardware stats in a tiny always-on-top desktop widget.

</div>

## Languages

> **Other Languages**: [简体中文](docs/README_zh-CN.md) | [繁體中文](docs/README_zh-TW.md) | **English** | [日本語](docs/README_ja.md) | [한국어](docs/README_ko.md) | [Español](docs/README_es.md) | [Français](docs/README_fr.md) | [Deutsch](docs/README_de.md) | [Português](docs/README_pt.md) | [Русский](docs/README_ru.md) | [العربية](docs/README_ar.md) | [ไทย](docs/README_th.md) | [Tiếng Việt](docs/README_vi.md) | [Bahasa Indonesia](docs/README_id.md) | [Türkçe](docs/README_tr.md) | [Italiano](docs/README_it.md) | [Nederlands](docs/README_nl.md) | [Polski](docs/README_pl.md) | [हिन्दी](docs/README_hi.md) | [বাংলা](docs/README_bn.md) | [Svenska](docs/README_sv.md) | [Norsk](docs/README_no.md) | [Dansk](docs/README_da.md) | [Suomi](docs/README_fi.md) | [Čeština](docs/README_cs.md) | [Ελληνικά](docs/README_el.md) | [Magyar](docs/README_hu.md) | [Română](docs/README_ro.md) | [Українська](docs/README_uk.md) | [Slovenčina](docs/README_sk.md) | [Български](docs/README_bg.md) | [Hrvatski](docs/README_hr.md) | [Српски](docs/README_sr.md) | [Català](docs/README_ca.md) | [Slovenščina](docs/README_sl.md) | [Eesti](docs/README_et.md) | [Latviešu](docs/README_lv.md) | [Lietuvių](docs/README_lt.md) | [فارسی](docs/README_fa.md) | [Bahasa Melayu](docs/README_ms.md) | [اردو](docs/README_ur.md) | [தமிழ்](docs/README_ta.md) | [తెలుగు](docs/README_te.md) | [मराठी](docs/README_mr.md) | [ગુજરાતી](docs/README_gu.md) | [ਪੰਜਾਬੀ](docs/README_pa.md) | [ಕನ್ನಡ](docs/README_kn.md) | [മലയാളം](docs/README_ml.md) | [Қазақ](docs/README_kk.md) | [O'zbek](docs/README_uz.md) | [עברית](docs/README_he.md) | [မြန်မာ](docs/README_my.md) | [ខ្មែរ](docs/README_km.md) | [ລາວ](docs/README_lo.md) | [Kiswahili](docs/README_sw.md) | [Afrikaans](docs/README_af.md) | [አማርኛ](docs/README_am.md) | [isiZulu](docs/README_zu.md) | [Filipino](docs/README_fil.md) | [Gaeilge](docs/README_ga.md) | [Íslenska](docs/README_is.md) | [Malti](docs/README_mt.md) | [Cymraeg](docs/README_cy.md) | [Euskara](docs/README_eu.md) | [Galego](docs/README_gl.md) | [नेपाली](docs/README_ne.md) | [සිංහල](docs/README_si.md) | [ქართული](docs/README_ka.md) | [Հայերեն](docs/README_hy.md) | [Македонски](docs/README_mk.md) | [Беларуская](docs/README_be.md) | [ייִדיש](docs/README_yi.md) | [Lëtzebuergesch](docs/README_lb.md) | [Esperanto](docs/README_eo.md) | [Føroyskt](docs/README_fo.md) | [Gàidhlig](docs/README_gd.md) | [Brezhoneg](docs/README_br.md) | [Corsu](docs/README_co.md) | [Rumantsch](docs/README_rm.md) | [Occitan](docs/README_oc.md) | [Asturianu](docs/README_ast.md) | [Frysk](docs/README_fy.md) | [Татарча](docs/README_tt.md) | [Башҡортса](docs/README_ba.md) | [Basa Jawa](docs/README_jv.md) | [Basa Sunda](docs/README_su.md) | [Cebuano](docs/README_ceb.md) | [བོད་སྐད](docs/README_bo.md) | [Kurdî](docs/README_ku.md) | [پښتو](docs/README_ps.md) | [سنڌي](docs/README_sd.md) | [Тоҷикӣ](docs/README_tg.md) | [Türkmen](docs/README_tk.md) | [Кыргызча](docs/README_ky.md) | [Монгол](docs/README_mn.md) | [Hausa](docs/README_ha.md) | [Igbo](docs/README_ig.md) | [Yorùbá](docs/README_yo.md) | [isiXhosa](docs/README_xh.md) | [Malagasy](docs/README_mg.md) | [chiShona](docs/README_sn.md) | [Kinyarwanda](docs/README_rw.md) | [Soomaali](docs/README_so.md)

<div align="center">

![ChipPeek Logo](logo.png)

</div>

---

## Overview

ChipPeek is a minimal hardware monitoring tool that displays **CPU frequency, CPU temperature, GPU frequency, GPU temperature, VRAM usage, and memory usage** in a small floating widget on your desktop. It uses Windows' always-on-top window behavior to keep the widget visible above desktop windows.

Fullscreen visibility depends on the application and display mode. Exclusive fullscreen games may cover the widget; try windowed or borderless mode if this happens.

No bloat, no ads, no telemetry — just a clean, customizable overlay powered by [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor).

---

## Table of Contents

- [Languages](#languages)
- [Why ChipPeek?](#why-chippeek)
- [Features](#features)
- [Quick Start](#quick-start)
- [Usage](#usage)
- [System Requirements](#system-requirements)
- [Build as EXE](#build-as-exe)
- [Tech Stack](#tech-stack)
- [Project Structure](#project-structure)
- [Multi-language Support](#multi-language-support)
- [Configuration File](#configuration-file)
- [Contributing](#contributing)
- [License](#license)
- [Credits](#credits)
- [Developer](#developer)

---

## Why ChipPeek?

ChipPeek provides a compact view of the hardware readings you use most:

- Choose a vertical corner widget or a horizontal top bar.
- Select the metrics, language, font size, and transparency that suit your desktop.
- Run the portable EXE or inspect and customize the Python source under the MIT License.

---

## Features

- **Real-time monitoring**: CPU frequency, CPU temperature, GPU frequency, GPU temperature, VRAM usage, memory usage
- **Dual display modes**: Corner widget / Top bar, one-click switch
- **Always on top**: Uses Windows' topmost window behavior; fullscreen visibility depends on the application
- **Customizable display**: Freely choose which metrics to show, toggle between percentage/actual values
- **Auto-sizing**: Window width automatically adjusts to fit content
- **Adjustable style**: Window opacity, background transparency, font size all adjustable
- **Multi-language support**: 103 languages, auto-detects system language
- **Convenient operation**: Left-drag to move, right-click menu for quick settings, auto snap to screen edges
- **Configurable sampling**: 200ms - 3000ms adjustable refresh rate
- **Auto start**: Launch automatically on Windows login
- **Low resource usage**: Minimal footprint in background
- **Portable**: No installation required — just run the EXE

---

## Quick Start

### Option 1: Download EXE (Recommended)

1. Go to the [latest release](https://github.com/shanyuduo/ChipPeek/releases/latest)
2. Download `ChipPeek.exe`
3. Double-click to run (will automatically request admin privileges for CPU temperature and accurate frequency reading)

### Option 2: Run from Source

Use Python 3 with Tkinter on Windows. Run your terminal as administrator when you need sensor readings that require elevated privileges; `python main.py` does not request elevation automatically.

```powershell
# Clone the repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Install dependencies
python -m pip install -r requirements.txt pythonnet

# Run
python main.py
```

`pythonnet` provides the `clr` module used to load LibreHardwareMonitor. Install it explicitly: it is currently missing from `requirements.txt`. Sensor availability also depends on your hardware, drivers, and permissions.

---

## Usage

### Basic Operations

| Action | Description |
|------|------|
| Left drag | Move window position |
| Right click | Open menu (switch mode / settings / exit) |
| Auto snap | Automatically snaps within 20px of screen edges |

### Display Modes

- **Corner Widget**: All metrics arranged vertically, can be placed at any screen corner
- **Top Bar**: All metrics arranged horizontally, centered at the top of the screen by default

### Settings

Right-click the widget to open the settings menu:

- **Display mode**: Corner widget / Top bar
- **Widget position**: Bottom right / Bottom left / Top right / Top left
- **Window transparency**: The 0% - 100% slider maps to 100% - 15% window opacity
- **Background transparency**: 0 keeps the background solid; any value above 0 enables a transparent background. The current implementation switches transparency on or off rather than blending it gradually
- **Sampling interval**: 200ms - 3000ms data refresh rate
- **Font size**: 8 - 20 point font
- **Language**: 103 languages, auto-detects system language
- **Display metrics**: Toggle each metric independently
- **Display format**: VRAM / Memory can toggle between percentage or actual values
- **Auto start**: Run automatically when logging into Windows

---

## System Requirements

- Windows 10 / Windows 11
- Python 3 with Tkinter for running from source or building; the release EXE does not require a separate Python installation
- Administrator privileges (recommended), otherwise CPU temperature and accurate frequency may not be available
- .NET Framework 4.7.2 or higher (required by LibreHardwareMonitor)

---

## Build as EXE

Run these commands from the repository root on Windows:

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

After building, the EXE file is located at `dist/ChipPeek.exe`.

The `i18n` directory must be bundled so that the packaged application can load all 103 languages. The included `build.bat` uses the machine-specific path `C:\Python314\python.exe`; adjust that path before using it on another machine.

---

## Tech Stack

| Component | Technology |
|-----------|-----------|
| GUI | Tkinter |
| Hardware data | LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (NVIDIA GPU fallback) |
| System integration | pywin32 (window topmost, auto-start registry) |
| Internationalization | Custom JSON-based i18n system |
| Packaging | PyInstaller |

---

## Project Structure

```
ChipPeek/
├── main.py                  # Entry point
├── monitor_window.py        # Window UI and interaction logic
├── hardware_monitor.py      # Hardware data collection
├── config.py                # Configuration management
├── i18n.py                  # Internationalization
├── generate_docs.py         # Generate and check localized READMEs
├── generate_icon.py         # Icon generation script
├── admin.manifest           # UAC admin privilege manifest
├── app.ico                  # Application icon
├── logo.png                 # Project logo
├── requirements.txt         # Python dependencies
├── build.bat                # Build script for PyInstaller
├── docs/                    # Multi-language README files
│   └── README_*.md
├── i18n/                    # Translation files (JSON)
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/                    # Created by the build, not included in the checkout
    └── ChipPeek.exe         # Compiled executable
```

---

## Multi-language Support

ChipPeek includes **103 UI languages and 103 localized READMEs**. The available languages are registered in `i18n.py`, with UI translations in `i18n/*.json` and localized documentation in `docs/README_*.md`.

Want to add or improve a translation? See [Contributing](#contributing).

<details>
<summary><b>📖 View descriptions in all 103 languages / 查看全部 103 种语言简介</b></summary>

<details>
<summary><b>East Asia / 东亚</b></summary>

- **简体中文**: 一款轻量级 Windows 硬件监控悬浮窗工具。 CPU 频率、CPU 温度、GPU 频率、GPU 温度、显存占用、内存占用
- **繁體中文**: 一款輕量級 Windows 硬體監控懸浮窗工具。 CPU 頻率、CPU 溫度、GPU 頻率、GPU 溫度、顯存佔用、記憶體佔用
- **日本語**: 軽量なWindowsハードウェアモニタリングツール。 CPU周波数、CPU温度、GPU周波数、GPU温度、VRAM使用率、メモリ使用率
- **한국어**: 가벼운 Windows 하드웨어 모니터링 플로팅 위젯입니다. CPU 주파수, CPU 온도, GPU 주파수, GPU 온도, VRAM 사용량, 메모리 사용량

</details>

<details>
<summary><b>Southeast Asia / 东南亚</b></summary>

- **ไทย**: วิดเจ็ตลอยสำหรับตรวจสอบฮาร์ดแวร์บน Windows ที่ใช้ทรัพยากรน้อย ความถี่ CPU อุณหภูมิ CPU ความถี่ GPU อุณหภูมิ GPU การใช้ VRAM การใช้หน่วยความจำ
- **Tiếng Việt**: Một tiện ích giám sát phần cứng nổi nhẹ cho Windows. tần số CPU, nhiệt độ CPU, tần số GPU, nhiệt độ GPU, sử dụng VRAM, sử dụng bộ nhớ
- **Bahasa Indonesia**: Widget pemantauan perangkat keras mengambang yang ringan untuk Windows. frekuensi CPU, suhu CPU, frekuensi GPU, suhu GPU, penggunaan VRAM, penggunaan memori
- **Bahasa Melayu**: Widget pemantauan perkakasan terapung yang ringan untuk Windows. frekuensi CPU, suhu CPU, frekuensi GPU, suhu GPU, penggunaan VRAM, penggunaan memori
- **Filipino**: Isang magaan na Windows hardware monitoring floating widget. Dalas ng CPU, temperatura ng CPU, dalas ng GPU, temperatura ng GPU, paggamit ng VRAM, paggamit ng memorya
- **Basa Jawa**: Alat pemantau perangkat keras Windows sing entheng. Frekuensi CPU, suhu CPU, frekuensi GPU, suhu GPU, panggunaan VRAM, panggunaan memori
- **Basa Sunda**: Alat pemantau parabot keras Windows anu énténg. Frékuénsi CPU, suhu CPU, frékuénsi GPU, suhu GPU, pamakéan VRAM, pamakéan mémori
- **Cebuano**: Usa ka gamay nga himo sa pagbantay sa hardware sa Windows. Frequency sa CPU, temperatura sa CPU, frequency sa GPU, temperatura sa GPU, pag-gamit sa VRAM, pag-gamit sa memory
- **မြန်မာ**: Windows အတွက် ပေါ့ပေါ့ဆ သော လွင့်ပျံသော ဟာ့ဒ်ဝဲ စောင့်ကြည့်မှု ဗီဂျက်။ CPU ကြိမ်နှုန်း၊ CPU အပူချိန်၊ GPU ကြိမ်နှုန်း၊ GPU အပူချိန်၊ VRAM အသုံးပြုမှု၊ မှတ်ဉာဏ်အသုံးပြုမှု
- **ខ្មែរ**: ឧបករណ៍តាមដានផ្នែករឹងអណ្តែតសម្រាប់ Windows ដែលមានទម្ងន់ស្រាល។ ប្រេកង់ CPU សីតុណ្ហភាព CPU ប្រេកង់ GPU សីតុណ្ហភាព GPU ការប្រើប្រាស់ VRAM ការប្រើប្រាស់មេម៉ូរី
- **ລາວ**: ເຄື່ອງມືຕິດຕາມຮາດແວທີ່ເລື່ອຍໄດ້ສຳລັບ Windows ທີ່ມີນ້ຳໜັກເບົາ. ຄວາມຖີ່ CPU ອຸນຫະພູມ CPU ຄວາມຖີ່ GPU ອຸນຫະພູມ GPU ການໃຊ້ VRAM ການໃຊ້ຫນ່ວຍຄວາມຈໍາ

</details>

<details>
<summary><b>South Asia / 南亚</b></summary>

- **हिन्दी**: Windows के लिए एक हल्का फ्लोटिंग हार्डवेयर मॉनिटरिंग विजेट। CPU आवृत्ति, CPU तापमान, GPU आवृत्ति, GPU तापमान, VRAM उपयोग, मेमोरी उपयोग
- **বাংলা**: Windows-এর জন্য একটি হালকা ফ্লোটিং হার্ডওয়্যার মনিটরিং উইজেট। CPU ফ্রিকোয়েন্সি, CPU তাপমাত্রা, GPU ফ্রিকোয়েন্সি, GPU তাপমাত্রা, VRAM ব্যবহার, মেমরি ব্যবহার
- **தமிழ்**: Windows க்கான ஒரு இலகுரக மிதக்கும் கணினி மானிட்டர் சாதனம். CPU அதிர்வெண், CPU வெப்பநிலை, GPU அதிர்வெண், GPU வெப்பநிலை, VRAMபயன்பாடு, நினைவகப் பயன்பாடு
- **తెలుగు**: Windows కోసం ఒక తేలికపాటి ఫ్లోటింగ్ హార్డ్వేర్ మానిటరింగ్ విడ్జెట్. CPU ఫ్రీక్వెన్సీ, CPU ఉష్ణోగ్రత, GPU ఫ్రీక్వెన్సీ, GPU ఉష్ణోగ్రత, VRAM వినియోగం, మెమరీ వినియోగం
- **मराठी**: Windows साठी एक हलके वजनाचे फ्लोटिंग हार्डवेअर मॉनिटरिंग विजेट. CPU फ्रिक्वेन्सी, CPU तापमान, GPU फ्रिक्वेन्सी, GPU तापमान, VRAM वापर, मेमरी वापर
- **ગુજરાતી**: Windows માટે એક હળવું વજનનું ફ્લોટિંગ હાર્ડવેર મોનિટરિંગ વિજેટ. CPU ફ્રીક્વન્સી, CPU તાપમાન, GPU ફ્રીક્વન્સી, GPU તાપમાન, VRAM વપરાશ, મેમરી વપરાશ
- **ਪੰਜਾਬੀ**: Windows ਲਈ ਇੱਕ ਹਲਕਾ ਭਾਰ ਦਾ ਫਲੋਟਿੰਗ ਹਾਰਡਵੇਅਰ ਮਾਨੀਟਰਿੰਗ ਵਿਜੇਟ. CPU ਫ੍ਰੀਕੁਐਂਸੀ, CPU ਤਾਪਮਾਨ, GPU ਫ੍ਰੀਕੁਐਂਸੀ, GPU ਤਾਪਮਾਨ, VRAM ਵਰਤੋਂ, ਮੈਮੋਰੀ ਵਰਤੋਂ
- **ಕನ್ನಡ**: Windows ಗಾಗಿ ಈಗಾದರೂ ಹಗುರವಾದ ಫ್ಲೋಟಿಂಗ್ ಹಾರ್ಡ್ವೇರ್ ಮಾನಿಟರಿಂಗ್ ವಿಜೆಟ್. CPU ಆವರ್ತನ, CPU ತಾಪಮಾನ, GPU ಆವರ್ತನ, GPU ತಾಪಮಾನ, VRAM ಬಳಕೆ, ಮೆಮೊರಿ ಬಳಕೆ
- **മലയാളം**: Windows നായി ഒരു ഇളം ഭാരമുള്ള ഫ്ലോട്ടിംഗ് ഹാർഡ്വെയർ മോനിറ്ററിംഗ് വിജെറ്റ്. CPU ഫ്രീക്വൻസി, CPU താപനില, GPU ഫ്രീക്വൻസി, GPU താപനില, VRAM ഉപയോഗം, മെമ്മറി ഉപയോഗം
- **नेपाली**: Windows को लागि हल्का हार्डवेयर मोनिटरिंग फ्लोटिंग विजेट। CPU फ्रिक्वेन्सी, CPU तापक्रम, GPU फ्रिक्वेन्सी, GPU तापक्रम, VRAM प्रयोग, मेमोरी प्रयोग
- **සිංහල**: සැහැල්ලු Windows දෘඩාංග මොනිටර් ප්‍රදර්ශන විජටයකි. CPU සංඛ්‍යාතය, CPU උෂ්ණත්වය, GPU සංඛ්‍යාතය, GPU උෂ්ණත්වය, VRAM භාවිතය, මතක භාවිතය
- **اردو**: ونڈوز کے لیے ایک ہلکا پھلکا فلوٹنگ ہارڈویئر مانیٹرنگ وجیٹ۔ CPU فریکوئنسی، CPU درجہ حرارت، GPU فریکوئنسی، GPU درجہ حرارت، VRAM استعمال، میموری استعمال
- **سنڌي**: Windows لاءِ هلڪو هارڊويئر نگراني وارو وجاٽ. CPU فريڪوينسي، CPU گرمي پد، GPU فريڪوينسي، GPU گرمي پد، VRAM استعمال، ميموري استعمال

</details>

<details>
<summary><b>Central Asia & Mongolia / 中亚与蒙古</b></summary>

- **Қазақ**: Windows үшін жеңіл қозғалтқыштық аппараттық қамтама мониторингі виджеті. CPU жиілігі, CPU температурасы, GPU жиілігі, GPU температурасы, VRAM пайдаланылуы, жадтың пайдаланылуы
- **O'zbek**: Windows uchun engil suzuvchi apparat ta'minot monitoring vidjeti. CPU chastotasi, CPU harorati, GPU chastotasi, GPU harorati, VRAM foydalanishi, xotira foydalanishi
- **Кыргызча**: Windows үчүн жеңил катуу жабдык көзөмөлдөөчү калкып жүрүүчү виджет. CPU жыштыгы, CPU температурасы, GPU жыштыгы, GPU температурасы, VRAM колдонуусу, эстутум колдонуусу
- **Монгол**: Хөнгөн Windows тоног төхөөрөмжийн хяналтын хөвөгч виджет. CPU давтамж, CPU хэм, GPU давтамж, GPU хэм, VRAM хэрэглээ, санах ойн хэрэглээ
- **Türkmen**: Windows üçin ýeňil enjamçylyk synlagyň ýüzüp ýören widjeti. CPU ýygylygy, CPU temperaturasy, GPU ýygylygy, GPU temperaturasy, VRAM ulanylyşy, çeper ulanylyşy
- **Тоҷикӣ**: Абзори сабуки назорати сахтафзори Windows. Басомади CPU, ҳарорати CPU, басомади GPU, ҳарорати GPU, истифодаи VRAM, истифодаи ҳофиза
- **Татарча**: Windows өчен җиңел җиһазлыҡ мониторингы йөзә торган виджеты. CPU ешлыгы, CPU температурасы, GPU ешлыгы, GPU температурасы, VRAM куллануы, хәтер куллануы
- **Башҡортса**: Windows өсөн еңел ҡорамал күҙәтеү йөҙә торған виджеты. CPU йышлығы, CPU температураһы, GPU йышлығы, GPU температураһы, VRAM ҡулланыуы, хәтер ҡулланыуы

</details>

<details>
<summary><b>Middle East & West Asia / 中东与西亚</b></summary>

- **العربية**: أداة عائمة خفيفة لمراقبة الأجهزة على Windows. تردد CPU، درجة حرارة CPU، تردد GPU، درجة حرارة GPU، استخدام VRAM، استخدام الذاكرة
- **فارسی**: یک ویجت شناور سبک برای مانیتورینگ سخت‌افزار در ویندوز. فرکانس CPU، دمای CPU، فرکانس GPU، دمای GPU، استفاده از VRAM، استفاده از حافظه
- **עברית**: כלי ניטור חומרה צף קל ל-Windows. תדר CPU, טמפרטורת CPU, תדר GPU, טמפרטורת GPU, שימוש ב-VRAM, שימוש בזיכרון
- **پښتو**: د Windows لپاره سپکې سختوالي څارنې وړوندې ویجیټ. د CPU فریکونسي، د CPU تودوخه، د GPU فریکونسي، د GPU تودوخه، د VRAM کارونه، د حافظې کارونه
- **Kurdî**: Amûra sivik a çavdêriya hardware ya Windowsê ye. Frekansa CPU, germahiya CPU, frekansa GPU, germahiya GPU, bikaranîna VRAM, bikaranîna bîrê
- **Türkçe**: Windows için hafif bir kayan donanım izleme widget'ı. CPU frekansı, CPU sıcaklığı, GPU frekansı, GPU sıcaklığı, VRAM kullanımı, bellek kullanımı
- **ייִדיש**: א לייטווייט פלאָוטינג ווידגעט פֿאַר Windows האַרדוואַרע מאָניטאָרינג. CPU אָפטקייַט, CPU טעמפּעראַטור, GPU אָפטקייַט, GPU טעמפּעראַטור, VRAM באַניץ, זכּרון באַניץ

</details>

<details>
<summary><b>Europe - Germanic & Nordic / 日耳曼与北欧</b></summary>

- **English**: A lightweight Windows hardware monitoring floating widget. CPU frequency, CPU temperature, GPU frequency, GPU temperature, VRAM usage, memory usage
- **Deutsch**: Ein leichtes schwebendes Hardware-Überwachungs-Widget für Windows. CPU-Frequenz, CPU-Temperatur, GPU-Frequenz, GPU-Temperatur, VRAM-Nutzung, Speichernutzung
- **Nederlands**: Een lichtgewicht zwevend hardware monitoring widget voor Windows. CPU frequentie, CPU temperatuur, GPU frequentie, GPU temperatuur, VRAM gebruik, geheugengebruik
- **Svenska**: En lättviktsflytande hårdvaruövervakningswidget för Windows. CPU-frekvens, CPU-temperatur, GPU-frekvens, GPU-temperatur, VRAM-användning, minnesanvändning
- **Norsk**: En lettvekts flytende maskinvareovervåkingswidget for Windows. CPU-frekvens, CPU-temperatur, GPU-frekvens, GPU-temperatur, VRAM-bruk, minnebruk
- **Dansk**: En letvægts flydende hardware-overvågningswidget til Windows. CPU-frekvens, CPU-temperatur, GPU-frekvens, GPU-temperatur, VRAM-forbrug, hukommelsesforbrug
- **Suomi**: Kevyt kelluva laitteiston valvontawidget Windowsille. CPU-nopeus, CPU-lämpötila, GPU-nopeus, GPU-lämpötila, VRAM-käyttö, muistin käyttö
- **Íslenska**: Léttur Windows vélbúnaðaeftirlitsflutningsforritshluti. CPU tíðni, CPU hiti, GPU tíðni, GPU hiti, VRAM notkun, minnisnotkun
- **Føroyskt**: Eitt lætt Windows tól til vélbúnaðareftirlit. CPU tíðni, CPU hiti, GPU tíðni, GPU hiti, VRAM nýtsla, minnisnýtsla
- **Frysk**: In lichtgewicht sweevjend widget foar hardwaremonitoring op Windows. CPU-frekwinsje, CPU-temperatuer, GPU-frekwinsje, GPU-temperatuer, VRAM-gebrûk, ûnthâldgebrûk
- **Lëtzebuergesch**: E liicht schwiewend Widget fir Windows Hardware-Monitoring. CPU-Frequenz, CPU-Temperatur, GPU-Frequenz, GPU-Temperatur, VRAM-Notzung, Späichernotzung
- **Afrikaans**: 'n Liggewig drywende hardeware moniteringsapparaat vir Windows. CPU frekwensie, CPU temperatuur, GPU frekwensie, GPU temperatuur, VRAM gebruik, geheuegebruik

</details>

<details>
<summary><b>Europe - Romance / 罗曼语族</b></summary>

- **Español**: Un widget flotante ligero de monitorización de hardware para Windows. frecuencia de CPU, temperatura de CPU, frecuencia de GPU, temperatura de GPU, uso de VRAM, uso de memoria
- **Français**: Un widget flottant léger de surveillance matérielle pour Windows. fréquence CPU, température CPU, fréquence GPU, température GPU, utilisation VRAM, utilisation mémoire
- **Português**: Um widget flutuante leve de monitoramento de hardware para Windows. frequência CPU, temperatura CPU, frequência GPU, temperatura GPU, uso de VRAM, uso de memória
- **Italiano**: Un widget fluttuante leggero per il monitoraggio hardware su Windows. frequenza CPU, temperatura CPU, frequenza GPU, temperatura GPU, utilizzo VRAM, utilizzo memoria
- **Català**: Un widget flotant lleuger de monitoratge de maquinari per a Windows. freqüència CPU, temperatura CPU, freqüència GPU, temperatura GPU, ús VRAM, ús de memòria
- **Galego**: Un widget flotante lixeiro de monitorización hardware para Windows. Frecuencia CPU, temperatura CPU, frecuencia GPU, temperatura GPU, uso de VRAM, uso de memoria
- **Euskara**: Windows hardware monitor widget arin bat. CPU maiztasuna, CPU tenperatura, GPU maiztasuna, GPU tenperatura, VRAM erabilera, memoria erabilera
- **Asturianu**: Una ferramienta llixera de widget flotante pa supervisión de hardware en Windows. frecuencia CPU, temperatura CPU, frecuencia GPU, temperatura GPU, usu de VRAM, usu de memoria
- **Occitan**: Una aisina leugièra de susvelhança materiala Windows en widget flotant. frequéncia CPU, temperatura CPU, frequéncia GPU, temperatura GPU, utilizacion VRAM, utilizacion memòria
- **Corsu**: Un strumentu leggju per surveglià l'hardware di Windows. Frequenza CPU, timperatura CPU, frequenza GPU, timperatura GPU, usu VRAM, usu di a memoria
- **Rumantsch**: In utensil lev per controllar il hardware da Windows. Frequenza CPU, temperatura CPU, frequenza GPU, temperatura GPU, niz da VRAM, niz da memoria
- **Brezhoneg**: Un ostillic'h skañv evit diwall periant Windows. Frekañs CPU, gwrez CPU, frekañs GPU, gwrez GPU, arver VRAM, arver ar vemor
- **Cymraeg**: Erfaun monitro caledn Windows ysgafn. Amlder CPU, tymheredd CPU, amlder GPU, tymheredd GPU, defnydd VRAM, defnydd cof
- **Gaeilge**: Giúirléid shnámhach éadrom do mhonatóireacht crua-earraí Windows. Minicíocht CPU, teocht CPU, minicíocht GPU, teocht GPU, úsáid VRAM, úsáid cuimhne
- **Gàidhlig**: Inneal aotrom airson monataireadh bathar-cruaidh Windows. Tricead CPU, teòthachd CPU, tricead GPU, teòthachd GPU, cleachdadh VRAM, cleachdadh cuimhne
- **Malti**: Widget liġġi ħafifa ta' monitoring tal-hardware ta' Windows. Frekwenza tal-CPU, temperatura tal-CPU, frekwenza tal-GPU, temperatura tal-GPU, użu tal-VRAM, użu tal-memorja

</details>

<details>
<summary><b>Europe - Slavic & Cyrillic / 斯拉夫语族</b></summary>

- **Русский**: Легковесный плавающий виджет мониторинга оборудования для Windows. частота CPU, температура CPU, частота GPU, температура GPU, использование VRAM, использование памяти
- **Українська**: Легкий плаваючий віджет для моніторингу апаратного забезпечення для Windows. частота CPU, температура CPU, частота GPU, температура GPU, використання VRAM, використання пам'яті
- **Polski**: Lekki widget monitorowania sprzętu dla Windows. częstotliwość CPU, temperatura CPU, częstotliwość GPU, temperatura GPU, zużycie VRAM, zużycie pamięci
- **Čeština**: Lehký plovoucí widget pro monitorování hardwaru ve Windows. frekvence CPU, teplota CPU, frekvence GPU, teplota GPU, využití VRAM, využití paměti
- **Slovenčina**: Ľahký plávajúci widget na monitorovanie hardvéru pre Windows. frekvencia CPU, teplota CPU, frekvencia GPU, teplota GPU, využitie VRAM, využitie pamäte
- **Български**: Лек плаващ уиджет за мониторинг на хардуер за Windows. честота на CPU, температура на CPU, честота на GPU, температура на GPU, използване на VRAM, използване на памет
- **Hrvatski**: Lagani plutajući widget za nadzor hardvera za Windows. frekvencija CPU, temperatura CPU, frekvencija GPU, temperatura GPU, korištenje VRAM, korištenje memorije
- **Српски**: Лаки плавајући виџет за надзор хардвера за Windows. фреквенција CPU, температура CPU, фреквенција GPU, температура GPU, коришћење VRAM, коришћење меморије
- **Slovenščina**: Lahek plavajoči pripomoček za nadzor strojne opreme za Windows. frekvenca CPU, temperatura CPU, frekvenca GPU, temperatura GPU, poraba VRAM, poraba pomnilnika
- **Македонски**: Лесен Windows хардверски монитор лебдечки виџет. CPU фреквенција, CPU температура, GPU фреквенција, GPU температура, VRAM употреба, употреба на меморија
- **Беларуская**: Лёгкі плаваючы віджэт для маніторынга абсталявання Windows. частата CPU, тэмпература CPU, частата GPU, тэмпература GPU, выкарыстанне VRAM, выкарыстанне памяці

</details>

<details>
<summary><b>Europe - Other / 欧洲其他</b></summary>

- **Ελληνικά**: Ένα ελαφρύ επιπλέον widget παρακολούθησης υλικού για Windows. συχνότητα CPU, θερμοκρασία CPU, συχνότητα GPU, θερμοκρασία GPU, χρήση VRAM, χρήση μνήμης
- **Magyar**: Egy könnyű súlyú lebegő hardvermonitorozó widget Windowshez. CPU frekvencia, CPU hőmérséklet, GPU frekvencia, GPU hőmérséklet, VRAM használat, memória használat
- **Română**: Un widget ușor de monitorizare hardware plutitor pentru Windows. frecvență CPU, temperatură CPU, frecvență GPU, temperatură GPU, utilizare VRAM, utilizare memorie
- **Eesti**: Kerge liikuv riistvara monitooringu vidin Windowsile. CPU sagedus, CPU temperatuur, GPU sagedus, GPU temperatuur, VRAM kasutuse, mälukasutuse
- **Latviešu**: Viegli peldošs aparatūras monitoringa logrīks Windows operētājsistēmai. CPU frekvence, CPU temperatūra, GPU frekvence, GPU temperatūra, VRAM izmantošana, atmiņas izmantošana
- **Lietuvių**: Lengvas plaukiojantis aparatinės įrangos stebėjimo valdiklis Windows operacinei sistemai. CPU dažnis, CPU temperatūra, GPU dažnis, GPU temperatūra, VRAM naudojimas, atminties naudojimas

</details>

<details>
<summary><b>Africa / 非洲</b></summary>

- **Kiswahili**: Zana ya ufuatiliaji wa vifaa vya kimataifa yenye uzito mdogo kwa Windows. Mzunguko wa CPU, joto la CPU, mzunguko wa GPU, joto la GPU, utumizi wa VRAM, utumizi wa kumbukumbu
- **አማርኛ**: ለ Windows ቀላል ክብደት ያለው የሚንሸራተት የሃርድዌር ክትትል መሳሪያ። የ CPU ድግግሞሽ፣ የ CPU ሙቀት፣ የ GPU ድግግሞሽ፣ የ GPU ሙቀት፣ VRAM አጠቃቀም፣ የማህደረ ትውስታ አጠቃቀም
- **Hausa**: Kayan aiki mai sauqi na Windows don kula da kayan aikin lissafi ta hanyar wijet mai tunawa. Mitar CPU, zafin CPU, mitar GPU, zafin GPU, amfani da VRAM, amfani da tunani
- **Igbo**: Ngwaọrụ Windows dị mfe maka ịlele igwe na widget na-ese n'elu. Mitar CPU, ọnụ CPU, mitar GPU, ọnụ GPU, ojiji VRAM, ojiji echiche
- **Yorùbá**: Ohun èlò Windows kékèké láti wo ipò ohun èlò pẹ̀lú widget tí ó n ṣàfìha. Ìgbohùn CPU, ìwọ̀n CPU, ìgbohùn GPU, ìwọ̀n GPU, ìlò VRAM, ìlò ìrántí
- **isiXhosa**: Isixhobo esilula sokuqapha izixhobo kwi-Windows esebenza njengesixhobo esihamba phezulu. Isinqumla se-CPU, ithemprisha ye-CPU, isinqumla se-GPU, ithemprisha ye-GPU, ukusebenzisa i-VRAM, ukusebenzisa inkumbulo
- **isiZulu**: Isithonzi sokulungisa izinhlelo ezibekwa ezintathini ze-Windows ezisendlala. Isilinganiso se-CPU, izinga lokushisa se-CPU, isilinganiso se-GPU, izinga lokushisa se-GPU, ukusetshenziswa kwe-VRAM, ukusetshenziswa kwememori
- **Malagasy**: Fitaovana maivana fanaraha-maso hardware Windows mivelatra. Hatingan'ny CPU, hafanana CPU, hatingan'ny GPU, hafanana GPU, fampiasana VRAM, fampiasana fitadidiana
- **chiShona**: Software yakaderera yokutarira hardware yeWindows. Frequency CPU, kudziya CPU, frequency GPU, kudziya GPU, kushandiswa VRAM, kushandiswa ndangariro
- **Kinyarwanda**: Igikoresho cyoroshye cyo kugenzura hardware ya Windows kigarambuje. Ubwisubire bwa CPU, ubushyuhe bwa CPU, ubwisubire bwa GPU, ubushyuhe bwa GPU, imikoreshereze VRAM, imikoreshereze y'umwanya w'ibyibutsa
- **Soomaali**: Qalab fudud oo kormeera hardware Windows oo kor u fadhiya. Tirtirka CPU, kuleylka CPU, tirtirka GPU, kuleylka GPU, isticmaalka VRAM, isticmaalka xusuusta

</details>

<details>
<summary><b>Constructed & Other / 人造与其他</b></summary>

- **Esperanto**: Malpeza ŝveba fenestreto por Windows aparatmonitorado. CPU frekvenco, CPU temperaturo, GPU frekvenco, GPU temperaturo, VRAM uzado, memoro uzado
- **བོད་སྐད**: Windows སྒྲིག་ཆས་ལྟ་ཞིབ་ཡོ་བྱད་ཡང་མོ་ཞིག ཡིན། CPU འགྱུར་ཚད། CPU དྲོད་ཚད། GPU འགྱུར་ཚད། GPU དྲོད་ཚད། VRAM བེད་སྤྱོད། དྲན་ཚད་བེད་སྤྱོད།
- **ქართული**: მსუბუქი Windows ტექნიკის მონიტორინგის მცურავი ვიჯეტი. CPU სიხშირე, CPU ტემპერატურა, GPU სიხშირე, GPU ტემპერატურა, VRAM მოხმარება, მეხსიერების მოხმარება
- **Հայերեն**: Թեթև լողացող վիջեթ Windows-ի սարքավորումների մոնիտորինգի համար։ CPU հաճախականություն, CPU ջերմաստիճան, GPU հաճախականություն, GPU ջերմաստիճան, VRAM օգտագործում, հիշողության օգտագործում

</details>

</details>

---

## Configuration File

Settings are saved automatically to `config.json`, beside `ChipPeek.exe` in a packaged release or beside `main.py` when running from source. Keep the application in a writable directory so settings can be saved.

---

## Contributing

Contributions are welcome! Whether it's a bug report, feature suggestion, translation improvement, or code contribution — all are appreciated.

### How to Contribute

1. **Bug reports / Feature requests**: Open an [Issue](https://github.com/shanyuduo/ChipPeek/issues)
2. **Translations**: Edit JSON files in `i18n/`, preserving the keys in `i18n/en.json`. New languages also need an entry in `LANGUAGES` in `i18n.py` and a matching template in `READMES` in `generate_docs.py`
3. **Code**: Fork the repo, make your changes, and submit a Pull Request

Localized README content is maintained in `generate_docs.py`. Update its templates and run:

```powershell
python -m json.tool i18n/en.json
python generate_docs.py
python generate_docs.py --check
```

Use `python -m json.tool i18n/<language-code>.json` to check the JSON file you changed. The documentation generator uses the runtime language registry for language counts and navigation, checks that every language has a README template, and leaves this root README unchanged. Update the root README separately when shared documentation changes.

### Recommended GitHub Topics

If you fork or reference this project, consider using these topics:

```
hardware-monitor  cpu-temperature  gpu-monitor  system-monitor  windows
overlay  floating-widget  tkinter  librehardwaremonitor  desktop-widget
cpu-frequency  gpu-temperature  vram-monitor  performance-overlay  lightweight
```

---

## License

This project is licensed under the MIT License — see the [LICENSE](LICENSE) file for details.

---

## Credits

- [LibreHardwareMonitor](https://github.com/LibreHardwareMonitor/LibreHardwareMonitor) — Hardware monitoring library
- [psutil](https://github.com/giampaolo/psutil) — Cross-platform system monitoring
- [PyInstaller](https://pyinstaller.org/) — Python packaging tool

---

## Developer

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Project URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

---

<div align="center">

### Star History

[![Star History Chart](https://api.star-history.com/svg?repos=shanyuduo/ChipPeek&type=Date)](https://star-history.com/#shanyuduo/ChipPeek&Date)

If you find ChipPeek useful, please consider giving it a star!

</div>
