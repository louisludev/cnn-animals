# cnn-animal

lion &amp; leopard

Python : 3.9.0

CUDA : 11.2.0

cuDNN : 8.1.0

dataset

https://www.kaggle.com/datasets/mikoajfish99/lions-or-cheetahs-image-classification?resource=download
https://www.kaggle.com/datasets/patriciabrezeanu/big-cats-image-classification-dataset
https://www.kaggle.com/datasets/antobenedetti/animals

基礎工具與通用套件
absl-py：Google 開發的 Python 庫，提供通用功能如應用程式框架和測試支持。
asttokens：處理 Python 抽象語法樹 (AST) 的工具，幫助理解程式結構。
astunparse：將 Python 抽象語法樹重新轉回程式碼。
cachetools：提供快取資料結構和管理的工具。
certifi：用於驗證 HTTPS 通訊時的 SSL 憑證。
charset-normalizer：檢測文字編碼並進行處理。
colorama：在終端上添加文字顏色支援，常用於 CLI 程式。
decorator：簡化 Python 裝飾器的撰寫。
________________________________________
科學計算與數據處理
numpy：數值計算的核心庫，處理矩陣和大規模數據運算。
scipy：基於 numpy，提供高級數值運算功能，如線性代數、優化和信號處理。
pandas：處理表格數據的強大工具，支援資料分析與操控。
matplotlib：2D 資料視覺化工具，用於繪製各類圖表。
seaborn：基於 matplotlib 的高階繪圖庫，適合統計視覺化。
h5py：用於處理 HDF5 格式文件，儲存大規模數據。
joblib：高效地保存和加載大型數據，支援多執行緒運算。
________________________________________
機器學習與深度學習
scikit-learn：機器學習的標準庫，包含分類、回歸和聚類等演算法。
tensorflow-gpu：深度學習框架 TensorFlow，支持 GPU 加速。
keras：深度學習高階 API，基於 TensorFlow，簡化網絡建模。
tensorflow-estimator：提供 TensorFlow 模型的簡單封裝，用於訓練和評估。
tensorflow-io-gcs-filesystem：TensorFlow 文件系統擴展，支持 Google Cloud Storage。
________________________________________
深度學習可視化與監控
tensorboard：深度學習模型的監控工具，可視化訓練過程。
tensorboard-data-server：TensorBoard 的數據服務層。
tensorboard-plugin-wit：TensorBoard 插件，用於查看和解釋模型預測。
________________________________________
網絡通信與身份驗證
requests：HTTP 請求庫，適用於與 Web API 通信。
google-auth、rsa：支援 Google API 的身份驗證。
requests-oauthlib：整合 OAuth 身份驗證到 requests。
oauthlib：實現 OAuth 身份驗證協議。
________________________________________
Jupyter 環境相關
ipykernel、ipython：支持 Jupyter Notebook 運行 Python 程式。
jupyter_client、jupyter_core：支援 Jupyter 的核心通信功能。
matplotlib-inline：在 Jupyter Notebook 中內嵌圖表顯示。
________________________________________
開發者工具
debugpy：為 VSCode 提供調試功能。
Pygments：程式碼高亮工具。
prompt_toolkit：交互式命令列應用框架。
stack-data：顯示錯誤堆疊時的詳細數據。
________________________________________
支援函式庫
python-dateutil、pytz：處理日期和時間操作。
typing_extensions：為舊版本 Python 提供新型別提示功能。
platformdirs：跨平台獲取應用程序目錄。
wrapt：裝飾器和包裝工具，實現功能拓展。

