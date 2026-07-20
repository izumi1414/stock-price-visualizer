# 株価可視化アプリ

Yahoo Financeから株価データを取得し、複数銘柄の終値を表やグラフで可視化するシンプルなWebアプリです。

## 主な機能
- 複数銘柄の株価取得
- 直近0~50日間の終値を表示
- 株価データの可視化

## 使用技術
- Python
- Streamlit
- Pandas
- yfinance
- Altair

# セットアップ手順

```bash
# Clone the repository
git clone <repository-url>

# Move to the project directory
cd stock-price-visualizer

# Create and activate a virtual environment
python -m venv .venv

# macOS / Linux
source .venv/bin/activate

# Windows
.venv\Scripts\activate

# Install dependencies
pip install -r requirements.txt

# Run the application
streamlit run main.py
```