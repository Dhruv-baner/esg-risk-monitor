# ESG Risk Monitoring System 

**AI-Powered ESG Risk Intelligence for UK & EU Companies**

An automated ESG (Environmental, Social, Governance) risk monitoring tool that aggregates multi-source data and unique agentic tools to provide early warning signals and risk assessments for investment and consulting professionals.

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Status](https://img.shields.io/badge/Status-In%20Development-yellow.svg)]()

## TL;DR

This system combines **natural language processing**, **AI agents**, and **multi-source data integration** to monitor ESG risks across 400+ UK and European companies. Built for consulting teams, investment professionals, and compliance officers who need rapid ESG insights for due diligence and portfolio management.

### Key Features
- 🔍 **Multi-Source Data Integration**: Companies House, news APIs, social media, regulatory filings
- 🤖 **AI-Powered Analysis**: Advanced NLP models (FinBERT, transformers) for ESG risk classification  
- 🚨 **Intelligent Alerts**: Autonomous research agents that investigate risk spikes
- 📈 **Predictive Analytics**: Early warning system for emerging ESG controversies
- 📊 **Interactive Dashboard**: Real-time risk scores, trends, and automated reports
- 💰 **Cost-Effective**: Built entirely on free/open APIs and models


### Long Term Plan 
- Expand to EMEA as a whole, integrating an extremely wide range of data sources for a massive pool of companies 
- Create an improved front-end with packaged deployment for convenient use 
- Expand the agentic capabilities to ensure constantly updated and relevant ESG risk insights 
- Ready to use reportgeneration for investors and consultants 

## 🏗️ System Architecture

```
Data Sources → NLP Classification → Risk Scoring → AI Agents → Dashboard
     ↓              ↓                 ↓            ↓          ↓
• Companies House  • FinBERT        • Severity   • Research • Streamlit
• News APIs        • Zero-shot      • Recency    • Predict  • Plotly
• Social Media     • Fine-tuning    • Source     • Alert    • Reports
• Regulatory       • Multi-label    • Composite  • Analyze  • Export
```

## 🚀 Quick Start

### Installation
```bash
git clone https://github.com/yourusername/esg-risk-monitor.git
cd esg-risk-monitor
pip install -r requirements.txt
```

### Configuration
1. Copy `config/api_keys.yaml.template` to `config/api_keys.yaml`
2. Add your API keys:
   - Companies House API (free registration)
   - Guardian News API (free tier)
   - NewsAPI (free tier)

### Run
```bash
# Start with data collection
jupyter notebook notebooks/01_data_collection/

# Launch dashboard (coming soon)
streamlit run src/dashboard/app.py
```

## 📁 Project Structure

```
esg-risk-monitor/
├── notebooks/           # Jupyter notebooks for development & analysis
│   ├── 01_data_collection/    # API testing & data pipeline setup
│   ├── 02_data_processing/    # Data cleaning & preprocessing  
│   ├── 03_nlp_classification/ # ESG risk classification models
│   ├── 04_risk_scoring/       # Risk scoring algorithms
│   ├── 05_ai_agents/          # Autonomous research & prediction agents
│   ├── 06_dashboard/          # Interactive web dashboard
│   └── 07_system_integration/ # Full pipeline & deployment
├── src/                 # Production-ready source code
├── data/               # Raw and processed datasets
├── config/             # Configuration files & API keys
└── results/            # Generated reports & visualizations
```

## 🎯 Business Impact

**Target Users**: Consulting firms, investment teams, compliance officers
**Use Cases**: 
- Due diligence screening
- Portfolio ESG monitoring  
- Early warning systems
- Regulatory compliance
- Competitive intelligence

**Value Proposition**: Detect ESG risks 2-3 weeks before mainstream coverage, enabling proactive decision-making and risk mitigation.

## 🔧 Technical Implementation

### Phase 1: Data Foundation ✅
- [x] Multi-source API integration
- [x] Data collection pipeline
- [x] Storage & preprocessing system

### Phase 2: NLP & Classification 🚧
- [ ] ESG risk category definition
- [ ] Zero-shot classification testing
- [ ] Model fine-tuning & validation

### Phase 3: Risk Engine 📅
- [ ] Severity scoring algorithm
- [ ] Source credibility weighting
- [ ] Composite risk scoring

### Phase 4: AI Agents 📅
- [ ] Autonomous research agent
- [ ] Predictive alert system
- [ ] Investigation workflows

### Phase 5: Dashboard & Deployment 📅
- [ ] Interactive web interface
- [ ] Automated reporting
- [ ] Production deployment

## 📊 Sample Output

**Company Risk Profile Example:**
```
BP PLC - ESG Risk Assessment
├── Overall Score: 67/100 (HIGH RISK)
├── Environmental: 78/100 ⚠️  
├── Social: 45/100 ✅
├── Governance: 56/100 ⚠️
└── Recent Alerts: 3 incidents (past 30 days)
```

## 🛠️ Technology Stack

- **Data Processing**: Python, Pandas, SQLite
- **NLP & ML**: Transformers, FinBERT, scikit-learn, PyTorch  
- **APIs**: Companies House, Guardian, NewsAPI, Twitter
- **Visualization**: Plotly, Streamlit, Matplotlib
- **AI Agents**: LangChain, Ollama, local LLMs
- **Deployment**: Streamlit Cloud, GitHub Actions



## 📞 Contact

**Dhruv Banerjee** - [D.Banerjee1@lse.ac.uk]  
Project Link: [https://github.com/Dhruv-baner/esg-risk-monitor](https://github.com/Dhruv-baner/esg-risk-monitor)

---

*Built for the future of ESG intelligence. Combining cutting-edge NLP with practical business applications.*

