# Problem-Solution Mapping: Why We Use These AI/Data Solutions

This document maps the real-world vulnerabilities of underserved communities to the specific data barriers faced by FSPs, and explains exactly **why** our proposed designs solve these problems.

---

## 🌾 1. Alternative-Data Agri-Credit Scoring

* **The Real-World Problem**: Smallholder farmers are locked out of formal bank loans because they have no formal bank accounts or physical collateral. To buy seeds or fertilizers, they must rely on local predatory lenders (*"5-6"* lenders) who charge interest rates of 20% or more per month, trapping them in poverty.
* **The Data Barrier**: Farmers keep handwritten logs of sales in paper notebooks. Formal bank underwriting systems cannot read or verify paper records, making these farmers look like a "zero-history high risk" on paper.
* **Our AI/Data Solution**: Mobile OCR scanning + climate API feeds (satellite NDVI indices) + peer trust scores from community cooperatives.
* **Why it Solves the Problem**: It translates physical farm activity and community reputation into a digital, verifiable **Credit Score**. Banks can now underwrite farmers based on crop yield potential and cooperative trust rather than requiring land titles.

---

## 🏪 2. Voice-Led Micro-Ledger for Retailers

* **The Real-World Problem**: Micro-merchants (*sari-sari* convenience stores, market vendors) work long, exhausting hours. Because they do not track cash flow, they often confuse revenues with profits, leading to stock outs, underpricing, and sudden business closures.
* **The Data Barrier**: Merchants are either too busy or lack the digital literacy to navigate complex accounting apps, type entries, or manage spreadsheets.
* **Our AI/Data Solution**: A WhatsApp/Viber chatbot utilizing Automatic Speech Recognition (ASR) and a natural language parsing LLM.
* **Why it Solves the Problem**: It eliminates the app interface entirely. Merchants track transactions by simply sending short voice notes in their native dialect (e.g., Tagalog, Cebuano). The AI structures the data and responds with simple audio summaries, giving them instant clarity on profit margins.

---

## 🌦️ 3. Parametric Micro-Insurance for Fisherfolk & Farmers

* **The Real-World Problem**: Climate shocks (typhoons, sea swells) regularly destroy boats, nets, and crops in coastal areas. Traditional crop/livelihood insurance takes months to inspect damage and pay out. By then, families have already sold off productive assets or taken high-interest emergency loans to survive.
* **The Data Barrier**: Sending physical insurance adjusters to verify damage in remote, post-disaster coastal barangays is slow, dangerous, expensive, and prone to disputes.
* **Our AI/Data Solution**: A rules engine linked to parametric satellites and ocean sensor feeds (measuring wind speed and wave height) connected directly to mobile wallets.
* **Why it Solves the Problem**: It bypasses the claims adjustment process completely. If a typhoon crosses a coordinate threshold, payouts land in the fisherfolk's mobile wallets (GCash/PayMaya) within 48 hours—allowing them to repair assets and purchase food immediately.

---

## 🧠 4. Subjective Well-being & Stress Tracker

* **The Real-World Problem**: Microfinance institutions (MFIs) push loans based on a borrower's 100% repayment rate. They don't see when a borrower is struggling, borrowing from predatory loan sharks to pay the MFI, or suffering from domestic financial abuse—until the borrower suddenly defaults or faces a mental health crisis.
* **The Data Barrier**: Bank databases only capture binary quantitative metrics (Repaid: YES/NO). They have no way to record qualitative factors, like borrower anxiety, household safety, or community group health.
* **Our AI/Data Solution**: Interactive, conversational voice surveys processed by NLP sentiment models to track "latent financial stress."
* **Why it Solves the Problem**: It flags emotional stress *before* default happens. Loan officers receive dashboard alerts prompting them to offer supportive care (like a flexible payment holiday) rather than deploying punitive collection agents.
