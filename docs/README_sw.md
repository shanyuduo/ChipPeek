# ChipPeek

Zana ya ufuatiliaji wa vifaa vya kimataifa yenye uzito mdogo kwa Windows.

> **Lugha zingine**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | **Kiswahili** | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Vipengele

- **Ufuatiliaji wa wakati halisi**: Mzunguko wa CPU, joto la CPU, mzunguko wa GPU, joto la GPU, utumizi wa VRAM, utumizi wa kumbukumbu
- **Hati mbili za kuonyesha**: Kijenzi cha kona / Baa ya juu, badilisha kwa bonyeza moja
- **Maonyesho ya utu**: Chagua kwa uhuru ni vipimo gvi vinavyoonyeshwa, badilisha kati ya asilimia/maadili halisi
- **Kila wakati juu**: Inabaki juu ya madirisha yote. Kuonekana katika skrini nzima kunategemea programu na hali ya kuonyesha
- **Ukubwa wa kiotomatiki**: Upana wa dirisha umeundwa kiotomatiki kulingana na maudhui
- **Mtindo unaoweza kurekebishwa**: Uwazi wa dirisha, uwazi wa mazingira, ukubwa wa fonti - zote zinaweza kurekebishwa
- **Msaada wa lugha nyingi**: 103 lugha, hujua lugha ya mfumo kiotomatiki
- **Operesheni rahisi**: Buruta na bonyeza kulia kuhamasisha, menyu ya kubonyeza kulia kwa mipangilio ya haraka, kufunga kiotomatiki kwa pembe za skrini
- **Urekebishaji wa masafa ya uchambuzi**: 200ms - 3000ms inaweza kurekebishwa
- **Kuanza kiotomatiki**: Inaanza kiotomatiki wakati wa kuingia Windows
- **Matumizi ya hivi karibuni ya rasilimali**: Inachukua nafasi ndogo sana kwenye mazingira

## Kuanza haraka

### Matumizi ya moja kwa moja

Pakua [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) na bonyeza mara mbili kuendesha (itaomba ruhusa ya msimamizi kiotomatiki kusoma joto la CPU na mzunguko sahihi).

### Kukimbia kutoka kwa nambari chanzo

```powershell
# Kloni hazina
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Sakin vigezo
python -m pip install -r requirements.txt pythonnet

# Kukimbia
python main.py
```

## Mahitaji ya mfumo

- Windows 10 / Windows 11
- Ruhusa ya msimamizi (inapendekezwa), vinginevyo joto la CPU na mzunguko sahihi huenda si patipati
- .NET Framework 4.7.2 au zaidi (inahitajika kwa LibreHardwareMonitor)
- Python 3 + Tkinter (Kukimbia kutoka kwa nambari chanzo)

## Jenga kama EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Baada ya kujengwa, faili la EXE iko katika `dist/ChipPeek.exe`.

## Matumizi

### Operesheni za msingi

| Operesheni | Maelezo |
|------|------|
| Kuburuta kwa kubonyeza kulia | Hamisha nafasi ya dirisha |
| Kubonyeza kulia | Fungua menyu (badilisha hali / mipangilio / toka) |
| Kufunga kiotomatiki | Inafunga kiotomatiki ndani ya 20px kutoka kwa pembe za skrini |

### Hati za kuonyesha

- **Kijenzi cha kona**: Vipimo vyote vimeandikwa wima, vinaweza kuwekwa katika kona yoyote ya skrini
- **Baa ya juu**: Vipimo vyote vimeandikwa zizi, kwa kawaida viko katikati ya sehemu ya juu ya skrini

### Mipangilio

- **Hali ya kuonyesha**: Kijenzi cha kona / Baa ya juu
- **Nafasi ya kijenzi**: Chini kulia / Chini kushoto / Juu kulia / Juu kushoto
- **Uwazi wa dirisha**: Kitelezi cha 0% - 100% kinalingana na kiwango cha kutopitisha mwanga cha dirisha cha 100% - 15%
- **Uwazi wa mazingira**: 0 huweka mandharinyuma yasiyopitisha mwanga; thamani yoyote zaidi ya 0 huyafanya ya uwazi
- **Kipindi cha uchambuzi**: 200ms - 3000ms kasi ya kisasa cha data
- **Ukubwa wa fonti**: 8 - 20 vidokezo
- **Lugha**: 103 lugha, hujua lugha ya mfumo kiotomatiki
- **Vipimo vya kuonyesha**: Washa / zima kila kipimo kwa uhuru
- **Format ya kuonyesha**: VRAM / kumbukumbu inaweza kubadilisha kati ya asilimia au maadili halisi
- **Kuanza kiotomatiki**: Kukimbia kiotomatiki wakati wa kuingia Windows

## Mkusanyiko wa teknolojia

- **GUI**：Tkinter
- **Data ya vifaa**：LibreHardwareMonitorLib (kupitia pythonnet), psutil, pynvml (backup kwa NVIDIA GPU)
- **Ujumuishaji wa mfumo**：pywin32 (dirisha kila wakati juu, sajili ya kuanza kiotomatiki)
- **Ufupishaji**：PyInstaller

## Muundo wa mradi

```
ChipPeek/
├── main.py                  # Kituo cha kuingia
├── monitor_window.py        # Dirisha la UI na mantiki ya mwingiliano
├── hardware_monitor.py      # Ukusanyaji wa data ya vifaa
├── config.py                # Usimamizi wa usanidi
├── i18n.py                  # Kimataifa
├── generate_docs.py
├── generate_icon.py         # Sikuithi ya kuzalisha ishara
├── admin.manifest           # Uthibitishaji wa ruhusa ya msimamizi wa UAC
├── app.ico                  # Ishara ya programu
├── logo.png
├── requirements.txt         # Vigezo vya Python
├── build.bat
├── docs/                    # Hati za lugha nyingi
│   └── README_*.md
├── i18n/                    # Faili za tafsiri
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Faili la utekelezaji lililojengwa
```

## Faili ya usanidi

Faili la `config.json` limehifadhiwa katika saraka sawa na `ChipPeek.exe` / `main.py` na ina mipangilio yote inayoweza kurekebishwa. Mipangilio huhifadhiwa kiotomatiki inapobadilika.

## Leseni

[MIT License](../LICENSE)

## Mrazishaji

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL ya mradi: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Sifa

- LibreHardwareMonitor - Maktaba ya ufuatiliaji wa vifaa
- psutil - Ufuatiliaji wa mfumo wa kuzungumza jukwaa
- PyInstaller - Zana ya ufupishaji wa Python
