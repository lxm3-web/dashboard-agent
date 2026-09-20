# dashboard-agent — 訂戶數據月報專員（Agent 版）

同事拿到這包後：
1. 瀏覽器 claude.ai/code 選這個 repo，或本機 `claude`
2. 說「林經理的指示在 inbox，出月報」→ 它去敏、串接、算指標，把月報 md、預警名單、儀表板 HTML 寫到 `outbox/`
3. 打開 `outbox/*_儀表板.html` 看 → 說「好，發下去」

資料全部虛構（example.com）；公司「觀點週刊」為虛構。

**demo 完要歸零**：`inbox/*.txt.done` 改回 `.txt`、清空 `outbox/`、`data/clean/`、`data/私密_代號對照表.csv`、`log/report_log.md` 只留表頭。
