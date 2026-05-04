# AI-IssacSim-Project

**專案目標:**
本專案旨在運用人工智慧建模技術，快速建立可用於模擬之數位場景，並整合至 NVIDIA Isaac Sim 平台中進行初步視覺化（visualization）驗證。並透過調整液體材質相關參數（如黏度、表面張力與流動性），模擬點膠設備於平面上釋放液體時的擴散行為與覆蓋範圍。

**操作說明（Operation Procedure）**

1.於 NVIDIA Isaac Sim 的 Stage 面板中搜尋並選取 particleMaterial 相關物件。
2.開啟 Property 面板，定位至 Extra Properties 區域。
3.根據模擬需求，調整以下等液體參數：Surface Tension,Viscosity, Gravity
4.透過不同參數組合，模擬液體在平面上的接觸、擴散及覆蓋範圍變化。
