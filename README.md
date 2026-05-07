# AquaSentinel 🌊
### Distributed Global Groundwater Crisis Intelligence Network

A real-time distributed system that monitors groundwater depletion
across 6 global crisis regions using NASA GRACE-FO satellite data,
Apache Kafka streaming, and Apache Spark parallel processing.

---

## 🌍 Global Coverage
| Region | Countries | Crisis Level |
|--------|-----------|-------------|
| South Asia | Pakistan, India, Bangladesh | 🔴 Critical |
| Middle East | Saudi Arabia, Iran, Yemen | 🔴 Critical |
| North Africa | Libya, Egypt, Tunisia | 🟠 High |
| North America | USA (California, Texas), Mexico | 🟠 High |
| Central Asia | Uzbekistan, Kazakhstan, Turkmenistan | 🟡 Medium |
| Sub-Saharan Africa | Ethiopia, Kenya, Somalia | 🔴 Critical |

---

## ⚙️ Tech Stack
| Layer | Technology | Purpose |
|-------|-----------|---------|
| Distributed Streaming | Apache Kafka | Node-to-node message passing |
| Parallel Processing | Apache Spark | Distributed data computation |
| ML Forecasting | LSTM (PyTorch) | 5-year depletion prediction |
| Dashboard | Streamlit + Plotly | Real-time crisis visualization |
| Backend API | FastAPI | Data serving endpoints |
| Orchestration | Apache Airflow | Automated pipeline scheduling |
| Containerization | Docker | One-command system startup |

---

## 📁 Project Structure
AquaSentinel/
├── nodes/              # Regional distributed node simulators
│   ├── south_asia/
│   ├── middle_east/
│   ├── north_africa/
│   ├── north_america/
│   ├── central_asia/
│   └── sub_saharan/
├── kafka/              # Message streaming producers & consumers
├── spark/              # Parallel processing Spark jobs
├── ml/                 # LSTM forecasting model
├── dashboard/          # Real-time crisis visualization
├── data/               # NASA GRACE-FO datasets
│   ├── raw/
│   ├── processed/
│   └── models/
├── docs/               # Architecture diagrams & reports
├── tests/              # Unit tests
├── main.py             # System entry point
├── config.py           # Global configuration
└── requirements.txt    # Dependencies
---

## 🚀 PDC Concepts Implemented
- **Distributed Nodes** — 6 independent regional nodes running in parallel
- **Message Passing** — Apache Kafka topics per region
- **Parallel Processing** — Apache Spark multi-worker cluster
- **MapReduce** — Global aggregation of depletion scores
- **Fault Tolerance** — System continues if one node fails
- **Load Balancing** — Processing distributed across Spark workers

---

## 📊 Key Features
- Real-time groundwater level monitoring across 6 global regions
- NASA GRACE-FO satellite data integration
- LSTM-based 5-year depletion forecasting
- Parallel vs sequential speedup benchmarking
- Automated crisis alert system
- Interactive global heatmap dashboard

---

## 🎓 Academic Context
**Subject:** Parallel and Distributed Computing  
**Program:** BS Data Science — 6th Semester  
**Institution:** Islamia University of Bahawalpur, 2026  

---

## 👨‍💻 Author
**Abu Sameer**  
GitHub: [Abu-Sameer-66](https://github.com/Abu-Sameer-66)  
Kaggle: [sameernadeem66](https://www.kaggle.com/sameernadeem66)  
Portfolio: [sameer-nadeem-portfolio.vercel.app](https://sameer-nadeem-portfolio.vercel.app)