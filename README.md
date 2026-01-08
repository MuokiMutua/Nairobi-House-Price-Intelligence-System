# House Price Intelligence System

## Introduction
This project analyzes a real-world Nairobi housing dataset to determine property values based on features like **location**, **size**, and **amenities**. Using insights from this analysis, we've developed an algorithm that predicts the **fair market price** for a property with high precision. This tool is designed to assist **home buyers, sellers, and real estate agents** in making data-driven valuation decisions in a variable market.

---

## Objectives
- Develop and implement a **high-precision house price prediction algorithm**.  
- Analyze and visualize **key price drivers** in the Nairobi real estate market.  
- Create a transparent system using **Explainable AI (XAI)** to show the "why" behind every valuation.

---

## The Data
The project uses data sourced from a specialized **Nairobi Property dataset**, originally scraped from leading real estate platforms like **Property24**. The dataset contains detailed listings from major suburbs including **Runda, Karen, Kilimani, and Westlands**.  

The data has been cleaned and adapted to demonstrate how **Automated Valuation Models (AVMs)** can accurately reflect local market hierarchies. The goal is to showcase the effectiveness of advanced regression methods in predicting prices in complex urban environments.

---

## Features
- **Advanced Machine Learning:** Built using the **ExtraTrees algorithm**, achieving an accuracy score (**$R^2$**) of 90%.  
- **Explainable AI (XAI):** Integrated **SHAP visualizations** to show which features (e.g., location, room count) impact price the most.  
- **Smart Preprocessing:** A robust pipeline handles **local currency formats (KSh)** and identifies luxury-market outliers.  
- **Feature Engineering:** Custom **Luxury Index** and **Total Room** metrics capture the nuances of premium properties.

---

## How It Works
1. **Data Input:** Property details such as location, property type, and room counts are fed into the system.  
2. **Processing:** The system cleans the input and applies **logarithmic scaling** to handle market outliers.  
3. **Algorithm Execution:** The **ExtraTrees regressor** processes the features to predict the most likely market value.  
4. **Insight Generation:** Results are displayed in **Kenyan Shillings (KSh)**, along with a breakdown of which features pushed the price up or down.
