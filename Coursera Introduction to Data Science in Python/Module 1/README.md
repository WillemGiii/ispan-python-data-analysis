# Coursera: Introduction to Data Science in Python - Module 1
## 資料處理基礎與描述性統計 (Basics of Data Manipulation and Descriptive Statistics)

### 課程概述 (Overview)
本單元旨在引導學習者掌握 Python 進行資料處理的最基礎技能。核心重點在於如何在不依賴第三方庫（如 Pandas）的情況下，使用 Python 標準函式庫處理結構化資料檔案（CSV），並實作基礎的描述性統計分析。透過「汽車燃油效率」真實案例，學習者將練習資料讀取、清理、分組與計算平均值等關鍵步驟。

### 核心學習目標 (Learning Objectives)
1. **資料存取技術**：熟練使用 Python `csv` 模組及其 `DictReader` 類別讀取結構化檔案。
2. **資料結構轉換**：理解如何將 CSV 內容映射為由字典組成之列表（List of Dictionaries）。
3. **基礎統計計算**：練習資料分組（Grouping）與聚合（Aggregation），如計算不同級距車輛的平均油耗。
4. **輔助工具運用**：掌握 Jupyter Notebook 魔術指令 `%precision` 以及 Python 重要內建函式如 `set()`、`lambda`。

---

### 目錄結構與檔案說明 (Directory Structure)

#### 核心教學檔案
- **`1 Reading and Writing CSV files.ipynb`**
  - 本單元的主教材。
  - 涵蓋 CSV 檔案讀取、資料字典化、計算城市（cty）與高速公路（hwy）之平均油耗。
  - 根據氣缸數（cyl）與車輛類別（class）進行進階分組統計分析。

#### 補充教材 (Supplementary Materials)
- **`99_[Supplementary Instructional Materials] %precision2.ipynb`**：詳細說明如何控制 Jupyter Notebook 中浮點數的顯示精度。
- **`99_[Supplementary Instructional Materials] Lambda_Anonymous_function.ipynb`**：介紹匿名函式（Lambda Function）的語法及其在資料處理（如 `sort`）中的應用。
- **`99_[Supplementary Instructional Materials] set function.ipynb`**：探討集合（Set）的特性及如何利用其自動去重功能提取資料庫中的唯一類別。

#### 資料集 (Datasets)
- **`datasets/mpg.csv`**
  - **來源**：汽車環保測試中心之調查資料。
  - **內容**：包含 234 筆車輛記錄。
  - **重要欄位**：
    - `manufacturer`：製造商
    - `cyl`：氣缸數量
    - `cty`：城市道路油耗
    - `hwy`：高速公路油耗
    - `class`：車輛級距（如 Compact, SUV, Pickup 等）

---

### 使用說明 (Usage)
1. 確保已安裝 Jupyter Notebook 環境或 VS Code Jupyter 擴充。
2. 開啟 `1 Reading and Writing CSV files.ipynb` 依序執行儲存格。
3. 閱讀補充教材以強化對 Python 進階動態語法的理解。

### 授課教師與版權資訊
本教材改編自 Coursera "Introduction to Data Science in Python" 課程，旨在為學員提供嚴謹且具實務性的 Python 數據分析基礎培訓。
