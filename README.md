# 🧠 AI-EDA-Report-Generator

Upload any dataset → Auto data profiling → 4 chart types → LLaMA 3 writes a professional business insight report → Exported as PDF.
The entire analysis runs in 2 lines of code.

## How to Use
1. Clone the repo
2. pip install -r requirements.txt
3. Get free Groq API key from https://console.groq.com
4. Open AI_EDA_Reporter.ipynb in Jupyter
5. Run all cells — enter your Groq key when prompted
6. df = pd.read_csv("your_file.csv") / analyze(df, filename="Your_Dataset")

## Tech Stack
- Python, Pandas, NumPy
- Matplotlib, Seaborn
- LLaMA 3 70B via Groq API (free)
- FPDF2 for PDF export
- Jupyter Notebook

## What You Get
- Distribution histograms
- Boxplots for outlier detection
- Correlation heatmap
- Categorical bar charts
- 6-section AI business report
- Auto PDF export
