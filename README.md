# AquaSight — End-to-End AI Water Quality Monitoring System

An end-to-end AI system for real-time water quality monitoring and forecasting, 
designed to automate the full pipeline from raw environmental data to actionable insights.

## Use Case
- Environmental monitoring for early detection of water quality degradation
- Supports decision-making for agencies or communities
- Automated alerting via LINE chatbot for real-time updates

## System Architecture
Raw Data → Preprocessing → Feature Engineering → ML Models → API → LINE Bot / Web Dashboard

## Repository Structure
- `model/` — ML experiments (ARIMA / LSTM / SVM), training notebooks, evaluation results
- `api/` — Data pipeline + backend API service (forecast endpoints, schemas, services)
- `chatbot/` — LINE messaging integration for delivering prediction results
- `web/` — Next.js dashboard for visualization and monitoring

## Key Features
- Multi-station water-quality time series pipeline (raw → cleaned → prepared)
- Statistical analysis & visualization outputs
- Real-time forecasting pipeline with REST API for scalable prediction serving
- Automated notification system via LINE chatbot
- Interactive web dashboard for monitoring and insights

## Models
- ARIMA (baseline)
- LSTM (deep learning)
- SVM (comparison model)

## Tech Stack
- Python (pandas, numpy, scikit-learn)
- FastAPI (REST API)
- Next.js (TypeScript)
- LINE Messaging API
