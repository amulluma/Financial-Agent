Financial-Agent

An intelligent AI-powered financial assistant that combines Large Language Models with Retrieval-Augmented Generation (RAG) to provide accurate, context-aware financial analysis.


🎯 What Does It Do?

📄 Analyze Financial Documents: Upload PDFs like annual reports, mutual fund factsheets, or balance sheets
💹 Real-Time Stock Prices: Get live stock market data
🔍 Financial Research: Search the web for latest financial news
🧮 Smart Calculations: Perform financial calculations using natural language
💬 Remembers Context: Intelligent conversation flow with memory


🚀 Quick Start (5 Minutes Setup)
Step 1: Get Your Free API Key

Go to Groq Console 🔗
Sign up for a free account (if you don't have one)
Click "Create API Key"
Copy your API key (keep it safe!)


Step 2: Download the Project
Option A - Using Git:
bashgit clone https://github.com/amulluma/financial-agent.git
cd financial-agent
Option B - Download ZIP:

Click the green "Code" button on GitHub
Select "Download ZIP"
Extract the ZIP file
Open terminal/command prompt in the extracted folder


Step 3: Configure Your API Key
Create a file named .env in the project folder and add your API key:
On Windows:
cmdecho GROQ_API_KEY=your_api_key_here > .env
On Mac/Linux:
bashecho "GROQ_API_KEY=your_api_key_here" > .env
Or manually:

Create a new file named .env
Add this line: GROQ_API_KEY=your_api_key_here
Replace your_api_key_here with your actual key
Save the file


Step 4: Install Requirements
bashpip install -r requirements.txt
⏱️ This will take 2-3 minutes

Step 5: Run the Application
bashpython app.py
Or use Streamlit (if you have the web interface):
bashstreamlit run app.py
🎉 Your Financial Agent is now running!

💡 How to Use
1️⃣ Upload Financial PDFs

Click "Upload PDF" or drag & drop your file
Supported files: Annual reports, factsheets, financial statements
Wait for processing (a few seconds)

2️⃣ Ask Questions
About your document:
"What is the total revenue?"
"Summarize the key financial metrics"
"What are the top 5 holdings in this fund?"
About stock market:
"What's the current price of Apple stock?"
"Get me the latest quote for TSLA"
Financial calculations:
"Calculate 15% of 50000"
"What's the ROI if I invested $10,000 and got $12,500?"
Market research:
"Search for recent Federal Reserve interest rate news"
"What are the latest cryptocurrency trends?"
3️⃣ Get Intelligent Answers
The AI will:

✅ Read your documents and find relevant information
✅ Fetch real-time stock prices
✅ Search the web for latest news
✅ Perform calculations
✅ Remember conversation context
