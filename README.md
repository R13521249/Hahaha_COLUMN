# Column Damage Detection Project

本專案使用 YOLOv8 模型進行混凝土柱裂縫檢測，並進行模型訓練、測試資料推論以及結果輸出。

---

## 專案架構
├── dataset_column/          # 訓練與測試資料集                                                                                                                                                                          
│   ├── column_crack/        # 訓練資料                                                                                                                                                                                 
│   │   ├── train/           # 訓練集                                                                                                                                                                                   
│   │   │   ├── images/      # 訓練圖片                                                                                                                                                                                
│   │   │   ├── labels/      # 訓練標註                                                                                                                                                                                 
│   │   └── test/            # 測試集                                                                                                                                                                                   
├── column_data_yolov8.yaml  # YOLOv8 訓練資料設定檔                                                                                                                                                                     
├── column_submission.csv    # 推論結果輸出檔案                                                                                                                                                                          
├── main.py                  # 主程式碼                                                                                                                                                                                
├── README.md                # 專案說明文件                                                                                                                                                                             
├── environment.yml          # Conda 環境設定檔                                                                                                                                                                         
└── .gitignore               # Git 忽略檔案規則                                                                                                                                                                         
Competetion2_Datasets_Link https://drive.google.com/drive/folders/1yDLcu1347yMhLSPXw9Mpt0ZT-po1hdvV?usp=sharing
