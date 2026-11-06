# ChipPeek

Alat pemantau parabot keras Windows anu énténg.

> **Basa Lianna**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | **Basa Sunda** | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Fitur

- **Pemantauan real-time**: Frékuénsi CPU, suhu CPU, frékuénsi GPU, suhu GPU, pamakéan VRAM, pamakéan mémori
- **Dua mode témbong**: Widget juru / Bar luhur, sakali klik ganti
- **Témbong anu bisa disaluyukeun**: Bisa milih metrik anu ditémbongkeun, ganti perséntase/nilai aktuel
- **Tetep di luhur**: Tetep di luhur sakabéh jandela. Katémbong dina layar pinuh gumantung kana aplikasi jeung mode tampilan
- **Otomatis ukuran**: Legana jandela otomatis nurutan eusi
- **Gaya anu bisa diatur**: Opacity jandela, transparansi latar, ukuran font kabéh bisa diatur
- **Dukungan multi-basa**: 103 basa, otomatis ngadeteksi basa sistem
- **Operasi gampang**: Sérét kénca pikeun mindahkeun, klik katuhu pikeun menu gancang, auto snap pinggir layar
- **Sampling anu bisa diatur**: 200ms - 3000ms
- **Mimiti otomatis**: Otomatis dimimitian nalika login Windows
- **Pamakéan sumber daya minimal**: Jejak minimal di latar

## Mimitian Gancang

### Paké Langsung

Unduh [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) teras klik ganda pikeun muka (bakal menta hak admin pikeun maca suhu CPU jeung frékuénsi anu akurat).

### Muka tina Sumber

```powershell
# Kloning repositori
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instal dependensi
python -m pip install -r requirements.txt pythonnet

# Muka
python main.py
```

## Syarat Sistem

- Windows 10 / Windows 11
- Hak administrator (dianjurkeun), upami teu suhu CPU jeung frékuénsi anu akurat bisa teu sayogi
- .NET Framework 4.7.2 atawa leuwih luhur (dibutuhkeun ku LibreHardwareMonitor)
- Python 3 + Tkinter (Muka tina Sumber)

## Jadi EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Sanggeus diwangun, file EXE aya di `dist/ChipPeek.exe`.

## Pamakéan

### Operasi Dasar

| Aksi | Katerangan |
|------|------|
| Sérét kénca | Mindahkeun posisi jandela |
| Klik katuhu | Buka menu (ganti mode / sétingan / kaluar) |
| Auto snap | Otomatis snap dina 20px ti pinggir layar |

### Mode Témbong

- **Widget juru**: Sakabéh metrik disusun nangtung, bisa ditepikeun dina mana waé juru layar
- **Bar luhur**: Sakabéh metrik disusun ngahorizontal, default di tengah luhur layar

### Sétingan

- **Mode témbong**: Widget juru / Bar luhur
- **Posisi widget**: Handap katuhu / Handap kénca / Luhur katuhu / Luhur kénca
- **Opacity jandela**: Geseran 0% - 100% sarua jeung opasitas jandéla 100% - 15%
- **Transparansi latar**: 0 ngajaga latar tukang teu tembus; nilai leuwih ti 0 ngajadikeun transparan
- **Interval sampling**: 200ms - 3000ms laju anyar data
- **Ukuran font**: 8 - 20 titik font
- **Basa**: 103 basa, otomatis ngadeteksi basa sistem
- **Metrik témbong**: Bisa dirobah unggal metrik
- **Format témbong**: VRAM / Mémori bisa ganti perséntase atawa nilai aktuel
- **Mimiti otomatis**: Otomatis dimimitian nalika login Windows

## Stack Téknologi

- **GUI**：Tkinter
- **Data hardware**：LibreHardwareMonitorLib (ngaliwatan pythonnet), psutil, pynvml (backup NVIDIA GPU)
- **Integrasi sistem**：pywin32 (jandela topmost, registri auto-start)
- **Packaging**：PyInstaller

## Struktur Proyék

```
ChipPeek/
├── main.py                  # Entry point
├── monitor_window.py        # UI jandela jeung logika interaksi
├── hardware_monitor.py      # Ngumpulkeun data hardware
├── config.py                # Manajemén konfigurasi
├── i18n.py                  # Internasionalisasi
├── generate_docs.py
├── generate_icon.py         # Skrip ngagenerative ikon
├── admin.manifest           # Manifest hak admin UAC
├── app.ico                  # Ikon aplikasi
├── logo.png
├── requirements.txt         # Dependensi Python
├── build.bat
├── docs/                    # Dokumén multi-basa
│   └── README_*.md
├── i18n/                    # File tarjamahan
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # DLL LibreHardwareMonitorLib
└── dist/
    └── ChipPeek.exe         # Executable kompilasi
```

## File Konfigurasi

File `config.json` diteundeun dina diréktori anu sarua jeung `ChipPeek.exe` / `main.py`, ngandung sakabéh sétingan. Sétingan diteundeun otomatis nalika dirobah.

## Lisénsi

[MIT License](../LICENSE)

## Pamekar

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL Proyék: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kridit

- LibreHardwareMonitor - Perpustakaan pemantauan hardware
- psutil - Pemantauan sistem cross-platform
- PyInstaller - Alat packaging Python
