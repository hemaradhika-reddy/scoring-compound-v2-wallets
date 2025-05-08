# scoring-compound-v2-wallets
Overview

This project develops an AI-powered, decentralized credit scoring system for wallets interacting with the Compound V2 protocol. Using raw transaction data (in JSON format), the system assigns credit scores (0–100) to wallets based on their behavior. Higher scores indicate reliable, responsible usage (e.g., high deposits, timely repayments), while lower scores reflect risky or exploitative behavior (e.g., high borrowing, frequent liquidations).

The solution uses unsupervised learning (K-means clustering) to group wallets by behavior, engineers features from transaction logs, and normalizes scores to reflect protocol health. The project includes a methodology document, a Python script, a CSV output with wallet scores, and a wallet behavior analysis.
