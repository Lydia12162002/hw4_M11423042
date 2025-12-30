# hw4_M11423042
---

####  圖像檔案
| 類別 | 檔名 | 說明 |
|------|------|------|
| Apriori演算法 | `Apriori_n_rules_maxlen3.png`, `Apriori_n_unique_recommendable_items_maxlen3.png`, `Apriori_time_total_sec_maxlen3.png` | Apriori演算法的的輸出結果。 |
| FP-Growth演算法| `Growth_denseplusreuse_itemsets_n_rules_maxlen3.png`, `Growth_denseplusreuse_itemsets_n_unique_recommendable_items_maxlen3.png`, `Growth_denseplusreuse_itemsets_time_total_sec_maxlen3.png` | FP-Growth演算法的的輸出結果。 |

####  程式與結果檔案
| 檔名 | 功能說明 |
|------|-----------|
| **HW4_Associative analysis.ipynb** | 對真實交易資料進行清理與轉換，建立交易與商品的關係，再分別使用 Apriori 與 FP-Growth 演算法進行關聯規則探勘，透過多組支持度與信心度參數比較規則數量與運算效能，並將結果存檔與視覺化呈現，最後實作一個可輸入多商品的推薦系統作為應用示範。 |
| **best_rules.csv** | 推薦系統實際使用的最終關聯規則。 |
| **mined_rules_fpgrowth_maxlen3.csv** | 保存 FP-Growth在指定參數下所挖掘的關聯規則，作為規則存檔與重複使用的示範。 |
| **result_apriori.csv** | Apriori演算法整體效能與產出結果的彙整表。 |
| **result_fpgrowth.csv** | FP-Growth演算法整體效能與產出結果的彙整表。 |

---
