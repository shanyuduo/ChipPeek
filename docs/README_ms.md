# ChipPeek

Widget pemantauan perkakasan terapung yang ringan untuk Windows.

> **Bahasa lain**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | **Bahasa Melayu** | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Ciri-ciri

- **Pemantauan masa nyata**: frekuensi CPU, suhu CPU, frekuensi GPU, suhu GPU, penggunaan VRAM, penggunaan memori
- **Dua mod paparan**: widget penjuru / bar atas, tukar dengan satu klik
- **Paparan boleh disesuaikan**: pilih metrik mana yang hendak dipaparkan secara bebas, tukar antara peratusan/nilai sebenar
- **Sentiasa di atas**: kekal di atas semua tetingkap. Keterlihatan skrin penuh bergantung pada aplikasi dan mod paparan
- **Saiz automatik**: lebar tetingkap diselaraskan secara automatik mengikut kandungan
- **Gaya boleh laras**: ketelusan tetingkap, ketelusan latar belakang, saiz fon - semuanya boleh laras
- **Sokongan berbilang bahasa**: 103 bahasa, mengesan bahasa sistem secara automatik
- **Operasi mudah**: alihkan dengan seret klik kiri, menu klik kanan untuk tetapan pantas, snap automatik ke tepi skrin
- **Kekerapan pensampelan boleh dikonfigurasi**: 200ms - 3000ms boleh laras
- **Bermula automatik**: bermula secara automatik apabila log masuk ke Windows
- **Penggunaan sumber rendah**: kesan minimum di latar belakang

## Mula Pantas

### Guna Terus

Muat turun [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) dan klik dua kali untuk menjalankan (akan meminta keistimewaan pentadbir secara automatik untuk suhu CPU dan bacaan frekuensi yang tepat).

### Jalankan dari Sumber

```powershell
# Klon repositori
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Pasang kebergantungan
python -m pip install -r requirements.txt pythonnet

# Jalankan
python main.py
```

## Keperluan Sistem

- Windows 10 / Windows 11
- Keistimewaan pentadbir (disyorkan), jika tidak suhu CPU dan frekuensi tepat mungkin tidak tersedia
- .NET Framework 4.7.2 atau lebih tinggi (diperlukan oleh LibreHardwareMonitor)
- Python 3 + Tkinter (Jalankan dari Sumber)

## Bina sebagai EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Selepas pembinaan, fail EXE terletak di `dist/ChipPeek.exe`.

## Penggunaan

### Operasi Asas

| Operasi | Penerangan |
|------|------|
| Seret klik kiri | Alihkan kedudukan tetingkap |
| Klik kanan | Buka menu (tukar mod / tetapan / keluar) |
| Snap automatik | Secara automatik snap dalam 20px dari tepi skrin |

### Mod Paparan

- **Widget penjuru**: semua metrik disusun menegak, boleh diletakkan di mana-mana penjuru skrin
- **Bar atas**: semua metrik disusun mendatar, secara lalai berpusat di bahagian atas skrin

### Tetapan

- **Mod paparan**: widget penjuru / bar atas
- **Kedudukan widget**: bawah kanan / bawah kiri / atas kanan / atas kiri
- **Ketelusan tetingkap**: Peluncur 0% - 100% sepadan dengan kelegapan tetingkap 100% - 15%
- **Ketelusan latar belakang**: 0 mengekalkan latar legap; sebarang nilai melebihi 0 menjadikannya telus
- **Selang pensampelan**: 200ms - 3000ms kadar muat semula data
- **Saiz fon**: 8 - 20 mata
- **Bahasa**: 103 bahasa, mengesan bahasa sistem secara automatik
- **Metrik paparan**: togol setiap metrik secara bebas
- **Format paparan**: VRAM / Memori boleh bertukar antara peratusan atau nilai sebenar
- **Bermula automatik**: jalankan secara automatik apabila log masuk ke Windows

## Teknologi

- **GUI**：Tkinter
- **Data perkakasan**：LibreHardwareMonitorLib (melalui pythonnet), psutil, pynvml (sandaran untuk GPU NVIDIA)
- **Integrasi sistem**：pywin32 (tetingkap sentiasa di atas, pendaftaran permulaan automatik)
- **Pembungkusan**：PyInstaller

## Struktur Projek

```
ChipPeek/
├── main.py                  # Titik masuk
├── monitor_window.py        # UI tetingkap dan logik interaksi
├── hardware_monitor.py      # Pengumpulan data perkakasan
├── config.py                # Pengurusan konfigurasi
├── i18n.py                  # Antarabangsa
├── generate_docs.py
├── generate_icon.py         # Skrip penjanaan ikon
├── admin.manifest           # Manifest keistimewaan pentadbir UAC
├── app.ico                  # Ikon aplikasi
├── logo.png
├── requirements.txt         # Kebergantungan Python
├── build.bat
├── docs/                    # Dokumentasi berbilang bahasa
│   └── README_*.md
├── i18n/                    # Fail terjemahan
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Fail boleh laku yang disusun
```

## Fail Konfigurasi

Fail `config.json` disimpan dalam direktori yang sama dengan `ChipPeek.exe` / `main.py` dan mengandungi semua tetapan boleh laras. Tetapan disimpan secara automatik apabila diubah.

## Lesen

[MIT License](../LICENSE)

## Pembangun

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL Projek: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kredit

- LibreHardwareMonitor - Perpustakaan pemantauan perkakasan
- psutil - Pemantauan sistem merentas platform
- PyInstaller - Alat pembungkusan Python
