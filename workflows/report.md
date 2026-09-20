# report — 出月報

1. 讀 `inbox/` 的指示（若有），確認月份；沒有就用今天所在月份。
2. 用 Python 讀 `data/raw/` 三張表：統一 Email 代號（寫 `data/私密_代號對照表.csv`）、統一日期；輸出去敏版到 `data/clean/`（三個 CSV，只有代號沒有個資）。
3. 依 `knowledge/02` 算全部指標；每個指標記下分子／分母。
4. 寫產出到 `outbox/`（每檔最上面 `> 狀態：待確認`，HTML 用 `<!-- 狀態：待確認 -->`）：
   - `YYYY-MM_訂戶月報.md`：資料盤點｜串接結果｜三個發現｜下一步，數字附算法
   - `YYYY-MM_流失預警名單.csv`：代號、方案、到期日、App 狀態、商城狀態、價值分群、建議順序
   - `YYYY-MM_儀表板.html`：照 `knowledge/03`
5. `log/report_log.md` 加一列
6. 依 `knowledge/04` 三行交件

## 不准做的
- 不准把姓名／Email／手機寫進 outbox
- 不准安裝套件、不准連網
