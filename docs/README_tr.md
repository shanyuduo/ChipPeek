# ChipPeek

Windows için hafif bir kayan donanım izleme widget'ı.

> **Diğer Diller**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | **Türkçe** | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Özellikler

- **Gerçek zamanlı izleme**: CPU frekansı, CPU sıcaklığı, GPU frekansı, GPU sıcaklığı, VRAM kullanımı, bellek kullanımı
- **İki görüntüleme modu**: Köşe widget'ı / üst çubuk, tek tıkla geçiş
- **Özelleştirilebilir görüntüleme**: Hangi metriklerin gösterileceğini serbestçe seçin, yüzde/gerçek değerler arasında geçiş yapın
- **Her zaman en üstte**: Tüm pencerelerin üzerinde kalır. Tam ekranda görünürlük uygulamaya ve görüntü moduna bağlıdır
- **Otomatik boyut**: Pencere genişliği içeriğe göre otomatik olarak ayarlanır
- **Ayarlanabilir stil**: Pencere opaklığı, arka plan şeffaflığı, yazı tipi boyutu - hepsi ayarlanabilir
- **Çok dilli destek**: 103 dil, sistem dilini otomatik olarak algılar
- **Kullanışlı çalıştırma**: Taşımak için sol tıkla sürükleyin, hızlı ayarlar için sağ tık menüsü, ekran kenarlarına otomatik yapışma
- **Yapılandırılabilir örnekleme**: 200ms - 3000ms ayarlanabilir
- **Otomatik başlatma**: Windows oturum açmada otomatik olarak başlar
- **Düşük kaynak kullanımı**: Arka planda minimum ayak izi

## Hızlı Başlangıç

### Doğrudan Kullanım

[`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) dosyasını indirin ve çalıştırmak için çift tıklayın (CPU sıcaklığı ve doğru frekans okuması için otomatik olarak yönetici izni isteyecektir).

### Kaynak Koddan Çalıştırma

```powershell
# Depoyu klonlayın
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Bağımlılıkları yükleyin
python -m pip install -r requirements.txt pythonnet

# Çalıştır
python main.py
```

## Sistem Gereksinimleri

- Windows 10 / Windows 11
- Yönetici izinleri (önerilir), aksi takdirde CPU sıcaklığı ve doğru frekans kullanılamayabilir
- .NET Framework 4.7.2 veya üstü (LibreHardwareMonitor tarafından gerekli)
- Python 3 + Tkinter (Kaynak Koddan Çalıştırma)

## EXE Olarak Derleme

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Derlemeden sonra, EXE dosyası `dist/ChipPeek.exe` konumunda bulunur.

## Kullanım

### Temel İşlemler

| Eylem | Açıklama |
|------|------|
| Sol tıkla sürükleme | Pencere konumunu taşı |
| Sağ tık | Menüyü aç (modu değiştir / ayarlar / çıkış) |
| Otomatik yapışma | Ekran kenarlarının 20px içinde otomatik olarak yapışır |

### Görüntüleme Modları

- **Köşe Widget'ı**: tüm metrikler dikey olarak düzenlenir, ekranın herhangi bir köşesine yerleştirilebilir
- **Üst Çubuk**: tüm metrikler yatay olarak düzenlenir, varsayılan olarak ekranın üst kısmında ortalanır

### Ayarlar

- **Görüntüleme modu**: köşe widget'ı / üst çubuk
- **Widget konumu**: sağ alt / sol alt / sağ üst / sol üst
- **Pencere opaklığı**: 0% - 100% kaydırıcısı, 100% - 15% pencere opaklığına karşılık gelir
- **Arka plan şeffaflığı**: 0 arka planı opak tutar; 0 üzerindeki her değer arka planı saydam yapar
- **Örnekleme aralığı**: 200ms - 3000ms veri yenileme hızı
- **Yazı tipi boyutu**: 8 - 20 punto yazı tipi
- **Dil**: 103 dil, sistem dilini otomatik olarak algılar
- **Görüntüleme metrikleri**: her metriği bağımsız olarak aç/kapat
- **Görüntüleme biçimi**: VRAM / Bellek yüzde veya gerçek değerler arasında geçiş yapabilir
- **Otomatik başlatma**: Windows oturum açmada otomatik olarak çalıştır

## Teknoloji Yığını

- **GUI**：Tkinter
- **Donanım verileri**：LibreHardwareMonitorLib (pythonnet aracılığıyla), psutil, pynvml (NVIDIA GPU için yedek çözüm)
- **Sistem entegrasyonu**：pywin32 (pencere en üstte, otomatik başlatma kayıt defteri)
- **Paketleme**：PyInstaller

## Proje Yapısı

```
ChipPeek/
├── main.py                  # Giriş noktası
├── monitor_window.py        # Pencere UI ve etkileşim mantığı
├── hardware_monitor.py      # Donanım veri toplama
├── config.py                # Yapılandırma yönetimi
├── i18n.py                  # Uluslararasılaştırma
├── generate_docs.py
├── generate_icon.py         # Simge oluşturma betiği
├── admin.manifest           # UAC yönetici izni bildirimi
├── app.ico                  # Uygulama simgesi
├── logo.png
├── requirements.txt         # Python bağımlılıkları
├── build.bat
├── docs/                    # Çok dilli belgeler
│   └── README_*.md
├── i18n/                    # Çeviri dosyaları
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Derlenmiş yürütülebilir dosya
```

## Yapılandırma Dosyası

`config.json` dosyası `ChipPeek.exe` / `main.py` ile aynı dizinde kaydedilir ve tüm ayarlanabilir ayarları içerir. Ayarlar değiştirildiğinde otomatik olarak kaydedilir.

## Lisans

[MIT License](../LICENSE)

## Geliştirici

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Proje URL'si: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Teşekkürler

- LibreHardwareMonitor - Donanım izleme kitaplığı
- psutil - Çapraz platform sistem izleme
- PyInstaller - Python paketleme aracı
