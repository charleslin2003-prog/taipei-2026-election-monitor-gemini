# 2026 台北市長選戰即時戰情室 (蔣萬安 vs. 沈伯洋)

本專案為單一檔案架構 (Single-File SPA) 之即時選情追蹤與司法鑑識級履歷查核儀表板。

## 核心功能
1. **即時輿情雷達 (Live War Room)**：支援每10秒自動推播模擬引擎與遠端 GitHub JSON 同步。
2. **得票率沙盤推演器**：動態調整青年投票率、高齡長者投票率、白營流向與辯論表現。
3. **17.1萬筆 QSearch 互相抹黑統計**：跨新聞、YouTube、Threads 與 PTT 負面情緒率分析。
4. **司法級個資與履歷查核**：比對加州律師公會 #254347 紀錄、LinkedIn 時程與立院公報。

## 快速部署至 GitHub Pages
本專案已設定 GitHub Actions 自動部署。首次請至儲存庫 **Settings → Pages**，將 **Build and deployment** 的來源設為 **GitHub Actions**；之後推送至 `main` 分支時會自動發布。

網站網址：<https://charleslin2003-prog.github.io/taipei-2026-election-monitor-gemini/>
