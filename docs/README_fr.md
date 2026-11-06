# ChipPeek

Un widget flottant léger de surveillance matérielle pour Windows.

> **Autres langues**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | **Français** | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Fonctionnalités

- **Surveillance en temps réel** : fréquence CPU, température CPU, fréquence GPU, température GPU, utilisation VRAM, utilisation mémoire
- **Double mode d'affichage** : widget de coin / barre supérieure, basculement en un clic
- **Affichage personnalisable** : choisissez librement les métriques à afficher, basculez entre pourcentage/valeurs réelles
- **Toujours au premier plan** : reste au-dessus de toutes les fenêtres. La visibilité en plein écran dépend de l’application et du mode d’affichage
- **Redimensionnement automatique** : la largeur de la fenêtre s'ajuste automatiquement au contenu
- **Style ajustable** : opacité de la fenêtre, transparence de l'arrière-plan, taille de police - tout est ajustable
- **Support multilingue** : 103 langues, détecte automatiquement la langue du système
- **Fonctionnement pratique** : glisser-clic gauche pour déplacer, menu clic droit pour paramètres rapides, accroche automatique aux bords de l'écran
- **Échantillonnage configurable** : 200ms - 3000ms ajustable
- **Démarrage automatique** : se lance automatiquement à la connexion Windows
- **Faible utilisation des ressources** : empreinte minimale en arrière-plan

## Démarrage rapide

### Utilisation directe

Téléchargez [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) et double-cliquez pour l'exécuter (demandera automatiquement les privilèges administrateur pour la température CPU et la lecture précise de la fréquence).

### Exécuter à partir du code source

```powershell
# Cloner le dépôt
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Installer les dépendances
python -m pip install -r requirements.txt pythonnet

# Exécuter
python main.py
```

## Configuration requise

- Windows 10 / Windows 11
- Privilèges administrateur (recommandé), sinon la température CPU et la fréquence précise peuvent ne pas être disponibles
- .NET Framework 4.7.2 ou supérieur (requis par LibreHardwareMonitor)
- Python 3 + Tkinter (Exécuter à partir du code source)

## Compiler en EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

Après compilation, le fichier EXE se trouve dans `dist/ChipPeek.exe`.

## Utilisation

### Opérations de base

| Action | Description |
|------|------|
| Glisser clic gauche | Déplacer la fenêtre |
| Clic droit | Ouvrir le menu (changer de mode / paramètres / quitter) |
| Accroche automatique | S'accroche automatiquement à 20px des bords de l'écran |

### Modes d'affichage

- **Widget de coin** : toutes les métriques disposées verticalement, peut être placé dans n'importe quel coin de l'écran
- **Barre supérieure** : toutes les métriques disposées horizontalement, centrée en haut de l'écran par défaut

### Paramètres

- **Mode d'affichage** : widget de coin / barre supérieure
- **Position du widget** : bas droite / bas gauche / haut droite / haut gauche
- **Opacité de la fenêtre** : Le curseur 0% - 100% correspond à une opacité de fenêtre de 100% - 15%
- **Transparence de l'arrière-plan** : 0 garde le fond opaque ; toute valeur supérieure à 0 le rend transparent
- **Intervalle d'échantillonnage** : 200ms - 3000ms taux de rafraîchissement des données
- **Taille de police** : police de 8 - 20 points
- **Langue** : 103 langues, détecte automatiquement la langue du système
- **Métriques d'affichage** : activez/désactivez chaque métrique indépendamment
- **Format d'affichage** : VRAM / Mémoire peuvent basculer entre pourcentage ou valeurs réelles
- **Démarrage automatique** : s'exécute automatiquement à la connexion Windows

## Stack technologique

- **GUI**：Tkinter
- **Données matérielles**：LibreHardwareMonitorLib (via pythonnet), psutil, pynvml (solution de secours pour GPU NVIDIA)
- **Intégration système**：pywin32 (fenêtre au premier plan, registre de démarrage automatique)
- **Empaquetage**：PyInstaller

## Structure du projet

```
ChipPeek/
├── main.py                  # Point d'entrée
├── monitor_window.py        # UI de la fenêtre et logique d'interaction
├── hardware_monitor.py      # Collecte de données matérielles
├── config.py                # Gestion de la configuration
├── i18n.py                  # Internationalisation
├── generate_docs.py
├── generate_icon.py         # Script de génération d'icônes
├── admin.manifest           # Manifeste de privilèges admin UAC
├── app.ico                  # Icône de l'application
├── logo.png
├── requirements.txt         # Dépendances Python
├── build.bat
├── docs/                    # Documentation multilingue
│   └── README_*.md
├── i18n/                    # Fichiers de traduction
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Exécutable compilé
```

## Fichier de configuration

Les paramètres sont enregistrés automatiquement dans `config.json`, à côté de `ChipPeek.exe` pour la version compilée ou de `main.py` pour l’exécution depuis le code source.

## Licence

[MIT License](../LICENSE)

## Développeur

**shanyuduo**

- GitHub : [@shanyuduo](https://github.com/shanyuduo)
- URL du projet: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Remerciements

- LibreHardwareMonitor - Bibliothèque de surveillance matérielle
- psutil - Surveillance système multiplateforme
- PyInstaller - Outil d'empaquetage Python
