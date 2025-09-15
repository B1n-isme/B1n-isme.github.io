---
title: "Projects"
layout: post
---

## Multi-Horizon Bitcoin Price Forecasting
- 5 horizons: 7/14/30/60/90 days; expanding-window CV (step = horizon)
- Features: log-returns + back-transform, stability selection, VIF/correlation pruning
- Models: AutoARIMA/ETS/Theta, iTransformer/TCN/TFT/TSMixer
- Metrics: MAE, RMSE, MASE, Directional Accuracy; tracked training time
- Findings: TCN (7/14d), ETS (30/60d), TFT (90d); U-shaped complexity–performance; concept drift
- Reproducible: config-driven runs, deterministic seeds, timestamped results and plots

[Links](https://github.com/B1n-isme/Multi-Horizon-Bitcoin-Price-Forecasting)

---

## Yellow Flies Detection (YOLOv8)
- Lightweight YOLOv8n optimized for edge devices
- Evaluated with precision, recall, mAP; visualizations and confusion matrices
- Hyperparameter tuning and training optimization based on metric insights
- Deployed `best.pt` for image and video inference

[Links](https://github.com/B1n-isme/Train-yolov8-on-yellow-fly-dataset)

---

## JourneyBot RAG Chatbot Website
- Personalized travel recommendations and itineraries
- Sources: API data, embedded PDFs, and local Ollama model knowledge
- Pipeline: extract → chunk → embed (sentence transformers) → store in Pinecone
- UI: responsive, animated, with direct file attachments

[Links](https://github.com/B1n-isme/JourneyBot)
