# hw1_M11423042
---

###  實驗一


####  圖像檔案
| 類別 | 檔名 | 說明 |
|------|------|------|
| 混淆矩陣圖 | `CM_ID3.png`, `CM_C45.png`, `CM_C50.png`, `CM_CART.png` | 各演算法在測試集的分類結果視覺化。 |
| 決策樹圖 | `Tree_ID3.png`, `Tree_C45.png`, `Tree_C50.png`, `Tree_CART.png` | 各模型的三層決策樹結構。 |

> 🔸 `CM_` 開頭 → 混淆矩陣圖  
> 🔸 `Tree_` 開頭 → 三層決策樹圖  

####  程式與結果檔案
| 檔名 | 功能說明 |
|------|-----------|
| **dm_decision_tree_ID3.C4.5.CART.ipynb** | 使用前處理後資料集訓練並測試 **ID3、C4.5、CART** 決策樹分類器。 |
| **dm_decision_tree_C5.0.ipynb** | 使用前處理後資料集訓練並測試 **C5.0** 決策樹分類器。 |
| **Test_Predictions_ID3.C4.5.CART.xlsx** | 彙整 ID3、C4.5、CART 模型的測試集預測結果。 |
| **Test_Predictions_C5.0.xlsx** | 彙整 C5.0 模型的測試集預測結果。 |

---

###  實驗二

共四個檔案，探討 **CART 決策樹** 之 **後剪枝 (Cost-Complexity Pruning)** 與模型複雜度。

| 檔名 | 功能說明 |
|------|-----------|
| **dm_post_pruning_decision_tree_finalver.ipynb** | 透過 **Grid Search** 比較不同樹深度與葉節點數的組合，並以 **Elbow Method** 尋找模型複雜度與準確率的平衡點。選出三組代表模型（Small、Medium、Large），最後於測試集進行評估。 |
| **Small_tree_d3_l16.png** | 小型模型（樹深度=3，葉節點=16）之決策樹圖。 |
| **Medium_tree_d6_l16.png** | 中型模型（樹深度=6，葉節點=16）之決策樹圖。 |
| **Large_tree_d10_l64.png** | 大型模型（樹深度=10，葉節點=64）之決策樹圖。 |
