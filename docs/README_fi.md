# ChipPeek

Kevyt kelluva laitteiston valvontawidget Windowsille.

> **Muut kielet**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | **Suomi** | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Ominaisuudet

- **Reaaliaikainen valvonta**: CPU-nopeus, CPU-lämpötila, GPU-nopeus, GPU-lämpötila, VRAM-käyttö, muistin käyttö
- **Kaksi näyttötilaa**: Nurkkawidget / Yläpalkki, yhdellä klikkauksella vaihto
- **Mukautettava näyttö**: Valitse vapaasti mitkä mittarit näytetään, vaihda prosentti-/todellisten arvojen välillä
- **Aina päällä**: Pysyy kaikkien ikkunoiden yläpuolella. Näkyvyys koko näytössä riippuu sovelluksesta ja näyttötilasta
- **Automaattinen koko**: Ikkunan leveys säätyy automaattisesti sisällön mukaan
- **Säädettävä tyyli**: Ikkunan läpinäkyvyys, taustan läpinäkyvyys, fontin koko - kaikki säädettävissä
- **Monikielinen tuki**: 103 kieltä, tunnistaa automaattisesti järjestelmän kielen
- **Mukava käyttö**: Siirrä vetämällä vasemmalla näppäimellä, oikean painikkeen valikko nopeisiin asetuksiin, automaattinen snap ruudun reunoille
- **Määritettävissä oleva näytteenottotaajuus**: 200ms - 3000ms säädettävissä
- **Automaattinen käynnistys**: Käynnistyy automaattisesti Windows-kirjautumisessa
- **Alhainen resurssin käyttö**: Vähän muistia taustalla

## Pika-aloitus

### Suora käyttö

Lataa [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) ja kaksoisklikkaa suorittaaksesi (pyytää automaattisesti järjestelmänvalvojan oikeuksia CPU-lämpötilan ja tarkan nopeuden lukemiseksi).

### Suorita lähdekoodista

```powershell
# Kloonaa arkisto
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Asenna riippuvuudet
python -m pip install -r requirements.txt pythonnet

# Suorita
python main.py
```

## Järjestelmävaatimukset

- Windows 10 / Windows 11
- Järjestelmänvalvojan oikeudet (suositeltu), muuten CPU-lämpötila ja tarkka nopeus eivät ehkä ole saatavilla
- .NET Framework 4.7.2 tai uudempi (vaaditaan LibreHardwareMonitor toimesta)
- Python 3 + Tkinter (Suorita lähdekoodista)

## Rakenna EXE:ksi

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Rakennuksen jälkeen EXE-tiedosto on sijainnissa `dist/ChipPeek.exe`.

## Käyttö

### Perustoiminnot

| Toiminto | Kuvaus |
|------|------|
| Vasemmalla vetäminen | Siirrä ikkunaa |
| Oikea painike | Avaa valikko (vaihda tilaa / asetukset / poistu) |
| Automaattinen snap | Liittyy automaattisesti 20px säteellä ruudun reunoista |

### Näyttötilat

- **Nurkkawidget**: Kaikki mittarit pystyssä, voidaan sijoittaa mihin tahansa ruudun nurkkaan
- **Yläpalkki**: Kaikki mittarit vaakasuunnassa, oletuksena keskitettynä ruudun yläreunaan

### Asetukset

- **Näyttötila**: Nurkkawidget / Yläpalkki
- **Widgetin sijainti**: Alhaalla oikealla / Alhaalla vasemmalla / Ylhäällä oikealla / Ylhäällä vasemmalla
- **Ikkunan läpinäkyvyys**: Liukusäätimen 0% - 100% vastaa ikkunan peittävyyttä 100% - 15%
- **Taustan läpinäkyvyys**: 0 pitää taustan peittävänä; kaikki arvot yli 0 tekevät siitä läpinäkyvän
- **Näytteentottoväli**: 200ms - 3000ms datan päivitysnopeus
- **Fontin koko**: 8 - 20 pistettä
- **Kieli**: 103 kieltä, tunnistaa automaattisesti järjestelmän kielen
- **Näyttömittarit**: Kytke kunkin mittarin päälle/pois itsenäisesti
- **Näyttömuoto**: VRAM / Muisti voidaan vaihtaa prosentiksi tai todellisiksi arvoiksi
- **Automaattinen käynnistys**: Suorita automaattisesti kirjautuessa Windowsiin

## Tekninen pino

- **GUI**：Tkinter
- **Laitteisto data**：LibreHardwareMonitorLib (pythonnet kautta), psutil, pynvml (NVIDIA GPU vara)
- **Järjestelmäintegraatio**：pywin32 (ikkuna aina päällä, automaattinen käynnistys rekisteri)
- **Paketointi**：PyInstaller

## Projektin rakenne

```
ChipPeek/
├── main.py                  # Ohjelman aloituspiste
├── monitor_window.py        # Ikkuna UI ja vuorovaikutuslogiikka
├── hardware_monitor.py      # Laitteisto datan keruu
├── config.py                # Asetusten hallinta
├── i18n.py                  # Kansainvälistyminen
├── generate_docs.py
├── generate_icon.py         # Kuvakkeen luontiskripti
├── admin.manifest           # UAC järjestelmänvalvojan oikeus manifesti
├── app.ico                  # Sovelluksen kuvake
├── logo.png
├── requirements.txt         # Python riippuvuudet
├── build.bat
├── docs/                    # Monikielinen dokumentaatio
│   └── README_*.md
├── i18n/                    # Käännöstiedostot
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Käännetty suoritettava tiedosto
```

## Asetustiedosto

`config.json` tiedosto tallennetaan samaan kansioon kuin `ChipPeek.exe` / `main.py` ja se sisältää kaikki säädettävät asetukset. Asetukset tallennetaan automaattisesti, kun niitä muutetaan.

## Lisenssi

[MIT License](../LICENSE)

## Kehittäjä

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projektin URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Kiitokset

- LibreHardwareMonitor - Laitteiston valvontakirjasto
- psutil - Alustariippumaton järjestelmän valvonta
- PyInstaller - Python paketoinnin työkalu
