# Earnings-Call-Catalyst-Intelligence-Lab

📈 Earnings Call and Stock Price Movement Details

An interactive, single-file notebook-style LLM application and quantitative options strategy chatbot for financial analysts, traders, and quant developers.

The Catalyst Intelligence Lab ingests management earnings transcripts, extracts forward guidance changes, quantifies executive tone shifts across quarters, calculates post-earnings volatility probability cones, and recommends options straddle / delta-neutral hedging setups in real time.

✨ Key Features

📓 Jupyter-Style Interactive Notebook Interface:

[In 1] Guidance Matrix Ingestion: Extract revenue, gross margin, and CapEx updates into tabular comparison models.

[In 2] Executive Tone Shift Quantification: 5-axis sentiment radar chart tracking Revenue Conviction, CapEx Intent, Pricing Power, Demand Stability, and Defensive Stance.

[In 3] Post-Earnings Volatility & Probability Cone: 14-day expected price movement envelope using $1\sigma$ and $2\sigma$ volatility bands powered by Chart.js.

[In 4] Python Strategy Sandbox: Editable execution cell simulating straddle breakeven bounds, options delta, and hedge ratios.

🤖 Strategy & Probability Chatbot:

Right-side conversational agent built with Gemini 3 Flash (gemini-3-flash-preview).

Capable of modeling implied volatility (IV) crush, options straddles vs. strangles, risk/reward profiles, and tail risk hedging.

⚡ Zero Setup & Client-Side Execution:

Built entirely as a standalone, single-file web application (index.html). No Node.js build tools, webpack, or backend servers required.

Custom API Key management with live connectivity validation status and persistent localStorage support.

🛠️ Tech Stack

Frontend: HTML5, Vanilla JavaScript (ES6+)

Styling: Tailwind CSS (via CDN)

Data Visualization: Chart.js

Markdown Parsing: Marked.js

LLM Engine: Google Gemini API (gemini-3-flash-preview)

🚀 Quick Start

Clone the repository:

git clone https://github.com/your-username/earnings-catalyst-intelligence-lab.git
cd earnings-catalyst-intelligence-lab


Launch the application:
Open index.html directly in any standard browser (Chrome, Safari, Firefox, Edge).

Configure API Key (Optional):

Enter your Google Gemini API Key into the top navigation header bar.

Click Test API to verify the connection. The status dot will turn glowing green once validated.

Note: If no API key is provided, the application runs using preset quantitative market simulations.

📖 How to Use

1. Preset Ticker Selection

Use the ticker dropdown in the header to load pre-built scenarios:

NVDA: AI Data Center CapEx surge & Blackwell architecture guidance.

AAPL: Services growth & Apple Intelligence guidance update.

COIN: Institutional ETF inflows, USDC interest revenue & crypto macro volatility.

CUSTOM: Paste your own 8-K filing snippet or corporate transcript.

2. Notebook Execution

Click Run Notebook in the top bar to execute all analysis cells sequentially, or run individual cells via their respective Run Cell buttons.

3. Quantitative Options Strategy Chat

Select quick prompt chips (Straddle Setup, Bearish Risks, Risk/Reward) or type custom queries into the chat prompt input.

Discuss optimal strikes, expiration dates, delta-neutral hedges, and implied volatility crush mitigation strategies.

📄 License

Distributed under the MIT License. See LICENSE for more information.
