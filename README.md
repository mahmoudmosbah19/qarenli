# qarenli
A price comparison application that searches B.TECH, Amazon, and Noon to find and display the lowest available product prices.
# 🛒 Product Price Comparison

A price comparison application designed to help users find the best available price for a product by searching and comparing prices across three major e-commerce platforms: **B.TECH, Amazon, and Noon**.

Instead of manually searching through multiple websites, the user can enter a product name once, and the application searches the available platforms, matches the relevant products, compares their prices, and displays the lowest available price.

## 🚀 Features

* 🔎 Search for products using a single search query.
* 🛍️ Compare products from **B.TECH, Amazon, and Noon**.
* 💰 Automatically identify the lowest available price.
* 📊 Display product name, price, platform, and product link.
* 🔗 Provide direct links to the original product pages.
* ⚡ Perform searches across multiple platforms in parallel.
* 🧩 Match similar products between different platforms.
* 📈 Store price information for future price-history tracking.
* 🖥️ Clean and organized user interface.

## 🔄 How It Works

```text
User Search
     ↓
Query Analyzer
     ↓
 ┌───────────┬───────────┬───────────┐
 ↓           ↓           ↓
B.TECH     Amazon       Noon
 ↓           ↓           ↓
 └───────────┴───────────┴───────────┘
              ↓
       Parallel Search
              ↓
       Product Matching
              ↓
       Price Comparison
              ↓
        Lowest Price
              ↓
       Display Results
```

## 🧠 Core Components

### Query Analyzer

Processes the user's search query and prepares it for searching across the supported platforms.

### Parallel Search

Searches B.TECH, Amazon, and Noon simultaneously to reduce waiting time and improve the overall search experience.

### Product Matching

Identifies products that represent the same or similar item across different platforms, taking into consideration product names, specifications, and other available information.

### Price Comparison

Collects the available prices and compares them to determine the lowest price.

### Price History

Stores product and price information in a database, allowing the project to be extended with historical price tracking and future price-change analysis.

## 🛠️ Technology Stack

The project is designed around a modern application architecture consisting of:

* Frontend GUI
* Backend/API layer
* Product search integrations
* Product matching and comparison logic
* Database for product and price history
* External e-commerce APIs or data sources

## 🎯 Project Goal

The goal of this project is to simplify online shopping by giving users a single place to compare product prices across multiple e-commerce platforms.

Rather than opening several websites and checking prices manually, users can search once and quickly see where the selected product is available at the lowest price.

## 🔮 Future Improvements

* Real-time price updates
* Price-drop notifications
* Advanced product matching
* Product availability tracking
* Price history charts
* Additional e-commerce platforms
* User accounts and personalized watchlists
* Mobile application support

## 📌 Supported Platforms

| Platform | Status    |
| -------- | --------- |
| B.TECH   | Supported |
| Amazon   | Supported |
| Noon     | Supported |

---

**Product Price Comparison** — Search once, compare multiple platforms, and find the lowest available price.
