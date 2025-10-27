# RebalanceAI
RebalanceAI is an intelligent investment assistant designed to make financial analysis simpler, 
smarter, and more transparent. 
It blends quantitative analytics; things like volatility, Sharpe ratio, and returns, with AI
driven market sentiment, helping investors understand not just the numbers, but also the 
narrative behind them. 
Built using LangChain’s agent framework, RebalanceAI coordinates several specialized tools 
that work together seamlessly. It automatically pulls live market data, cleans it, computes 
technical indicators, interprets sentiment trends, evaluates portfolio risk, and finally, suggests 
optimized allocations, all while explaining its reasoning in plain language. 


```
Setup & Installation 
Prerequisites 
• Python 3.8+ 
• Google Colab (recommended) or local Jupyter environment 
• OpenAI API Key 
Step 1: Clone/Download 
# Download the notebook: Hackathon_final.ipynb 
Step 2: Install Dependencies 
!pip install -q yfinance matplotlib numpy pandas gradio openai langchain 
langchain-openai 
Step 3: Configure API Key 
For Google Colab: 
from google.colab import userdata 
os.environ["OPENAI_API_KEY"] = userdata.get("OPENAI_API_KEY") 
For Local Environment: 
import os 
os.environ["OPENAI_API_KEY"] = "your-api-key-here" 
Step 4: Run Cells Sequentially 
Execute all cells in order from Cell 1 to Cell 20 to initialize all components. 
Step 5: Launch Interface 
Option A: Gradio Web UI 
# Run the Gradio cell to launch web interface 
# Access via the generated public URL 
Option B: Command-Line Chat 
chat_with_agent()
```

The warnings are avoidable. Gradio Interface, works once deployed in your system on a seperate tab (That's not an error)
