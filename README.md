# 🕵️ RealtyCheck

**RealtyCheck** is a smart, no-fluff web app that helps real estate investors — especially those looking at vacation homes — make safer, smarter decisions. By using data from Redfin, Zillow, FEMA, and vacation rental trends, RealtyCheck acts like a digital detective, spotting hidden risks in properties, forecasting returns, and comparing investment options with ease.

---

## 📌 Project Summary

**Investing in real estate is hard.**  
RealtyCheck simplifies the process by showing users the *real story* behind each property — from flood zones and crime trends to vacation rental restrictions and ROI forecasts — so they don’t fall into costly traps.

---

## 🔑 Key Features

### 🔍 Smart Risk Detection
- Generates a **Risk Score** (0–100) based on:
  - Natural disaster zones (FEMA)
  - Crime rate trends (Crimeometer API)
  - Suspicious listing behavior (frequent relisting, flips)
  - HOA lawsuits, zoning changes, foundation issues

### 🏖️ Vacation Home Insights
- **Vacation Viability Index**:
  - Airbnb/VRBO income estimates
  - Occupancy rates and seasonal trends
  - Local STR (short-term rental) regulations
  - Warns against holiday-adjacent or oversaturated zones

### 📊 Investment Comparison Tool
- Compare any number of properties side-by-side:
  - Risk score
  - Insurance cost and loan eligibility
  - Natural disaster risk
  - Neighborhood business vitality
  - ROI potential (resale + rental)

### 💰 Forecast Tool
- Input your:
  - Investment amount
  - Timeframe (in years)
- Outputs:
  - Projected ROI or loss
  - Estimated rental income
  - Price appreciation trends
  - Tax benefits (first/second home)

### 🧾 Financial Snapshot
- For each property, RealtyCheck shows:
  - Estimated insurance premiums
  - Property taxes
  - Loan options (FHA, VA, conventional)
  - HOA fees and hidden costs

---

## 🗂 File Structure

/RealtyCheck
├── index.html              # Homepage – search by ZIP, browse top listings
├── compare.html            # Compare selected properties by risk & return
├── forecast.html           # Investment calculator (timeframe, return, risk)
│
├── /css
│   └── styles.css          # Styling for all pages
│
├── /js
│   ├── app.js              # Logic for homepage and ZIP search
│   ├── comparison.js       # Comparison dashboard logic
│   └── forecast.js         # ROI calculator logic
│
├── /assets
│   └── icons/              # Icons and images used in UI
│
├── /data
│   └── sample-listings.json  # Example listing data or API-connected results


---

## 🔧 Tech Stack

- **Frontend:** HTML, CSS, Vanilla JavaScript
- **No frameworks (no React.js)**  
- **APIs & Data Sources:**
  - **Zillow & Redfin** – Property data and trends
  - **FEMA API** – Disaster zone mapping (flood, wildfire, earthquake)
  - **Crimeometer API** – Crime trends and safety scores
  - **AirDNA / Mashvisor (optional)** – Vacation rental income and occupancy
  - **Google Maps & Yelp APIs** – Business activity and neighborhood insights
  - **Bankrate/NerdWallet (optional)** – Loan comparison and mortgage insights

---

## 📈 How It Works

1. **Search** by ZIP code or location
2. **View top properties** with risk and ROI highlights
3. **Compare** multiple listings in a detailed breakdown
4. **Forecast** your investment’s potential based on time and money
5. **Decide** with clarity, backed by real data — not just realtor talk

---

## 🔮 Future Features

- In-app verified real estate agents
- AI assistant to explain reports and risks
- PDF upload for home inspections → instant AI summary
- International vacation markets support
- Real-time reviews from past buyers

---

## ⚖️ License

**MIT License** – Free for personal, academic, and non-commercial use.

---

## 👥 Contributors

Created by a team passionate about:
- Smarter real estate investing  
- Data-driven decision-making  
- Building tools that protect and empower everyday investors

---
