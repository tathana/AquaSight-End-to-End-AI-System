# AquaSight — End-to-End AI Water Quality Monitoring System

An end-to-end system for water quality monitoring and forecasting, covering:
**data preprocessing → feature engineering → model training/evaluation → REST API → LINE chatbot → web dashboard**.

## Repository Structure
- `model/` — ML experiments (ARIMA / LSTM / SVM), training notebooks, evaluation results
- `api/` — Data pipeline + backend API service (forecast endpoints, schemas, services)
- `chatbot/` — LINE messaging integration for delivering prediction results
- `web/` — Next.js dashboard for visualization and monitoring

## Key Features
- Multi-station water-quality time series preparation (raw → cleaned → prepared)
- Statistical analysis & visualization outputs (figures, stats json)
- Forecast generation and serving predictions via REST API
- User-facing delivery through LINE bot + web dashboard

## Tech Stack
- Python (pandas, numpy, scikit-learn), notebooks
- API: (your framework in `api/backend/app` — FastAPI/Flask; update here)
- Web: Next.js (TypeScript)
- LINE Messaging API

## Quick Start
### 1) API
```bash
cd api/backend
pip install -r requirements.txt
# run command: update according to your framework (e.g., uvicorn app.main:app --reload)
