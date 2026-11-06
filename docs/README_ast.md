# ChipPeek

Una ferramienta llixera de widget flotante pa supervisión de hardware en Windows.

> **Otres llingües**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | **Asturianu** | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Carauterístiques

- **Supervisión en tiempu real**: frecuencia CPU, temperatura CPU, frecuencia GPU, temperatura GPU, usu de VRAM, usu de memoria
- **Dos moos d'amuesu**: Widget d'esquina / Barra cimera, cambéu con un clic
- **Amuesu personalizable**: llibre escoyeta de les métriques a amosar, alternanza porcentaxe/valor actual
- **Siempre enriba**: queda enriba de toles ventanes. La visibilidá a pantalla completa depende de l’aplicación y del mou de visualización
- **Autoaxuste de tamañu**: l'anchor de la ventana axústase automáticamente al conteníu
- **Estilu axustable**: opacidá de la ventana, tresparencia del fondu, tamañu de fonte axustables
- **Sofitu multillingüe**: 103 llingües, detección automática de la llingua del sistema
- **Operación conveniente**: arrastre esquierda pa mover, menú de clic drechu pa configuración rápida, auto-adhesión a los berbesos de la pantalla
- **Muestréu configurable**: 200ms - 3000ms axustable
- **Aniciu automáticu**: aníciase automáticamente al aniciar sesión en Windows
- **Usu baxu de recursos**: consumu mínimu en segundu planu

## Aniciu rápidu

### Usu direutu

Descarga [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) y doble clic pa executar (solicitará automáticamente privilexos d'alministrador pa la temperatura CPU y la llectura de frecuencia precisa).

### Executar dende la fonte

```powershell
# Clonar el depósitu
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Instalar dependencies
python -m pip install -r requirements.txt pythonnet

# Executar
python main.py
```

## Requisitos del sistema

- Windows 10 / Windows 11
- Privilexos d'alministrador (recomendaos), en casu contrariu la temperatura CPU y la frecuencia precisa puen nun tar disponibles
- .NET Framework 4.7.2 o superior (requeríu por LibreHardwareMonitor)
- Python 3 + Tkinter (Executar dende la fonte)

## Compilar como EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Tres la compilación, el ficheru EXE atópase en `dist/ChipPeek.exe`.

## Usu

### Operaciones básiques

| Aición | Descripción |
|------|------|
| Arrastre esquierda | Mover la ventana |
| Clic drechu | Abrir el menú (camudar mou / configuración / salir) |
| Auto-adhesión | Ahesión automática a menos de 20px de los berbesos de la pantalla |

### Moos d'amuesu

- **Widget d'esquina**: toles métriques ordenaes verticalmente, pue allugase en cualquier esquina de la pantalla
- **Barra cimera**: toles métriques ordenaes horizontalmente, centrada na parte cimera de la pantalla por defectu

### Configuración

- **Mou d'amuesu**: Widget d'esquina / Barra cimera
- **Posición del widget**: Abaxo drecha / Abaxo izquierda / Arriba drecha / Arriba izquierda
- **Opacidá de la ventana**: El control de 0% - 100% correspuende a una opacidá de ventana de 100% - 15%
- **Tresparencia del fondu**: 0 caltién el fondu opacu; cualquier valor mayor que 0 faelu tresparente
- **Intervalu de muestréu**: tasa d'actualización 200ms - 3000ms
- **Tamañu de fonte**: fonte 8 - 20 puntos
- **Llingua**: 103 llingües, detección automática de la llingua del sistema
- **Métriques amosaes**: alternanza independiente de cada métrica
- **Formatu d'amuesu**: VRAM / Memoria puen alternar ente porcentaxe o valor actual
- **Aniciu automáticu**: execución automática al aniciar sesión en Windows

## Tecnoloxíes utilizaes

- **Interfaz gráfica**：Tkinter
- **Datos de hardware**：LibreHardwareMonitorLib (vía pythonnet), psutil, pynvml (solución de respaldu pa GPU NVIDIA)
- **Integración del sistema**：pywin32 (ventana enriba, rexistru d'aniciu automáticu)
- **Empaquetáu**：PyInstaller

## Estructura del proyeutu

```
ChipPeek/
├── main.py                  # Puntu d'entrada
├── monitor_window.py        # UI y lóxica d'interaición de la ventana
├── hardware_monitor.py      # Recoyida de datos de hardware
├── config.py                # Xestión de la configuración
├── i18n.py                  # Internacionalización
├── generate_docs.py
├── generate_icon.py         # Script de xeneración d'iconu
├── admin.manifest           # Manifiestu de privilexos d'alministrador UAC
├── app.ico                  # Iconu de l'aplicación
├── logo.png
├── requirements.txt         # Dependencies de Python
├── build.bat
├── docs/                    # Documentación multillingüe
│   └── README_*.md
├── i18n/                    # Ficheros de torna
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # DLL de LibreHardwareMonitorLib
└── dist/
    └── ChipPeek.exe         # Executable compiláu
```

## Ficheru de configuración

El ficheru `config.json` guardar nel mesmu direutoriu que l'`ChipPeek.exe` / `main.py`, conteniendo tolos axustes configurables. Los axustes guardar automáticamente al modificase.

## Llicencia

[MIT License](../LICENSE)

## Desendolcador

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL del proyeutu: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Créditos

- LibreHardwareMonitor - Biblioteca de supervisión de hardware
- psutil - Supervisión de sistema multiplataforma
- PyInstaller - Ferramienta d'empaquetáu de Python
