# Phrase Segmentation of Jiangnan Music Using YNote Representation

[![Conference](https://img.shields.io/badge/Conference-Ubi--Media_2026-blue.svg)](https://2026umediaconf.com/)
[![DOI](https://img.shields.io/badge/DOI-10.1007%2F978--981--95--9843--4__16-orange.svg)](https://link.springer.com/chapter/10.1007/978-981-95-9843-4_16)
[![Paper PDF](https://img.shields.io/badge/Paper-Download_PDF-red.svg)](./PhraseSegmentation.pdf)

> 本儲存庫收錄發表於 **The 2026 International Conference on Ubi-Media Computing (Ubi-Media 2026)** 之研究論文全文與相關資料。

---

## Publication Details

* **Title:** Phrase Segmentation of Jiangnan Music Using YNote Representation
* **Venue:** The 2026 International Conference on Ubi-Media Computing (Ubi-Media 2026), Penang, Malaysia
* **Authors:** **Yu-Chia Wang (第一作者)**, Yung-Chi Tseng, Cheng-Yang Tsai, Tzu-Wei Huang, Shu-Yen Shih, and Yu-Cheng Lin
* **Publisher:** SpringerLink
* **Official Link:** [https://doi.org/10.1007/978-981-95-9843-4_16](https://link.springer.com/chapter/10.1007/978-981-95-9843-4_16)
* **Full Paper:** [📄 點此檢視 / 下載 PDF (Direct PDF Link)](./PhraseSegmentation.pdf)

---

## Abstract
傳統音樂樂句切分多依賴連續音訊特徵，缺乏符號層級的可解釋性。本研究提出一套基於結構化文本與統計機率模型的自動樂句分段系統。透過 **YNote 表徵法** 將江南絲竹等符號音樂轉換為結構化文本序列，萃取切分點前後之音高、音程與時值特徵，並導入**蒙地卡羅模擬（Monte Carlo Simulation）**進行邊界搜尋。實驗結果顯示，本方法在均勻採樣下達到約 0.7 之 F1-score，並從計算角度證實「音符時值（Note Duration）」為判定樂句邊界之關鍵特徵。

---

## Contributions

* **特徵工程與機率模型建構：** 主導萃取樂句邊界前後之音符特徵，建立統計機率分佈規則。
* **符號化表徵轉換：** 運用 YNote 表徵法將音樂結構化為可計算之文本序列，奠定後續演算法基礎。
* **蒙地卡羅邊界探索：** 實作動態邊界搜尋機制，量化驗證音符時值對分段之關鍵影響。

---

## Citation

若本研究對您的研究有所啟發，歡迎引用本篇論文：

```bibtex
@inproceedings{wang2026phrase,
  title={Phrase Segmentation of Jiangnan Music Using YNote Representation},
  author={Wang, Yu-Chia and Tseng, Yung-Chi and Tsai, Cheng-Yang and Huang, Tzu-Wei and Shih, Shu-Yen and Lin, Yu-Cheng},
  booktitle={The 2026 International Conference on Ubi-Media Computing (Ubi-Media 2026)},
  year={2026},
  publisher={Springer},
  doi={10.1007/978-981-95-9843-4_16}
}
