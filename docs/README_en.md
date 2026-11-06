# ChipPeek

A lightweight Windows hardware monitoring floating widget.

> **Other Languages**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | **English** | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Features

- **Real-time monitoring**: CPU frequency, CPU temperature, GPU frequency, GPU temperature, VRAM usage, memory usage
- **Dual display modes**: Corner widget / Top bar, one-click switch
- **Customizable display**: Freely choose which metrics to show, toggle between percentage/actual values
- **Always on top**: Stays above desktop windows. Fullscreen visibility depends on the application and display mode
- **Auto-sizing**: Window width automatically adjusts to fit content
- **Adjustable style**: Window opacity, background transparency, font size all adjustable
- **Multi-language support**: 103 languages, auto-detects system language
- **Convenient operation**: Left-drag to move, right-click menu for quick settings, auto snap to screen edges
- **Configurable sampling**: 200ms - 3000ms adjustable
- **Auto start**: Launch automatically on Windows login
- **Low resource usage**: Minimal footprint in background

## Quick Start

### Direct Use

Download [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) and double-click to run (will automatically request admin privileges for CPU temperature and accurate frequency reading).

### Run from Source

```powershell
# Clone the repository
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Install dependencies
python -m pip install -r requirements.txt pythonnet

# Run
python main.py
```

## System Requirements

- Windows 10 / Windows 11
- Administrator privileges (recommended), otherwise CPU temperature and accurate frequency may not be available
- .NET Framework 4.7.2 or higher (required by LibreHardwareMonitor)
- Python 3 + Tkinter (Run from Source)

## Build as EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

After building, the EXE file is located at `dist/ChipPeek.exe`.

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

- **Display mode**: Corner widget / Top bar
- **Widget position**: Bottom right / Bottom left / Top right / Top left
- **Window opacity**: Slider 0% - 100% maps to window opacity 100% - 15%
- **Background transparency**: 0 keeps the background solid; any value above 0 makes it transparent
- **Sampling interval**: 200ms - 3000ms data refresh rate
- **Font size**: 8 - 20 point font
- **Language**: 103 languages, auto-detects system language
- **Display metrics**: Toggle each metric independently
- **Display format**: VRAM / Memory can toggle between percentage or actual values
- **Auto start**: Run automatically when logging into Windows

## Tech Stack

- **GUI**：Tkinter
- **Hardware data**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (NVIDIA GPU fallback)
- **System integration**：pywin32 (window topmost, auto-start registry)
- **Packaging**：PyInstaller

## Project Structure

```
ChipPeek/
├── main.py                  # Entry point
├── monitor_window.py        # Window UI and interaction logic
├── hardware_monitor.py      # Hardware data collection
├── config.py                # Configuration management
├── i18n.py                  # Internationalization
├── generate_docs.py
├── generate_icon.py         # Icon generation script
├── admin.manifest           # UAC admin privilege manifest
├── app.ico                  # Application icon
├── logo.png
├── requirements.txt         # Python dependencies
├── build.bat
├── docs/                    # Multi-language docs
│   └── README_*.md
├── i18n/                    # Translation files
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Compiled executable
```

## Configuration File

Settings are saved automatically to `config.json`, beside `ChipPeek.exe` in a packaged release or beside `main.py` when running from source.

## License

[MIT License](../LICENSE)

## Developer

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Project URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Credits

- LibreHardwareMonitor - Hardware monitoring library
- psutil - Cross-platform system monitoring
- PyInstaller - Python packaging tool
