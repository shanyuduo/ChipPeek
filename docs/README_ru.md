# ChipPeek

Легковесный плавающий виджет мониторинга оборудования для Windows.

> **Другие языки**: [简体中文](README_zh-CN.md) | [繁體中文](README_zh-TW.md) | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | **Русский** | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## Возможности

- **Мониторинг в реальном времени**: частота CPU, температура CPU, частота GPU, температура GPU, использование VRAM, использование памяти
- **Два режима отображения**: угловой виджет / верхняя панель, переключение одним кликом
- **Настраиваемое отображение**: свободный выбор отображаемых метрик, переключение между процентами/фактическими значениями
- **Всегда поверх окон**: отображается поверх всех окон. Видимость в полноэкранном режиме зависит от приложения и режима отображения
- **Автоматический размер**: ширина окна автоматически подстраивается под содержимое
- **Настраиваемый стиль**: непрозрачность окна, прозрачность фона, размер шрифта - всё настраивается
- **Многоязычная поддержка**: 103 языка, автоматическое определение системного языка
- **Удобное управление**: перетаскивание левой кнопкой для перемещения, меню правой кнопкой для быстрых настроек, автоматическое прилипание к краям экрана
- **Настраиваемая дискретизация**: 200ms - 3000ms настраивается
- **Автозапуск**: автоматический запуск при входе в Windows
- **Низкое потребление ресурсов**: минимальный след в фоновом режиме

## Быстрый старт

### Прямое использование

Скачайте [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest) и дважды кликните для запуска (автоматически запросит права администратора для температуры CPU и точного чтения частоты).

### Запуск из исходного кода

```powershell
# Клонировать репозиторий
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# Установить зависимости
python -m pip install -r requirements.txt pythonnet

# Запустить
python main.py
```

## Системные требования

- Windows 10 / Windows 11
- Права администратора (рекомендуется), иначе температура CPU и точная частота могут быть недоступны
- .NET Framework 4.7.2 или выше (требуется для LibreHardwareMonitor)
- Python 3 + Tkinter (Запуск из исходного кода)

## Сборка в EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

После сборки EXE-файл находится в `dist/ChipPeek.exe`.

## Использование

### Основные операции

| Действие | Описание |
|------|------|
| Перетаскивание левой кнопкой | Переместить положение окна |
| Правая кнопка | Открыть меню (сменить режим / настройки / выход) |
| Автоматическое прилипание | Автоматически прилипает в пределах 20px от краев экрана |

### Режимы отображения

- **Угловой виджет**: все метрики расположены вертикально, можно разместить в любом углу экрана
- **Верхняя панель**: все метрики расположены горизонтально, по умолчанию центрированы вверху экрана

### Настройки

- **Режим отображения**: угловой виджет / верхняя панель
- **Положение виджета**: снизу справа / снизу слева / сверху справа / сверху слева
- **Непрозрачность окна**: Ползунок 0% - 100% соответствует непрозрачности окна 100% - 15%
- **Прозрачность фона**: При 0 фон непрозрачный; любое значение больше 0 делает его прозрачным
- **Интервал дискретизации**: 200ms - 3000ms частота обновления данных
- **Размер шрифта**: шрифт 8 - 20 пунктов
- **Язык**: 103 языка, автоматическое определение системного языка
- **Отображаемые метрики**: включение/выключение каждой метрики независимо
- **Формат отображения**: VRAM / Память могут переключаться между процентами или фактическими значениями
- **Автозапуск**: выполнять автоматически при входе в Windows

## Технологический стек

- **GUI**：Tkinter
- **Данные оборудования**：LibreHardwareMonitorLib (через pythonnet), psutil, pynvml (резервный вариант для GPU NVIDIA)
- **Системная интеграция**：pywin32 (окно поверх всех, автозапуск в реестре)
- **Упаковка**：PyInstaller

## Структура проекта

```
ChipPeek/
├── main.py                  # Точка входа
├── monitor_window.py        # UI окна и логика взаимодействия
├── hardware_monitor.py      # Сбор данных оборудования
├── config.py                # Управление конфигурацией
├── i18n.py                  # Интернационализация
├── generate_docs.py
├── generate_icon.py         # Скрипт генерации иконок
├── admin.manifest           # Манифест прав администратора UAC
├── app.ico                  # Иконка приложения
├── logo.png
├── requirements.txt         # Зависимости Python
├── build.bat
├── docs/                    # Многоязычная документация
│   └── README_*.md
├── i18n/                    # Файлы переводов
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # Скомпилированный исполняемый файл
```

## Файл конфигурации

Файл `config.json` сохраняется в том же каталоге, что и `ChipPeek.exe` / `main.py`, и содержит все настраиваемые параметры. Настройки сохраняются автоматически при изменении.

## Лицензия

[MIT License](../LICENSE)

## Разработчик

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- URL проекта: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## Благодарности

- LibreHardwareMonitor - Библиотека мониторинга оборудования
- psutil - Кроссплатформенный системный мониторинг
- PyInstaller - Инструмент упаковки Python
