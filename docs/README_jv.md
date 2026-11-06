# ChipPeek

Alat pemantau perangkat keras Windows sing entheng.

> **Basa Liyane**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | **Basa Jawa** | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Fitur

- **Pemantauan real-time**: Frekuensi CPU, suhu CPU, frekuensi GPU, suhu GPU, panggunaan VRAM, panggunaan memori
- **Rong mode tampilan**: Widget sudut / Bar atas, siji klik ganti
- **Tampilan sing bisa disesuaikan**: Bisa milih metrik sing ditampilake, ganti persentase/nilai aktual
- **Tansah ing ndhuwur**: Tetep ing ndhuwur kabeh jendela. Katon ing layar kebak gumantung marang aplikasi lan mode tampilan
- **Otomatis ukuran**: Ambane jendela otomatis miturut konten
- **Gaya sing bisa diatur**: Opacity jendela, transparansi latar, ukuran font kabeh bisa diatur
- **Dhukungan multi-basa**: 103 basa, otomatis ndeteksi basa sistem
- **Operasi gampang**: Seret kiwa kanggo mindahake, klik tengen kanggo menu cepet, auto snap pinggir layar
- **Sampling sing bisa diatur**: 200ms - 3000ms
- **Mulai otomatis**: Otomatis diwiwiti nalika login Windows
- **Panggunaan sumber daya minimal**: Jejak minimal ing latar

## Wiwitan Cepet

### Nganggo Langsung

Ngundhuh [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) banjur klik pindho kanggo mbukak (bakal njaluk hak admin kanggo maca suhu CPU lan frekuensi sing akurat).

### Mbukak saka Sumber

```powershell
# Kloning repositori
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instal dependensi
python -m pip install -r requirements.txt pythonnet

# Mbukak
python main.py
```

## Syarat Sistem

- Windows 10 / Windows 11
- Hak administrator (disaranake), yen ora suhu CPU lan frekuensi sing akurat bisa ora kasedhiya
- .NET Framework 4.7.2 utawa luwih dhuwur (dibutuhake dening LibreHardwareMonitor)
- Python 3 + Tkinter (Mbukak saka Sumber)

## Dadi EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Sawise dibangun, file EXE ana ing `dist/ChipPeek.exe`.

## Panggunaan

### Operasi Dasar

| Aksi | Katrangan |
|------|------|
| Seret kiwa | Mindahake posisi jendela |
| Klik tengen | Buka menu (ganti mode / setelan / metu) |
| Auto snap | Otomatis snap ing 20px saka pinggir layar |

### Mode Tampilan

- **Widget sudut**: Kabeh metrik disusun vertikal, bisa diselehake ing sembarang sudut layar
- **Bar atas**: Kabeh metrik disusun horisontal, default ing tengah ndhuwur layar

### Setelan

- **Mode tampilan**: Widget sudut / Bar atas
- **Posisi widget**: Ngisor kanan / Ngisor kiri / Nduwur kanan / Nduwur kiri
- **Opacity jendela**: Slider 0% - 100% cocog karo opasitas jendhela 100% - 15%
- **Transparansi latar**: 0 ndadekake latar mburi tetep ora tembus; nilai luwih saka 0 ndadekake transparan
- **Interval sampling**: 200ms - 3000ms angkaanyar data
- **Ukuran font**: 8 - 20 titik font
- **Basa**: 103 basa, otomatis ndeteksi basa sistem
- **Metrik tampilan**: Bisa diowahi saben metrik
- **Format tampilan**: VRAM / Memori bisa ganti persentase utawa nilai aktual
- **Mulai otomatis**: Otomatis diwiwiti nalika login Windows

## Stack Teknologi

- **GUI**：Tkinter
- **Data hardware**：LibreHardwareMonitorLib (liwat pythonnet), psutil, pynvml (backup NVIDIA GPU)
- **Integrasi sistem**：pywin32 (jendela topmost, registri auto-start)
- **Packaging**：PyInstaller

## Struktur Proyek

```
ChipPeek/
├── main.py                  # Entry point
├── monitor_window.py        # UI jendela lan logika interaksi
├── hardware_monitor.py      # Ngumpulake data hardware
├── config.py                # Manajemen konfigurasi
├── i18n.py                  # Internasionalisasi
├── generate_docs.py
├── generate_icon.py         # Skrip nggawe ikon
├── admin.manifest           # Manifest hak admin UAC
├── app.ico                  # Ikon aplikasi
├── logo.png
├── requirements.txt         # Dependensi Python
├── build.bat
├── docs/                    # Dokumen multi-basa
│   └── README_*.md
├── i18n/                    # File terjemahan
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # DLL LibreHardwareMonitorLib
└── dist/
    └── ChipPeek.exe         # Executable kompilasi
```

## File Konfigurasi

File `config.json` disimpen ing direktori sing padha karo `ChipPeek.exe` / `main.py`, ngemot kabeh setelan. Setelan disimpen otomatis nalika diganti.

## Lisensi

[MIT License](../LICENSE)

## Pangembang

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL Proyek: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kredit

- LibreHardwareMonitor - Perpustakaan pemantauan hardware
- psutil - Pemantauan sistem cross-platform
- PyInstaller - Alat packaging Python
