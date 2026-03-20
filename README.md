# 🎙️ Voice Creator Pro (神秘哞ㄉ Voice Creator)

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Release](https://img.shields.io/github/v/release/dryade36513/Voice-Creator-Pro)](https://github.com/dryade36513/Voice-Creator-Pro/releases)

輕輕鬆鬆複製聲紋，或創造專屬聲紋來進行 TTS (Text-to-Speech)！

**Voice Creator Pro** 是一款主打極速語音克隆與文字轉語音的強大本地端工具。只要提供 3 到 5 秒的參考音訊，就能快速複製出高相似度的聲線。更棒的是，它內建了 **HTTP API** 功能，讓你可以直接將它轉發為 API Endpoint，完美取代市面上昂貴的 TTS 服務！

## 🎥 實際展示 (Demo)

點擊下方縮圖觀看 Voice Creator Pro 實際操作與 API 串接教學：

[![Voice Creator Pro 展示](https://img.youtube.com/vi/uVyRPYO6UsE/maxresdefault.jpg)](https://www.youtube.com/watch?v=uVyRPYO6UsE)
---

## ✨ 核心特色 (Features)

- ⚡ **極速語音克隆**：只需 3～5 秒的參考音訊，即可精準複製聲線。
- 🔌 **內建 HTTP API**：一鍵開啟 API 服務，讓其他應用程式或腳本輕鬆串接，打造你專屬的免費 TTS 伺服器！
- 💻 **智慧硬體偵測**：自動偵測並最佳化你的 GPU 或 CPU，確保生成速度與效能（支援 NVIDIA CUDA）。
- 🌍 **多國語系支援**：介面支援中文、英文等多種語言。
- 🎵 **多重輸出格式**：支援將生成的音訊匯出為 WAV、MP3、FLAC 格式。
- 📚 **歷史紀錄管理**：內建便利的歷史生成紀錄面板，隨時試聽與管理過去生成的語音檔案。

---

## 🎥 實際展示 (Demo)

> **(這裡請使用 GitHub 編輯器的拖曳功能，把你的展示影片拖進來，GitHub 會自動生成影片連結取代這行文字)**

---

## 🚀 快速上手 (Quick Start)

### 1. 安裝與執行
1. 前往 [Releases](https://github.com/dryade36513/Voice-Creator-Pro/releases) 頁面下載最新版的 `VoiceCreatorPro.exe`。
2. 雙擊執行檔案。首次啟動時，系統會自動進行環境安裝與硬體（GPU/CPU）檢測，請耐心等待。
3. 進入主介面後，即可開始使用！

### 2. 如何複製聲線？
1. 點擊「上傳參考音訊」上傳一段 3～5 秒的語音檔案。
2. 於文字框內輸入你想要朗讀的文字。
3. 選擇輸出的語言與格式。
4. 點擊「生成」，短短幾秒鐘即可在下方歷史紀錄區聽到成品！

---

## 🌐 API 串接指南 (API Documentation)

不想花大錢買市面上的 TTS 服務嗎？開啟 Voice Creator Pro 的 API 功能吧！

1. 點擊右上角「齒輪」進入設定頁面。
2. 勾選開啟 **「啟用 HTTP API」**。
3. 預設 Port 為 `8100`。
4. 啟動後，你可以前往 API 說明文件網站查看詳細的 endpoints 與串接方法，輕鬆整合進你自己的專案中！

*(如有架設線上 Swagger/Redoc 文件，可以將網址貼在這裡，例如：`https://voicecreator.pro`)*

---

## 👨‍💻 作者 (Author)

**Guenter (哞哞糖)** - GitHub: [@dryade36513](https://github.com/dryade36513)

## 📄 授權條款 (License)

本專案採用 [Apache-2.0 License](LICENSE) 授權。
