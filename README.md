# 李宏毅「AI YouTuber 小金」演講深度導讀

臺大電機系李宏毅教授在「人文與科技的對話」課上的演講（影片 1 小時 49 分，演講拍攝日 2026-04-22，臺大演講網 2026-11-03 上傳）。他用自己養的 AI agent「小金」（會自己開 YouTube 頻道、做影片、上傳）拆解 AI agent 的運作：語言模型只會文字接龍，Harness（馬具）把設定檔、歷史紀錄與工具清單塞進 prompt，記憶、心跳排程、skill 都是文字檔與定時程式；再談風險與人的角色（「想做什麼比會做什麼重要」）。導讀依演講順序整理，並對照他引用的外部事件與官方資料。

## 製作聲明

本導讀的研究、撰稿、查證、審稿與插圖皆由 AI 模型完成，不是人類分析，也沒有經過人工逐句校稿；內容依 YouTube 機器字幕整理，未對照原音。分工：主控與撰稿 Claude Sonnet 5.5；字幕誤聽審修、獨立審稿與總編輯潤稿 Claude Opus；網路查證 Claude Sonnet；封面圖 Codex imagegen；圖表 Mermaid 與自繪 SVG。

## 檔案

| 檔案 | 說明 |
|---|---|
| `lee_hungyi_ai_youtuber_xiaojin_agent.md` | 導讀主文（由 `research/guide_src.md` 展開時間戳產生） |
| `index.html` | 導讀網頁（可直接用瀏覽器開啟） |
| `player.html` | 中文字幕同步播放器（YouTube 嵌入，需網路） |
| `images/` | 封面圖 16:9、9:16 與 og 圖；SVG 圖 10 張（`fig-*-zh.svg`、`fig-*-zh-mobile.svg`） |
| `qa/` | 桌面 1440×900、手機 390×844 截圖與檢查結果 |
| `research/` | 研究與流程紀錄（帳本、術語表、審稿意見、重建腳本），僅本機 |

來源為繁體中文，所以沒有做譯文頁。重建：`bash research/rebuild_page.sh`。

## 原始資料

- 影片：[從 AI YouTuber 小金的故事理解 AI Agent 的運作原理｜114-2 人文與科技的對話](https://www.youtube.com/watch?v=Y72C9EJRM7Q)（臺大演講網）
- 逐字稿：YouTube 機器字幕（SRT），為本機研究檔，不隨本 repo 公開。

## 重要來源

- [Summer Yue 本人貼文（2026-02-23）](https://x.com/summeryue0/status/2025774069124399363)
- [TechCrunch：Anthropic 訂閱不再涵蓋 OpenClaw（2026-04-04）](https://techcrunch.com/2026/04/04/anthropic-says-claude-code-subscribers-will-need-to-pay-extra-for-openclaw-support/)
- [Agents4Science 論文 arXiv 2511.15534](https://arxiv.org/abs/2511.15534)
- [Anthropic：Emotion concepts and their function（2026-04-02）](https://www.anthropic.com/research/emotion-concepts-function)

## 狀態

僅本機完成，未發布、未建立 Git 倉庫、未推送。
