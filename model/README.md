# AquaSight – Water Quality Prediction Models

This repository contains machine learning and time-series models
for coastal water quality prediction in the Gulf of Thailand.

## Target Variables
- Secchi Depth
- Chlorophyll-a
- Trophic State Index (TSI)

## Models
| Variable | Model | Usage |
|--------|------|------|
| Secchi Depth | ARIMA | Production |
| Chlorophyll-a | SVM (RBF) | Production |
| TSI | ARIMA | Production |
| TSI | LSTM (Full Feature) | Research / Comparison |

## Folder Structure
- data/ : Raw in-situ data
- data_prepared/ : Cleaned datasets
- notebooks/ : Training notebooks
- models_* / : Trained models
- results_* / : Evaluation results

This project is developed for I-New Gen Award submission.
