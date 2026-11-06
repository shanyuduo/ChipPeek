# ChipPeek

Una aisina leugièra de susvelhança materiala Windows en widget flotant.

> **Autras lengas**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | **Occitan** | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Foncionalitats

- **Susvelhança en temps real** : frequéncia CPU, temperatura CPU, frequéncia GPU, temperatura GPU, utilizacion VRAM, utilizacion memòria
- **Dos mòdes d'afichatge** : Widget d'angle / Barra superiora, cambiament en un clic
- **Afichatge personalizat** : causida liura de las metricas a afichar, bascula percentatge/valor actuala
- **Totjorn al dessús** : demòra al dessús de totas las fenèstras. La visibilitat en ecran complet depend de l’aplicacion e del mòde d’afichatge
- **Talha autoadaptativa** : la largor de la fenèstra s'ajusta automaticament al contengut
- **Estil ajustable** : opacitat de la fenèstra, transparéncia del fons, talha de poliça tot ajustable
- **Supòrt multilingüe** : 103 lengas, deteccion automatica de la lenga del sistèma
- **Operacion convenienta** : gliscament esquèrra per desplaçar, menú de clic drech per paramètres rapids, acoblament automatic als bòrds de l'ecran
- **Escandalhatge configurable** : 200ms - 3000ms ajustable
- **Aviada automatica** : aviada automaticament a la connexion Windows
- **Utilizacion febla de ressorsas** : emprencha minimala en rèireplan

## Aviada rapide

### Utilizacion dirècta

Telecargatz [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) e doble-clicatz per l'aviar (demandarà automaticament los privilègis administrator per la temperatura CPU e la lectura de frequéncia precisa).

### Aviar a partir de la font

```powershell
# Clonar lo depaus
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Installar las dependéncias
python -m pip install -r requirements.txt pythonnet

# Aviar
python main.py
```

## Configuracion requerida

- Windows 10 / Windows 11
- Privilègis administrator (recomandats), autrament la temperatura CPU e la frequéncia precisa pòdon èsser indisponiblas
- .NET Framework 4.7.2 o superior (exigit per LibreHardwareMonitor)
- Python 3 + Tkinter (Aviar a partir de la font)

## Compilar en EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Aprèp compilacion, lo fichièr EXE se tròba a `dist/ChipPeek.exe`.

## Utilizacion

### Operacions basicas

| Accion | Descripcion |
|------|------|
| Gliscament esquèrra | Desplaçar la fenèstra |
| Clic drech | Dobrir lo menú (cambiar de mòde / paramètres / quitar) |
| Acoblament automatic | S'acoblís automaticament a mens de 20px dels bòrds de l'ecran |

### Mòdes d'afichatge

- **Widget d'angle** : totas las metricas aranjadas verticalament, pòdon èsser plaçadas a quin caire d'ecran que siá
- **Barra superiora** : totas las metricas aranjadas orizontalament, centradas en naut de l'ecran per defaut

### Paramètres

- **Mòde d'afichatge** : Widget d'angle / Barra superiora
- **Posicion del widget** : Bas a drecha / Bas a esquèrra / Naut a drecha / Naut a esquèrra
- **Opacitat de la fenèstra** : Lo cursor 0% - 100% correspond a una opacitat de fenèstra de 100% - 15%
- **Transparéncia del fons** : 0 manten lo fons opac; tota valor superiora a 0 lo rend transparent
- **Interval d'escandalhatge** : frequéncia d'actualizacion 200ms - 3000ms
- **Talha de poliça** : poliça 8 - 20 punts
- **Lenga** : 103 lengas, deteccion automatica de la lenga del sistèma
- **Metricas afichadas** : bascula independenta de cada metrica
- **Format d'afichatge** : VRAM / Memòria pòdon bascular entre percentatge o valor actuala
- **Aviada automatica** : aviament automatic a la connexion Windows

## Tecnologias utilizadas

- **Interfàcia grafica**：Tkinter
- **Donadas materialas**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (solucion de replan per GPU NVIDIA)
- **Integracion sistèma**：pywin32 (fenèstra al dessús, registre d'aviada automatic)
- **Empaquetatge**：PyInstaller

## Estructura del projècte

```
ChipPeek/
├── main.py                  # Punt d'intrada
├── monitor_window.py        # UI e logica d'interaccion de la fenèstra
├── hardware_monitor.py      # Collecta de donadas materialas
├── config.py                # Gestion de la configuracion
├── i18n.py                  # Internacionalizacion
├── generate_docs.py
├── generate_icon.py         # Script de generacion d'icòna
├── admin.manifest           # Manifèst de privilègis administrator UAC
├── app.ico                  # Icòna de l'aplicacion
├── logo.png
├── requirements.txt         # Dependéncias Python
├── build.bat
├── docs/                    # Documentacion multilingüe
│   └── README_*.md
├── i18n/                    # Fichièrs de traduccion
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # DLL LibreHardwareMonitorLib
└── dist/
    └── ChipPeek.exe         # Executable compilat
```

## Fichièr de configuracion

Lo fichièr `config.json` es enregistrat dins lo meteis repertòri que l'`ChipPeek.exe` / `main.py`, que conten totes los paramètres ajustables. Los paramètres son enregistrats automaticament a la modificacion.

## Licéncia

[MIT License](../LICENSE)

## Desvolopaire

**shanyuduo**

- GitHub : [@shanyuduo](https://github.com/shanyuduo)
- URL del projècte: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Crèdits

- LibreHardwareMonitor - Bibliotèca de susvelhança materiala
- psutil - Susvelhança sistèma multiplatafòrma
- PyInstaller - Aisina d'empaquetatge Python
