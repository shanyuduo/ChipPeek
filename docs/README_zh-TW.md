# ChipPeek

一款輕量級 Windows 硬體監控懸浮窗工具。

> **其他語言**: [简体中文](README_zh-CN.md) | **繁體中文** | [English](README_en.md) | [日本語](README_ja.md) | [한국어](README_ko.md) | [Español](README_es.md) | [Français](README_fr.md) | [Deutsch](README_de.md) | [Português](README_pt.md) | [Русский](README_ru.md) | [العربية](README_ar.md) | [ไทย](README_th.md) | [Tiếng Việt](README_vi.md) | [Bahasa Indonesia](README_id.md) | [Türkçe](README_tr.md) | [Italiano](README_it.md) | [Nederlands](README_nl.md) | [Polski](README_pl.md) | [हिन्दी](README_hi.md) | [বাংলা](README_bn.md) | [Svenska](README_sv.md) | [Norsk](README_no.md) | [Dansk](README_da.md) | [Suomi](README_fi.md) | [Čeština](README_cs.md) | [Ελληνικά](README_el.md) | [Magyar](README_hu.md) | [Română](README_ro.md) | [Українська](README_uk.md) | [Slovenčina](README_sk.md) | [Български](README_bg.md) | [Hrvatski](README_hr.md) | [Српски](README_sr.md) | [Català](README_ca.md) | [Slovenščina](README_sl.md) | [Eesti](README_et.md) | [Latviešu](README_lv.md) | [Lietuvių](README_lt.md) | [فارسی](README_fa.md) | [Bahasa Melayu](README_ms.md) | [اردو](README_ur.md) | [தமிழ்](README_ta.md) | [తెలుగు](README_te.md) | [मराठी](README_mr.md) | [ગુજરાતી](README_gu.md) | [ਪੰਜਾਬੀ](README_pa.md) | [ಕನ್ನಡ](README_kn.md) | [മലയാളം](README_ml.md) | [Қазақ](README_kk.md) | [O'zbek](README_uz.md) | [עברית](README_he.md) | [မြန်မာ](README_my.md) | [ខ្មែរ](README_km.md) | [ລາວ](README_lo.md) | [Kiswahili](README_sw.md) | [Afrikaans](README_af.md) | [አማርኛ](README_am.md) | [isiZulu](README_zu.md) | [Filipino](README_fil.md) | [Gaeilge](README_ga.md) | [Íslenska](README_is.md) | [Malti](README_mt.md) | [Cymraeg](README_cy.md) | [Euskara](README_eu.md) | [Galego](README_gl.md) | [नेपाली](README_ne.md) | [සිංහල](README_si.md) | [ქართული](README_ka.md) | [Հայերեն](README_hy.md) | [Македонски](README_mk.md) | [Беларуская](README_be.md) | [ייִדיש](README_yi.md) | [Lëtzebuergesch](README_lb.md) | [Esperanto](README_eo.md) | [Føroyskt](README_fo.md) | [Gàidhlig](README_gd.md) | [Brezhoneg](README_br.md) | [Corsu](README_co.md) | [Rumantsch](README_rm.md) | [Occitan](README_oc.md) | [Asturianu](README_ast.md) | [Frysk](README_fy.md) | [Татарча](README_tt.md) | [Башҡортса](README_ba.md) | [Basa Jawa](README_jv.md) | [Basa Sunda](README_su.md) | [Cebuano](README_ceb.md) | [བོད་སྐད](README_bo.md) | [Kurdî](README_ku.md) | [پښتو](README_ps.md) | [سنڌي](README_sd.md) | [Тоҷикӣ](README_tg.md) | [Türkmen](README_tk.md) | [Кыргызча](README_ky.md) | [Монгол](README_mn.md) | [Hausa](README_ha.md) | [Igbo](README_ig.md) | [Yorùbá](README_yo.md) | [isiXhosa](README_xh.md) | [Malagasy](README_mg.md) | [chiShona](README_sn.md) | [Kinyarwanda](README_rw.md) | [Soomaali](README_so.md)

## 功能特性

- **即時監控**：CPU 頻率、CPU 溫度、GPU 頻率、GPU 溫度、顯存佔用、記憶體佔用
- **雙顯示模式**：角落小框 / 頂部橫條，一鍵切換
- **自訂顯示**：可自由選擇顯示哪些指標，支援百分比/實際數值切換
- **懸浮置頂**：置頂顯示在桌面視窗上方；全螢幕時能否顯示取決於應用程式和顯示模式
- **自適應大小**：視窗寬度根據內容自動調整，文字完整顯示
- **可調整式樣**：視窗透明度、背景透明度、字號大小均可調節
- **多語言支援**：支援 103 種語言，自動偵測系統語言
- **便捷操作**：左鍵拖動移動位置，右鍵選單快速設定，自動吸附螢幕邊緣
- **採樣頻率**：200ms - 3000ms 可調節
- **開機自啟**：支援開機自動啟動
- **低資源佔用**：後台執行佔用極低

## 快速開始

### 直接使用

下載 [`ChipPeek.exe`](https://github.com/shanyuduo/ChipPeek/releases/latest)，雙擊執行（會自動請求管理員權限以讀取 CPU 溫度和精確頻率）。

### 原始碼執行

```powershell
# 複製專案
git clone https://github.com/shanyuduo/ChipPeek.git
cd ChipPeek

# 安裝依賴
python -m pip install -r requirements.txt pythonnet

# 執行
python main.py
```

## 系統需求

- Windows 10 / Windows 11
- 管理員權限（推薦），否則 CPU 溫度和精確頻率可能無法讀取
- .NET Framework 4.7.2 或更高（LibreHardwareMonitor 依賴）
- Python 3 + Tkinter (原始碼執行)

## 打包為 EXE

```powershell
python -m pip install -r requirements.txt pythonnet pyinstaller
python -m PyInstaller --noconfirm --onefile --windowed --name "ChipPeek" --icon "app.ico" --manifest "admin.manifest" --add-data "libs;libs" --add-data "app.ico;." --add-data "i18n;i18n" --hidden-import "clr" --hidden-import "pynvml" --hidden-import "win32gui" --hidden-import "win32con" main.py
```

打包完成後，EXE 檔案位於 `dist/ChipPeek.exe`。

## 使用說明

### 基本操作

| 操作 | 說明 |
|------|------|
| 左鍵拖動 | 移動視窗位置 |
| 右鍵 | 打開選單（切換模式 / 設定 / 退出） |
| 自動吸附 | 拖動到螢幕邊緣 20px 內自動吸附 |

### 顯示模式

- **角落小框**：縱向排列所有指標，可放在螢幕四角
- **頂部橫條**：橫向排列所有指標，預設置中顯示在螢幕頂部

### 設定選項

- **顯示模式**：角落小框 / 頂部橫條
- **小框位置**：右下角 / 左下角 / 右上角 / 左上角
- **視窗透明度**：滑桿 0% - 100% 對應視窗不透明度 100% - 15%
- **背景透明度**：0 為不透明背景，大於 0 時背景完全透明
- **採樣間隔**：200ms - 3000ms 資料重新整理頻率
- **字號大小**：8 - 20 號字型
- **語言**：支援 103 種語言，自動偵測系統語言
- **顯示指標**：可獨立開關每一項指標
- **顯示格式**：顯存 / 記憶體可切換百分比或實際數值
- **開機自啟動**：登入 Windows 後自動執行

## 技術棧

- **GUI**：Tkinter
- **硬體資料**：LibreHardwareMonitorLib（透過 pythonnet 呼叫）、psutil、pynvml（NVIDIA GPU 備用方案）
- **系統整合**：pywin32（視窗置頂、自動啟動註冊表）
- **打包**：PyInstaller

## 專案結構

```
ChipPeek/
├── main.py                  # 程式入口
├── monitor_window.py        # 視窗 UI 與互動邏輯
├── hardware_monitor.py      # 硬體資料採集
├── config.py                # 設定管理
├── i18n.py                  # 多語言支援
├── generate_docs.py
├── generate_icon.py         # 圖示生成指令碼
├── admin.manifest           # UAC 管理員權限清單
├── app.ico                  # 程式圖示
├── logo.png
├── requirements.txt         # Python 依賴
├── build.bat
├── docs/                    # 多語言文件
│   └── README_*.md
├── i18n/                    # 翻譯檔案
│   └── *.json
├── libs/
│   └── lhm/
│       └── lib/net472/      # LibreHardwareMonitorLib DLL
└── dist/
    └── ChipPeek.exe         # 編譯後的可執行檔
```

## 設定檔

設定會自動儲存至 `config.json`：使用打包版本時位於 `ChipPeek.exe` 同目錄，從原始碼執行時位於 `main.py` 同目錄。請確保該目錄可寫。

## 授權條款

[MIT License](../LICENSE)

## 開發者

**shanyuduo**

- GitHub: [@shanyuduo](https://github.com/shanyuduo)
- 專案地址: [https://github.com/shanyuduo/ChipPeek](https://github.com/shanyuduo/ChipPeek)

## 致謝

- LibreHardwareMonitor - 硬體監控庫
- psutil - 跨平台系統監控
- PyInstaller - Python 程式打包工具
