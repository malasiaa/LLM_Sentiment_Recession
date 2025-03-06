# LLM-Powered Sentiment Analyzer for Financial News

## Overview

This project leverages a Large Language Model (LLM) to analyze financial news sentiment, specifically focusing on recession fear. By maximizing the number of classified articles per day, the system aims to smooth out micro-noises and biases, providing a more reliable sentiment assessment.

## Key Features

- Automated financial news retrieval using the NewsAPI free plan.

- Sentiment classification with Gemini-2.0-Pro LLM via OpenRouter API.

- Scalable and adaptive approach to ensure efficient API usage while maintaining accuracy (whithin free tier limits - check notes).

- Oversight analysis correlating sentiment scores with SP500 movements and sector trends.

## Insights & Findings

- Recession Fear Score vs. SP500: Appears to predict inverse SP500 movements, particularly in high-delta peaks.

- 5-day moving average analysis: Acts as a lagging indicator, leading SP500 trends.

- Sector-wise analysis: Scores generally align with SP500 trends, with unique behaviors in Technology and Retail sectors.

## Future Improvements

- Explore fine-tuning models like DistilBERT for a more resource-efficient alternative.

- Expand financial indicators beyond recession fear to cover broader economic metrics.