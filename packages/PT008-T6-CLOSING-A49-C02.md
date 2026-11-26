# PT-008 · A49-C02 · 六跑者選時器封版裁決

**裁決日期**　2026-11-26（MYT）  
**裁決**　接收 A49-O01。六跑者（T6）選時器 A49-T01 v0.1 通過項目內獨立驗收，准作 GeoGarden 第四站與 Salon No.019 的共用引用版本。歸檔材料由 Tuzi 經 Hesper 轉交。

## 核對與裁決理由

1. **版本一致。** 原選時器 ZIP 的 SHA-256 為 f2a09e1251c71b2bb25f7f564521f0a5236eb08dd3c2d3a0cc2e2b8c5997a54a。A49-O01 的 21 項清單與選時器的 10 項清單均通過。主席從乾淨解壓目錄重跑兩個腳本，輸出與包內日誌以及 Opus 日誌的程式輸出相同。Opus 另做約 13 萬次獨立壓力測試，九條路徑皆出現，回報零失敗。驗收鎖定原 ZIP。診斷、輸入型別說明等改善可另列版本。
2. **低範數兩種計數都成立。** 對平方範數至多 21,608 的正、嚴格遞增五元組，主席以 Opus 的遮罩枚舉另加公因數計數。偶數首項的 40,189,228 組中有 37,785,408 組本原，奇數首項的 42,915,931 組中有 42,759,932 組本原。合計 **83,105,159 組，其中 80,545,340 組本原**，遮罩交集為空的案例為零。前者是 A49-O01 的覆蓋超集，後者是 A47-C11 與實際正規化的口徑。「規範輸入」在 A49-O01 的這一行應讀為正且嚴格遞增，未加本原條件。
3. **中段的程式確實使用飽和平面。** 設 \(H=z^\perp\)、\(\Lambda_H=H\cap\mathbb Z^5\)，令 \(\pi\) 為到 \(H\cap U^\perp\) 的正交投影，\(\Gamma=\pi(\Lambda_H)\)。因 \(U\) 本原，\(\ker(\pi|_{\Lambda_H})=\mathbb ZU\)。程式選的是 \(\Gamma\) 基底的首向量 \(\gamma_1\)，並取整數抬升 \(v\in\Lambda_H\)。若 \(x\in\operatorname{span}_{\mathbb R}(U,v)\cap\mathbb Z^5\)，則 \(x\in\Lambda_H\)，且 \(\pi(x)\in\mathbb R\gamma_1\cap\Gamma=\mathbb Z\gamma_1\)。因此 \(x-nv\in\mathbb ZU\)，平面整數格正是 \(\mathbb ZU+\mathbb Zv\)。Opus 對一般整數向量對的提醒適用。這一支的投影基底條件提供了飽和性。
4. **中段上界已複核。** A49-C01 的有理頂點驗算已重跑。對 \(Z=6,\ldots,13\)，所需的整數 Gram 行列式上界依序是 **647、4630、246、728、289、521、332、540**，與 v0.1 的 MIDDLE_BOUNDS 一致，均落在對應平面證書的範圍。A48-O01 的第二關係平方範數界 **10**（\(Z=4\)）與 **19**（\(Z=5\) 全一型）均採用。19 界的平面由已驗收的 37 界證書包含。
5. **驗收命題。** 給定任意五個非零整數相對速度，v0.1 選出有理時刻 \(t=a/b\)，使各 \(\|U_i t\|_{\mathbb R/\mathbb Z}\ge1/6\)。安全條件含等號，輸出按原始速度作整數驗證。封版範圍為 T6 的構造與實作，包含有限證書、格約化及平面相位胞讀出。任意跑者數的終端公式（Terminal Formula）仍開放。

## 歸檔入口

原包、獨立驗收、全域分流與本裁決應以各自版本一併留存。程式重放入口是選時器內的 replay.py 與 find_fixtures.py；中段界的驗算入口是 A49-C01 包內的 bridge_bounds.py。A47-C11、A48-C01 及 A38、A40–A46 分支證書，依 A49-C01 的對應表列入索引。

- [A49-T01 選時器 v0.1](https://chatgpt.com/library?file_id=libfile_9d8bc423b0dc8191a3375931de9cd79e&account_id=personal)
- [A49-O01 Opus 獨立驗收](https://chatgpt.com/library?file_id=libfile_e083eaf3d42c81918a5ad1f4309f177b&account_id=personal)
- [A49-C01 全域分流](https://chatgpt.com/library?file_id=libfile_916f55818de08191b0a54a2c9743e444&account_id=personal)
- [A47-C11 獨立重放包](https://chatgpt.com/library?file_id=libfile_c4243e97740881918d5c9863ad03fc9a&account_id=personal)
- [A48-C01 獨立重放包](https://chatgpt.com/library?file_id=libfile_77e3d6c506e48191860b22ba80f00049&account_id=personal)
