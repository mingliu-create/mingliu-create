# Tzu-Ming Liu 劉子銘

國立中興大學資訊工程學系碩士班（2025–2027）。
研究興趣：人工智慧代理人(AI agent)與地理資訊（GIS）應用、邊緣 AI、序列預測。

## Selected Work

### 第六屆航港大數據創意應用競賽（航港盃）學生組 冠軍
團隊 SpaceY（6 人）作品「永續智能航港生態系」。我主責「短時微氣候預測 × 派工建議」模組：
設計以 LSTM 為核心、各氣象特徵分開建模的高雄港短時預測方案，並負責該模組的前端介面。
- 後端：[iMarine-mircoclimate-I-O](https://github.com/NCHU-ICTALab/iMarine-mircoclimate-I-O)
- 前端：[iMarine-FrontEnd](https://github.com/NCHU-ICTALab/iMarine-FrontEnd)（我以 PR 貢獻微氣候模組介面，其餘部分非我負責）

### 手術器械序列預測（中國醫合作專案）
YOLO 模型由組員訓練；我負責器械標記資料、序列前處理與馬可夫鏈預測。1 階馬可夫鏈下一支器械預測準確率：人工標註序列 86.8%、YOLO 偵測序列 92.9%（0 階約 48%）。
- 程式與實驗報告：[markov_prediction_tools](https://github.com/mingliu-create/markov_prediction_tools)

### FloodGuard：強健性邊緣 AI 颱風洪水預警系統（TGIS 2026，第一作者）
ESP32 + LoRa 邊緣推論，斷網時仍可本地預警。以合作教師提供的模擬資料驗證，輕量 MLP 召回率 100.0%、精確率 82.0%；INT8 量化後模型縮小約 75%。

## Tech
Python · PyTorch · scikit-learn · YOLO · LSTM · FastAPI
