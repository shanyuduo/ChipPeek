# ChipPeek

Ein leichtes schwebendes Hardware-Überwachungs-Widget für Windows.

> **Andere Sprachen**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | **Deutsch** | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Funktionen

- **Echtzeit-Überwachung**: CPU-Frequenz, CPU-Temperatur, GPU-Frequenz, GPU-Temperatur, VRAM-Nutzung, Speichernutzung
- **Zwei Anzeigemodi**: Eck-Widget / obere Leiste, Umschaltung mit einem Klick
- **Anpassbare Anzeige**: Wählen Sie frei, welche Metriken angezeigt werden sollen, wechseln Sie zwischen Prozentwerten/tatsächlichen Werten
- **Immer im Vordergrund**: Bleibt über allen Fenstern. Die Sichtbarkeit im Vollbild hängt von der Anwendung und dem Anzeigemodus ab
- **Automatische Größenanpassung**: Die Fensterbreite passt sich automatisch dem Inhalt an
- **Anpassbarer Stil**: Fensteroberfläche, Hintergrundtransparenz, Schriftgröße - alles einstellbar
- **Mehrsprachige Unterstützung**: 103 Sprachen, erkennt automatisch die Systemsprache
- **Praktische Bedienung**: Linksklick-Ziehen zum Verschieben, Rechtsklick-Menü für Schnelleinstellungen, automatisches Einrasten an Bildschirmkanten
- **Konfigurierbare Abtastung**: 200ms - 3000ms einstellbar
- **Automatischer Start**: Startet automatisch bei der Windows-Anmeldung
- **Niedriger Ressourcenverbrauch**: Minimaler Fußabdruck im Hintergrund

## Schnellstart

### Direkte Verwendung

Laden Sie [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) herunter und doppelklicken Sie zum Ausführen (fordert automatisch Administratorrechte für CPU-Temperatur und genaue Frequenzablesung an).

### Aus Quellcode ausführen

```powershell
# Repository klonen
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Abhängigkeiten installieren
python -m pip install -r requirements.txt pythonnet

# Ausführen
python main.py
```

## Systemanforderungen

- Windows 10 / Windows 11
- Administratorrechte (empfohlen), sonst sind CPU-Temperatur und genaue Frequenz möglicherweise nicht verfügbar
- .NET Framework 4.7.2 oder höher (erforderlich für LibreHardwareMonitor)
- Python 3 + Tkinter (Aus Quellcode ausführen)

## Als EXE kompilieren

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Nach der Kompilierung befindet sich die EXE-Datei unter `dist/ChipPeek.exe`.

## Verwendung

### Grundlegende Operationen

| Aktion | Beschreibung |
|------|------|
| Linksklick ziehen | Fensterposition verschieben |
| Rechtsklick | Menü öffnen (Modus wechseln / Einstellungen / Beenden) |
| Automatisches Einrasten | Rastet automatisch innerhalb von 20px an den Bildschirmkanten ein |

### Anzeigemodi

- **Eck-Widget**: Alle Metriken vertikal angeordnet, können in jeder Bildschirmecke platziert werden
- **Obere Leiste**: Alle Metriken horizontal angeordnet, standardmäßig oben zentriert auf dem Bildschirm

### Einstellungen

- **Anzeigemodus**: Eck-Widget / obere Leiste
- **Widget-Position**: Unten rechts / unten links / oben rechts / oben links
- **Fenstertransparenz**: Der Regler 0% - 100% entspricht einer Fensterdeckkraft von 100% - 15%
- **Hintergrundtransparenz**: 0 lässt den Hintergrund undurchsichtig; jeder Wert über 0 macht ihn transparent
- **Abtastintervall**: 200ms - 3000ms Datenaktualisierungsrate
- **Schriftgröße**: 8 - 20 Punkt Schrift
- **Sprache**: 103 Sprachen, erkennt automatisch die Systemsprache
- **Anzeigemetriken**: Jede Metrik kann unabhängig ein- und ausgeschaltet werden
- **Anzeigeformat**: VRAM / Speicher kann zwischen Prozentwerten oder tatsächlichen Werten wechseln
- **Automatischer Start**: Wird automatisch bei der Windows-Anmeldung ausgeführt

## Technologie-Stack

- **GUI**：Tkinter
- **Hardwaredaten**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (NVIDIA GPU Fallback)
- **Systemintegration**：pywin32 (Fenster immer im Vordergrund, Autostart-Registry)
- **Verpackung**：PyInstaller

## Projektstruktur

```
ChipPeek/
├── main.py                  # Einstiegspunkt
├── monitor_window.py        # Fenster-UI und Interaktionslogik
├── hardware_monitor.py      # Hardwaredatenerfassung
├── config.py                # Konfigurationsverwaltung
├── i18n.py                  # Internationalisierung
├── generate_docs.py
├── generate_icon.py         # Skript zur Symbolgenerierung
├── admin.manifest           # UAC-Administratorrechte-Manifest
├── app.ico                  # Anwendungssymbol
├── logo.png
├── requirements.txt         # Python-Abhängigkeiten
├── build.bat
├── docs/                    # Mehrsprachige Dokumentation
│   └── README_*.md
├── i18n/                    # Übersetzungsdateien
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Kompilierte ausführbare Datei
```

## Konfigurationsdatei

Die Einstellungen werden automatisch in `config.json` gespeichert: neben `ChipPeek.exe` bei der gepackten Version oder neben `main.py` beim Start aus dem Quellcode.

## Lizenz

[MIT License](../LICENSE)

## Entwickler

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- Projekt-URL: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Danksagungen

- LibreHardwareMonitor - Hardware-Überwachungsbibliothek
- psutil - Plattformübergreifende Systemüberwachung
- PyInstaller - Python-Verpackungstool
