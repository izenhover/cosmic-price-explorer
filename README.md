# cosmic-price-explorer
Multi-Source B2B/B2C Data Aggregator (Demo)
# 🚀 Cosmic Price Explorer (Multi-Source Data Aggregator)

A high-performance, stealth-focused data aggregation engine and web interface built with Python (FastAPI) and Playwright.

## 🎯 Project Overview
This project is a fully functional prototype designed to aggregate product data from multiple global B2B and B2C e-commerce platforms in real-time. It features an advanced smart-filtering system that removes irrelevant items (like accessories) to ensure only the primary products are displayed.

## ✨ Key Features
*   **Stealth Browsing Engine:** Utilizes `playwright-stealth` to mimic human behavior and bypass complex anti-bot systems (WAFs) and CAPTCHAs.
*   **Smart Relevance Scoring:** Custom Python algorithm that calculates the relevance of product titles to the searched keyword and drops accessories.
*   **Real-time API:** Lightning-fast FastAPI backend with built-in caching and SQLite price-history tracking.
*   **Modern UI:** A fully responsive, custom-designed "Space Theme" UI (HTML/CSS/JS) with lazy-loading, skeleton screens, and interactive seller-trust validation.
*   **Seller Trust Score:** An innovative algorithm to evaluate supplier reliability based on multiple data points.

## 🛠 Tech Stack
*   **Backend:** Python, FastAPI, Uvicorn
*   **Scraping:** Playwright, BeautifulSoup4
*   **Database:** SQLite
*   **Frontend:** HTML5, CSS3, Vanilla JavaScript

## ⚠️ Disclaimer
*This repository is for **Portfolio and Demonstration purposes only**. The actual scraping logic, API endpoints, and target market credentials have been removed to protect proprietary business logic. The frontend code provided here includes a mocked API response to demonstrate the user interface and user experience.*
