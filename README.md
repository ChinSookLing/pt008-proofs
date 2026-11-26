# PT-008 Time Forge · 公開證明包鏡像

六跑者（T6）選時器封版檔案（A49-C02）附錄 A 所列原件的免登入公開鏡像。每個檔案與原件逐位元組相同，可用完整 SHA-256 驗證。

- 下載：`packages/` 目錄，或 GitHub 頁面的 Code → Download ZIP。
- 驗證：在 `packages/` 內執行 `sha256sum -c ../SHA256SUMS`。
- `a45_t01_certs.zip`（115,167,798 bytes）超過 GitHub 單檔 100 MB 上限，分成 `a45_t01_certs.zip.part00`、`part01`。還原：`cat a45_t01_certs.zip.part* > a45_t01_certs.zip`，再驗 SHA-256。分段摘要見 `packages/PARTS.sha256`。

狀態：T6 整數核心在項目內閉合（主席裁決 A49-C02）。外部同行評審（peer review）待進行。任意人數終端公式（Terminal Formula）仍開放。

## 清冊

| 項目 | 內容 | 檔名 | bytes | SHA-256 |
|---|---|---|---|---|
| A48-T01 | Hesper 的 Z=3、4 首輪三維中心表 | `a48_t01.zip` | 53,334 | `11692a6a8c3834b555e667cb2415b2ed782e4a68354817e9339596d7b5bad31f` |
| A48-O01 | Z=3、4 上界及全一型 Z=5 改進 | `PT008-TF-R002-A48-O01.zip` | 25,783 | `43614fc4254f95835fa8baf1ea69bec1a840565c7c7999b65a675f03feb6ce6f` |
| A48-C01 | Z=3、4 尾端全量重放 | `PT008-TF-R002-A48-C01-replay.zip` | 60,550 | `4dfe57239f767157ede18858256b641c9dbc0a2b5b09e9d75a9486324b25cce9` |
| A49-O01 | Opus 獨立驗收、有限窮舉與壓力測試原件 | `PT008-TF-R002-A49-O01.zip` | 21,463 | `4e577f6ff7588cc2be16b058934e477804f04060d20f242c835e640895a0db03` |
| A45-T01 | Z=7 上段的程式、批表及例外 | `a45_t01.zip` | 2,709,742 | `50b19e99c6dcab9035643a66f6c94e1608d57a5d9cc5955182eafd35518248cc` |
| A46-T01 | Z=6，含原 31 批證書及精確核對 | `a46_t01.zip` | 2,130,430 | `5151053275c6c1a0f109b68169c511a9cc9270b6463de6017d5c8605e505c7f1` |
| 降維審核 O01 | Z=5 的 HKZ 及第二關係界 | `PT008-TF-R002-Z5-DESCENT-LEMMA-REVIEW-O01.zip` | 14,606 | `57342029affad3a1b0635ef81d8c5e469b7f99997becb7f40da2551f0e6a486a` |
| A42 | Z=10 原證書 | `a42_code.zip` | 11,343,122 | `692ed57f061b512d4e52c82aefb1eb4f746561380bb70301c46f27afa9d903fb` |
| A49-C01 | 全域銜接證明與橋接界 | `PT008-TF-R002-A49-C01-stitch.zip` | 3,987 | `6b1bcf0bc2a8183714e007baf8a269bd33568c4228afb6d22aac07680b86a401` |
| A45-O03 | Z=7、D≤728，Opus 精確核對 | `PT008-TF-R002-A45-O03.zip` | 1,098,294 | `6fa83d5d2e0111f299c4388fb01d2d02c6ce7cca7fceb42ac8f879f49cc0eedc` |
| A47-T11 | Hesper 的 Z=5 原程式與輸出摘要 | `t11_hesper.zip` | 75,897 | `71ac2f3524d01d415e792ed771ced27da186b3d774d1a1ae1facd3e7947514b5` |
| A47-O09 | 秩一等號、剩餘枚舉完備性及退化分支 | `PT008-TF-R002-A47-O09.zip` | 47,110 | `74c32ad95b7938fddc940cd0f688479fac96dfc58e9645391620fff517487f8d` |
| A45 開放清單 | Z=7、D≤728，原全表及開放表 | `a45_open.zip` | 3,250,119 | `78f048d82d7889e856b51a04294da4e594270a8bfb047150f4f5dc3334809880` |
| A47-C11 | 低範數獨立見證及 Z=5 尾端全量重放 | `PT008-TF-R002-A47-C11-replay.zip` | 402,750 | `7d4fef0664e68315fa859fa3dba57da0d494e5ba8025fc5345591ae0c393313e` |
| A40 | Z=12 原證書 | `a40_code.zip` | 3,048,438 | `8172162b8974cab4cd21d79fa08db9999ae094d00e67502e8ae48b5153e9c663` |
| A45-T01 資料 | Z=7 上段 78 批原資料 | `a45_t01_certs.zip` | 115,167,798 | `973f8fac18be82c072bfc0581b1f23dfc2078d26a8d6a0aefbc44b0ea380d0b7` |
| A38 | Z=13 原證書，資料表在包內，剩餘見證可按 README 重建 | `a38_code.zip` | 2,139,811 | `b0f923174952abe1e00278f879f006ade38415c4a2a0242b6020f5bec9257dda` |
| A44 | Z=8 原證書 | `a44_code.zip` | 317,019 | `bfbff4fe44a42054761f4020de13349f59e4687064e55baa2adfccd8258e8bb6` |
| A47-O08 | 三維空間到平面及秩一降維 | `PT008-TF-R002-A47-O08.zip` | 320,886 | `da0a523bf48b2907141e5e04c333a5c98366e49eb3a491a4873ff8f432eba12e` |
| A43 | Z=9 原證書 | `a43_code.zip` | 86,631,357 | `e2d1c778273c567bbedd53c7134542a0eeade20ee175641582d9e2a216f65e9e` |
| A39 G1 | 圓盤取時引理獨立審核與 Lean 環境紀錄 | `PT008-TF-R002-A39-G1-OPUS-REVIEW.zip` | 11,250 | `f00735a281bf83a0d904d6b09a060f68f745748ca47283eba61f1d874e454de4` |
| A49-T01 | 封版原程式、固定例、遮罩及重放日誌 | `PT008-TF-R002-A49-T01-selector-v0.1.zip` | 57,657 | `f2a09e1251c71b2bb25f7f564521f0a5236eb08dd3c2d3a0cc2e2b8c5997a54a` |
| A41 | Z=11 原證書 | `a41_code.zip` | 30,027,508 | `f2e636e561483abb2f8b1472b94d4f684ef43703a4b300bf4341dbe15311a1ae` |
| A45-O01 | 閉胞讀出及完備性，PolyT45.lean 與檢查紀錄 | `PT008-TF-R002-A45-O01.zip` | 142,714 | `fd824ac061536ace11b9e9a101cfdebb3c5ad549662feb5171d82cf579fe0754` |
| A49-C02 | 封版裁決、平面飽和性與兩種計數口徑 | `PT008-T6-CLOSING-A49-C02.md` | 3,786 | `d205d20b941ad63bb9c0de80e8abc0de4b30ef7a089704b43452580140f90559` |
| A45／A46 精確重放 | 主席續存的獨立核對原碼、重放入口和參照輸出 | `PT008-T6-A45-A46-exact-replay.zip` | 14,913 | `0cebd90e830ed318806bbab0d96973f3a587e68b82e7d54cb2afdb7804d27b03` |

R002 歷史補檔為內部交接包，不列入公開鏡像。

上傳整理：Hesper（Hark）。統籌：Tuzi。
