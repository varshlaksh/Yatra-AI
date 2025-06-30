# 🛕 YatraAI – Smart Pilgrimage Planner

YatraAI is a smart pilgrimage planning assistant that helps users find the most suitable **travel**, **stay**, and **food** options for their religious trips across India — based entirely on **mock data stored in `.csv` files** and calculated via **Python in Jupyter Notebook**.

---

## 📌 Project Overview

> This project is part of the **UtsavAI Internship – Round 1**, and is designed to simulate a backend planning system without using any real-time APIs. All logic and recommendations are driven through pre-created mock datasets and processed in Python.

---

## 🎯 Key Features

- Takes input for:
  - Starting city
  - Destination (pilgrimage place)
  - Number of travelers
  - Budget
  - Duration of trip (in days)

- Calculates:
  - Best travel route and cost
  - Nearest affordable stay option
  - Suitable food vendor with meal cost
  - Total trip cost and budget match
  - Simulated vendor negotiation (discount logic)
  - Day-wise Itinerary generation

---

## 🧠 Tech Stack

| Layer        | Tech Used               |
|--------------|--------------------------|
| 💻 Interface | Jupyter Notebook (Python) |
| 🧮 Logic     | Pandas, CSV Data          |
| 📂 Data      | `.csv` files (mock data)  |

---

## 📁 Folder Structure
yatraai/
├── YatraAI.ipynb # Main notebook with full logic
├── data/ # All mock data stored here
│ ├── travel_options.csv
│ ├── accommodation.csv
│ ├── food_vendors.csv
│ └── pilgrimage_sites.csv
│ └── sample_output.png
└── README.md # This file

